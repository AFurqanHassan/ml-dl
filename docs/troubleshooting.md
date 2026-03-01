# Troubleshooting Guide

Common issues and their solutions.

## Installation Issues

### Package Conflicts

**Problem:** Import errors or version conflicts.

**Solution:**

```bash
# Create fresh environment
python -m venv .venv_new
.venv_new\Scripts\activate
pip install -r requirements.txt
```

### CUDA/GPU Issues

**Problem:** PyTorch not detecting GPU.

**Solution:**

```python
import torch
print(torch.cuda.is_available())
print(torch.cuda.get_device_name(0))
```

If `False`, install CUDA toolkit or use Google Colab for free GPU.

## Notebook Issues

### Kernel Not Starting

**Problem:** Jupyter kernel fails to start.

**Solution:**

```bash
# Install ipykernel
pip install ipykernel
python -m ipykernel install --user --name=ml-dl
```

### Out of Memory Errors

**Problem:** CUDA out of memory or RAM exhausted.

**Solutions:**

1. Reduce batch size:

   ```python
   batch_size = 16  # Instead of 32
   ```

2. Clear GPU cache:

   ```python
   import torch
   torch.cuda.empty_cache()
   ```

3. Use gradient checkpointing in large models

### Missing Data Files

**Problem:** Data file not found errors.

**Solution:**

- Check `data/` folder exists
- Run extraction cells in notebooks first
- Re-download from source if corrupted

## Module-Specific Issues

### Module 2: Land Cover Classification

**Problem:** rasterio or rioxarray errors.

**Solution:**

```bash
pip install rasterio rioxarray
```

### Module 3-5: Deep Learning

**Problem:** Slow training on CPU.

**Solution:**

- Reduce epochs for testing
- Use smaller model variants
- Consider Google Colab for GPU

### Module 5: Ollama Not Found

**Problem:** Ollama command not recognized.

**Solution:**

1. Install Ollama: https://ollama.ai/download
2. Start Ollama daemon: `ollama serve`
3. Pull model: `ollama pull llama2`

## Getting Help

1. Check module README for specific requirements
2. Review notebook error messages
3. Ensure all dependencies from `requirements.txt` are installed

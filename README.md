# GitHub Codespaces Devcontainer - CUDA Template

Contains a default Devcontainer setup, based on Ubuntu, with:

 - CUDA
 - Python 
 - Jupyter Lab

## Getting started

### New repository

Click `Use repository` on this repository's GitHub page

### Existing repository

Download the template files to your repository root directory:

```bash
curl https://raw.githubusercontent.com/alan-cooney/devcontainer-cuda/main/.devcontainer/Dockerfile \
  --create-dirs -o .devcontainer/Dockerfile
curl https://raw.githubusercontent.com/alan-cooney/devcontainer-cuda/main/.devcontainer/devcontainer.json \
  -o .devcontainer/devcontainer.json
```

# Minimal Working Example of Shebang in repo2docker

This is a investigation for https://github.com/gesistsa/usemh/issues/11.

## Step-by-Step

```bash
micromamba create \
    -y \
    -n repo2docker-shebang-mwe \
    jupyter-repo2docker
```

```bash
micromamba run \
    -n repo2docker-shebang-mwe \
    repo2docker --version
```

```bash
micromamba run \
    -n repo2docker-shebang-mwe \
    repo2docker --no-run .
```
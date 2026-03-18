# ソフトウェア工学用リポジトリ

## コード

- git clone

```bash
# Git
git clone https://github.com/se-nitech/diff-patch-git.git

# Docker
git clone https://github.com/se-nitech/docker-python.git
git clone https://github.com/se-nitech/docker-c.git
git clone https://github.com/se-nitech/docker-java.git

# Debug
git clone https://github.com/se-nitech/debug-c.git
git clone https://github.com/se-nitech/debug-python.git
git clone https://github.com/se-nitech/debug-java.git

# Test
git clone https://github.com/se-nitech/unittest-pytest.git
git clone https://github.com/se-nitech/unittest-java.git

# Formatting
git clone https://github.com/se-nitech/format-python.git
git clone https://github.com/se-nitech/format-c.git
git clone https://github.com/se-nitech/format-java.git

# Documentation
git clone https://github.com/se-nitech/document-sphinx.git
git clone https://github.com/se-nitech/document-doxygen.git
git clone https://github.com/se-nitech/document-javadoc.git
```

- update

```bash
foreach i in *; do cd $i; git pull; cd .. ; done
```

## Dockerコンテナ

```bash
docker pull python:slim
docker pull gcc
docker pull quay.io/jupyter/datascience-notebook
docker pull plantuml/plantuml-server
docker pull tttamaki/dfd-generator
docker pull maven:3.9-eclipse-temurin-25
```

- update

```bash
foreach i in *; do cd $i; docker compose build; cd .. ; done
```

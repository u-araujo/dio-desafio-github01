# Comandos básicos Git

## Repositório Local

### Criar novo repositório

```bash
git init
```

### Verificar estado dos arquivos/diretórios

```bash
git status
```

## Adicionar arquivo/diretório — Staged Area

### Adicionar um arquivo específico

```bash
git add meu_arquivo.txt
```

### Adicionar um diretório específico

```bash
git add meu_diretorio
```

### Adicionar todos os arquivos/diretórios

```bash
git add .
```

### Adicionar um arquivo listado no `.gitignore`

```bash
git add -f arquivo_no_gitignore.txt
```

## Commitar arquivo/diretório

### Commitar um arquivo

```bash
git commit meu_arquivo.txt
```

### Commitar vários arquivos

```bash
git commit meu_arquivo.txt meu_outro_arquivo.txt
```

### Commitar informando uma mensagem

```bash
git commit -m "Minha mensagem de commit"
```

## Remover arquivo/diretório

### Remover um arquivo

```bash
git rm meu_arquivo.txt
```

### Remover um diretório

```bash
git rm -r diretorio
```

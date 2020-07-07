# Comandos básicos Git

## Criando um repositório vazio
```
git init <caminho>
```

# Adicionando um arquivo para ser rastreado
```
git add <caminho ou . para tudo>
```

# Realizando o commit no repositório local
```
git commit <-m "mensagem">
```

# Enviar para o repositório remoto
```
git push
```

# Baixar do repositório remoto fazendo o merge automático
```
git pull
```

# Voltar o repositório local para um versão específica
```
git checkout <HEAD, HEAD~1 ou hash do commit> <caminho>
```

# Voltar o repositório local para um versão específica ignorando alterações em arquivos
```
git checkout <HEAD, HEAD~1 ou hash do commit> -- <caminho>
```

# Clonando um repositório local ou remoto
```
git clone <URL> <caminho>
```

# Realiza um novo commit revertendo (desfazendo) um commit em um repositório local
```
git revert <HEAD, HEAD~1 ou hash do commit que será desfeito>
```

# Reseta um commit e seus arquivos em um repositório local, voltando tudo para o estado do commit informado.
# Deve ser evitado caso já tenha feito o push das alterações
```
git reset <HEAD, HEAD~1 ou hash do commit que será desfeito>
```
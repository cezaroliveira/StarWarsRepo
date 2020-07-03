# Exemplo de projeto do curso "Git e contribuições para projetos Open Source" da Udemy

## Conectando o repositório local com o GitHub via SSH
https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh

## Iniciando o agente SSH
```
ssh-agent -s
```

## Gerando uma chave SSH
```
ssh-keygen -t rsa -b 4096 -C "cezaroliveira1987@gmail.com"
```

## Adicionando uma chave gerada ao agente (conforme caminho gerado acima)
```
ssh-add C:\Users\55319\.ssh
```

## Testando o acesso ao GitHub via SSH
```
ssh -T git@github.com
```

## Alterando para usar HTTPS ou SSH
## SSH
```
git remote set-url origin git@github.com:cezaroliveira/StarWarsRepo.git
```
## HTTPS
```
git remote set-url origin https://github.com/cezaroliveira/StarWarsRepo.git
```

## Adicionando uma chave SSH no GitHub
Copiar o conteúdo do arquivo "C:\Users\55319\.ssh\id_rsa.pub" e colar no GitHub

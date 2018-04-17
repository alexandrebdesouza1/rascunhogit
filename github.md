# Criação de chave github

## Intro

### Gerar chave: 

```bash
ssh-keygen
```

### Entrar no diretorio da chave: 

```bash 
cd ~/.ssh/
```

## Dar push: 

```bash
$ git add <ArquivosQueVoceQuerAcidionar> <PodeSerMaisDeUM> <E/OuUmaPasta/>
$ git push origin -> nome padrão do arquivo
```
- Dar push em outro arquivos

```bash
$ git add novoArquivo
$ git push origin <branch>
```

## Branch

- Ver todos os branch:

```
$ git branch -a 
```

- Criar novo branch:

```bash
$ git checkout -b funcionalidade1 origin/funcionalidade1
```

## Atualizar repositorio local com alterações do remoto

```bash
$ git pull origin irineu
```

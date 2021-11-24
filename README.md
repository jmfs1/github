
# GitHub 🚀


## CONFIGURAÇÕES

### Criando conta GitHub

- Primeiro vamos criar uma conta acessando [GitHub](https://github.com/) e depois clicando em criar conta.

## Instalando  Git
- Agora vamos instalar o Git clicando nesse [LINK](https://git-scm.com/download) e seguindo as instruções.

#### Configurações locais
- Depois de criar a conta e baixar o git vamos rodar os seguintes comandos para configurar nosso git local.

```
# Configurando usuário e e-mail

git config --global user.name "Fulano de Tal"

git config --global user.email "your_email@example.com"
```

```
# Listando configurações
git config --list
```

## _REPOSITÓRIOS_

#### Rodaremos esses comandos para configurar e guardar dados em um repositório local.

```
# Iniciando um repositório local
$ git init 

# Adicionando mudanças de tudo ou um arquivo a esse repositório
$ git add * ou git add README.md 

# Salvando essas mudanças em um comentário ou commit
$ git commit -m "first commit"

# Criando a branch master local
$ git branch -M master
```

#### Repositório remoto 

- Agora vamos criar um repositório remoto na nossa conta do GitHub para depois conseguirmos sincronizar ambos os repositórios.

#### Sincronizar e subir versão do código

```
# Com esse comando e URL vamos conectar o repositório local com o remoto
git remote add origin <url_repositorio_remoto>

# Agora com os repositórios conectados, vamos subir os dados locais para o remoto com o comando
git push -u origin master
```

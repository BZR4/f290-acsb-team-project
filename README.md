# Team Project Acessibilidade

Este projeto será desenvolvido em conjunto por 4 times do componente curricular `Acessibilidade` do curso `Sistemas para Internet` utilizando sistema de versionamento no desenvolvimento.

## Instruções

### Clonar o projeto
Clone o projeto em um diretorio de sua escolha atraves do `Git-Bash`:
```shell
git clone https://github.com/BZR4/f290-acsb-team-project.git
```

### Atualizar o projeto
Certifique-se que voce esta trabalhando na branch `master`.
```shell
git branch
```
O resultado deve apontar para a branch master com um asterisco como prefixo
```shell
* master
time-3
```

### Criar a branch do seu time
#### Times
Time | Integrantes | Tema | Página
-- | -- | -- | --
TIME 1 | Nicolas e Silvio | Cegueira e Baixa Visão | Tema
TIME 2 | Fabio e Diego | Auditiva | Tema e página Sobre
TIME 3 | Edmilson e Jonas | Cognitiva | Tema e página Contato
TIME 4 | Gabriel e Lucas e Allan | Motora | Tema e página Principal

##### Crie a branch de seu time, com exceção do time-3
Para criar sua branch digite o comando abaixo tocando o `X` pelo numero do seu time.
```shell
git checkout -b time-x
```
O comando acima cria a branch especifica e realiza a mudanca da branch `master` para a branch de seu time `time-x`.

### Realize as alterações e crie seus commits
Após criar seus arquivos e realizar as alterações, verifique se esta trabalhando na branch de seu time.
```shell
git branch
```
Após confirmar, realize os `commits`.
```shell
git add .
git commit -m "Mensagem descritiva do commit (descrição das alterações realizadas)"
```
Visualize o log para confirmar a criação do commit.
```shell
git log
```
Se ouverem muitos commits, pressione a tecla `Q` para sair da visualização de LOG.

### Enviar suas aterações para o repositorio remoto
No primeiro envio ao repositorio remoto, suas alterações existem apenas na sua máquina.
Voce precisa informar o destino da branch `time-x`.
Para enviar suas alterações para o repositorio remoto, digite o comando abaixo.
```shell
git push -u origin time-x
```
Depois de ter criado a branch no prepositorio remoto com o comando acima; voce pode realizar o push simplesmente com o comando abaixo.
```shell
git push
```

## Mesclar o código de trabalho
Após todos enviarem as alterações iremos realizar os `Pull Requests` para integrar as páginas e concluir o projeto.


# Comandos Git

## DESCKTOP
1. Instalar o git -
 [Linux | Windows | Mac](https://git-scm.com/)

2. Configurar nome e e-mail para Git
 ``` bash
 git config --global user.name "Seu Nome"
 git config --global user.email "seu@email.com"

 ```
 3. Na pasta do prjeto que queira fazer git 
 ``` bash
 git init

 ```
 4. Cada iteração você pode executar seginte comando para verificar 
 ``` bash
 git status

 ```
 5. Adicionar o seu projeto o arquivo ao controle de versão 
 ``` bash
 git add nome-do-arquivo

 # Todos os aquivos
 git add .
 
 ```
 6. Fazer commit em sua aplicação | cada comite deve term uma mesagem diferente
 ``` bash
git commit -m "Sua mensagem de commit aqui"

 ```
 6. Cada commit você pode executar seginte comando ver historico
 ``` bash
 git log

 ```
 7. no seu terminal digite o comando abaixo para gerar chave ssh apert ENTER em tudo
 ``` bash
 ssh-keygen

 cat ~/.ssh/id_rsa.pub 

 ```
 logo depois de gerado copie a chave e cole la nas configurações do GITHUB -
 https://github.com/settings/keys 

 ## GITHUB

 1. passar o repositorio de sua maquina para GITHUB
 
    criar um repositorio no GITHUB
    
    * Conectar repositorio Local ao repositorio do GITHUB
    ``` bash
    git remote add origin https://github.com/seu-usuario/seu-repositorio.git

    ```
    * Defina o nome da sua Branch principal - main
    ``` bash
    git branch -M main

    ```
    * Adiciona o conteudo da pasta do computador para o GITHUB
    ``` bash
    git push -u origin main

    ```
2. clonar o repositorio do GITHUB para seu computador
    ``` bash
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

    ```

    
 
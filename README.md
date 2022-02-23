# Configuração iniciais do Cypress
Para rodar o cypress precisa ter baixado e configurado corretamente:

**1º** NPM que é responsável para interpretar os arquivos do cypress

**2º** NODE.JS que é o servidor onde vai rodar o cypress

**3º** VS CODE que é a ide

**4º** CYPRESS
 
**Observação:** Quando o nodeJS é baixado o NPM também é baixado 
 
**Site para baixar o NODE.JS e NPM:** https://nodejs.org/en/download/
**Site para baixar o VS CODE:** https://code.visualstudio.com/download 

**PASSOS:**

**1º **Após baixar o node.js e o npm,  tem que verificar a sua versão para validar se foi baixado corretamente, e para verificar é só usar o comando: node -v e  npm -v 

**2º **acessa a pasta do projeto no terminal, e dentro da pasta coloca o comando npm init -y para iniciar a configuração dentro do package.json

**3º** adicionar o cypress como dependência do projeto dentro do projeto coloca o comando  npm install cypress, mas caso queira outra versão 
do cypress é só rodar o comando  npm install cypress@ e a versão desejada. Exemplo: EXEMPLO: npm install cypress@9.1.0, para verificar todas as versões do cypress é só ir em sua documentação e fica dentro de  Changelog

**4º** quando o cypress for baixado dentro da pasta do projeto colocar o comando code . para abrir o vscode já com a pasta do projeto, ou importar o projeto para dentro do vscode

**5º** dentro do PACKAGE.JASON do cypress onde tem o comando "scripts” após a sua conclusão depois das " tem que colocar um vírgula e adicionar o comando "cypress:open": "cypress open"  para que possa inicializar o cypress, quando o cypress é executado ele abre uma aplicação Eletron, e gera vários testes que ficam dentro da pasta integration esses testes podem ser excluídos 

**Observação:** para executar o cypress dentro do vs code tem que abrir um novo terminal e inserir o comando npm run cypress:open e confirmar a sua execução clicando no enter

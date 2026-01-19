# Teste-QA-Pleno
Teste de API Rest do manual a CI/CD
## O que é
Este repositório foi criado para o bootcamp de Teste de API Rest.
## Tecnologias utilizadas
- Postman versão web
- node version v24.11.1
- newman v6.2.1
- newman-reporter-html
## Documentações
- Analise Técnica: Analise/
## Como instalar o ambiente
- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
- Segundo: realize a instalação do newman de forma global [baixe aqui a dependencia](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: realize a instalação da dependencia dos relatórios (opcional) [newman-reporter-html
](https://www.npmjs.com/package/newman-reporter-html)
```
npm install -g newman-reporter-html
```
## Como rodar os testes
### Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os teste de forma manual ou automatizada
### Pelo newman
- Abra o console de preferência
- Execute a seguinte linha de comando para rodar os testes
```
npx newman run "Teste QA Pleno - Assets.postman_collection.json" -r cli
```
- Execute os teste com relatório
```
npx newman run "Teste QA Pleno - Assets.postman_collection.json" -r cli,htmlextra 
```
### Report
Se você optou por rodar os teste com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validaçõe
## Entre em contato
email: santosleandro1805@gmail.com

redes socias: https://www.linkedin.com/in/leandro-santos-501ba11a4/

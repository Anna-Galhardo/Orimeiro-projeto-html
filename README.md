## Como publicar uma página no gitpages

***Pré requisitos***
* Conta no GitHub;
* Git instalado em seu computador (opcional, se for usar linha de comando);
* Um repositório com os arquivos do seu site (por exemplo: index.html);

***Passo a Passo***
1. Crie um novo repositório no GitHub
* Vá para https://github.com;
* Dê um nome ao repositório (ex: primeiro-site);
* Marque a opção Public (público);
* Clique em Create repository;

2. Envie seus arquivos para o repositório
```   
   git init
   git add .
   git commit -m " Meu site "
   git push
```
3. Ative o GitHub Pages
* Vá até o seu repositório no GitHub
* Clique em Settings (⚙️)
* No menu lateral, clique em Pages
* Em Branch, selecione:
* Branch: main
* Folder: / (root)
* Clique em Save

4. Acesse o site
* Após algum tempo, cerca de 5 minutos no máximo, o git irá gerar um link
* ex: https://SEU_USUARIO.github.io/primeiro-site/

***Exemplo de como fica o site***

<img width="1276" height="650" alt="image" src="https://github.com/user-attachments/assets/49885b81-efa1-4186-a514-643ca1ac9474" />






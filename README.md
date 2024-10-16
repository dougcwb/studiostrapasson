# Site HTML
Site do Studio Strapasson, antigo Strapasson Pilates.

- [Instalar o Node.Js](https://nodejs.org/en/download/package-manager)
- Clonar este repositório `git clone https://github.com/dougcwb/studiostrapasson.git`
- Abra o VsCode na pasta `studiostrapasson`
- No terminal (Ctrl+j), rode o comando `npm install -g firebase-tools`
- Fazer login com o comando `firebase login`
- Inicializar o projeto `firebase init`
    * Are you ready to proceed? `Yes`
    * Which Firebase features do you want to set up for this directory? Press Space to select features, then Enter to confirm your choices. `Hosting: Configure files for Firebase. Hosting and (optionally) set up GitHub Action deploys`
    * What do you want to use as your public directory? `public`
    * Configure as a single-page app (rewrite all urls to /index.html)? `Yes`
    * Set up automatic builds and deploys with GitHub? `No`
    * File public/index.html already exists. Overwrite? `No`
- Faça as alterações necessárias no projeto
- Para finalizar e enviar as alterações para o servidor use `firebase deploy`
- Adicione os arquivos ao github `git add .`
- Faça commit das modificações `git commit -m 'Modificações'`
- Adicione os arquivos ao github `git push origin main`
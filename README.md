# Site HTML
Site do Studio Strapasson, antigo Strapasson Pilates.

- [Instalar o Node.Js](https://nodejs.org/en/download/package-manager)
- Clonar este repositório `git clone https://github.com/dougcwb/studiostrapasson.git`
- Abra o VsCode na pasta `studiostrapasson`
- No terminal (Ctrl+j), rode o comando `npm install -g firebase-tools`
- Fazer login com o comando `firebase login`
- Inicializar o projeto `firebase init`
    * Digite "Y" para prosseguir
    * Escolha a opção `Hosting`
    * What do you want to use as your public directory? `public`
    * Configure as a single-page app (rewrite all urls to /index.html)? `Yes`
    * Set up automatic builds and deploys with GitHub? `Yes`
    * File public/index.html already exists. Overwrite? `No`
    * For which GitHub repository would you like to set up a GitHub workflow? `dougcwb/studiostrapasson`
    * Set up the workflow to run a build script before every deploy? `N` 
    * GitHub workflow file for PR previews exists. Overwrite?  `N`
    * Set up automatic deployment to your site's live channel when a PR is merged?  `Y`
    * What is the name of the GitHub branch associated with your site's live channel? `main`
    * The GitHub workflow file for deploying to the live channel already exists. Overwrite? `N`
- Para finalizar e enviar as alterações `firebase deploy`
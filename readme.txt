1) Créer un projet
2) Créer un menu de navigation à partir de "blank"


1) Installer le CLI :
- yarn global add @ionic/cli

Créer un projet :
- ionic start
-> choisir Angular ou React
-> choisir un nom
-> choisir le starter template : tabs ou sidemenu ou blank
-> choisir si l'on veut installer capacitor
-> choisir si l'on veut partager les données avec Google
-> choisir si l'on veut créer un compte Ionic

Pour lancer le projet :
- ionic serve

ionic build


2) - ng generate page menu
   - ng generate page login
   - ng generate page contact
   - ng generate page register
   Changer 'app/app-routing.module.ts'
   Changer 'app/menu/menu.module.ts'
   Changer 'app/menu/menu.page.ts'
   Changer 'app/menu/menu.page.html'
   Changer 'app/contact/contact.page.html'
   Changer 'app/home/home.page.html'
   Changer 'app/login/login.page.html'
   Changer 'app/menu/menu.page.html'
   Changer 'app/register/register.page.html'
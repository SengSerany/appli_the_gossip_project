Application The gossip project a.k.a "TGP" pour les intimes

pour lancer l'appication,
  télécharger le dossier rails:
  https://github.com/SengSerany/appli_the_gossip_project.git
  
  puis sur le terminal:
    - bundle install
    - rails db:migrate
    - rails serveur
    
  Puis sur un navigateur internet:
     http://localhost:3000/
     
   Exercice Jour 20:
    - 2.2 / 
              1 - Génerer le controller nommer "static_pages" et la view "team"
              2 - Créé depuis le logiciel de texte un fichier view 'contact' et le placer dans : 'app/views/static_pages'
              3 - Faire le lien dans config/routes.rb avec les views de 'contact et 'team': 
                     - get 'static_pages/team'
                     - get 'static_pages/contact'
                     
              

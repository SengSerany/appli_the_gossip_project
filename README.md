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
                     
   - 2.3.1 / 
              1 - Aller sur la page: 'https://getbootstrap.com/docs/4.1/getting-started/introduction/'
              2 - Prendre le premier lien de la page
              3 - Ajouter le lien Bootstrap dans le fichier dans le <head> </head> 'app/views/layout/application.html.erb'
          
   - 2.3.2 /
              1 - Choisir une barre de navigation sur la page: https://getbootstrap.com/docs/4.0/components/navbar/
              2 - L'integrer dans le fichier view: 'app/views/layout/application.html.erb'
              3 - Bien échanger les liens dans la navbar les liens comme 'feature' ou 'pricing' par 'Team' et Contact'
                pour faire plus tard le lien avec.
   - 2.3.3 /
              1 - Dans le fichier: 'app/views/layout/application.html.erb',
                    - Dans les liens <a href=#> Lien </a>; et mettre le lien ici du type:
                    '<%= link_to "Home", index_path %> '
                  Signifiant:
                    <% %> : signifiant que ce qui est entre ses balises est du language ruby
                    <%= %> : signifiant que ce qui est entre ses balises est du language ruby 
                             et qu'il faut l'afficher dans le navigateur
                    link_to "Texte_a_cliquer_pour_acceder_au_lien", "nom_du_chemin_accedant_a_la_page_desiré"_path
                  
    
                    
                    
                    
                    
                    

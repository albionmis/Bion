!DOCTYPE html>

<html lang="fr">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Bion</title>

  <link rel="stylesheet" href="styles.css">

  <!--Arrière-plan-->

  <style>
    body {
      background-image: url('image/ia/plan.png'); /* chemin vers votre image */

      background-size: cover; /*L'image couvre tout l'écran */

      background-repeat: no-repeat; /* Pas de répétition de l'image */

      background-position: center; /* Centrer l'image */
    }
  </style>

</head>

<body>

  <header>

    <nav>
   <!-- menu-->
      <ul>
        
       <center>

        <button type="service"><li><a href="#accueil">Accueil </a></li></button>

        <button type="service"><li><a href="#about">À propos</a></li></button>

        <button type="service"><li><a href="#services">Services</a></li></button>                                 

        <button type="service"><li><a href="#contact">Contact</a></li></button>
  
       </center> 


      </ul>

    </nav>

  </header>

     <!-- commande de menu-->

  <main>

    <section id="accueil">

      <center>

    <h1>Bienvenue sur Bion</h1>
     
     </center>
     
    </section>




   <section id="about">

      <h2>À propos de nous</h2>

      <p style="color:#0A4359;"> Nous sommes une équipe dédiée à fournir des services de qualité en développement web.</p>

    </section>


    </section>



    <section id="services">

      <h2>Nos Services</h2>

      <div class="service">

        <h3><p style="color: white;">Design</h3></p>

        <p style="color: #0A4359;"> Conception de designs modernes et adaptés.</p>

      </div>
      
   <!--title-->

        <h3><p style="color: white;">Développement</h3></p>

        <p style="color: #0A4359;">Création de sites web performants et réactifs.</p>

      </div>

      <div class="service">

        <h3><p style="color: white;">Support</h3></p>

        <p style="color: #0A4359;">Assistance technique pour vos projets web.</p>

     <!--a quoi servent les ia-->
     
        <h3><p style="color: white;">A quoi servent les IA</h3></p>

        <I><p style="color:#0A4359;">Les intelligences artificielles (IA) servent à accomplir diverses tâches en automatisant des processus, en aidant à la prise de décision et en simplifiant la vie quotidienne dans de nombreux domaines. Voici quelques exemples d'applications des IA :</br></I>

1. Automatisation des tâches répétitives
Dans les entreprises, l'IA est utilisée pour gérer des tâches routinières comme le tri d'e-mails, le traitement des factures ou la gestion des stocks.
Dans l'industrie, des robots équipés d'IA réalisent des opérations de fabrication complexes.</br>
2. Analyse de données
Les IA traitent de grandes quantités de données pour en extraire des tendances ou des informations utiles.
Elles sont utilisées dans la finance pour détecter des fraudes ou dans la santé pour analyser des images médicales et poser des diagnostics.</br>
3. Assistants virtuels et chatbots
Les assistants comme Siri, Alexa ou Google Assistant aident à répondre aux questions, à gérer des calendriers ou à contrôler des appareils domestiques.
Les chatbots offrent un support client en ligne rapide et personnalisé.</br>
4. Personnalisation des expériences
Dans le commerce en ligne, l'IA recommande des produits en fonction des préférences des utilisateurs.
Dans le divertissement, elle propose des films, des séries ou des playlists personnalisées (Netflix, Spotify).</br>
5. Conduite autonome
Dans le domaine des transports, les véhicules autonomes utilisent l’IA pour analyser leur environnement et prendre des décisions en temps réel.</br>
6. Recherche scientifique et innovation
L'IA accélère la découverte de médicaments, l'analyse génomique ou encore la modélisation du climat.</br>
7. Création artistique et contenu généré
Les IA créent de l’art, composent de la musique, écrivent des articles ou génèrent des designs.</br>
8. Sécurité et surveillance
Elle est utilisée pour surveiller les réseaux et prévenir les cyberattaques.
Dans les villes, l'IA aide à analyser les flux de circulation ou à reconnaître des comportements suspects.
En résumé, l'IA est un outil puissant qui peut être utilisé pour améliorer l’efficacité, la précision et la qualité de nombreuses activités, tout en laissant les humains se concentrer sur des tâches plus créatives et complexes. Cependant, son utilisation soulève aussi des questions éthiques, comme la vie privée, le biais algorithmique ou l’impact sur l’emploi.</p></br>   

   <!--images-->

        <section id="img">  

         <h3><p style="color: #8C8C8C;">Image</h3></p>
         
         <p style="color: #0A4359;">Vous pouvez prendre des exemples avec des image que on a crée avec IA.</p>

         <img src="image/ia/robote.png"width="150">

         <img src="image/ia/satelit.png"width="150">

         <img src="image/ia/ordinateur.png"width="150">

         <img src="image/ia/serveur.png"width="150"></br>

         <img src="image/ia/voiture.png"width="150">

         <img src="image/ia/usb.png"width="150">

       </section>

   <!--vidéo-->

       <section id="iframe">
         
         <h3><p style="color: white;">Vidéo</h3></p>

         <p style="color: #9FB9BF;">Pouvez-vous regardez les vidéo pour comprendre comment ça marche l'IA.</p>

         <iframe width="250" src="image/ia/vidéo.mp4"iframeborder="0" allowfullscreen></iframe>

       </section>


  </div>

   <!--envoyer une message-->


    <section id="contact">


      <h2><p style="color: gray;"><p style="color: white;"> Contactez-nous</p></h2>

      <form action="#" method="post">

        <label for="nom">Nom :</label>

        <input type="text" id="nom" name="nom" required>



        <label for="email">Email :</label>

        <input type="email" id="email" name="email" required>



        <label for="message">Message :</label>

        <textarea id="message" name="message" rows="4" required></textarea>



        <button type="submit">Envoyer</button>

      </form>

    </section>

  </main>


<!--les IA--> 

    <h2>Les IA</h2>


   <button type="https"><a href="https://gemini.google.com/?hl=fr">IA questions</a></button>

   <button type="https"><a href="https://www.blogdumoderateur.com/tools/craiyon/">générateur d'image</a></button></br>

   <button type="https"><a href="https://www.chatgpt.com">IA question</a></button>

    <button type="https"><a href="https://www.renderforest.com/fr/home/main/for-you">générateur de vidéo</a></button>


<!--Trouver vos téléphone-->

   <h2>Trouve les téléphones</p></h2>

 <button type="https"><a href="https://myaccount.google.com/find-your-phone">Trouve votre télephone android</a></button>

 <button type="https"><a href="https://www.icloud.com/">Trouve votre téléphone iphone</a></button>


    <!-- les tableau-->
     
     <h2>Tableau</h2>


    <table border="1"> 

    <tr>                                 

          <th>Nom IA</th>                                    

          <th>il fait quoi cette IA</th>                 

     </tr>                         
     <tr>                         
       
         <td>Chat GPT</td> 

         <td>Questions et réponses</td>                

     </tr>                         
     <tr>                       
       
        <td>Gemini</td>

        <td>questions et réponses</td>

    </tr>
    <tr>

       <td>Crayon</td>
     
     <td>Créeation des images</td>

   </tr>
   <tr>

    <td>Renderforest</td>

    <td>Création des vidéo</td>

    </table>

    <table border="2">  

 </tr>

 <tr>
   
   <th>Trouve votre téléphone</th>

   <th>Quelle appareille</th>

 </tr>

 <tr>

   <td>Google.com</td>

   <td>Android</td>

 </tr>

 <tr>

  <td>icloud.com</td>

  <td>Apple</td>

</tr>

</table>
  
</body>

</html>

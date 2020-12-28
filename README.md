<!DOCTYPE html>

<html lang="fr">
  <head>
    <meta charset="utf-8">
    <title>Reservia</title>
    <link rel="stylesheet" type="text/css" href="style.css"> 
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/da042e0cd0.js" crossorigin="anonymous"></script>
  </head>

  <body>
        
  <!--Header-->

    <header>
      <img class="website_logo" src="images/logo/Reservia.svg" alt="website logo"/>
      <nav class="navigation" >  
        <a class="nav_title" href="#lodging" >Hébergements</a>
        <a class="nav_title" href="#activities">Activités</a>
      </nav>
      <a class="inscription" href="#">S'inscrire</a>   
    </header>

  <!--Section 1 Recherche-->

    <section id="research">
    <h1 class="found_lodging">Trouvez votre hébergement pour des vacances de rêve</h1>
      <p>En plein centre ville ou en pleine nature </p>
      <br>
      <br>
      <!--rechercher--> 
      <form class="search">
        <div class="search_icon">
          <i class="fas fa-map-marker-alt"></i>
        </div>
        <input class="search_input" type="search" placeholder="Veuillez saisir la ville">
        <button class="search_submit">
          <span class="search_button">Rechercher</span>
          <i class="fas fa-search search_button2"></i>
        </button>
      </form>
      <br>
      <!--filtres--> 
      <div class="search_filters_area">
        <h2 class="search_filters_title">Filtres</h2>
        <!--Economique--> 
        <div class="search_filter_button search_filter_button1">
          <div class="search_filter_logos">
            <i class="fas fa-money-bill-wave search_button_logo"></i>
          </div>
          <a href="#" class="search_button_title">Économique</a>
        </div>
        <!--Familial--> 
        <div class="search_filter_button search_filter_button2">
          <div class="search_filter_logos">
            <i class="fas fa-child search_button_logo"></i>
          </div>
          <a href="#" class="search_button_title">Familial</a>
        </div>
        <!--Romantique--> 
        <div class="search_filter_button search_filter_button3">
          <div class="search_filter_logos">
            <i class="fas fa-heart search_button_logo"></i>
          </div>
          <a href="#" class="search_button_title">Romantique</a>
        </div>
        <!--Animaux--> 
        <div class="search_filter_button search_filter_button4">
          <div class="search_filter_logos">
            <i class="fas fa-dog search_button_logo"></i>
          </div>
          <a href="#" class="search_button_title">Animaux autorisés</a>
        </div>
      </div>
      <!--Informations--> 
      <div class="info">
        <div class="info_text">
          <i class="fas fa-info info_button_logo"></i>
        </div>
        <p class="info_text_smart">Plus de 500 logements sont disponibles dans cette ville</p>
      </div>   
      </section>

  <!--Section 2 Hebergement-->
    <!--Lodging-->
    <section id="lodging">
      <div class="lodging_tag_price">  
        <header class="lodging_city">
          <h2 class="lodging_city_title">Hébergements à Marseille</h2>
        </header>   
        <article class="lodging_photo">
          <a href="#">
            <figure class="lodging_photo_figure">
              <img 
                    class="lodging_photo_figure_images"
                    src="images/hebergements/4_small/auberge_de_la_cannebiere.jpg"
                    alt="la cannebiere"
              >
              <figcaption class="lodging_photo_figure_figcaption">
                <h3>Auberge la Cannebière</h3>
              </figcaption>
            </figure>
            <p class="lodging-night">Nuit à partir de <strong>25€</strong></p>
            <div class="lodging_stars">
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons2"></i>
              </div>
          </a>
        </article>
        <article class="lodging_photo">
          <a href="#">
            <figure class="lodging_photo_figure">
              <img 
                class="lodging_photo_figure_images"
                src="images/hebergements/4_small/hotel_du_port.jpg"
                alt="hotel du port"
              >
              <figcaption class="lodging_photo_figure_figcaption">
                  <h3>Hôtel du port</h3>
              </figcaption>
            </figure>
            <p class="lodging-night">Nuit à partir de <strong>52€</strong></p>
            <div class="lodging_stars">
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
            </div>
          </a>
        </article>
        <article class="lodging_photo">
          <a href="#">
            <figure class="lodging_photo_figure">
              <img 
                class="lodging_photo_figure_images"
                src="images/hebergements/4_small/hotel_les_mouettes.jpg"
                alt="les mouettes"
              >
              <figcaption class="lodging_photo_figure_figcaption">
                <h3>Hôtel Les mouettes</h3>
              </figcaption>
            </figure>
            <p class="lodging-night">Nuit à partir de <strong>76€</strong></p>
            <div class="lodging_stars">
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons2"></i>
            </div>
          </a>
        </article>
        <article class="lodging_photo">
          <a href="#">
            <figure class="lodging_photo_figure">
              <img 
                class="lodging_photo_figure_images"
                src="images/hebergements/4_small/hotel_de_la_mer.jpg"
                alt="hotel de la mer"
              >
              <figcaption class="lodging_photo_figure_figcaption">
                <h3>Hôtel de la mer</h3>
              </figcaption>
            </figure>
            <p class="lodging-night">Nuit à partir de <strong>46€</strong></p>
            <div class="lodging_stars">
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons2"></i>
              <i class="fas fa-star lodging_stars_icons2"></i>
            </div>
          </a>
        </article>  
        <article class="lodging_photo">
          <a href="#">
            <figure class="lodging_photo_figure">
              <img 
                class="lodging_photo_figure_images"
                src="images/hebergements/4_small/auberge_le_panier.jpg"
                alt="auberge le panier"
              >
              <figcaption class="lodging_photo_figure_figcaption">
                <h3>Auberge Le Panier</h3>
              </figcaption>
            </figure>
            <p class="lodging-night">Nuit à partir de <strong>23€</strong></p>
            <div class="lodging_stars">
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons2"></i>
            </div>
          </a>
        </article>    
        <article class="lodging_photo">
          <a href="#">
            <figure class="lodging_photo_figure">
              <img 
                class="lodging_photo_figure_images"
                src="images/hebergements/4_small/chez_amina.jpg"
                alt="chez amina"
              >
              <figcaption class="lodging_photo_figure_figcaption">
                <h3>Hôtel chez Amina</h3>
              </figcaption>
            </figure>
            <p class="lodging-night">Nuit à partir de <strong>96€</strong></p>
            <div class="lodging_stars">
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
              <i class="fas fa-star lodging_stars_icons"></i>
            </div>
          </a>
        </article>
        <a href="#"><strong>Afficher plus</strong></a>
      </div>
      <!--Lodging popular-->
      <aside class="lodging_popular">
        <h2 class="lodging_popular_title">Les plus populaires<i class="fas fa-chart-line"></i></h2>
        <article class="lodging_photo lodging_popular_card">
          <a class="lodging_popular_content" href="#">
            <div class="lodging_popular_content2">
              <img 
                class="lodging_popular_images"
                src="images/hebergements/4_small/hotel_le_soleil_du_matin.jpg"
                alt="hotel le soleil du matin"
              >
            </div>
            <div class="lodging_popular_content3">
              <h3>Hôtel Le soleil du matin</h3>
              <p class="lodging-night">Nuit à partir de <strong>128€</strong></p>
              <div class="lodging_popular_content4"></div>
              <div class="lodging_stars">
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
              </div>
            </div>
          </a>
        </article>
        <article class="lodging_photo lodging_popular_card">
          <a class="lodging_popular_content" href="#">
            <div class="lodging_popular_content2">
              <img 
                class="lodging_popular_images"
                src="images/hebergements/4_small/au_coeur_de_leau.jpg"
                alt="coeur de l'eau"
              >
            </div>
            <div class="lodging_popular_content3">
              <h3>Au coeur de l'eau <br>Chambres d'hôtes</h3>
              <p class="lodging-night">Nuit à partir de <strong>71€</strong></p>
              <div class="lodging_popular_content4"></div>
              <div class="lodging_stars">
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons2"></i>
              </div>
            </div>
          </a>
        </article>
        <article class="lodging_photo lodging_popular_card">
          <a class="lodging_popular_content" href="#">
            <div class="lodging_popular_content2">
              <img 
                class="lodging_popular_images"
                src="images/hebergements/4_small/hotel_tout_bleu_et_blanc.jpg"
                alt="tout bleu"
              >
            </div>
            <div class="lodging_popular_content3">
              <h3>Hôtel Tout bleu et Blanc</h3>
              <p class="lodging-night">Nuit à partir de <strong>68€</strong></p>
              <div class="lodging_popular_content4"></div>
              <div class="lodging_stars">
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons"></i>
                <i class="fas fa-star lodging_stars_icons2"></i>
              </div>
            </div>  
          </a>
        </article>
      </aside>    
    </section>
        
  <!--Section 3 Activités-->

  <section id="activities">
    <div class="activity">
      <h2 class="activites_head_title">Activités à Marseille</h2>
      <article class="activity_photo activity_photo1">
        <a href="#">
          <figure class="activity_picture1">
            <img 
              class="activity_image activity_image1"
              src="images/activites/3_medium/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg"
              alt="vieux port"
            >
            <figcaption class="activity_photo_figure_figcaption">
            <h3 class="activity_title">Vieux Port</h3>
            </figcaption>
          </figure>
        </a>
      </article>
      <article class="activity_photo activity_photo2">
        <a href="#">
          <figure class="activity_picture2">
            <img 
              class="activity_image activity_image2"
              src="images/activites/4_small/paul-hermann-QFTrLdQIRhI-unsplash.jpg"
              alt="Fort de Pomegues"
            >
            <figcaption class="activity_photo_figure_figcaption">
            <h3 class="activity_title">Fort de Pomegues</h3>
            </figcaption>
          </figure>
        </a>
      </article>
      <article class="activity_photo activity_photo3">
        <a href="#">
          <figure class="activity_picture3">
            <img 
              class="activity_image activity_image3"
              src="images/activites/3_medium/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg"
              alt="parc national des calanques"
            >
            <figcaption class="activity_photo_figure_figcaption">
            <h3 class="activity_title">Parc National des Calanques</h3>
            </figcaption>
          </figure>
        </a>
      </article>
      <article class="activity_photo activity_photo4">
        <a href="#">
          <figure class="activity_picture4">
            <img 
              class="activity_image activity_image4"
              src="images/activites/4_small/florian-wehde-xW9e8gdotxI-unsplash.jpg"
              alt="notre dame de la garde"
            >
            <figcaption class="activity_photo_figure_figcaption">
            <h3 class="activity_title">Notre-Dame-De-La-Garde</h3>
            </figcaption>
          </figure>
        </a>
      </article>
      <article class="activity_photo activity_photo5">
        <a href="#">
          <figure class="activity_picture5">
            <img 
              class="activity_image activity_image5"
              src="images/activites/4_small/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg"
              alt="iles du frioul"
            >
            <figcaption class="activity_photo_figure_figcaption">
            <h3 class="activity_title">Iles du Frioul</h3>
            </figcaption>
          </figure>
        </a>
      </article>
      <article class="activity_photo activity_photo6">
        <a href="#">
          <figure class="activity_picture6">
            <img 
              class="activity_image activity_image6"
              src="images/activites/4_small/lena-paulin-wH2-EJoDcV0-unsplash.jpg"
              alt="parc longchamp"
            >
            <figcaption class="activity_photo_figure_figcaption">
            <h3 class="activity_title">Parc Longchamp</h3>
            </figcaption>
          </figure>
        </a>
      </article>		
     </div>	
  </section>

  <!--Footer-->       
    <footer>
        <div class="footer_div_container">
        <div class="footer_div1">
          <h3 class="footer_head_title">A propos</h3>
          <ul>
            <li><a href="#" class="footer_link">Fonctionnement du site</a></li>
            <li><a href="#" class="footer_link">Conditions générales de vente</a></li>
            <li><a href="#" class="footer_Link">Données et confidentialité</a></li>
          </ul>
        </div>
        <div class="footer_div2">
          <h3 class="footer_head_title">Nos hébergements</h3>
          <ul>
            <li><a href="#" class="footer_link">Charte qualité</a></li>
            <li><a href="#" class="footer_link">Soumettre votre hôtel</a></li>
          </ul>
        </div>
        <div class="footer_div3">
          <h3 class=footer_head_title>Assistance</h3>
          <ul>
            <li><a href="#" class="footer_link">Centre d'aide</a></li>
            <li><a href="#" class="footer_link">Nous contacter</a></li>
          </ul>
        </div>
      </div>
   </footer>     
  </body>
</html>

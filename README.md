# Prix-de-l-immobilier 
Quelle est l'influence des aménagements sur les prix de l'immobilier à Marseille
En termes démographiques, la ville de Marseille est la deuxième ville de France. Elle est de ces villes qui voient, depuis vingt ans, sa population augmenter d’année en année. Selon le site internet de la ville qui tient ses sources de l’INSEE, Marseille acquiert annuellement près de 3 244 habitants. Nous nous sommes intéressées ainsi au prix de l'immobilier à Marseille, les différences de prix selon les arrondissements et leur évolution. Pour ce faire, nous avons utilisé la base de données "Demande de valeurs foncières" (DVF) qui recense l'ensemble des ventes des biens fonciers de ces cinq dernières années en France. Nous avons également utilisé le site d'Euromed qui recense les divers aménagements Euromed dans l'ensemble de la ville et des jeux de données sur les autres aménagements marseillais. 
# Disparités des prix immobiliers entre les arrondissements à Marseille
Nous avons mis au point ce graphique réalisé sur DataWrapper afin de rendre compte des disparités des prix de l'immobilier qui existent entre les différents arrondissements à Marseille.Pour ce faire, nous avons utilisé les données DVF sur l'évolution du prix de l'immobilier à Marseille. Comme nous pouvons le voir, le 8e arrondissement est l'arrondissement le plus cher : en 2019, le prix médian de vente culmine à plus de 200 000 euros. A l'inverse, le 3e arrondissement de la ville est celui dont la médiane du prix de vente est la plus basse, avec une baisse importante en 2019 : la médiane s'élève alors à un peu plus de 50 000 euros. 
C'est là que les questions suivantes nous sont parvenues : Quels sont les facteurs de hausse du prix de l'immobilier à Marseille ? Quelle est la raison majeure de la disparité du prix de vente immobilière entre les arrondissements ? 
Ainsi, nous sommes parties de l'hypothèse suivante : les nouveaux aménagements participent grandement à la hausse du prix de vente immobilière dans le quartier où ils sont construits. 
# Comparaison de l'évolution du prix de vente immobilière entre le 2e et le 3e arrondissement en fonction des aménagements. 
Afin de vérifier notre hypothèse, nous avons décidé de centrer cette étude sur les 2e et 3e arrondissements de Marseille. Nous avons choisi ces deux arrondissements car ils ont connu ces dernières années de nombreux aménagements, notamment avec les aménagements Euromed, considérables. Ce sont deux arrondissements de centre-ville qui présentent de nombreuses similitudes. En ce sens, une étude comparative nous a semblée bénéfique afin de répondre à notre hypothèse. Tout d'abord, voici un tour d'horizon du projet Euromed à Marseille. 
# # Le projet EUROMED 
En 1995, Robert Vigouroux, maire de Marseille, lance le programme Euroméditerranée pour la mise en place d’un établissement public d’aménagement. Le programme Euroméditerranée acte 2, en 2007, relance et étend ce projet. Dans ce cadre-là, de nombreuses constructions et rénovations voient le jour, depuis 2014 notamment, permettant la redynamisation de certains quartiers. 
Nous avons établi une cartographie des constructions EUROMED entre 2014 et 2019 pour rendre compte de l'importance de ces aménagements. Comme nous pouvons le remarquer, ces aménagements concernent les 2e et 3e arrondissements de Marseille. Pour réaliser cette carte, nous avons extrait des données directement depuis le site Euromed. 
# # Les aménagements du 2e et du 3e arrondissements de Marseille. 
Pour rendre compte des aménagements du 2e et du 3e arrondissements à Marseille, nous avons réalisé une autre cartographie, toujours avec DataWrapper, qui recense la plupart des constructions qui ont eu lieues entre 2014 et 2019. Nous pouvons voir que des centres commerciaux, des bureaux, des espaces publics, des musées ou encore des lignes de tramway ont permis une dynamisation de ces quartiers. 

<!DOCTYPE html>

<html lang="{{ site.lang | default: "fr-FR" }}">

  <head>

    <meta charset="UTF-8">



{% seo %}

    <meta name="viewport" content="width=device-width, initial-scale=1">

    <meta name="theme-color" content="#157878">

    <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,700' rel='stylesheet' type='text/css'>

    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">

  </head>

  <body>

    <section class="page-header">

      <h1 class="project-name">TITRE</h1>

      <h1 class="project-tagline">SOUS-TITRE</h2>

      <h3>AUTEURS</a></h3>

    </section>



    <section class="main-content">

      {{ content }}

									

    <footer class="site-footer">

	    <p style="font-weight:bold"> A propos</p>

	    <p>Cet article a été produit dans le cadre du cours "Données et Médiation" du master Métiers de l'information Sciences Po Aix/EJCAM. Ce cours supervisé par Samuel Goëta vise à s'approprier les étapes de la réutilisation de données ouvertes en produisant un article en groupe à partir d'un angle, d'identifier des sources de données, de les retraiter et les visualiser pour en tirer un certain nombre d'enseignements. </p>

	    <p>Les analyses produites dans cet article doivent être prises avec précaution et complétées par d'autres recherches. Elles ont été produites à titre expérimental à des fins d'enseignements. </p>

	    </footer>

    </section>



  </body>

</html>

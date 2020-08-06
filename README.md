<!DOCTYPE html> 
<html>
    <head>
        <title>Coco'air companie !</title>
        
        <!-- lier la page html avec le css pour ajouter le design -->
        <link rel="stylesheet" type="text/css" href="css/styles.css">

        <!-- ajouter une police d'ecriture -->
        <link href="https://fonts.googleapis.com/css2?family=Acme&display=swap" rel="stylesheet">

        <!-- je prend en compte les accents -->
        <meta charset="utf-8">
    </head>
    <body>

        <!-- Balise pour le haut de page -->
        <header>
            <!-- Titre de la page -->
            <h1 class="titre">Coco'air ✈</h1>

            <!-- Slogan -->
            <h3 class="slogan">«La tête dans les nuages !»</h3>

            <div class="search-form">
                <!-- Formulaire de recherche -->
                <form method="post">
                                
                    <div class="form-group">
                        <label for="provenance">Ville de départ</label>
                        <input type="text" name="provenance" id="provenance" placeholder="Paris, Milan, ...">

                        <label for="arrivee">Ville d'arrivée</label>
                        <input type="text" name="arrivee" id="arrivee" placeholder="Paris, Milan, ...">
                    </div>

                    <div class="form-group">
                        <label for="depart">Date de départ</label>
                        <input type="date" name="depart" id="depart" value="13/04/2020">

                        <label for="retour">Date de Retour</label>
                        <input type="date" name="retour" id="retour" value="14/04/2020">
                    </div>

                    <div class="form-group">
                        <label for="adultes">Nombre d'adultes</label>
                        <select name="adultes" id="adultes">
                            <option selected="selected">0 Adulte</option>
                            <option>1 Adulte</option>
                            <option>2 Adultes</option>
                            <option>3 Adultes</option>
                            <option>4 Adultes</option>
                            <option>5 Adultes</option>
                        </select>

                        <label for="enfants">Nombre d'enfants</label>
                        <select name="enfants" id="enfants">
                            <option selected="selected">0 Enfant</option>
                            <option>1 Enfant</option>
                            <option>2 Enfants</option>
                            <option>3 Enfants</option>
                            <option>4 Enfants</option>
                            <option>5 Enfants</option>
                        </select>

                        <label for="type">Categorie</label>
                        <select name="type" id="type">
                            <option selected="selected">Classe Economique</option>
                            <option>Classe Affaires</option>
                        </select>
                    </div>

                    <div class="button-submit">
                        <input type="submit" value="Lancer la recherche" name="recherche" id="recherche">
                    </div>
                    
                </form>
            </div>

        </header>

        <!-- Une section avec les destinations -->
        <section id="destinations">

            <h3>Nous proposons differentes destinations pour découvrir le monde !</h3>

            <div class="destinations-group">
                <!-- destination 1 -->
                <div class="destination-item barcelone">
                    <div class="overlay">
                        <span class="prix">Dès 80€</span>
                        <span class="nom">Barcelone</span>
                    </div>
                </div>

                <!-- destination 2 -->
                <div class="destination-item dubai">
                    <div class="overlay">
                        <span class="prix">Dès 300€</span>
                        <span class="nom">Dubai</span>
                    </div>
                </div>

                <!-- destination 3 -->
                <div class="destination-item philippines">
                    <div class="overlay">
                        <span class="prix">Dès 1200€</span>
                        <span class="nom">Manille</span>
                    </div>
                </div>

                <!-- destination 4 -->
                <div class="destination-item paris">
                    <div class="overlay">
                        <span class="prix">Dès 55€</span>
                        <span class="nom">Paris</span>
                    </div>
                </div>

                <!-- destination 5 -->
                <div class="destination-item tunis">
                    <div class="overlay">
                        <span class="prix">Dès 90€</span>
                        <span class="nom">Tunis</span>
                    </div>
                </div>

                <!-- destination 6 -->
                <div class="destination-item londres">
                    <div class="overlay">
                        <span class="prix">Dès 65€</span>
                        <span class="nom">Londres</span>
                    </div>
                </div>
            </div>

        </section>

        <!-- Pied de page -->

        <footer>
            <hr>
            <p>&copy; 2020 - Coco'air - Tout droits réservés - <a href="cgu.html">CGU</a> </p>
        </footer>

    </body>
</html>

#dar el halwa
rayen miladi
1 info 17
#
2page se dite:
index.html : page d'accueil.
carte.html : carte des produits et des prix.
commande.html : formulaire de commande.
3. Types HTML5 utilisés dans le formulaire
Type HTML5	Champ concerné
text	Nom et prénom
email	Adresse e-mail
tel	Numéro de téléphone
date	Date souhaitée de livraison
time	Heure souhaitée de livraison
number	Quantité commandée
radio	Choix unique
checkbox	Options supplémentaires
submit	Bouton d'envoi
reset	Bouton de réinitialisation

Remarque : cette liste est à adapter aux types réellement présents dans le fichier commande.html.

4. Liste des décors

Les options de la liste des décors sont regroupées avec la balise optgroup en deux catégories :

Décors sucrés
Décors frais

Exemple :

<select id="decors" name="decors[]" multiple size="4">
    <optgroup label="Décors sucrés">
        <option value="fleurs">Fleurs en pâte à sucre</option>
        <option value="chocolat">Décors en chocolat</option>
    </optgroup>

    <optgroup label="Décors frais">
        <option value="fruits">Fruits frais</option>
        <option value="fleurs_fraiches">Fleurs fraîches</option>
    </optgroup>
</select>
5 Technologies utilisées
HTML5
Visual Studio Code
Git
6. Objectif

Créer un site web structuré et accessible permettant de découvrir les produits de la pâtisserie Dar El Halwa et de passer une commande en ligne.
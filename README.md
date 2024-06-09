

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parti Souverainiste Identitaire (PSI)</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- En-tête du site -->
    <header>
        <h1>Parti Souverainiste Identitaire (PSI)</h1>
        <nav>
            <ul>
                <li><a href="#manifeste">Manifeste</a></li>
                <li><a href="#equipe">Équipe</a></li>
                <li><a href="#actualites">Actualités</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <!-- Contenu principal -->
    <main>
        <!-- Section Manifeste -->
        <section id="manifeste">
            <h2>Manifeste Politique</h2>
            <ul>
                <!-- Point 1 -->
                <li><strong>Renforcement du Pouvoir Présidentiel :</strong> Accroître les pouvoirs exécutifs pour une gouvernance autoritaire et centralisée, permettant des décisions rapides et efficaces pour le bien de la nation.</li>
                <!-- Ajoutez d'autres points ici -->
            </ul>
        </section>
        <!-- Section Équipe -->
        <section id="equipe">
            <h2>Équipe</h2>
            <p>Une équipe dévouée au projet.</p>
        </section>
        <!-- Section Actualités -->
        <section id="actualites">
            <h2>Actualités</h2>
            <p>Vous serez informé dès que prévu.</p>
        </section>
        <!-- Section Contact -->
        <section id="contact">
            <h2>Contactez-nous</h2>
            <form action="#">
                <label for="adresse">Votre adresse :</label>
                <input type="text" id="adresse" name="adresse" required>
                <label for="numero">Votre numéro :</label>
                <input type="text" id="numero" name="numero" required>
                <label for="nom">Votre nom :</label>
                <input type="text" id="nom" name="nom" required>
                <label for="email">Votre adresse email :</label>
                <input type="email" id="email" name="email" required>
                <label for="raison">Pour quelle raison vous nous contactez :</label>
                <textarea id="raison" name="raison" required></textarea>
                <button type="submit">Envoyer</button>
            </form>
        </section>
    </main>
    <!-- Pied de page -->
    <footer>
        <p>&copy; 2024 Parti Souverainiste Identitaire (PSI). Tous droits réservés.</p>
    </footer>
</body>
</html>
```

**styles.css** :

```css
/* Styles pour le corps de la page */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* Couleur de fond */
}

/* Styles pour l'en-tête */
header {
    background-color: #333; /* Couleur de fond */
    color: white; /* Couleur du texte */
    padding: 1em 0;
    text-align: center;
}

/* Styles pour la barre de navigation */
nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1em;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

/* Styles pour le contenu principal */
main {
    padding: 1em;
}

/* Styles pour les titres */
h1, h2 {
    color: #333; /* Couleur du texte */
}

/* Styles pour les sections */
section {
    margin-bottom: 2em;
}

/* Styles pour le formulaire de contact */
form label {
    display: block;
    margin: 0.5em 0 0.2em;
}

form input, form textarea, form button {
    width: 100%;
    padding: 0.5em;
    margin-bottom: 1em;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box; /* Pour inclure la bordure dans la largeur */
}

form button {
    background-color: #333; /* Couleur de fond */
    color: white; /* Couleur du texte */
    border: none;
    cursor: pointer;
}

form button:hover {
    background-color: #555; /* Couleur de fond au survol */
}

/* Styles pour le pied de page */
footer {
    background-color: #333; /* Couleur de fond */
    color: white; /* Couleur du texte */
    text-align: center;
    padding: 1em 0;
}
```

Ces commentaires seront visibles dans le code source de votre site et ne s'afficheront pas sur la page elle-même lorsque vous la visualiserez dans un navigateur.

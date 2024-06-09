# PSI-website-

### Étape 1 : Préparez vos fichiers sur votre téléphone

1. **Utilisez une application d'édition de code** sur votre téléphone, telle que Notepad++, Code Editor, ou une autre application de rédaction de code.

2. **Créez deux fichiers** : `index.html` et `styles.css` et copiez-y les codes suivants :

**index.html** :

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
    <main>
        <section id="manifeste">
            <h2>Manifeste Politique</h2>
            <ul>
                <li><strong>Renforcement du Pouvoir Présidentiel :</strong> Accroître les pouvoirs exécutifs pour une gouvernance autoritaire et centralisée, permettant des décisions rapides et efficaces pour le bien de la nation.</li>
                <li><strong>Priorité Absolue à l'Aide Nationale :</strong> Réduire toutes les aides internationales et concentrer exclusivement les ressources sur les besoins domestiques pour garantir le bien-être des citoyens.</li>
                <li><strong>Réglementation Extrêmement Stricte de l'Immigration :</strong> Adopter des politiques très strictes de contrôle et de régulation de l'immigration, incluant des renvois définitifs et des lois plus sévères pour les immigrés.</li>
                <li><strong>Souveraineté Totale et Union Européenne :</strong> Sortir de l'Union européenne pour assurer une complète autonomie nationale et récupérer tous les pouvoirs délégués aux institutions européennes.</li>
                <li><strong>Sortie du Conseil Permanent de l'ONU :</strong> Se retirer du Conseil de sécurité des Nations Unies et réduire l'implication dans les organisations internationales pour se concentrer uniquement sur les intérêts nationaux.</li>
                <li><strong>Indépendance Économique :</strong> Promouvoir l'autosuffisance économique par le soutien aux industries locales et une réduction drastique de la dépendance aux importations étrangères.</li>
                <li><strong>Socio-Capitalisme National :</strong> Assurer une répartition équitable des richesses en fonction des contributions sociales et économiques, mais exclusivement à l'intérieur du pays, garantissant un filet de sécurité social robuste pour tous les citoyens.</li>
                <li><strong>Peine de Mort :</strong> Réinstaurer ou maintenir la peine de mort pour les crimes les plus graves afin de renforcer la sécurité et l'ordre public.</li>
                <li><strong>Lois Plus Strictes pour les Immigrés :</strong> Mettre en place des lois plus strictes pour les immigrés, incluant des conditions de résidence rigides et des peines sévères pour les infractions, avec des renvois définitifs pour ceux qui ne respectent pas les lois.</li>
                <li><strong>Rigidité Extérieure :</strong> Adopter une politique étrangère ferme et inflexible, protégeant les intérêts nationaux avec vigueur et réduisant les engagements internationaux non essentiels.</li>
                <li><strong>Souplesse et Autorité Intérieure :</strong> Promouvoir une politique intérieure flexible et autoritaire, où l'État assure l'ordre et la sécurité tout en permettant une certaine liberté et autonomie aux citoyens dans leur vie quotidienne et économique. Encourager l'innovation et l'entrepreneuriat tout en maintenant des contrôles stricts sur les aspects critiques de la société.</li>
            </ul>
        </section>
        <section id="equipe">
            <h2>Équipe</h2>
            <p>Une équipe dévouée au projet.</p>
        </section>
        <section id="actualites">
            <h2>Actualités</h2>
            <p>Vous serez informé dès que prévu.</p>
        </section>
        <section id="contact">
            <h2>Contactez-nous</h2>
            <form>
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
    <footer>
        <p>&copy; 2024 Parti Souverainiste Identitaire (PSI). Tous droits réservés.</p>
    </footer>
</body>
</html>
```

**styles.css** :

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1em 0;
    text-align: center;
}

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

main {
    padding: 1em;
}

h1, h2 {
    color: #333;
}

section {
    margin-bottom: 2em;
}

form label {
    display: block;
    margin: 0.5em 0 0.2em;
}

form input, form textarea {
    width: 100%;
    padding: 0.5em;
    margin-bottom: 1em;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    display: block;
    width: 100%;
    padding: 0.7em;
    background-color: #333;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```

### Étape 2 : Créez un dépôt GitHub depuis l'application GitHub

1. **Téléchargez et installez l'application GitHub** depuis l'App Store (iOS) ou Google Play Store (Android).
2. **Ouvrez l'application GitHub** et connectez-vous à votre compte.
3. **Appuyez sur l'icône "+"** en bas de l'écran pour créer un nouveau dépôt.
4. **Entrez les détails du dépôt** :
   - **Repository name** : `psi-website`
   - **Description** : Facultatif
   - **Public/Private** : Choisissez "Public"
   - **Initialize this repository with a README** : Ne cochez pas cette option
5. **Appuyez sur "Create repository"**.

### Étape 3 : Ajouter des fichiers au dépôt via l'application GitHub

1. **Ouvrez le dépôt `psi-website`** dans l'application GitHub.
2. **Appuyez sur l'onglet "Code"**.
3. **Appuyez sur l'icône de menu (trois points) en haut à droite**.
4. **Sélectionnez "Upload file"**.
5. **Ajoutez vos fichiers `index.html` et `styles.css`** depuis votre téléphone. Répétez l'opération pour chaque fichier.

### Étape 4 : Configurez GitHub Pages via l'application GitHub

1. **Ouvrez le dépôt `psi-website`**.
2. **Appuyez sur l'onglet "Settings"** (paramètres).
3. **Descendez jusqu'à la section "GitHub Pages"**.
4. **Sous "Source"**, choisissez `main branch`.
5. **Appuyez sur "Save"**.

### Étape 5 : Accédez à votre site web

1. **Attendez quelques minutes** que GitHub Pages génère votre site.
2. Votre site sera accessible à l'adresse `https://<votre_nom_utilisateur>.github.io/psi-website/`.


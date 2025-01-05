# Réseaux sociaux : Facebook Instagram Tiktok
index.html:
```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Réseaux Sociaux - Accueil</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Les Réseaux Sociaux</h1>
        <nav>
            <ul>
                <li><a href="index.html">Accueil</a></li>
                <li><a href="facebook.html">Facebook</a></li>
                <li><a href="instagram.html">Instagram</a></li>
                <li><a href="tiktok.html">TikTok</a></li>
            </ul>
        </nav>
    </header>
    <section>
        <h2>Bienvenue sur notre site des Réseaux Sociaux</h2>
        <p>Découvrez l'historique, les paramètres de confidentialité, et les services rendus par Facebook, Instagram, et TikTok.</p>
        <img src="images/social_media.jpg" alt="Illustration des réseaux sociaux">
    </section>
</body>
</html>
```

facebook.html:
```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Facebook</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Facebook</h1>
        <nav>
            <ul>
                <li><a href="index.html">Accueil</a></li>
                <li><a href="facebook.html">Facebook</a></li>
                <li><a href="instagram.html">Instagram</a></li>
                <li><a href="tiktok.html">TikTok</a></li>
            </ul>
        </nav>
    </header>
    <section>
        <h2>Historique</h2>
        <p>Facebook a été créé en 2004 par Mark Zuckerberg...</p>
        <h2>Paramètres de confidentialité</h2>
        <ul>
            <li>Gestion des publications...</li>
            <li>Contrôle des identifications...</li>
        </ul>
        <h2>Services rendus</h2>
        <ol>
            <li>Partage de contenu multimédia...</li>
            <li>Groupes communautaires...</li>
        </ol>
        <table>
            <tr>
                <th>Année</th>
                <th>Utilisateurs (millions)</th>
            </tr>
            <tr>
                <td>2004</td>
                <td>1</td>
            </tr>
            <tr>
                <td>2023</td>
                <td>2900</td>
            </tr>
        </table>
    </section>
</body>
</html>
```

style.css:
```css
body {
    font-family: Arial, sans-serif;
    color: #333;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}
header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
}
header nav ul {
    list-style-type: none;
    padding: 0;
}
header nav ul li {
    display: inline;
    margin-right: 15px;
}
header nav ul li a {
    color: #fff;
    text-decoration: none;
}
section {
    padding: 20px;
}
h1, h2 {
    color: #0056b3;
}
img {
    max-width: 100%;
    height: auto;
}
table {
    width: 100%;
    border-collapse: collapse;
}
table, th, td {
    border: 1px solid #ddd;
}
th, td {
    padding: 8px;
    text-align: left;
}

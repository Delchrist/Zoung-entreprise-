# Zoung-entreprise-
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Location de Machines de Construction</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Location de Machines de Construction</h1>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#machines">Machines à Louer</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#a-propos">À propos</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="accueil">
        <h2>Bienvenue chez [Nom de l'Entreprise]</h2>
        <p>Nous offrons une large gamme de machines de construction à louer pour tous vos besoins.</p>
    </section>

    <section id="machines">
        <h2>Nos Machines à Louer</h2>
        <div class="machine">
            <img src="chemin/vers/image1.jpg" alt="Machine 1">
            <h3>Machine 1</h3>
            <p>Description de la machine 1</p>
        </div>
        <div class="machine">
            <img src="chemin/vers/image2.jpg" alt="Machine 2">
            <h3>Machine 2</h3>
            <p>Description de la machine 2</p>
        </div>
        <!-- Ajoute plus de machines ici -->
    </section>

    <section id="services">
        <h2>Nos Services</h2>
        <p>Nous offrons des services de livraison et de maintenance pour toutes nos machines.</p>
    </section>

    <section id="a-propos">
        <h2>À propos de Nous</h2>
        <p>Découvrez l'histoire de notre entreprise et rencontrez notre équipe.</p>
    </section>

    <section id="contact">
        <h2>Contactez-nous</h2>
        <form>
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 [Nom de l'Entreprise]. Tous droits réservés.</p>
    </footer>
</body>
</html>

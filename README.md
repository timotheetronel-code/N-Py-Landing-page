<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Carte ski étudiant Pyrénées : fini le passage en caisse, ski paiement à l’usage et réductions jusqu'à -30% dans 14 stations pour les étudiants.">
    <meta property="og:title" content="Carte ski étudiant Pyrénées | Carte No Souci Pyrénées">
    <meta property="og:description" content="BDE, campus et étudiants : accédez directement aux pistes sans rechargement. Skiez à prix réduit dans 14 stations des Pyrénées.">
    <meta property="og:type" content="website">
    <title>Partenariat BDE : Carte ski étudiant Pyrénées | Carte No Souci Pyrénées</title>
    <style>
        :root {
            --primary: #1a2f4e;
            --secondary: #ffffff;
            --accent: #ff6b35;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --light-bg: #f8f9fa;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: system-ui, -apple-system, sans-serif;
        }

        body {
            background-color: var(--secondary);
            color: var(--primary);
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* En-tête avec le logo */
        .top-nav {
            background-color: var(--secondary);
            padding: 1rem 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            position: relative;
            z-index: 10;
        }

        .top-nav img {
            height: 60px;
            width: auto;
        }

        /* Section Héro */
        header {
            background: linear-gradient(135deg, #1a2f4e 0%, #0d1a2a 100%);
            color: var(--secondary);
            padding: 4rem 0 0 0; /* Padding en bas à 0 pour coller l'image */
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            padding: 0 20px;
        }

        .hero-subtitle {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 2rem;
            padding: 0 20px;
        }

        .hero-image {
            width: 100%;
            max-width: 1000px;
            height: auto;
            display: block;
            margin: 0 auto;
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
            box-shadow: 0 -10px 20px rgba(0,0,0,0.2);
            /* Object-fit pour s'assurer que l'image de la montagne rende bien */
            object-fit: cover;
            max-height: 400px;
        }

        /* Avantages */
        .benefits {
            padding: 5rem 0;
            background-color: var(--secondary);
        }

        .benefits-intro {
            text-align: center;
            margin-bottom: 3rem;
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }

        .benefit-card {
            background: var(--light-bg);
            border-radius: 12px;
            padding: 2rem;
            box-shadow: var(--shadow);
            transition: transform 0.3s ease;
            border-top: 4px solid var(--accent);
        }

        .benefit-card:hover {
            transform: translateY(-5px);
        }

        .benefit-card h3 {
            color: var(--primary);
            margin-bottom: 1rem;
            font-size: 1.2rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        /* Image étudiante au milieu de la page */
        .lifestyle-section {
            padding: 0 0 4rem 0;
            text-align: center;
        }

        .lifestyle-image {
            width: 100%;
            max-width: 900px;
            height: 400px;
            object-fit: cover;
            border-radius: 15px;
            box-shadow: var(--shadow);
            margin: 0 auto;
        }

        /* Crédibilité / La Carte */
        .credibility {
            background-color: var(--primary);
            color: var(--secondary);
            padding: 5rem 0;
        }

        .credibility h2 {
            text-align: center;
            margin-bottom: 3rem;
        }

        .credibility-content {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 4rem;
            flex-wrap: wrap;
        }

        .credibility-text {
            flex: 1;
            min-width: 300px;
            font-size: 1.1rem;
        }

        .card-image-container {
            flex: 1;
            min-width: 300px;
            display: flex;
            justify-content: center;
            /* Animation pour faire flotter la carte */
            animation: float 6s ease-in-out infinite;
        }

        .card-image {
            max-width: 300px;
            height: auto;
            /* On enlève le shadow ici car l'image PNG a probablement déjà une ombre intégrée */
            filter: drop-shadow(0 20px 30px rgba(0,0,0,0.5));
        }

        @keyframes float {
            0% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-15px) rotate(2deg); }
            100% { transform: translateY(0px) rotate(0deg); }
        }

        /* FAQ */
        .faq {
            padding: 5rem 0;
            background-color: var(--light-bg);
        }

        .faq h2 {
            text-align: center;
            margin-bottom: 3rem;
            color: var(--primary);
        }

        .faq-item {
            margin-bottom: 1rem;
            background: var(--secondary);
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            overflow: hidden;
        }

        .faq-item h3 {
            color: var(--primary);
            cursor: pointer;
            padding: 1.5rem;
            margin: 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 1.1rem;
        }

        .faq-item h3::after {
            content: '+';
            font-size: 1.5rem;
            color: var(--accent);
            transition: transform 0.3s ease;
        }

        .faq-item.active h3::after {
            transform: rotate(45deg);
        }

        .faq-content {
            display: none;
            padding: 0 1.5rem 1.5rem 1.5rem;
            color: #555;
            border-top: 1px solid #eee;
        }

        .faq-item.active .faq-content {
            display: block;
            animation: fadeIn 0.3s ease;
        }

        /* CTA */
        .cta {
            text-align: center;
            padding: 5rem 0;
            background: linear-gradient(135deg, #ff6b35 0%, #e65c2a 100%);
            color: var(--secondary);
        }

        .cta h2 {
            font-size: 2.2rem;
            margin-bottom: 1rem;
        }

        .cta p {
            margin-bottom: 2.5rem;
            font-size: 1.2rem;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .btn {
            display: inline-block;
            background-color: var(--primary);
            color: var(--secondary);
            padding: 1.2rem 2.5rem;
            border-radius: 50px; /* Bouton plus arrondi */
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            margin: 0.5rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .btn:hover {
            background-color: #0d1a2a;
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
        }

        /* Footer */
        footer {
            background-color: #0a1320;
            color: #888;
            text-align: center;
            padding: 3rem 0;
            font-size: 0.9rem;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-5px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @media (max-width: 768px) {
            h1 { font-size: 2rem; }
            .hero-subtitle { font-size: 1rem; }
            .credibility-content { flex-direction: column-reverse; gap: 2rem;}
            .credibility-text { text-align: center; }
            .card-image-container { margin-bottom: 2rem; }
        }
    </style>
</head>
<body>

    <nav class="top-nav">
        <div class="container">
            <img src="logo-npy.jpg" alt="Logo Nouvelles Pyrénées N'PY">
        </div>
    </nav>

    <header>
        <div class="container">
            <h1>Offrez le ski facile et à prix réduit à vos étudiants</h1>
            <p class="hero-subtitle">Proposez à votre campus le sésame ultime pour skier dans 14 stations des Pyrénées. Fini les attentes aux caisses, place au paiement à l'usage et aux réductions étudiantes massives.</p>
        </div>
        <img src="npy.jpg" alt="Domaine skiable des Pyrénées N'PY" class="hero-image">
    </header>

    <section class="benefits">
        <div class="container">
            <div class="benefits-intro">
                <h2>4 raisons d'adopter la Carte No Souci pour votre BDE</h2>
            </div>

            <div class="benefits-grid">
                <div class="benefit-card">
                    <h3>✅ Zéro charge mentale</h3>
                    <p>Valorisez votre offre étudiante avec un service "clé en main". Vous n'avez aucune commande de forfaits cartonnés à gérer, aucune récolte de fonds. Tout est 100% digitalisé via un code promo école.</p>
                </div>

                <div class="benefit-card">
                    <h3>💸 Budget étudiant préservé</h3>
                    <p>Les réductions sont automatiques : <strong>jusqu'à -30%</strong> sur les journées skiées en semaine (hors vacances), et <strong>-15%</strong> le week-end. La 7ème journée de la saison est à <strong>-50%</strong> !</p>
                </div>

                <div class="benefit-card">
                    <h3>🎿 Fini le passage en caisse</h3>
                    <p>Le système est basé sur le télépéage : on skie d'abord, on est prélevé le mois suivant uniquement pour les journées réellement consommées. Accès direct aux remontées !</p>
                </div>

                <div class="benefit-card">
                    <h3>🛡️ Assurance secours incluse</h3>
                    <p>C'est l'argument qui rassure l'administration : l'assurance secours sur piste est <strong>intégrée par défaut</strong> à l'abonnement. En cas de pépin, les frais d'évacuation sont couverts.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="lifestyle-section">
        <div class="container">
            <img src="https://images.unsplash.com/photo-1551698618-1dfe5d97d256?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="Groupe d'étudiants profitant du ski" class="lifestyle-image">
        </div>
    </section>

    <section class="credibility">
        <div class="container">
            <h2>Le plus grand terrain de jeu des Pyrénées</h2>
            <div class="credibility-content">
                <div class="credibility-text">
                    <p style="margin-bottom: 1.5rem;">La <strong>Carte No Souci Pyrénées</strong> s'appuie sur le savoir-faire pionnier de N'PY. Elle ouvre les portes de <strong>14 domaines skiables majeurs</strong> à travers la chaîne (Ouest, Centre, Est et Ariège).</p>
                    
                    <p style="margin-bottom: 1rem; font-size: 1.2rem; color: var(--accent); font-weight: bold;">Vos étudiants pourront rider à :</p>
                    <ul style="list-style-type: none; margin-left: 0; line-height: 1.8;">
                        <li>❄️ <strong>Réseau historique :</strong> Peyragudes, Piau-Engaly, Grand Tourmalet, Pic du Midi, Luz-Ardiden, Cauterets, Gourette, La Pierre Saint-Martin.</li>
                        <li>❄️ <strong>Partenaires :</strong> Ax 3 Domaines, Guzet, Les Monts d'Olmes, Formiguères, Porté-Puymorens et le Cambre d'Aze.</li>
                    </ul>
                </div>
                <div class="card-image-container">
                    <img src="carte-no-souci-pyrenees.png" alt="Carte No Souci Pyrénées" class="card-image">
                </div>
            </div>
        </div>
    </section>

    <section class="faq">
        <div class="container" style="max-width: 800px;">
            <h2>Questions Fréquentes (FAQ BDE)</h2>

            <div class="faq-item">
                <h3>À qui s'adresse le programme Partenaire N'PY ?</h3>
                <div class="faq-content">
                    <p>Il s'adresse aux Bureaux des Élèves (BDE), Bureaux des Sports (BDS), associations universitaires et administrations d'écoles qui souhaitent offrir un avantage exclusif à leurs étudiants pour la saison d'hiver.</p>
                </div>
            </div>

            <div class="faq-item">
                <h3>L'école ou le BDE doit-il payer quelque chose ?</h3>
                <div class="faq-content">
                    <p><strong>Non, c'est un partenariat 100% gratuit pour votre structure.</strong> Nous vous fournissons un code promotionnel unique. Les étudiants s'abonnent individuellement sur notre plateforme en utilisant ce code pour bénéficier d'un tarif préférentiel sur l'adhésion annuelle.</p>
                </div>
            </div>

            <div class="faq-item">
                <h3>Comment les étudiants reçoivent-ils leur carte ?</h3>
                <div class="faq-content">
                    <p>Tout se passe en ligne. L'étudiant s'inscrit, renseigne son adresse postale, et reçoit sa carte personnelle équipée d'une puce RFID directement dans sa boîte aux lettres sous quelques jours.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="cta">
        <div class="container">
            <h2>Prêt à booster la vie de votre campus ?</h2>
            <p>Mettez en place votre partenariat BDE gratuitement en moins de 48 heures. Proposez à vos étudiants le ski en toute liberté.</p>
            <a href="mailto:contact@n-py.com" class="btn">Créer notre partenariat BDE (Gratuit)</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2026 N'PY - Carte No Souci Pyrénées</p>
            <p style="margin-top: 0.5rem;">Le réseau n°1 des stations de ski des Pyrénées françaises</p>
        </div>
    </footer>

    <script>
        document.querySelectorAll('.faq-item h3').forEach(item => {
            item.addEventListener('click', function() {
                const parent = this.parentElement;
                
                // Si on clique sur un élément déjà ouvert, on le ferme
                if (parent.classList.contains('active')) {
                    parent.classList.remove('active');
                } else {
                    // Sinon, on ferme tout et on ouvre celui cliqué
                    document.querySelectorAll('.faq-item').forEach(otherItem => {
                        otherItem.classList.remove('active');
                    });
                    parent.classList.add('active');
                }
            });
        });
    </script>
</body>
</html>

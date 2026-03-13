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

        header {
            background: linear-gradient(135deg, #1a2f4e 0%, #0d1a2a 100%);
            color: var(--secondary);
            padding: 3rem 0;
            text-align: center;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero-subtitle {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 2rem;
        }

        .hero-image {
            max-width: 100%;
            height: auto;
            border-radius: 12px;
            box-shadow: 0 8px 16px rgba(0,0,0,0.3);
            margin-top: 1.5rem;
            max-height: 400px;
            object-fit: cover;
        }

        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 4rem 0;
        }

        .benefit-card {
            background: var(--secondary);
            border-radius: 10px;
            padding: 2rem;
            box-shadow: var(--shadow);
            transition: transform 0.3s ease;
        }

        .benefit-card:hover {
            transform: translateY(-5px);
        }

        .benefit-card h3 {
            color: var(--accent);
            margin-bottom: 1rem;
            font-size: 1.2rem;
        }

        .credibility {
            background-color: #f5f5f5;
            padding: 4rem 0;
            text-align: center;
        }

        .credibility-content {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
            margin-top: 2rem;
        }

        .credibility-text {
            flex: 1;
            min-width: 300px;
            text-align: left;
        }

        .card-image {
            max-width: 350px;
            border-radius: 10px;
            box-shadow: var(--shadow);
        }

        .faq {
            padding: 4rem 0;
        }

        .faq-item {
            margin-bottom: 1.5rem;
            border-bottom: 1px solid #ddd;
            padding-bottom: 1rem;
        }

        .faq-item h3 {
            color: var(--accent);
            cursor: pointer;
            margin-bottom: 0.5rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .faq-item h3::after {
            content: '+';
            font-size: 1.5rem;
            color: var(--primary);
        }

        .faq-item.active h3::after {
            content: '-';
        }

        .faq-content {
            display: none;
            animation: fadeIn 0.3s ease;
            color: #444;
        }

        .faq-item.active .faq-content {
            display: block;
        }

        .cta {
            text-align: center;
            padding: 4rem 0;
            background: linear-gradient(135deg, #1a2f4e 0%, #0d1a2a 100%);
            color: var(--secondary);
        }

        .cta p {
            margin-bottom: 2rem;
            font-size: 1.1rem;
        }

        .btn {
            display: inline-block;
            background-color: var(--accent);
            color: var(--secondary);
            padding: 1rem 2rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin: 0.5rem;
            transition: all 0.3s ease;
        }

        .btn:hover {
            background-color: #e65c2a;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .btn-outline {
            background-color: transparent;
            border: 2px solid var(--accent);
            color: var(--accent);
        }

        .btn-outline:hover {
            background-color: rgba(255, 107, 53, 0.1);
        }

        footer {
            background-color: #0d1a2a;
            color: #888;
            text-align: center;
            padding: 2rem 0;
            font-size: 0.9rem;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            .hero-subtitle {
                font-size: 1rem;
            }
            .credibility-content {
                flex-direction: column;
            }
            .credibility-text {
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Offrez le ski facile et à prix réduit à vos étudiants</h1>
            <p class="hero-subtitle">Proposez à votre campus le sésame ultime pour skier dans 14 stations des Pyrénées. Fini les attentes aux caisses, place au paiement à l'usage et aux réductions étudiantes massives avec la Carte No Souci Pyrénées.</p>
            <img src="http://googleusercontent.com/image_collection/image_retrieval/11769741549560998232" alt="Étudiants profitant du ski dans les Pyrénées avec N'PY" class="hero-image">
        </div>
    </header>

    <section class="benefits">
        <div class="container">
            <h2 style="text-align: center; margin-bottom: 3rem;">4 raisons d'adopter la Carte No Souci pour votre BDE</h2>

            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem;">
                <div class="benefit-card">
                    <h3>✅ Zéro charge mentale pour le BDE</h3>
                    <p>Valorisez votre offre étudiante avec un service "clé en main". Vous n'avez aucune commande de forfaits cartonnés à gérer, aucune récolte de fonds ni distribution le samedi matin. Tout est 100% digitalisé : vous diffusez votre code promo école, on s'occupe du reste.</p>
                </div>

                <div class="benefit-card">
                    <h3>💸 Un budget étudiant préservé</h3>
                    <p>Les réductions sont automatiques : <strong>jusqu'à -30%</strong> sur les journées skiées en semaine (hors vacances scolaires), et <strong>-15%</strong> garantis tous les week-ends. La 7ème journée de la saison est même à <strong>-50%</strong> !</p>
                </div>

                <div class="benefit-card">
                    <h3>🎿 Fini le passage en caisse</h3>
                    <p>Une fois la carte reçue, vos étudiants accèdent directement aux remontées mécaniques. Le système est basé sur le télépéage : on skie d'abord, on est prélevé sur son compte bancaire le mois suivant uniquement pour les journées réellement consommées.</p>
                </div>

                <div class="benefit-card">
                    <h3>🛡️ L'Assurance secours incluse</h3>
                    <p>C'est l'argument qui rassure l'administration de l'école : l'assurance secours sur piste est <strong>intégrée par défaut</strong> à l'abonnement. En cas de pépin sur les pistes, les frais d'évacuation sont couverts sans avoir à payer un supplément journalier.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="credibility">
        <div class="container">
            <h2>Le plus grand terrain de jeu des Pyrénées</h2>
            <div class="credibility-content">
                <div class="credibility-text">
                    <p>La Carte No Souci s'appuie sur le savoir-faire pionnier de N'PY. Elle ne se limite plus à quelques stations, elle ouvre désormais les portes de <strong>14 domaines skiables majeurs</strong> à travers la chaîne des Pyrénées (Ouest, Centre, Est et Ariège).</p>
                    <br>
                    <p><strong>Vos étudiants pourront rider à :</strong><br>
                    Peyragudes, Piau-Engaly, Grand Tourmalet, Pic du Midi, Luz-Ardiden, Cauterets, Gourette, La Pierre Saint-Martin, mais aussi Ax 3 Domaines, Guzet, Les Monts d'Olmes, Formiguères, Porté-Puymorens et le Cambre d'Aze.</p>
                </div>
                <img src="http://googleusercontent.com/image_collection/image_retrieval/8835171390932294707" alt="Aperçu de la Carte No Souci Pyrénées" class="card-image">
            </div>
        </div>
    </section>

    <section class="faq">
        <div class="container">
            <h2 style="text-align: center; margin-bottom: 3rem;">Questions Fréquentes (FAQ BDE)</h2>

            <div class="faq-item">
                <h3>À qui s'adresse le programme Partenaire N'PY ?</h3>
                <div class="faq-content">
                    <p>Il s'adresse aux Bureaux des Élèves (BDE), Bureaux des Sports (BDS), associations universitaires et administrations d'écoles qui souhaitent offrir un avantage exclusif à leurs étudiants pour la saison d'hiver (et d'été !).</p>
                </div>
            </div>

            <div class="faq-item">
                <h3>L'école ou le BDE doit-il payer quelque chose ?</h3>
                <div class="faq-content">
                    <p><strong>Non, c'est un partenariat 100% gratuit pour votre structure.</strong> Nous vous fournissons un code promotionnel unique. Les étudiants s'abonnent individuellement sur notre plateforme en utilisant ce code pour bénéficier du tarif réduit sur l'adhésion annuelle de la carte.</p>
                </div>
            </div>

            <div class="faq-item">
                <h3>Comment les étudiants reçoivent-ils leur carte ?</h3>
                <div class="faq-content">
                    <p>Tout se passe en ligne. L'étudiant s'inscrit, renseigne son adresse et son moyen de paiement, et reçoit sa carte personnelle équipée d'une puce RFID directement dans sa boîte aux lettres en quelques jours.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="cta">
        <div class="container">
            <h2>Passez à l'action pour booster la vie de votre campus</h2>
            <p>Mettez en place votre partenariat BDE gratuitement en moins de 48 heures. Proposez à vos étudiants le ski sans contraintes.</p>
            <a href="#devenir-partenaire" class="btn">Créer un partenariat BDE (Gratuit)</a>
            <a href="#contact" class="btn btn-outline">Contacter notre équipe Campus</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2026 N'PY - Carte No Souci Pyrénées</p>
            <p>Le réseau n°1 des stations de ski des Pyrénées</p>
        </div>
    </footer>

    <script>
        // Script pour l'accordéon de la FAQ
        document.querySelectorAll('.faq-item h3').forEach(item => {
            item.addEventListener('click', function() {
                // Ferme les autres onglets ouverts (optionnel)
                document.querySelectorAll('.faq-item').forEach(otherItem => {
                    if (otherItem !== this.parentElement) {
                        otherItem.classList.remove('active');
                    }
                });
                // Ouvre/ferme l'onglet cliqué
                this.parentElement.classList.toggle('active');
            });
        });
    </script>
</body>
</html>

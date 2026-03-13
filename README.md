# N-Py-Landing-page
Landing page N'Py
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Carte ski étudiant Pyrénées : carte ski sans abonnement, ski paiement à l’usage et accès simplifié aux stations N’PY pour les étudiants.">
    <meta property="og:title" content="Carte ski étudiant Pyrénées | Carte No Souci N’PY">
    <meta property="og:description" content="Carte ski étudiant Pyrénées : carte ski sans abonnement, ski paiement à l’usage et accès simplifié aux stations N’PY pour les étudiants.">
    <meta property="og:type" content="website">
    <title>Carte ski étudiant Pyrénées | Carte No Souci N’PY</title>
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
            padding: 2rem 0;
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

        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 3rem 0;
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
        }

        .credibility {
            background-color: #f5f5f5;
            padding: 3rem 0;
            text-align: center;
        }

        .faq {
            padding: 3rem 0;
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
        }

        .faq-content {
            display: none;
            animation: fadeIn 0.3s ease;
        }

        .faq-item.active .faq-content {
            display: block;
        }

        .cta {
            text-align: center;
            padding: 3rem 0;
            background: linear-gradient(135deg, #1a2f4e 0%, #0d1a2a 100%);
            color: var(--secondary);
        }

        .btn {
            display: inline-block;
            background-color: var(--accent);
            color: var(--primary);
            padding: 0.8rem 1.5rem;
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

        footer {
            background-color: var(--primary);
            color: var(--secondary);
            text-align: center;
            padding: 2rem 0;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }

            .hero-subtitle {
                font-size: 1rem;
            }

            .benefits {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Offrez le ski facile à vos étudiants avec N’PY</h1>
            <p class="hero-subtitle">Proposez à vos étudiants une carte unique pour skier dans les Pyrénées sans racheter un forfait à chaque visite. La Carte No Souci N’PY simplifie l'accès aux stations, fluidifie l'expérience et favorise les adhésions individuelles.</p>
        </div>
    </header>

    <section class="benefits">
        <div class="container">
            <h2>4 bénéfices clés de la Carte No Souci pour le ski étudiant</h2>

            <div class="benefit-card">
                <h3>Pour votre établissement : un avantage campus concret</h3>
                <p>Valorisez votre offre étudiante avec un service immédiatement utile, simple à comprendre et facile à relayer. La Carte No Souci renforce l'attractivité de votre établissement en associant vie campus, sport et loisirs. C'est une opportunité de proposer un bénéfice différenciant qui parle aux étudiants et s'intègre naturellement dans votre communication.</p>
            </div>

            <div class="benefit-card">
                <h3>Pour votre établissement : une carte ski sans abonnement simple à promouvoir</h3>
                <p>La promesse est claire : une carte, plusieurs stations, un paiement à l'usage. Cette simplicité facilite la diffusion de l'offre auprès des étudiants, des BDE et des associations. Vous gagnez en lisibilité, sans avoir à porter une organisation complexe, grâce à un dispositif déjà structuré par le réseau N'PY.</p>
            </div>

            <div class="benefit-card">
                <h3>Pour les étudiants : un accès au ski plus fluide dans les stations ski Pyrénées étudiants</h3>
                <p>Une fois inscrits, les étudiants accèdent directement aux remontées mécaniques avec leur carte personnelle. Plus besoin d'acheter un forfait ski étudiant Pyrénées à chaque venue. Ils gagnent du temps, évitent les files d'attente et profitent d'une expérience plus pratique pour les journées ski, snowboard, week-ends montagne ou séjours répés.</p>
            </div>

            <div class="benefit-card">
                <h3>Pour les étudiants : plus de liberté avec le ski paiement à l'usage</h3>
                <p>La Carte No Souci fonctionne sur un principe de ski paiement à l'usage : les étudiants paient uniquement les journées réellement skiées. Ils peuvent également utiliser la même carte dans plusieurs stations du réseau N'PY, comme Cauterets, Peyragudes, Piau-Engaly et Grand Tourmalet, avec des avantages tarifaires associés.</p>
            </div>
        </div>
    </section>

    <section class="credibility">
        <div class="container">
            <h2>Une offre crédible pour les stations ski Pyrénées étudiants, pensée à l'échelle des Pyrénées</h2>
            <p>La Carte No Souci s'appuie sur le réseau N'PY et sur un système digitalisé déjà en place dans plusieurs stations des Pyrénées françaises. Une seule carte permet l'accès aux remontées mécaniques dans 8 stations du réseau, avec une inscription en ligne, une carte personnelle équipée d'une puce et un paiement automatique à l'usage.</p>
        </div>
    </section>

    <section class="faq">
        <div class="container">
            <h2>FAQ sur la carte ski sans abonnement N'PY</h2>

            <div class="faq-item">
                <h3>À qui s'adresse la Carte No Souci pour le forfait ski étudiant Pyrénées ?</h3>
                <div class="faq-content">
                    <p>Elle s'adresse principalement aux personnes qui fréquentent régulièrement les stations des Pyrénées, notamment les étudiants, les BDE, les associations sportives et les publics campus qui souhaitent skier plusieurs fois dans la saison sans refaire les mêmes démarches à chaque visite.</p>
                </div>
            </div>

            <div class="faq-item">
                <h3>Dans quelles stations ski Pyrénées étudiants la carte fonctionne-t-elle ?</h3>
                <div class="faq-content">
                    <p>La carte est utilisable dans les stations du réseau N'PY, parmi lesquelles figurent notamment Cauterets, Peyragudes, Piau-Engaly et Grand Tourmalet. Elle permet de profiter plus facilement des remontées mécaniques dans plusieurs domaines skiables des Pyrénées.</p>
                </div>
            </div>

            <div class="faq-item">
                <h3>Pourquoi proposer cette offre de ski accessible campus dans un établissement ?</h3>
                <div class="faq-content">
                    <p>Parce qu'elle permet de diffuser un avantage simple, concret et attractif, en lien direct avec les attentes étudiantes autour du ski, du snowboard et des loisirs de montagne. Elle contribue à dynamiser la vie campus et à encourager les adhésions individuelles à un service réellement utile.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="cta">
        <div class="container">
            <h2>Passez à l'action pour proposer un ski accessible campus</h2>
            <p>Proposez à vos étudiants une nouvelle façon de profiter du ski dans les Pyrénées : plus simple, plus rapide et plus flexible.</p>
            <a href="#" class="btn">Demander un partenariat Carte No Souci</a>
            <a href="#" class="btn">Recevoir la présentation de l'offre</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2023 N'PY - Carte No Souci</p>
            <p>Réseau de stations de ski des Pyrénées françaises</p>
        </div>
    </footer>

    <script>
        document.querySelectorAll('.faq-item h3').forEach(item => {
            item.addEventListener('click', function() {
                this.parentElement.classList.toggle('active');
            });
        });
    </script>
</body>
</html>

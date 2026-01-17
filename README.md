# Bproservice.github.io.
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>B-Pro Service – Nettoyage professionnel à Bruxelles & Schaerbeek</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="B-Pro Service – Nettoyage professionnel de bureaux, bâtiments, communs et fins de chantier à Bruxelles et Schaerbeek. Devis rapide et service soigné.">
    
    @media (max-width: 480px) {
    .container {
        padding: 0 10px;
    }

    .btn {
        width: 100%;
        justify-content: center;
    }

    .hero-actions {
        flex-direction: column;
    }

    .section-title {
        font-size: 1.3rem;
    }
}

    <style>
        :root {
            --primary: #1c7ed6;
            --primary-dark: #1864ab;
            --accent: #82c91e;
            --bg: #f5f7fb;
            --text-main: #222;
            --text-muted: #666;
            --card-bg: #ffffff;
            --border: #dde1ea;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
            background: #ffffff;
            color: var(--text-main);
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 16px;
        }

        /* HEADER */
        header {
            position: sticky;
            top: 0;
            z-index: 50;
            background: rgba(255,255,255,0.96);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid var(--border);
        }

        .nav {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 0;
        }

        .logo-block {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo-icon {
            width: 34px;
            height: 34px;
            border-radius: 10px;
            border: 2px solid var(--primary);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 700;
            color: var(--primary);
            font-size: 0.9rem;
        }

        .logo-text {
            display: flex;
            flex-direction: column;
            font-size: 0.95rem;
        }

        .logo-text span:first-child {
            font-weight: 700;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 18px;
            font-size: 0.9rem;
        }

        nav a {
            padding: 4px 0;
            border-bottom: 2px solid transparent;
        }

        nav a:hover {
            border-color: var(--primary);
        }

        .nav-actions {
            display: flex;
            gap: 8px;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 9px 18px;
            border-radius: 999px;
            font-size: 0.9rem;
            font-weight: 500;
            border: none;
            cursor: pointer;
            transition: 0.2s ease;
            white-space: nowrap;
        }

        .btn-primary {
            background: var(--primary);
            color: #fff;
        }

        .btn-primary:hover {
            background: var(--primary-dark);
        }

        .btn-ghost {
            background: transparent;
            border: 1px solid var(--border);
            color: var(--text-main);
        }

        .btn-ghost:hover {
            border-color: var(--primary);
        }

        /* HERO */
        .hero {
            background: radial-gradient(circle at top left, #e7f5ff, #ffffff);
            padding: 38px 0 40px;
        }

        .hero-grid {
            display: grid;
            grid-template-columns: minmax(0, 1.1fr) minmax(0, 0.9fr);
            gap: 32px;
            align-items: center;
        }

        .hero-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: #e7f5ff;
            color: var(--primary-dark);
            padding: 4px 10px;
            border-radius: 999px;
            font-size: 0.8rem;
            margin-bottom: 10px;
        }

        .hero-badge span {
            font-size: 1rem;
        }

        .hero h1 {
            font-size: 2.2rem;
            line-height: 1.2;
            margin-bottom: 10px;
        }

        .hero-subtitle {
            font-size: 0.98rem;
            color: var(--text-muted);
            margin-bottom: 18px;
            max-width: 550px;
        }

        .hero-actions {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 18px;
        }

        .hero-list {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 6px 20px;
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        .hero-list span {
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .hero-list span::before {
            content: "✓";
            color: var(--accent);
            font-size: 0.95rem;
        }

        .hero-visual {
            background: #ffffff;
            border-radius: 20px;
            padding: 18px;
            border: 1px solid var(--border);
            box-shadow: 0 14px 40px rgba(15, 23, 42, 0.12);
        }

        .hero-illustration {
            border-radius: 14px;
            background: linear-gradient(135deg, #1c7ed6, #82c91e);
            color: #fff;
            padding: 18px;
            display: grid;
            grid-template-columns: auto 1fr;
            gap: 14px;
            align-items: center;
        }

        .hero-emoji {
            font-size: 2.4rem;
        }

        .hero-illu-text {
            font-size: 0.9rem;
        }

        .hero-stats {
            display: flex;
            gap: 18px;
            margin-top: 12px;
            font-size: 0.8rem;
            color: var(--text-muted);
        }

        .hero-stats div {
            flex: 1;
        }

        .hero-stats strong {
            display: block;
            font-size: 1.1rem;
            color: var(--primary-dark);
        }

        /* SECTIONS */
        section {
            padding: 40px 0;
        }

        .section-header {
            margin-bottom: 18px;
        }

        .section-title {
            font-size: 1.5rem;
            margin-bottom: 4px;
        }

        .section-subtitle {
            font-size: 0.95rem;
            color: var(--text-muted);
            max-width: 540px;
        }

        /* CARDS */
        .cards {
            display: grid;
            grid-template-columns: repeat(3, minmax(0, 1fr));
            gap: 18px;
        }

        .card {
            background: var(--card-bg);
            border-radius: 16px;
            padding: 16px;
            border: 1px solid var(--border);
            box-shadow: 0 4px 14px rgba(15, 23, 42, 0.04);
            transition: transform 0.15s ease, box-shadow 0.15s ease;
        }

        .card:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 26px rgba(15, 23, 42, 0.12);
        }

        .card-icon {
            font-size: 1.7rem;
            margin-bottom: 6px;
        }

        .card h3 {
            font-size: 1.02rem;
            margin-bottom: 4px;
        }

        .card p {
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        .chip-row {
            margin-top: 8px;
            display: flex;
            flex-wrap: wrap;
            gap: 4px;
        }

        .chip {
            font-size: 0.75rem;
            padding: 3px 8px;
            border-radius: 999px;
            background: #f1f3f5;
            color: var(--text-muted);
        }

        /* POUR QUI */
        .grid-2 {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 22px;
        }

        .list {
            list-style: none;
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        .list li {
            position: relative;
            padding-left: 18px;
            margin-bottom: 6px;
        }

        .list li::before {
            content: "•";
            position: absolute;
            left: 5px;
            top: 0;
            color: var(--primary);
        }

        /* PROCESS */
        .steps {
            display: grid;
            grid-template-columns: repeat(4, minmax(0, 1fr));
            gap: 14px;
            margin-top: 16px;
        }

        .step {
            background: #f5f7fb;
            border-radius: 14px;
            padding: 12px;
            font-size: 0.85rem;
        }

        .step-number {
            width: 24px;
            height: 24px;
            border-radius: 999px;
            background: #ffffff;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.85rem;
            font-weight: 600;
            color: var(--primary);
            margin-bottom: 4px;
        }

        .step h3 {
            font-size: 0.9rem;
            margin-bottom: 3px;
        }

        .pill-row {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 12px;
        }

        .pill {
            font-size: 0.8rem;
            padding: 6px 10px;
            border-radius: 999px;
            border: 1px solid var(--border);
            background: #fff;
            color: var(--text-muted);
        }

        /* TEMOIGNAGES */
        .testimonials {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 16px;
            margin-top: 12px;
        }

        .testimonial {
            background: #ffffff;
            border-radius: 14px;
            padding: 14px;
            border: 1px solid var(--border);
            font-size: 0.88rem;
            color: var(--text-muted);
        }

        .testimonial strong {
            display: block;
            margin-top: 8px;
            color: var(--text-main);
        }

        /* FAQ (INTERACTIF) */
        .faq {
            margin-top: 18px;
        }

        .faq-item {
            border-radius: 12px;
            border: 1px solid var(--border);
            padding: 10px 12px;
            margin-bottom: 8px;
            background: #ffffff;
            cursor: pointer;
        }

        .faq-question {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 0.92rem;
            font-weight: 500;
        }

        .faq-toggle {
            font-size: 1.2rem;
            color: var(--primary);
        }

        .faq-answer {
            margin-top: 6px;
            font-size: 0.86rem;
            color: var(--text-muted);
            display: none;
        }

        .faq-item.open .faq-answer {
            display: block;
        }

        /* CONTACT */
        .contact-section {
            background: var(--bg);
        }

        .contact-grid {
            display: grid;
            grid-template-columns: minmax(0, 1.1fr) minmax(0, 0.9fr);
            gap: 22px;
            margin-top: 16px;
        }

        .contact-block {
            font-size: 0.92rem;
            color: var(--text-main);
        }

        .contact-block p {
            margin-bottom: 6px;
        }

        .contact-highlight {
            margin-top: 10px;
            padding: 10px 12px;
            border-radius: 12px;
            background: #ffffff;
            border: 1px dashed var(--border);
            font-size: 0.84rem;
            color: var(--text-muted);
        }

        form {
            display: grid;
            gap: 8px;
        }

        label {
            font-size: 0.82rem;
            font-weight: 500;
        }

        input, textarea {
            width: 100%;
            padding: 7px 9px;
            border-radius: 10px;
            border: 1px solid var(--border);
            font-size: 0.9rem;
            font-family: inherit;
        }

        textarea {
            resize: vertical;
            min-height: 80px;
        }

        /* FOOTER */
        footer {
            padding: 16px 0 24px;
            border-top: 1px solid var(--border);
            font-size: 0.8rem;
            color: var(--text-muted);
        }

        footer .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 8px;
        }

        /* RESPONSIVE */
        @media (max-width: 900px) {
            .hero-grid,
            .contact-grid {
                grid-template-columns: minmax(0, 1fr);
            }
        }

        @media (max-width: 800px) {
            nav ul {
                display: none;
            }
            .cards {
                grid-template-columns: repeat(2, minmax(0, 1fr));
            }
            .steps {
                grid-template-columns: repeat(2, minmax(0, 1fr));
            }
            .testimonials {
                grid-template-columns: minmax(0, 1fr);
            }
        }

        @media (max-width: 600px) {
            .cards {
                grid-template-columns: minmax(0, 1fr);
            }
            .steps {
                grid-template-columns: minmax(0, 1fr);
            }
            .hero h1 {
                font-size: 1.9rem;
            }
        }
    </style>
</head>
<body>

<header>
    <div class="container nav">
        <div class="logo-block">
            <div class="logo-icon">BP</div>
            <div class="logo-text">
                <span>B-Pro Service</span>
                <span>Nettoyage professionnel – Bruxelles</span>
            </div>
        </div>

        <nav>
            <ul>
                <li><a href="#services">Services</a></li>
                <li><a href="#secteurs">Pour qui ?</a></li>
                <li><a href="#pourquoi">Pourquoi nous</a></li>
                <li><a href="#contact">Devis</a></li>
            </ul>
        </nav>

        <div class="nav-actions">
            <a href="tel:+32477135113" class="btn btn-ghost">Appeler</a>
            <a href="#contact" class="btn btn-primary">Devis gratuit</a>
        </div>
    </div>
</header>

<main>
    <!-- HERO -->
    <section class="hero">
        <div class="container hero-grid">
            <div>
                <div class="hero-badge">
                    <span>🧹</span> Nettoyage général • Bureaux • Fin de chantier
                </div>
                <h1>Nettoyage professionnel de bureaux & bâtiments à Bruxelles</h1>
                <p class="hero-subtitle">
                    B-Pro Service est une société de nettoyage basée à Schaerbeek.
                    Nous prenons en charge l’entretien de vos bureaux, bâtiments,
                    communs et fins de chantier, avec un service fiable, soigné
                    et adapté à vos horaires.
                </p>

                <div class="hero-actions">
                    <a href="#contact" class="btn btn-primary">Demander un devis sous 24h</a>
                    <a href="tel:+32477135113" class="btn btn-ghost">📞 Appeler B-Pro Service</a>
                </div>

                <div class="hero-list">
                    <span>Spécialiste bureaux & immeubles</span>
                    <span>Fin de chantier prête à livrer</span>
                    <span>Interventions tôt le matin ou soirée</span>
                    <span>Service pour syndics & entrepreneurs</span>
                </div>
            </div>

            <div class="hero-visual">
                <div class="hero-illustration">
                    <div class="hero-emoji">🧽🧼🧹</div>
                    <div class="hero-illu-text">
                        <strong>B-Pro Service</strong><br>
                        Entretien régulier, remises en état après travaux,
                        parties communes propres et accueillantes pour vos
                        occupants et vos clients.
                    </div>
                </div>
                <div class="hero-stats">
                    <div>
                        <strong>+ Bruxelles</strong>
                        Zone principale : Schaerbeek & environs
                    </div>
                    <div>
                        <strong>Service pro</strong>
                        Interlocuteur unique : Cédric De Backer
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SERVICES -->
    <section id="services">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Nos services de nettoyage</h2>
                <p class="section-subtitle">
                    Prestations régulières ou ponctuelles, adaptées à la surface de vos locaux
                    et à votre activité.
                </p>
            </div>

            <div class="cards">
                <div class="card">
                    <div class="card-icon">🏢</div>
                    <h3>Nettoyage de bureaux</h3>
                    <p>
                        Entretien complet des bureaux, open-spaces, salles de réunion,
                        cuisines et sanitaires pour offrir à vos équipes un environnement
                        propre et agréable.
                    </p>
                    <div class="chip-row">
                        <span class="chip">Dépoussiérage</span>
                        <span class="chip">Sols & poubelles</span>
                        <span class="chip">Sanitaires</span>
                    </div>
                </div>

                <div class="card">
                    <div class="card-icon">🏢🧹</div>
                    <h3>Bâtiments & communs</h3>
                    <p>
                        Nettoyage des halls d’entrée, escaliers, couloirs,
                        ascenseurs et autres parties communes pour valoriser
                        vos immeubles et rassurer les occupants.
                    </p>
                    <div class="chip-row">
                        <span class="chip">Copropriétés</span>
                        <span class="chip">Résidences</span>
                        <span class="chip">Parkings</span>
                    </div>
                </div>

                <div class="card">
                    <div class="card-icon">🚧</div>
                    <h3>Fin de chantier</h3>
                    <p>
                        Remise en état après travaux ou rénovation : élimination
                        des poussières, résidus, traces sur les sols et menuiseries
                        pour une livraison propre et soignée.
                    </p>
                    <div class="chip-row">
                        <span class="chip">Avant livraison</span>
                        <span class="chip">Promoteurs</span>
                        <span class="chip">Entrepreneurs</span>
                    </div>
                </div>

                <div class="card">
                    <div class="card-icon">🪟</div>
                    <h3>Vitres & vitrines</h3>
                    <p>
                        Nettoyage de vitres intérieures et extérieures,
                        vitrines de commerces et grandes surfaces vitrées.
                    </p>
                    <div class="chip-row">
                        <span class="chip">Bureaux</span>
                        <span class="chip">Commerces</span>
                    </div>
                </div>

                <div class="card">
                    <div class="card-icon">🚗</div>
                    <h3>Parkings & locaux techniques</h3>
                    <p>
                        Entretien de parkings, caves, garages et locaux techniques,
                        en interventions ponctuelles ou dans le cadre d’un contrat.
                    </p>
                    <div class="chip-row">
                        <span class="chip">Balayage</span>
                        <span class="chip">Lavage</span>
                    </div>
                </div>

                <div class="card">
                    <div class="card-icon">✨</div>
                    <h3>Prestations sur mesure</h3>
                    <p>
                        Nettoyages ponctuels, remises à blanc, besoins spécifiques…
                        Expliquez votre situation, B-Pro Service vous propose une
                        solution adaptée.
                    </p>
                    <div class="chip-row">
                        <span class="chip">Ponctuel</span>
                        <span class="chip">Sur mesure</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- POUR QUI -->
    <section id="secteurs">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Pour qui travaillons-nous ?</h2>
                <p class="section-subtitle">
                    B-Pro Service s’adresse principalement aux professionnels
                    à Bruxelles, Schaerbeek et les communes voisines.
                </p>
            </div>

            <div class="grid-2">
                <div>
                    <h3>Entreprises & bureaux</h3>
                    <ul class="list">
                        <li>PME, indépendants, cabinets, coworking</li>
                        <li>Horaires adaptés : tôt le matin, journée ou soirée</li>
                        <li>Contrats réguliers (journalier, hebdomadaire, mensuel)</li>
                    </ul>

                    <h3 style="margin-top:12px;">Immeubles & copropriétés</h3>
                    <ul class="list">
                        <li>Syndics, gestionnaires immobiliers, propriétaires</li>
                        <li>Entretien des parties communes et extérieurs proches</li>
                        <li>Interventions ponctuelles en cas de besoin</li>
                    </ul>
                </div>

                <div>
                    <h3>Promoteurs & entrepreneurs</h3>
                    <ul class="list">
                        <li>Fin de chantier logements, bureaux, commerces</li>
                        <li>Nettoyage avant réception ou remise des clés</li>
                        <li>Organisation flexible selon l’avancement des travaux</li>
                    </ul>

                    <h3 style="margin-top:12px;">Commerces & autres locaux</h3>
                    <ul class="list">
                        <li>Magasins, petits showrooms, bureaux en rez-de-chaussée</li>
                        <li>Nettoyage avant ouverture ou après fermeture</li>
                        <li>Prestation unique ou récurrente selon vos besoins</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- POURQUOI NOUS -->
    <section id="pourquoi">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Pourquoi choisir B-Pro Service ?</h2>
                <p class="section-subtitle">
                    Un interlocuteur unique, un suivi sérieux et un nettoyage soigné
                    pour que vous puissiez vous concentrer sur votre activité.
                </p>
            </div>

            <div class="pill-row">
                <div class="pill">Entreprise à taille humaine</div>
                <div class="pill">Contact direct avec le fondateur</div>
                <div class="pill">Devis clairs et transparents</div>
                <div class="pill">Respect des locaux et du voisinage</div>
                <div class="pill">Horaires flexibles</div>
                <div class="pill">Travail soigné</div>
            </div>

            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Prise de contact</h3>
                    <p>Vous expliquez vos besoins (type de locaux, surface, fréquence souhaitée).</p>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Visite si nécessaire</h3>
                    <p>Une visite des lieux permet d’évaluer précisément le travail à réaliser.</p>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Devis sur mesure</h3>
                    <p>Vous recevez un devis adapté à votre situation, sans surprise.</p>
                </div>
                <div class="step">
                    <div class="step-number">4</div>
                    <h3>Prestation & suivi</h3>
                    <p>Les interventions sont réalisées comme convenu, avec possibilité d’ajustement.</p>
                </div>
            </div>

            <div class="testimonials">
                <div class="testimonial">
                    « Locaux toujours propres, communication simple et directe.
                    Très pratique pour notre petite structure. »
                    <strong>Client PME – Bruxelles (témoignage type)</strong>
                </div>
                <div class="testimonial">
                    « Fin de chantier nettoyée dans les délais, livraison impeccable
                    pour le client final. »
                    <strong>Entrepreneur rénovation – Région Bruxelles (témoignage type)</strong>
                </div>
            </div>

            <div class="faq">
                <div class="section-header" style="margin-top:18px;">
                    <h3 style="font-size:1.05rem;">Questions fréquentes</h3>
                </div>

                <div class="faq-item">
                    <div class="faq-question">
                        <span>Intervenez-vous aussi chez les particuliers ?</span>
                        <span class="faq-toggle">+</span>
                    </div>
                    <div class="faq-answer">
                        B-Pro Service est principalement orientée vers les bureaux,
                        immeubles, syndics et chantiers. Pour certains nettoyages
                        spécifiques chez les particuliers (fin de travaux, remise en
                        état), une étude est possible au cas par cas.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">
                        <span>Dans quelles communes intervenez-vous ?</span>
                        <span class="faq-toggle">+</span>
                    </div>
                    <div class="faq-answer">
                        La société est basée à Schaerbeek et intervient en priorité
                        à Bruxelles et dans les communes voisines. Pour des chantiers
                        spécifiques, un déplacement un peu plus large est possible.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">
                        <span>Pouvez-vous travailler tôt le matin ou en soirée ?</span>
                        <span class="faq-toggle">+</span>
                    </div>
                    <div class="faq-answer">
                        Oui, les horaires sont adaptés au maximum pour ne pas perturber
                        votre activité : tôt le matin, en journée ou en soirée selon
                        les disponibilités.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="contact-section">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Contact & devis</h2>
                <p class="section-subtitle">
                    Expliquez brièvement vos besoins (type de locaux, surface, fréquence).
                    Vous recevrez une réponse dans les meilleurs délais.
                </p>
            </div>

            <div class="contact-grid">
                <div class="contact-block">
                    <p><strong>B-Pro Service</strong></p>
                    <p>Fondateur : Cédric De Backer</p>

                    <p style="margin-top:6px;">
                        Emile Wittmann 14<br>
                        1030 Schaerbeek – Belgique
                    </p>

                    <p style="margin-top:6px;">
                        N° TVA : BE 1020.676.164
                    </p>

                    <p style="margin-top:6px;">
                        📞 <a href="tel:+32477135113">+32 477 13 51 13</a><br>
                        ✉️ <a href="mailto:b-proservice@hotmail.com">b-proservice@hotmail.com</a>
                    </p>

                    <div class="contact-highlight">
                        Exemple de message à envoyer :<br><br>
                        « Bonjour, nous recherchons un service de nettoyage pour
                        nos bureaux à [ville], environ [surface] m², avec une
                        fréquence de [x] fois par semaine. Pourriez-vous nous
                        faire parvenir un devis ? »
                    </div>
                </div>

                <div>
                    <!-- Formulaire simple (à connecter plus tard si tu veux l’envoyer vers ton mail via un script) -->
                    <form action="https://formspree.io/f/xykkkbjv" method="POST" onsubmit="showConfirmation()">

    <!-- Anti-spam -->
    <input type="text" name="_gotcha" style="display:none">

    <!-- Sujet de l’e-mail -->
    <input type="hidden" name="_subject" value="Nouvelle demande de devis – B-Pro Service">

     <input type="hidden" name="_next" value="#merci">

    <div>
        <label for="nom">Nom / Société</label>
        <input type="text" id="nom" name="nom" placeholder="Votre nom ou celui de la société" required>
    </div>

    <div>
        <label for="email">E-mail</label>
        <input type="email" id="email" name="email" placeholder="votre.email@example.com" required>
    </div>

    <div>
        <label for="tel">Téléphone</label>
        <input type="tel" id="tel" name="telephone" placeholder="Votre numéro de téléphone">
    </div>

    <div>
        <label for="locaux">Type de locaux</label>
        <input type="text" id="locaux" name="locaux" placeholder="Bureaux, immeuble, fin de chantier…">
    </div>

    <div>
        <label for="message">Message</label>
        <textarea id="message" name="message" placeholder="Surface approximative, fréquence souhaitée, contraintes horaires…" required></textarea>
    </div>

    <button type="submit" class="btn btn-primary">
        Envoyer ma demande
    </button>
    <p id="confirmation-message" style="display:none; margin-top:10px; font-size:0.9rem; color:green;">
    ✅ Merci ! Votre demande de devis a bien été envoyée.
    Nous vous recontactons dans les plus brefs délais.
</p>

    <p style="font-size:0.8rem; color:#666; margin-top:6px;">
        Après l’envoi, vous recevrez un e-mail de confirmation.
    </p>
</form>

<div id="merci" style="display:none; margin-bottom:14px; padding:12px; border:1px solid #dde1ea; border-radius:12px; background:#ffffff;">
  <strong style="color:#2f9e44;">✅ Merci !</strong>
  <div style="color:#666; margin-top:6px;">
    Votre demande de devis a bien été envoyée.<br>
    Nous vous recontactons dans les plus brefs délais.
  </div>
</div>

                    <p style="font-size:0.8rem; color:var(--text-muted); margin-top:6px;">
                    </p>
                </div>
            </div>
        </div>
    </section>
</main>

<footer>
    <div class="container">
        <span>© <span id="year"></span> B-Pro Service – Tous droits réservés</span>
        <span>Nettoyage de bureaux • bâtiments • communs • fin de chantier – Bruxelles & Schaerbeek</span>
    </div>
</footer>

<script>
    // Année automatique
    document.getElementById("year").textContent = new Date().getFullYear();

    // FAQ interactive
    document.querySelectorAll('.faq-item').forEach(function(item) {
        item.addEventListener('click', function() {
            item.classList.toggle('open');
            const toggle = item.querySelector('.faq-toggle');
            if (item.classList.contains('open')) {
                toggle.textContent = '−';
            } else {
                toggle.textContent = '+';
            }
        });
    });
<script>
function showConfirmation() {
    setTimeout(function () {
        document.getElementById("confirmation-message").style.display = "block";
    }, 500);
}
</script>

</body>
</html>

# site-academia
Site oficial da Academia Feminina Adnanref - 27 anos transformando mulheres em Praia Grande/SP.
<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Academia Feminina Adnanref - 27 anos transformando mulheres</title>  
    <meta name="description" content="Academia 100% feminina em Praia Grande/SP. Musculação, Pilates, +12 modalidades. Ambiente exclusivo para mulheres.">  
      
    <!-- Google Fonts -->  
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">  
      
    <!-- Font Awesome -->  
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">  
      
    <style>  
        * {  
            margin: 0;  
            padding: 0;  
            box-sizing: border-box;  
        }  
  
        body {  
            font-family: 'Poppins', sans-serif;  
            line-height: 1.6;  
            color: #333;  
            overflow-x: hidden;  
        }  
  
        /* Header */  
        header {  
            background: linear-gradient(135deg, #ff6b9d 0%, #c44569 100%);  
            color: white;  
            padding: 1rem 0;  
            position: fixed;  
            width: 100%;  
            top: 0;  
            z-index: 1000;  
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);  
        }  
  
        nav {  
            max-width: 1200px;  
            margin: 0 auto;  
            display: flex;  
            justify-content: space-between;  
            align-items: center;  
            padding: 0 2rem;  
        }  
  
        .logo {  
            font-size: 1.8rem;  
            font-weight: 700;  
            display: flex;  
            align-items: center;  
            gap: 10px;  
        }  
  
        .logo i {  
            font-size: 2.2rem;  
        }  
  
        .nav-links {  
            display: flex;  
            list-style: none;  
            gap: 2rem;  
        }  
  
        .nav-links a {  
            color: white;  
            text-decoration: none;  
            font-weight: 500;  
            transition: opacity 0.3s;  
        }  
  
        .nav-links a:hover {  
            opacity: 0.8;  
        }  
  
        .cta-button {  
            background: rgba(255,255,255,0.2);  
            padding: 10px 20px;  
            border-radius: 25px;  
            text-decoration: none;  
            color: white;  
            font-weight: 600;  
            transition: all 0.3s;  
            backdrop-filter: blur(10px);  
        }  
  
        .cta-button:hover {  
            background: rgba(255,255,255,0.3);  
            transform: translateY(-2px);  
        }  
  
        /* Hero Section */  
        .hero {  
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 600"><rect fill="%23f8f9fa" width="1200" height="600"/><path fill="%23ff6b9d" opacity="0.1" d="M0 300 Q300 0 600 300 T1200 300 V600 H0 Z"/></svg>');  
            background-size: cover;  
            background-position: center;  
            height: 100vh;  
            display: flex;  
            align-items: center;  
            justify-content: center;  
            text-align: center;  
            color: white;  
            margin-top: 80px;  
        }  
  
        .hero-content h1 {  
            font-size: clamp(2.5rem, 5vw, 4rem);  
            margin-bottom: 1rem;  
            animation: fadeInUp 1s ease;  
        }  
  
        .hero-content .rating {  
            font-size: 1.2rem;  
            margin-bottom: 2rem;  
            opacity: 0.9;  
        }  
  
        .hero-content .slogan {  
            font-size: 1.3rem;  
            margin-bottom: 2.5rem;  
            max-width: 600px;  
            animation: fadeInUp 1s ease 0.2s both;  
        }  
  
        .hero-buttons {  
            display: flex;  
            gap: 1rem;  
            flex-wrap: wrap;  
            justify-content: center;  
            animation: fadeInUp 1s ease 0.4s both;  
        }  
  
        .btn {  
            padding: 15px 30px;  
            border: none;  
            border-radius: 30px;  
            font-size: 1.1rem;  
            font-weight: 600;  
            cursor: pointer;  
            transition: all 0.3s;  
            text-decoration: none;  
            display: inline-block;  
        }  
  
        .btn-primary {  
            background: #ff6b9d;  
            color: white;  
        }  
  
        .btn-secondary {  
            background: transparent;  
            color: white;  
            border: 2px solid white;  
        }  
  
        .btn:hover {  
            transform: translateY(-3px);  
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);  
        }  
  
        /* Sections */  
        .container {  
            max-width: 1200px;  
            margin: 0 auto;  
            padding: 0 2rem;  
        }  
  
        section {  
            padding: 100px 0;  
        }  
  
        .section-title {  
            text-align: center;  
            font-size: 2.5rem;  
            margin-bottom: 3rem;  
            color: #333;  
        }  
  
        /* About */  
        .about {  
            background: #f8f9fa;  
        }  
  
        .about-content {  
            display: grid;  
            grid-template-columns: 1fr 1fr;  
            gap: 4rem;  
            align-items: center;  
        }  
  
        .about-text h3 {  
            font-size: 1.8rem;  
            color: #ff6b9d;  
            margin-bottom: 1rem;  
        }  
  
        .about-text p {  
            font-size: 1.1rem;  
            margin-bottom: 1.5rem;  
            color: #666;  
        }  
  
        .stats {  
            display: grid;  
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));  
            gap: 2rem;  
            margin-top: 2rem;  
        }  
  
        .stat {  
            text-align: center;  
        }  
  
        .stat-number {  
            font-size: 2.5rem;  
            font-weight: 700;  
            color: #ff6b9d;  
        }  
  
        /* Services */  
        .services-grid {  
            display: grid;  
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));  
            gap: 2rem;  
        }  
  
        .service-card {  
            background: white;  
            padding: 2.5rem;  
            border-radius: 20px;  
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);  
            text-align: center;  
            transition: all 0.3s;  
            height: 100%;  
        }  
  
        .service-card:hover {  
            transform: translateY(-10px);  
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);  
        }  
  
        .service-icon {  
            font-size: 3rem;  
            color: #ff6b9d;  
            margin-bottom: 1rem;  
        }  
  
        /* Contact */  
        .contact {  
            background: linear-gradient(135deg, #ff6b9d 0%, #c44569 100%);  
            color: white;  
        }  
  
        .contact-content {  
            display: grid;  
            grid-template-columns: 1fr 1fr;  
            gap: 4rem;  
            align-items: start;  
        }  
  
        .contact-info h3 {  
            font-size: 1.8rem;  
            margin-bottom: 2rem;  
        }  
  
        .contact-item {  
            display: flex;  
            align-items: center;  
            gap: 1rem;  
            margin-bottom: 1.5rem;  
            padding: 1rem;  
            background: rgba(255,255,255,0.1);  
            border-radius: 15px;  
        }  
  
        .contact-item i {  
            font-size: 1.5rem;  
            width: 40px;  
        }  
  
        .contact-form {  
            background: rgba(255,255,255,0.1);  
            padding: 2.5rem;  
            border-radius: 20px;  
            backdrop-filter: blur(10px);  
        }  
  
        .form-group {  
            margin-bottom: 1.5rem;  
        }  
  
        .form-group label {  
            display: block;  
            margin-bottom: 0.5rem;  
            font-weight: 500;  
        }  
  
        .form-group input,  
        .form-group textarea {  
            width: 100%;  
            padding: 15px;  
            border: none;  
            border-radius: 10px;  
            font-family: inherit;  
            font-size: 1rem;  
            background: rgba(255,255,255,0.9);  
        }  
  
        /* Footer */  
        footer {  
            background: #333;  
            color: white;  
            text-align: center;  
            padding: 3rem 0 1rem;  
        }  
  
        .social-links {  
            display: flex;  
            justify-content: center;  
            gap: 1rem;  
            margin-bottom: 2rem;  
        }  
  
        .social-links a {  
            color: white;  
            font-size: 1.5rem;  
            transition: color 0.3s;  
        }  
  
        .social-links a:hover {  
            color: #ff6b9d;  
        }  
  
        /* Animations */  
        @keyframes fadeInUp {  
            from {  
                opacity: 0;  
                transform: translateY(30px);  
            }  
            to {  
                opacity: 1;  
                transform: translateY(0);  
            }  
        }  
  
        /* Responsive */  
        @media (max-width: 768px) {  
            .nav-links {  
                display: none;  
            }  
  
            .hero-buttons {  
                flex-direction: column;  
                align-items: center;  
            }  
  
            .about-content,  
            .contact-content {  
                grid-template-columns: 1fr;  
                gap: 2rem;  
            }  
  
            .section-title {  
                font-size: 2rem;  
            }  
        }  
  
        /* Status indicator */  
        .status-badge {  
            position: fixed;  
            top: 100px;  
            right: 2rem;  
            background: #ff4444;  
            color: white;  
            padding: 10px 20px;  
            border-radius: 25px;  
            font-weight: 600;  
            box-shadow: 0 5px 15px rgba(255,68,68,0.4);  
            z-index: 1000;  
            animation: pulse 2s infinite;  
        }  
  
        .status-badge.open {  
            background: #4CAF50;  
        }  
  
        @keyframes pulse {  
            0% { transform: scale(1); }  
            50% { transform: scale(1.05); }  
            100% { transform: scale(1); }  
        }  
    </style>  
</head>  
<body>  
    <!-- Header -->  
    <header>  
        <nav>  
            <div class="logo">  
                <i class="fas fa-dumbbell"></i>  
                Adnanref  
            </div>  
            <ul class="nav-links">  
                <li><a href="#home">Início</a></li>  
                <li><a href="#about">Sobre</a></li>  
                <li><a href="#services">Serviços</a></li>  
                <li><a href="#contact">Contato</a></li>  
            </ul>  
            <a href="tel:+551334956410" class="cta-button">  
                <i class="fab fa-whatsapp"></i> WhatsApp  
            </a>  
        </nav>  
    </header>  
  
    <!-- Status Badge -->  
    <div class="status-badge" id="statusBadge">  
        🏋️‍♀️ Fechado - Abre 06:00  
    </div>  
  
    <!-- Hero -->  
    <section id="home" class="hero">  
        <div class="hero-content">  
            <h1>Academia Feminina Adnanref</h1>  
            <div class="rating">  
                <i class="fas fa-star"></i>  
                <i class="fas fa-star"></i>  
                <i class="fas fa-star"></i>  
                <i class="fas fa-star"></i>  
                <i class="fas fa-star"></i>  
                4,8 (411 avaliações)  
            </div>  
            <p class="slogan">27 anos transformando mulheres<br>Ambiente 100% feminino</p>  
            <div class="hero-buttons">  
                <a href="#contact" class="btn btn-primary">Agendar Visita</a>  
                <a href="https://wa.me/551334956410" class="btn btn-secondary">  
                    <i class="fab fa-whatsapp"></i> Falar no WhatsApp  
                </a>  
            </div>  
        </div>  
    </section>  
  
    <!-- About -->  
    <section id="about" class="about">  
        <div class="container">  
            <h2 class="section-title">Sobre a Adnanref</h2>  
            <div class="about-content">  
                <div class="about-text">  
                    <h3>Seu espaço exclusivo para mulheres</h3>  
                    <p>Há 27 anos transformamos vidas em um ambiente 100% feminino. Oferecemos musculação, Pilates e mais de 12 modalidades para você alcançar seus objetivos com segurança e conforto.</p>  
                    <p>Localizada no coração da Cidade Ocian, somos referência em Praia Grande/SP com mais de 5,4 mil seguidoras no Instagram.</p>  
                    <div class="stats">  
                        <div class="stat">  
                            <div class="stat-number">27</div>  
                            <div>Anos de história</div>  
                        </div>  
                        <div class="stat">  
                            <div class="stat-number">4,8</div>  
                            <div>Avaliação Google</div>  
                        </div>  
                        <div class="stat">  
                            <div class="stat-number">411</div>  
                            <div>Avaliações</div>  
                        </div>  
                        <div class="stat">  
                            <div class="stat-number">5,4K</div>  
                            <div>Seguidores IG</div>  
                        </div>  
                    </div>  
                </div>  
                <div style="text-align: center;">  
                    <i class="fas fa-heart" style="font-size: 8rem; color: #ff6b9d;"></i>  
                </div>  
            </div>  
        </div>  
    </section>  
  
    <!-- Services -->  
    <section id="services">  
        <div class="container">  
            <h2 class="section-title">Nossos Serviços</h2>  
            <div class="services-grid">  
                <div class="service-card">  
                    <div class="service-icon">  
                        <i class="fas fa-dumbbell"></i>  
                    </div>  
                    <h3>Musculação</h3>  
                    <p>Equipamentos modernos para ganho de força e definição muscular.</p>  
                </div>  
                <div class="service-card">  
                    <div class="service-icon">  
                        <i class="fas fa-child-reaching"></i>  
                    </div>  
                    <h3>Pilates</h3>  
                    <p>Alongamento, fortalecimento e consciência corporal.</p>  
                </div>  
                <div class="service-card">  
                    <div class="service-icon">  
                        <i class="fas fa-running"></i>  
                    </div>  
                    <h3>Treino Funcional</h3>  
                    <p>Atividades dinâmicas para condicionamento físico completo.</p>  
                </div>  
                <div class="service-card">  
                    <div class="service-icon">  
                        <i class="fas fa-user-friends"></i>  
                    </div>  
                    <h3>Personal Trainer</h3>  
                    <p>Acompanhamento individualizado para melhores resultados.</p>  
                </div>  
                <div class="service-card">  
                    <div class="service-icon">  
                        <i class="fas fa-spa"></i>  
                    </div>  
                    <h3>Estética</h3>  
                    <p>Massagens, RPG, acupuntura, depilação e mais.</p>  
                </div>  
                <div class="service-card">  
                    <div class="service-icon">  
                        <i class="fas fa-utensils"></i>  
                    </div>  
                    <h3>Nutricionista</h3>  
                    <p>Acompanhamento nutricional especializado.</p>  
                </div>  
            </div>  
        </div>  
    </section>  
  
    <!-- Contact -->  
    <section id="contact" class="contact">  
        <div class="container">  
            <h2 class="section-title" style="color: white;">Entre em Contato</h2>  
            <div class="contact-content">  
                <div class="contact-info">  
                    <h3>Venha nos visitar!</h3>  
                    <div class="contact-item">  
                        <i class="fas fa-map-marker-alt"></i>  
                        <div>  
                            <strong>R. Guilherme de Almeida, 432</strong><br>  
                            Cidade Ocian, Praia Grande - SP<br>  
                            11704-210  
                        </div>  
                    </div>  
                    <div class="contact-item">  
                        <i class="fas fa-phone"></i>  
                        <div>  
                            <strong>(13) 3495-6410</strong>  
                        </div>  
                    </div>  
                    <div class="contact-item">  
                        <i class="fab fa-whatsapp"></i>  
                        <div>  
                            <strong>WhatsApp</strong><br>  
                            Clique para falar conosco  
                        </div>  
                    </div>  
                    <div class="contact-item">  
                        <i class="fas fa-clock"></i>  
                        <div>  
                            <strong>Horário:</strong><br>  
                            Seg-Sex: 06:00 - 22:00<br>  
                            Sáb: 08:00 - 12:00  
                        </div>  
                    </div>  
                </div>  
                <form class="contact-form" onsubmit="submitForm(event)">  
                    <div class="form-group">  
                        <label>Nome</label>  
                        <input type="text" required>  
                    </div>  
                    <div class="form-group">  
                        <label>WhatsApp/Telefone</label>  
                        <input type="tel" required>  
                    </div>  
                    <div class="form-group">  
                        <label>Mensagem</label>  
                        <textarea rows="

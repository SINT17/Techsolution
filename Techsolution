<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechSolutions - IT-услуги</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Базовые стили */
        :root {
            --primary: #2563eb;
            --dark: #1e293b;
            --light: #f8fafc;
            --gray: #94a3b8;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Кнопки (увеличенные) */
        .btn {
            display: inline-block;
            background-color: var(--primary);
            color: white;
            padding: 1.2rem 2.5rem;
            border-radius: 8px;
            text-decoration: none;
            transition: all 0.3s ease;
            font-size: 1.2rem;
            font-weight: 500;
            letter-spacing: 0.5px;
            box-shadow: 0 4px 6px rgba(37, 99, 235, 0.2);
            border: 2px solid transparent;
            cursor: pointer;
        }

        .btn:hover {
            background-color: #1d4ed8;
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(37, 99, 235, 0.3);
        }

        .btn i {
            margin-right: 10px;
            font-size: 1em;
            vertical-align: middle;
        }

        /* Шапка */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            z-index: 1000;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav a {
            color: var(--dark);
            text-decoration: none;
            padding: 1rem;
            display: block;
            transition: 0.3s;
            font-weight: 500;
        }

        nav a:hover {
            color: var(--primary);
        }

        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--primary);
        }

        .menu-toggle {
            font-size: 1.5rem;
            cursor: pointer;
            display: none;
        }

        /* Герой-секция */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1467232004584-a241de8bcf5d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            color: white;
            display: flex;
            align-items: center;
            text-align: center;
            padding-top: 80px;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
        }

        .hero p {
            font-size: 1.3rem;
            margin-bottom: 3rem;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        /* Секции */
        section {
            padding: 6rem 0;
        }

        h2 {
            font-size: 2.8rem;
            margin-bottom: 3rem;
            text-align: center;
            position: relative;
        }

        h2::after {
            content: '';
            display: block;
            width: 100px;
            height: 5px;
            background-color: var(--primary);
            margin: 1.5rem auto;
            border-radius: 3px;
        }

/* О компании */
        .about p {
            max-width: 800px;
            margin: 0 auto 4rem;
            text-align: center;
            font-size: 1.1rem;
            line-height: 1.8;
        }

        .stats {
            display: flex;
            justify-content: center;
            gap: 3rem;
            flex-wrap: wrap;
        }

        .stat-item {
            text-align: center;
            padding: 2.5rem;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
            min-width: 220px;
            transition: transform 0.3s ease;
        }

        .stat-item:hover {
            transform: translateY(-10px);
        }

        .number {
            font-size: 3rem;
            font-weight: bold;
            color: var(--primary);
            display: block;
            margin-bottom: 0.5rem;
        }

        /* Услуги */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 3rem;
            margin-top: 4rem;
        }

        .service-card {
            background-color: white;
            padding: 2.5rem;
            border-radius: 12px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
            text-align: center;
            transition: all 0.4s ease;
        }

        .service-card:hover {
            transform: translateY(-15px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.12);
        }

        .service-card i {
            font-size: 3.5rem;
            color: var(--primary);
            margin-bottom: 2rem;
        }

        .service-card h3 {
            margin-bottom: 1.5rem;
            font-size: 1.5rem;
        }

        .service-card p {
            color: var(--gray);
            font-size: 1.1rem;
        }

        /* Контакты */
        .contact-wrapper {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 4rem;
            margin-top: 4rem;
        }

        .contact-info {
            background-color: var(--primary);
            color: white;
            padding: 3rem;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(37, 99, 235, 0.2);
        }

        .contact-info h3 {
            margin-bottom: 2rem;
            font-size: 1.8rem;
        }

        .contact-info p {
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 1rem;
            font-size: 1.1rem;
        }

        .contact-info i {
            font-size: 1.3rem;
            width: 30px;
        }

        .contact-form {
            display: grid;
            gap: 1.5rem;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 1.2rem;
            border: 1px solid var(--gray);
            border-radius: 8px;
            font-size: 1.1rem;
            transition: border 0.3s ease;
        }

        .contact-form input:focus,
        .contact-form textarea:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
        }

        .contact-form textarea {
            min-height: 180px;
            resize: vertical;
        }

        /* Футер */
        footer {
            background-color: var(--dark);
            color: white;
            padding: 4rem 0 2rem;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 3rem;
            margin-bottom: 3rem;
        }

        .footer-section h3 {
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            color: var(--primary);
        }

        .footer-section p {
            margin-bottom: 1.5rem;
            opacity: 0.8;
        }

        .socials {
            display: flex;
            gap: 1.5rem;
        }

.socials a {
            color: white;
            font-size: 1.8rem;
            transition: 0.3s;
        }

        .socials a:hover {
            color: var(--primary);
            transform: translateY(-3px);
        }

        .copyright {
            text-align: center;
            padding-top: 3rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            opacity: 0.7;
        }

        /* Адаптивность */
        @media (max-width: 992px) {
            .hero h1 {
                font-size: 2.8rem;
            }
            
            h2 {
                font-size: 2.3rem;
            }
        }

        @media (max-width: 768px) {
            nav {
                position: fixed;
                top: 80px;
                left: -100%;
                width: 100%;
                background-color: white;
                transition: 0.3s;
                box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
            }

            nav.active {
                left: 0;
            }

            nav ul {
                flex-direction: column;
                padding: 2rem;
            }

            .menu-toggle {
                display: block;
            }

            .hero {
                padding-top: 100px;
                height: auto;
                padding-bottom: 6rem;
            }

            .hero h1 {
                font-size: 2.3rem;
            }

            .hero p {
                font-size: 1.1rem;
            }

            section {
                padding: 4rem 0;
            }

            .btn {
                padding: 1rem 2rem;
                font-size: 1.1rem;
            }

            .stat-item {
                padding: 2rem;
                min-width: 180px;
            }

            .number {
                font-size: 2.5rem;
            }
        }

        @media (max-width: 576px) {
            .hero h1 {
                font-size: 2rem;
            }

            h2 {
                font-size: 1.8rem;
            }

            .stats {
                gap: 1.5rem;
            }

            .stat-item {
                width: 100%;
                max-width: 250px;
            }

            .services-grid {
                grid-template-columns: 1fr;
            }

            .contact-wrapper {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Шапка -->
    <header>
        <div class="container header-container">
            <div class="logo">TechSolutions</div>
            <nav>
                <ul>
                    <li><a href="#home">Главная</a></li>
                    <li><a href="#about">О нас</a></li>
                    <li><a href="#services">Услуги</a></li>
                    <li><a href="#contact">Контакты</a></li>
                </ul>
            </nav>
            <div class="menu-toggle"><i class="fas fa-bars"></i></div>
        </div>
    </header>

    <!-- Герой-секция -->
    <section id="home" class="hero">
        <div class="container">
            <h1>Инновационные IT-решения</h1>
            <p>Мы создаем технологии для роста вашего бизнеса. Профессиональный подход и индивидуальные решения для каждого клиента.</p>
            <a href="#contact" class="btn">
                <i class="fas fa-paper-plane"></i> Связаться с нами
            </a>
        </div>
    </section>

<!-- О компании -->
    <section id="about" class="about">
        <div class="container">
            <h2>О компании</h2>
            <p>TechSolutions - ведущий разработчик IT-решений с 2010 года. Наша команда профессионалов помогает бизнесу трансформироваться с помощью цифровых технологий, предлагая комплексные решения от разработки программного обеспечения до внедрения сложных корпоративных систем.</p>
            <div class="stats">
                <div class="stat-item">
                    <span class="number">12+</span>
                    <span>Лет опыта</span>
                </div>
                <div class="stat-item">
                    <span class="number">200+</span>
                    <span>Проектов</span>
                </div>
                <div class="stat-item">
                    <span class="number">50+</span>
                    <span>Специалистов</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Услуги -->
    <section id="services" class="services">
        <div class="container">
            <h2>Наши услуги</h2>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-code"></i>
                    <h3>Веб-разработка</h3>
                    <p>Создание современных веб-приложений, интернет-магазинов и корпоративных сайтов с адаптивным дизайном</p>
                    <a href="#contact" class="btn" style="margin-top: 1.5rem; display: inline-block; padding: 0.8rem 1.5rem; font-size: 1rem;">
                        Заказать
                    </a>
                </div>
                <div class="service-card">
                    <i class="fas fa-mobile-alt"></i>
                    <h3>Мобильные приложения</h3>
                    <p>Разработка нативных и кроссплатформенных приложений для iOS и Android с продуманным UX/UI</p>
                    <a href="#contact" class="btn" style="margin-top: 1.5rem; display: inline-block; padding: 0.8rem 1.5rem; font-size: 1rem;">
                        Заказать
                    </a>
                </div>
                <div class="service-card">
                    <i class="fas fa-cloud"></i>
                    <h3>Облачные решения</h3>
                    <p>Развертывание, миграция и поддержка облачной инфраструктуры для бизнеса любого масштаба</p>
                    <a href="#contact" class="btn" style="margin-top: 1.5rem; display: inline-block; padding: 0.8rem 1.5rem; font-size: 1rem;">
                        Заказать
                    </a>
                </div>
            </div>
        </div>
    </section>

<!-- Контакты -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Контакты</h2>
            <div class="contact-wrapper">
                <div class="contact-info">
                    <h3>Наши данные</h3>
                    <p><i class="fas fa-map-marker-alt"></i> Москва, ул. Примерная, 123</p>
                    <p><i class="fas fa-phone"></i> +7 (495) 123-45-67</p>
                    <p><i class="fas fa-envelope"></i> info@techsolutions.ru</p>
                    <p><i class="fas fa-clock"></i> Пн-Пт: 9:00 - 18:00</p>
                    <div class="socials" style="margin-top: 2rem;">
                        <a href="#"><i class="fab fa-vk"></i></a>
                        <a href="#"><i class="fab fa-telegram"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                        <a href="#"><i class="fab fa-github"></i></a>
                    </div>
                </div>
                <form class="contact-form">
                    <input type="text" placeholder="Ваше имя" required>
                    <input type="email" placeholder="Ваш Email" required>
                    <input type="tel" placeholder="Ваш телефон">
                    <textarea placeholder="Ваше сообщение" required></textarea>
                    <button type="submit" class="btn">
                        <i class="fas fa-paper-plane"></i> Отправить сообщение
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Футер -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>TechSolutions</h3>
                    <p>Инновационные технологии для цифровой трансформации вашего бизнеса. Профессиональные IT-решения с 2010 года.</p>
                </div>
                <div class="footer-section">
                    <h3>Навигация</h3>
                    <ul style="list-style: none;">
                        <li><a href="#home" style="color: white; text-decoration: none; opacity: 0.8; transition: 0.3s; display: block; margin-bottom: 0.8rem;">Главная</a></li>
                        <li><a href="#about" style="color: white; text-decoration: none; opacity: 0.8; transition: 0.3s; display: block; margin-bottom: 0.8rem;">О компании</a></li>
                        <li><a href="#services" style="color: white; text-decoration: none; opacity: 0.8; transition: 0.3s; display: block; margin-bottom: 0.8rem;">Услуги</a></li>
                        <li><a href="#contact" style="color: white; text-decoration: none; opacity: 0.8; transition: 0.3s; display: block; margin-bottom: 0.8rem;">Контакты</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Соцсети</h3>
                    <div class="socials">
                        <a href="#"><i class="fab fa-vk"></i></a>
                        <a href="#"><i class="fab fa-telegram"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                        <a href="#"><i class="fab fa-github"></i></a>
                    </div>
                </div>
            </div>
            <div class="copyright">
                &copy; 2023 TechSolutions. Все права защищены.
            </div>
        </div>
    </footer>

    <script>
        // Мобильное меню
        document.querySelector('.menu-toggle').addEventListener('click', function() {
            document.querySelector('nav').classList.toggle('active');
            this.querySelector('i').classList.toggle('fa-times');
        });

        // Плавная прокрутка
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });

if (document.querySelector('nav').classList.contains('active')) {
                    document.querySelector('nav').classList.remove('active');
                    document.querySelector('.menu-toggle i').classList.remove('fa-times');
                }
            });
        });

        // Анимация кнопок при клике
        document.querySelectorAll('.btn').forEach(button => {
            button.addEventListener('mousedown', function() {
                this.style.transform = 'translateY(2px)';
                this.style.boxShadow = '0 2px 4px rgba(37, 99, 235, 0.3)';
            });
            
            button.addEventListener('mouseup', function() {
                this.style.transform = 'translateY(-3px)';
                this.style.boxShadow = '0 6px 12px rgba(37, 99, 235, 0.3)';
            });
            
            button.addEventListener('mouseleave', function() {
                this.style.transform = 'translateY(0)';
                this.style.boxShadow = '0 4px 6px rgba(37, 99, 235, 0.2)';
            });
        });

        // Анимация при скролле
        const animateOnScroll = () => {
            const elements = document.querySelectorAll('.service-card, .stat-item');
            const windowHeight = window.innerHeight;
            
            elements.forEach(element => {
                const elementPosition = element.getBoundingClientRect().top;
                const animationPoint = windowHeight * 0.85;
                
                if (elementPosition < animationPoint) {
                    element.style.opacity = '1';
                    element.style.transform = 'translateY(0)';
                }
            });
        };

        // Изначально скрываем элементы
        document.querySelectorAll('.service-card, .stat-item').forEach(element => {
            element.style.opacity = '0';
            element.style.transform = 'translateY(30px)';
            element.style.transition = 'all 0.6s ease-out';
        });

        window.addEventListener('scroll', animateOnScroll);
        window.addEventListener('load', animateOnScroll);
    </script>
</body>
</html>

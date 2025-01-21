# -climate
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Современные системы вентиляции и кондиционирования для вашего комфорта.">
    <title>Ventura | Вентиляция и Кондиционирование</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .hero {
            background: url('images/hero-bg.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .service-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
        }
        footer {
            background-color: #222;
            color: white;
            padding: 20px 0;
        }
        .contact-form {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header class="bg-dark text-light py-3">
        <div class="container d-flex justify-content-between align-items-center">
            <h1 class="h3">Ventura</h1>
            <nav>
                <ul class="nav">
                    <li class="nav-item"><a href="index.html" class="nav-link text-light">Главная</a></li>
                    <li class="nav-item"><a href="about.html" class="nav-link text-light">О нас</a></li>
                    <li class="nav-item"><a href="services.html" class="nav-link text-light">Услуги</a></li>
                    <li class="nav-item"><a href="catalog.html" class="nav-link text-light">Каталог</a></li>
                    <li class="nav-item"><a href="contacts.html" class="nav-link text-light">Контакты</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero">
            <div class="container">
                <h1 class="display-4">Современные решения для климата</h1>
                <p class="lead">Вентиляция и кондиционирование для дома и бизнеса</p>
                <a href="services.html" class="btn btn-primary btn-lg">Наши услуги</a>
            </div>
        </section>

        <section id="about" class="py-5">
            <div class="container text-center">
                <h2 class="mb-4">О нас</h2>
                <p>Мы предоставляем высококачественные услуги по установке, проектированию и обслуживанию климатического оборудования. Наша команда профессионалов заботится о вашем комфорте круглый год.</p>
            </div>
        </section>

        <section id="services" class="bg-light py-5">
            <div class="container">
                <h2 class="text-center mb-4">Наши услуги</h2>
                <div class="row">
                    <div class="col-md-4">
                        <div class="card service-card">
                            <div class="card-body text-center">
                                <h5 class="card-title">Проектирование</h5>
                                <p class="card-text">Разработка индивидуальных решений для вашего помещения.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card service-card">
                            <div class="card-body text-center">
                                <h5 class="card-title">Монтаж</h5>
                                <p class="card-text">Качественная установка вентиляционных систем и кондиционеров.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card service-card">
                            <div class="card-body text-center">
                                <h5 class="card-title">Сервисное обслуживание</h5>
                                <p class="card-text">Регулярный осмотр и ремонт оборудования.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="catalog" class="py-5">
            <div class="container">
                <h2 class="text-center mb-4">Каталог</h2>
                <div class="row">
                    <div class="col-md-3">
                        <div class="card">
                            <img src="images/item1.jpg" class="card-img-top" alt="Товар">
                            <div class="card-body">
                                <h5 class="card-title">Кондиционер SmartCool</h5>
                                <p class="card-text">Цена: 35,000 ₽</p>
                                <a href="#" class="btn btn-outline-primary">Подробнее</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card">
                            <img src="images/item2.jpg" class="card-img-top" alt="Товар">
                            <div class="card-body">
                                <h5 class="card-title">Вентиляция ProAir</h5>
                                <p class="card-text">Цена: 50,000 ₽</p>
                                <a href="#" class="btn btn-outline-primary">Подробнее</a>
                            </div>
                        </div>
                    </div>
                    <!-- Add more items here -->
                </div>
            </div>
        </section>

        <section id="contacts" class="py-5 bg-light">
            <div class="container">
                <h2 class="text-center mb-4">Контакты</h2>
                <div class="row">
                    <div class="col-md-6">
                        <p><strong>Адрес:</strong> г. Екатеринбург, ул. Примерная, д. 15</p>
                        <p><strong>Телефон:</strong> +7 (343) 123-45-67</p>
                        <p><strong>Email:</strong> info@ventura.ru</p>
                    </div>
                    <div class="col-md-6">
                        <form class="contact-form">
                            <div class="mb-3">
                                <label for="name" class="form-label">Ваше имя</label>
                                <input type="text" class="form-control" id="name" placeholder="Введите имя">
                            </div>
                            <div class="mb-3">
                                <label for="email" class="form-label">Ваш Email</label>
                                <input type="email" class="form-control" id="email" placeholder="Введите email">
                            </div>
                            <div class="mb-3">
                                <label for="message" class="form-label">Сообщение</label>
                                <textarea class="form-control" id="message" rows="4" placeholder="Введите сообщение"></textarea>
                            </div>
                            <button type="submit" class="btn btn-primary">Отправить</button>
                        </form>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container text-center">
            <p>&copy; 2025 Ventura. Все права защищены.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

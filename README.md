# my-second-work
✨ Key Features * **🕒 Dynamic Daily Schedule:** Automatically displays the timetable for the current day of the week. * **🎉 Holiday Countdown:** A real-time tracker showing exactly how many days are left until the next school holiday. * **🔔 Bell Times:** A dedicated section for lesson start/end times and break duratio
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Школьное Расписание - Гимназия №1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Гимназия №1</h1>
            <nav>
                <button class="nav-button" onclick="showSection('home')">Главная</button>
                <button class="nav-button" onclick="showSection('about')">О Школе</button>
                <button class="nav-button" onclick="showSection('timetable')">Расписание</button>
                <button class="nav-button" onclick="showSection('day-at-school')">День в Школе</button>
            </nav>
        </div>
    </header>

    <main class="container">
        <section id="home" class="active">
            <h2>Добро пожаловать в Гимназию №1!</h2>
            <p>На этом сайте вы найдете всю необходимую информацию: актуальное расписание уроков, интересные факты о нашей школе и описание типичного учебного дня.</p>
            <p>Используйте кнопки навигации выше, чтобы перемещаться по разделам.</p>
            <img src="https://via.placeholder.com/600x300?text=Здание+Школы" alt="Здание школы" class="hero-image">
            <p class="slogan">Учимся, развиваемся, достигаем!</p>
        </section>

        <section id="about">
            <h2>О нашей Гимназии</h2>
            <p>Гимназия №1 — это современное образовательное учреждение с богатой историей, основанное в 19XX году. Мы гордимся нашими выпускниками, многие из которых стали успешными специалистами в различных областях.</p>
            <h3>Наша миссия:</h3>
            <ul>
                <li>Обеспечение высокого качества образования.</li>
                <li>Развитие творческого потенциала каждого ученика.</li>
                <li>Формирование активной гражданской позиции.</li>
            </ul>
            <p>В нашей школе работают высококвалифицированные педагоги, использующие инновационные методики обучения. Мы стремимся создать благоприятную атмосферу для всестороннего развития детей.</p>
        </section>

        <section id="timetable">
            <h2>Расписание Уроков</h2>
            <p>Выберите день недели, чтобы посмотреть расписание:</p>
            <div class="day-selector">
                <button onclick="displayTimetable(0)">Пн</button>
                <button onclick="displayTimetable(1)">Вт</button>
                <button onclick="displayTimetable(2)">Ср</button>
                <button onclick="displayTimetable(3)">Чт</button>
                <button onclick="displayTimetable(4)">Пт</button>
                <button onclick="displayTimetable(5)">Сб</button>
            </div>
            <div id="timetable-display">
                </div>
            <p class="note">** Расписание может быть изменено. Пожалуйста, уточняйте у классного руководителя.</p>
        </section>

        <section id="day-at-school">
            <h2>Типичный День в Школе</h2>
            <p>Как проходит учебный день в Гимназии №1:</p>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="time">8:00 - 8:30</div>
                    <div class="description">Сбор учащихся, подготовка к урокам.</div>
                </div>
                <div class="timeline-item">
                    <div class="time">8:30 - 14:00</div>
                    <div class="description">Учебные занятия (4-6 уроков), перемены.</div>
                </div>
                <div class="timeline-item">
                    <div class="time">12:00 - 13:00</div>
                    <div class="description">Обед в школьной столовой (для младших классов).</div>
                </div>
                <div class="timeline-item">
                    <div class="time">14:00 - 16:00</div>
                    <div class="description">Внеурочная деятельность: кружки, секции, факультативы.</div>
                </div>
                <div class="timeline-item">
                    <div class="time">16:00 - 17:00</div>
                    <div class="description">Самостоятельная подготовка, консультации с учителями.</div>
                </div>
            </div>
            <img src="https://via.placeholder.com/400x200?text=Урок+в+Классе" alt="Урок в классе" class="section-image">
            <p>Мы стараемся, чтобы каждый день был насыщенным и продуктивным!</p>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Гимназия №1. Все права защищены.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
почта:rahmatildaevan@gmail.com

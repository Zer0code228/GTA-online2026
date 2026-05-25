
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>GTA Online | Наше Комьюнити</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', 'Poppins', system-ui, -apple-system, BlinkMacSystemFont, 'Roboto', sans-serif;
            background: radial-gradient(circle at 10% 20%, #0a0f1e, #03050a);
            color: #f0f3fa;
            line-height: 1.5;
        }

        /* контейнер */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
        }

        /* хедер */
        .hero {
            text-align: center;
            margin-bottom: 3rem;
        }
        .hero h1 {
            font-size: 3rem;
            background: linear-gradient(135deg, #ffd966, #ffaa33);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            letter-spacing: -0.5px;
            margin-bottom: 0.5rem;
        }
        .hero p {
            font-size: 1.2rem;
            opacity: 0.85;
            max-width: 600px;
            margin: 1rem auto 0;
        }

        /* карточки */
        .card {
            background: rgba(15, 25, 45, 0.7);
            backdrop-filter: blur(8px);
            border-radius: 32px;
            padding: 1.8rem;
            margin-bottom: 2rem;
            border: 1px solid rgba(255, 200, 100, 0.25);
            box-shadow: 0 15px 35px rgba(0,0,0,0.3);
            transition: transform 0.2s ease;
        }
        .card:hover {
            transform: translateY(-3px);
            border-color: rgba(255, 200, 100, 0.5);
        }
        .card h2 {
            font-size: 1.8rem;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 10px;
            border-left: 4px solid #f5a623;
            padding-left: 15px;
        }
        .card h2 i {
            font-size: 1.6rem;
        }

        /* кнопки */
        .btn {
            display: inline-block;
            background: #2a3b5c;
            color: white;
            font-weight: 600;
            text-decoration: none;
            padding: 12px 28px;
            border-radius: 40px;
            transition: 0.2s;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            margin-right: 12px;
            margin-top: 10px;
            text-align: center;
        }
        .btn-primary {
            background: linear-gradient(95deg, #f5a623, #ff7e05);
            box-shadow: 0 5px 15px rgba(245,166,35,0.3);
            color: #0a0c15;
        }
        .btn-primary:hover {
            transform: scale(1.02);
            background: linear-gradient(95deg, #ffb347, #ff8c1a);
            box-shadow: 0 8px 20px rgba(245,166,35,0.5);
        }
        .btn-discord {
            background: #5865F2;
        }
        .btn-discord:hover {
            background: #4752c4;
        }
        .btn-outline {
            background: transparent;
            border: 1.5px solid #f5a623;
            color: #f5a623;
        }
        .btn-outline:hover {
            background: #f5a62320;
        }

        /* сетка правил */
        .rules-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0 10px;
        }
        .rule-item {
            background: #0e1622cc;
            border-radius: 60px;
            padding: 8px 20px;
            font-size: 0.9rem;
            backdrop-filter: blur(4px);
        }

        /* таблица участников (пример) */
        .members-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }
        .members-table th, .members-table td {
            text-align: left;
            padding: 12px 8px;
            border-bottom: 1px solid rgba(255,255,240,0.15);
        }
        .members-table th {
            color: #f5a623;
            font-weight: 600;
        }
        .social-link {
            color: #ffd966;
            text-decoration: none;
            font-weight: 500;
        }
        .social-link:hover {
            text-decoration: underline;
        }

        /* форма */
        .form-group {
            margin-bottom: 1.2rem;
        }
        label {
            display: block;
            margin-bottom: 6px;
            font-weight: 500;
        }
        input, select, textarea {
            width: 100%;
            padding: 12px 16px;
            background: #0c1222;
            border: 1px solid #2d3a5e;
            border-radius: 28px;
            color: white;
            font-size: 1rem;
            outline: none;
            transition: 0.2s;
        }
        input:focus, select:focus, textarea:focus {
            border-color: #f5a623;
        }
        textarea {
            border-radius: 20px;
            resize: vertical;
        }
        .form-row {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .form-row .form-group {
            flex: 1;
        }
        .footer {
            text-align: center;
            margin-top: 3rem;
            font-size: 0.8rem;
            opacity: 0.6;
        }
        hr {
            border-color: #2d3a5e;
            margin: 1rem 0;
        }
        @media (max-width: 700px) {
            .container {
                padding: 1.2rem;
            }
            .hero h1 {
                font-size: 2.2rem;
            }
            .card h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
<div class="container">
    <!-- Hero -->
    <div class="hero">
        <h1>🚗 LOS SANTOS CREW</h1>
        <p>Онлайн-сообщество для активных игроков GTA Online • Гонки, ограбления, патрули и катки</p>
    </div>

    <!-- Блок Discord + Crew -->
    <div class="card">
        <h2>🎮 Присоединяйся к движу</h2>
        <p style="margin-bottom: 15px;">Нажми на кнопку, чтобы попасть в наш Discord — там мы собираемся ежедневно. В игре легко найти напарников через закрытые сессии и друзей Rockstar.</p>
        <div>
            <a href="https://discord.gg/ЗДЕСЬ_ВАША_ССЫЛКА" target="_blank" class="btn btn-discord">🔊 Discord сервер</a>
            <a href="https://socialclub.rockstargames.com/crew/ваш_crew_id" target="_blank" class="btn btn-outline">🎖️ Crew в Social Club</a>
        </div>
        <div style="margin-top: 20px; background: #00000030; border-radius: 18px; padding: 10px 15px;">
            💡 <strong>Как играть вместе?</strong> Добавьте друг друга в друзья Rockstar → создайте закрытую сессию (Invite Only) → пригласите через меню друзей.
        </div>
    </div>

    <!-- Правила и особенности -->
    <div class="card">
        <h2>📜 Наши правила</h2>
        <div class="rules-grid">
            <span class="rule-item">✅ 18+ (адекватное общение)</span>
            <span class="rule-item">🚫 No cheats / моды на читы</span>
            <span class="rule-item">🤝 Уважение к другим</span>
            <span class="rule-item">🎙️ Голосовой чат приветствуется</span>
            <span class="rule-item">🏆 Фэйр-плей в PvP</span>
        </div>
        <p style="margin-top: 12px;">Нарушители получают бан в комьюнити и репорт в Social Club.</p>
    </div>

    <!-- Таблица активных участников (пример статический, можно редактировать вручную) -->
    <div class="card">
        <h2>👥 Активные члены Crew</h2>
        <p>Добавляй в друзья и врывайся в сессии!</p>
        <table class="members-table">
            <thead>
                <tr><th>Ник в игре</th><th>Уровень</th><th>Любимый режим</th><th>Social Club ID</th></tr>
            </thead>
            <tbody>
                <tr><td>Vortex_77</td><td>342</td><td>Гонки</td><td><a href="#" class="social-link" onclick="copyToClipboard('Vortex_77'); return false;">Скопировать</a></td></tr>
                <tr><td>N1ghtR1der_</td><td>189</td><td>Ограбления</td><td><a href="#" class="social-link" onclick="copyToClipboard('N1ghtR1der_'); return false;">Скопировать</a></td></tr>
                <tr><td>LS_Patrol</td><td>510</td><td>Сражения</td><td><a href="#" class="social-link" onclick="copyToClipboard('LS_Patrol'); return false;">Скопировать</a></td></tr>
                <tr><td>FastCash_</td><td>276</td><td>Склад/Бизнес</td><td><a href="#" class="social-link" onclick="copyToClipboard('FastCash_'); return false;">Скопировать</a></td></tr>
            </tbody>
        </table>
        <p style="font-size: 0.8rem; margin-top: 12px;">⭐ Добавьте себя в таблицу — напишите в Discord модератору.</p>
    </div>

    <!-- Форма для поиска тиммейтов / заявка на ивент (Google Sheets style) -->
    <div class="card">
        <h2>✍️ Найти тиммейтов или записаться на ивент</h2>
        <p>Оставь заявку, и мы свяжемся с тобой в Discord или в игре</p>
        <form id="playerForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
            <!-- Если хочешь использовать Formspree (бесплатно) – замени YOUR_FORM_ID. 
            Либо можно отправить данные на email через обычный mailto, но лучше использовать Formspree или Google Forms. -->
            <div class="form-row">
                <div class="form-group">
                    <label>Ваш ник в GTA Online</label>
                    <input type="text" name="nickname" placeholder="например: FastDriver_88" required>
                </div>
                <div class="form-group">
                    <label>Discord тег (или ID Social Club)</label>
                    <input type="text" name="contact" placeholder="username#1234 / SocialClubID" required>
                </div>
            </div>
            <div class="form-group">
                <label>Что ищете?</label>
                <select name="activity">
                    <option>Ограбление (Казно, Остров Кейо)</option>
                    <option>Гонки / Стэнты</option>
                    <option>PvP / Сражения в свободном режиме</option>
                    <option>Прокачка бизнесов</option>
                    <option>Просто поиграть в компании</option>
                </select>
            </div>
            <div class="form-group">
                <label>Когда планируете играть?</label>
                <textarea name="time" rows="2" placeholder="вечером по МСК / уточните время"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">📨 Отправить заявку</button>
        </form>
        <p style="font-size: 12px; margin-top: 15px;">*Данные никуда не уходят без вашего согласия. После отправки мы найдём вас в течение суток.</p>
    </div>

    <!-- блок с копированием ID организатора -->
    <div class="card">
        <h2>🎯 Быстрый контакт</h2>
        <p><strong>Rockstar ID основателя:</strong> <span id="rsID" style="background:#10141f; padding:4px 10px; border-radius:20px;">Skilled_Runner</span> 
        <button class="btn-outline" style="padding: 4px 16px; margin-left: 8px;" onclick="copyToClipboard('Skilled_Runner')">Скопировать ID</button>
        </p>
        <p>➕ Добавляй в друзья и пиши «с сайта», получишь приглашение в комьюнити-сессию.</p>
        <hr>
        <p style="display: flex; gap: 15px; justify-content: center; flex-wrap: wrap;">
            <span>🏆 Ежедневные ивенты 20:00 МСК</span>
            <span>📢 Розыгрыши игровой валюты</span>
        </p>
    </div>
    <div class="footer">
        © 2025 Los Santos Community · Неофициальный сайт для GTA Online
    </div>
</div>

<script>
    // функция копирования любого текста в буфер
    function copyToClipboard(text) {
        navigator.clipboard.writeText(text).then(() => {
            // создаём временное уведомление
            let msg = document.createElement('div');
            msg.innerText = `✅ ${text} скопирован!`;
            msg.style.position = 'fixed';
            msg.style.bottom = '20px';
            msg.style.left = '50%';
            msg.style.transform = 'translateX(-50%)';
            msg.style.backgroundColor = '#f5a623';
            msg.style.color = '#0a0c15';
            msg.style.padding = '8px 20px';
            msg.style.borderRadius = '40px';
            msg.style.fontWeight = 'bold';
            msg.style.zIndex = '9999';
            document.body.appendChild(msg);
            setTimeout(() => msg.remove(), 1800);
        }).catch(() => alert('Нажми Ctrl+C, чтобы скопировать вручную: ' + text));
    }

    // Для формы если используете Formspree – уведомление об отправке
    const form = document.getElementById('playerForm');
    if(form) {
        form.addEventListener('submit', function(e) {
            // Если action пустой или заглушка, то покажем предупреждение
            if(form.action.includes('YOUR_FORM_ID')) {
                e.preventDefault();
                alert('🔧 Настройка: замените YOUR_FORM_ID на реальный ID от Formspree, либо используйте Google Forms. Пока форма демонстрационная.');
                return false;
            }
            // если action нормальный, то всё равно дадим сообщение
            setTimeout(() => {
                alert('Спасибо! Мы скоро свяжемся с вами в Discord/GTA.');
            }, 100);
        });
    }
</script>
</body>
</html>

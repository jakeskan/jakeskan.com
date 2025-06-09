<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Jakeskan.com</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 99%, #fad0c4 100%);
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }

    header {
      margin-top: 40px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      font-weight: 700;
      color: #6a0572;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.1);
    }

    main {
      max-width: 600px;
      background: white;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      padding: 30px;
      margin: 40px 20px;
      text-align: center;
    }

    main img {
      width: 100%;
      border-radius: 15px;
      margin-bottom: 20px;
      box-shadow: 0 4px 15px rgba(106,5,114,0.3);
    }

    main p {
      font-size: 1.2rem;
      color: #444;
      margin-bottom: 30px;
      line-height: 1.5;
    }

    .social-links {
      display: flex;
      justify-content: center;
      gap: 40px;
      margin-bottom: 30px;
    }

    .social-links a {
      text-decoration: none;
      color: #6a0572;
      font-weight: 700;
      font-size: 1.4rem;
      transition: color 0.3s ease;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .social-links a:hover {
      color: #d6336c;
    }

    .social-links svg {
      width: 24px;
      height: 24px;
      fill: currentColor;
    }

    footer {
      font-size: 1.1rem;
      color: #6a0572;
      margin-bottom: 30px;
      font-weight: 600;
    }

    /* Responsive */
    @media (max-width: 480px) {
      header h1 {
        font-size: 2.2rem;
      }

      main {
        padding: 20px;
        margin: 20px 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Jakeskan.com</h1>
  </header>

  <main>
    <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80" alt="Motivational" />
    <p>Dream big, work hard, and never give up! Every step forward is a step closer to your goals.</p>

    <div class="social-links">
      <a href="https://facebook.com/kanyuira.jakes" target="_blank" rel="noopener noreferrer" aria-label="Facebook">
        <svg viewBox="0 0 24 24"><path d="M22 12.07C22 6.51 17.52 2 12 2S2 6.51 2 12.07c0 5 3.66 9.13 8.44 9.93v-7.03h-2.54v-2.9h2.54V9.41c0-2.5 1.49-3.89 3.77-3.89 1.09 0 2.23.2 2.23.2v2.46h-1.26c-1.24 0-1.62.77-1.62 1.56v1.87h2.77l-.44 2.9h-2.33v7.03C18.34 21.2 22 17.07 22 12.07z"/></svg>
        Facebook
      </a>
      <a href="https://instagram.com/kanyuira.jakes" target="_blank" rel="noopener noreferrer" aria-label="Instagram">
        <svg viewBox="0 0 24 24"><path d="M7.75 2h8.5C19.55 2 22 4.45 22 7.75v8.5c0 3.3-2.45 5.75-5.75 5.75h-8.5C4.45 22 2 19.55 2 16.25v-8.5C2 4.45 4.45 2 7.75 2zm0 2C5.68 4 4 5.68 4 7.75v8.5C4 18.32 5.68 20 7.75 20h8.5c2.07 0 3.75-1.68 3.75-3.75v-8.5c0-2.07-1.68-3.75-3.75-3.75h-8.5zM12 7a5 5 0 110 10 5 5 0 010-10zm0 2a3 3 0 100 6 3 3 0 000-6zm4.75-3.5a1.25 1.25 0 112.5 0 1.25 1.25 0 01-2.5 0z"/></svg>
        Instagram
      </a>
    </div>

    <footer>
      📞 Call me: <a href="tel:+821012345678" style="color:#d6336c; text-decoration:none;">010-1234-5678</a>
    </footer>
  </main>

</body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vitae — Téléchargements</title>
  <style>
    * { box-sizing: border-box; }

    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: #f5f5f7;
      color: #1d1d1f;
    }

    .container {
      width: min(620px, calc(100% - 40px));
      text-align: center;
      padding: 48px 30px;
      background: white;
      border: 1px solid #e5e5e7;
      border-radius: 24px;
      box-shadow: 0 12px 40px rgba(0,0,0,.06);
    }

    .logo {
      font-size: 42px;
      font-weight: 700;
      letter-spacing: -1.5px;
      margin-bottom: 8px;
    }

    .subtitle {
      color: #777;
      margin-bottom: 36px;
    }

    .version {
      display: inline-block;
      padding: 7px 12px;
      border-radius: 999px;
      background: #f0f0f2;
      font-size: 14px;
      margin-bottom: 30px;
    }

    .downloads {
      display: grid;
      gap: 12px;
    }

    .download {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 17px 20px;
      border-radius: 14px;
      background: #f5f5f7;
      color: #1d1d1f;
      text-decoration: none;
      transition: .15s ease;
    }

    .download:hover {
      background: #e9e9ec;
      transform: translateY(-1px);
    }

    .download strong {
      font-size: 16px;
    }

    .arrow {
      color: #777;
      font-size: 20px;
    }

    .date {
      margin-top: 28px;
      color: #888;
      font-size: 13px;
    }

    .test-note {
      margin-top: 25px;
      font-size: 12px;
      color: #aaa;
    }
  </style>
</head>
<body>

  <main class="container">
    <div class="logo">Vitae</div>
    <div class="subtitle">Centre de téléchargement</div>

    <div class="version">
      Version <strong id="version">1.0.0</strong>
    </div>

    <div class="downloads">
      <a class="download" href="https://mega.nz/" target="_blank" rel="noopener">
        <strong>Windows</strong>
        <span class="arrow">→</span>
      </a>

      <a class="download" href="https://mega.nz/" target="_blank" rel="noopener">
        <strong>Android</strong>
        <span class="arrow">→</span>
      </a>

      <a class="download" href="https://mega.nz/" target="_blank" rel="noopener">
        <strong>Mac</strong>
        <span class="arrow">→</span>
      </a>
    </div>

    <div class="date">
      Publiée le <span id="date">7 octobre 2026</span>
    </div>

    <div class="test-note">
      Page de test — les liens MEGA sont actuellement des liens d'exemple.
    </div>
  </main>

</body>
</html>


<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Vitae — Téléchargement</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;

      display: flex;
      align-items: center;
      justify-content: center;

      font-family:
        -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        sans-serif;

      background: #f5f5f7;
      color: #1d1d1f;
    }

    .container {
      width: min(620px, calc(100% - 40px));
      padding: 48px 30px;

      text-align: center;

      background: #ffffff;
      border: 1px solid #e5e5e7;
      border-radius: 24px;

      box-shadow: 0 12px 40px rgba(0, 0, 0, 0.06);
    }

    .logo {
      margin-bottom: 8px;

      font-size: 42px;
      font-weight: 700;
      letter-spacing: -1.5px;
    }

    .subtitle {
      margin-bottom: 36px;

      color: #777;
      font-size: 16px;
    }

    .version {
      display: inline-block;

      margin-bottom: 30px;
      padding: 7px 12px;

      border-radius: 999px;

      background: #f0f0f2;

      font-size: 14px;
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

      transition:
        background 0.15s ease,
        transform 0.15s ease;
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
  </style>
</head>

<body>

  <main class="container">

    <div class="logo">
      Vitae
    </div>

    <div class="subtitle">
      Centre de téléchargement
    </div>

    <div class="version">
      Version <strong>Vitae-1.0.0-rc.12</strong>
    </div>

    <div class="downloads">

      <!-- WINDOWS -->
      <a
        class="download"
        href="https://mega.nz/file/YI830AZT#qxMDFgJ_seXAVZqw7HQnfVd4nTkoQrx7ZvkGmlNkn1E"
        target="_blank"
        rel="noopener noreferrer"
      >
        <strong>Windows</strong>
        <span class="arrow">→</span>
      </a>

      <!-- ANDROID -->
      <a
        class="download"
        href="https://mega.nz/file/cdNwCA5K#03z8yXse8r6djTKnj92yuBK81M36bcNUpMnprpToonM"
        target="_blank"
        rel="noopener noreferrer"
      >
        <strong>Android</strong>
        <span class="arrow">→</span>
      </a>

      <!-- MAC (Non-disponible) -->
      <a
        class="download"
        href="https://mega.nz/"
        target="_blank"
        rel="noopener noreferrer"
      >
        <strong>Mac</strong>
        <span class="arrow">→</span>
      </a>

    </div>

    <div class="date">
      Publiée le 07/10/2026
    </div>

  </main>

</body>
</html>
```

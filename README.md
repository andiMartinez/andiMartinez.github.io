<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tinta Estudio — Sitio en construcción</title>
<style>
  :root {
    --verde: #b6d334;
    --morado: #3d2b3a;
    --blanco: #ffffff;
  }

  * {
    box-sizing: border-box;
  }

  html, body {
    margin: 0;
    padding: 0;
    height: 100%;
  }

  body {
    background-color: var(--verde);
    color: var(--morado);
    font-family: 'Segoe UI', Verdana, Arial, sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    text-align: center;
    padding: 20px;
  }

  .logo {
    max-width: 320px;
    width: 60%;
    height: auto;
    margin-bottom: 40px;
    animation: fadeIn 1.2s ease-out;
  }

  h1 {
    font-size: clamp(1.6rem, 4vw, 2.4rem);
    letter-spacing: 2px;
    margin: 0 0 12px 0;
    text-transform: uppercase;
  }

  p {
    font-size: 1.05rem;
    max-width: 480px;
    line-height: 1.5;
    margin: 0 0 30px 0;
    opacity: 0.9;
  }

  .dots span {
    display: inline-block;
    width: 10px;
    height: 10px;
    margin: 0 4px;
    border-radius: 50%;
    background-color: var(--morado);
    animation: bounce 1.4s infinite ease-in-out both;
  }

  .dots span:nth-child(1) { animation-delay: -0.32s; }
  .dots span:nth-child(2) { animation-delay: -0.16s; }
  .dots span:nth-child(3) { animation-delay: 0s; }

  footer {
    position: absolute;
    bottom: 20px;
    font-size: 0.8rem;
    opacity: 0.7;
  }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(-10px); }
    to { opacity: 1; transform: translateY(0); }
  }

  @keyframes bounce {
    0%, 80%, 100% { transform: scale(0); }
    40% { transform: scale(1); }
  }
</style>
</head>
<body>

  <img src="assets/logo.png" alt="Tinta Estudio" class="logo">

  <h1>Sitio en construcción</h1>
  <p>Estamos preparando algo nuevo. Muy pronto podrás ver el sitio completo de Tinta Estudio.</p>

  <div class="dots">
    <span></span>
    <span></span>
    <span></span>
  </div>

  <footer>&copy; 2026 Tinta Estudio. Todos los derechos reservados.</footer>

</body>
</html>

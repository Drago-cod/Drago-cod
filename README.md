<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Drago Samuel</title>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Segoe UI", sans-serif;
  }

  body {
    background: #05070d;
    color: white;
    text-align: center;
    overflow-x: hidden;
  }

  /* Hero Container */
  .hero {
    padding: 80px 20px;
    position: relative;
  }

  /* Animated Gradient Banner */
  .banner {
    background: linear-gradient(270deg, #f7b500, #ff8c00, #f7b500);
    background-size: 400% 400%;
    animation: gradientMove 8s ease infinite;
    padding: 60px 20px;
    border-radius: 10px;
    margin-bottom: 40px;
    position: relative;
  }

  @keyframes gradientMove {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  .banner h1 {
    font-size: 2.5rem;
    animation: fadeInDown 1.2s ease;
  }

  /* Wave Effect */
  .wave {
    position: absolute;
    bottom: -20px;
    left: 0;
    width: 100%;
    height: 60px;
    background: #05070d;
    border-top-left-radius: 50% 100%;
    border-top-right-radius: 50% 100%;
  }

  /* Intro Text */
  .intro {
    font-size: 1.8rem;
    margin: 20px 0;
    animation: fadeInUp 1.5s ease;
  }

  .tagline {
    color: #f7b500;
    font-weight: bold;
    margin-top: 10px;
    animation: fadeInUp 2s ease;
  }

  /* Roles */
  .roles {
    margin-top: 20px;
    font-size: 1.1rem;
    opacity: 0.9;
    animation: fadeInUp 2.5s ease;
  }

  /* Animations */
  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(40px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes fadeInDown {
    from {
      opacity: 0;
      transform: translateY(-40px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  /* Typing Effect */
  .typing {
    border-right: 2px solid #fff;
    white-space: nowrap;
    overflow: hidden;
    width: 0;
    animation: typing 4s steps(30, end) forwards, blink 0.8s infinite;
  }

  @keyframes typing {
    to { width: 100%; }
  }

  @keyframes blink {
    50% { border-color: transparent; }
  }
</style>
</head>

<body>

<section class="hero">

  <div class="banner">
    <h1>Drago Samuel</h1>
    <div class="wave"></div>
  </div>

  <div class="intro typing">Hi 👋, I'm Drago Samuel Jared</div>

  <div class="tagline">Turning Ideas into Reality</div>

  <div class="roles">
    🎨 Frontend Developer | UI/UX Designer | Creative Thinker
  </div>

</section>

</body>
</html>

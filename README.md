<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Roys Wanimbo</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #1f1c2c, #928dab);
      color: white;
      text-align: center;
      margin: 0;
      padding: 40px 20px;
    }

    h1 {
      font-size: 2.5em;
      animation: fadeInDown 1s ease-out;
    }

    h3 {
      font-weight: 400;
      margin-top: -10px;
      animation: fadeInUp 1.5s ease-out;
    }

    ul {
      list-style: none;
      padding: 0;
      margin-top: 30px;
      animation: fadeIn 2s ease-out;
    }

    ul li {
      margin-bottom: 10px;
    }

    a {
      color: #FFD700;
      text-decoration: none;
    }

    .social-icons {
      margin-top: 20px;
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
      animation: fadeInUp 2.5s ease-out;
    }

    .social-icons a img {
      transition: transform 0.3s ease;
    }

    .social-icons a:hover img {
      transform: scale(1.2);
    }

    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <h1>Hi 👋, I'm Roys Wanimbo</h1>
  <h3>A passionate frontend developer from Papua</h3>

  <ul>
    <li>🔭 I’m currently working on <a href="https://github.com/royswanimbo" target="_blank">my dream</a></li>
    <li>👯 I’m looking to collaborate on <a href="http://www.sacode.web.id/" target="_blank">with the sacode community</a></li>
  </ul>

  <h3>Connect with me:</h3>
  <div class="social-icons">
    <a href="https://twitter.com/royswanimbo" target="_blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter" height="30" width="40">
    </a>
    <a href="https://linkedin.com/in/royswanimbo" target="_blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40">
    </a>
    <a href="https://fb.com/royswanimbo" target="_blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" height="30" width="40">
    </a>
    <a href="https://instagram.com/royswanimbo" target="_blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="30" width="40">
    </a>
    <a href="https://www.youtube.com/c/royswanimbo" target="_blank">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube" height="30" width="40">
    </a>
  </div>

</body>
</html>

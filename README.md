<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <title>Turki Portfolio</title>

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:#0A0A0A;
      color:#F5F5F5;
      overflow-x:hidden;
    }

    .hero{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      flex-direction:column;
      text-align:center;
      position:relative;
    }

    .glow{
      position:absolute;
      width:350px;
      height:350px;
      background:#FACC15;
      filter:blur(120px);
      opacity:0.15;
      border-radius:50%;
      z-index:0;
    }

    h1{
      font-size:70px;
      color:white;
      letter-spacing:2px;
      z-index:1;
    }

    .subtitle{
      margin-top:15px;
      font-size:20px;
      color:#999;
      z-index:1;
    }

    .cards{
      margin-top:50px;
      display:flex;
      gap:20px;
      z-index:1;
      flex-wrap:wrap;
      justify-content:center;
    }

    .card{
      width:220px;
      height:130px;
      border:1px solid rgba(255,255,255,0.1);
      background:rgba(255,255,255,0.03);
      border-radius:20px;
      display:flex;
      justify-content:center;
      align-items:center;
      font-size:22px;
      transition:0.3s;
      backdrop-filter:blur(10px);
    }

    .card:hover{
      transform:translateY(-8px);
      border-color:#FACC15;
      box-shadow:0 0 25px rgba(250,204,21,0.2);
    }

    .yellow{
      color:#FACC15;
    }

  </style>
</head>

<body>

  <section class="hero">

    <div class="glow"></div>

    <h1>
      Turki <span class="yellow">Portfolio</span>
    </h1>

    <p class="subtitle">
      Academic • Projects • Future
    </p>

    <div class="cards">

      <div class="card">
        About Me
      </div>

      <div class="card">
        Certificates
      </div>

      <div class="card">
        My Letters
      </div>

      <div class="card">
        Projects
      </div>

    </div>

  </section>

</body>
</html>

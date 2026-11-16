<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Body Is a Machine</title>
  <style>
    body {
      margin: 0;
      min-height: 100vh;
      display: grid;
      place-items: center;
      background: #f4f0e8;
      color: #171717;
      font: 800 clamp(2rem, 7vw, 6rem)/0.95 Arial, sans-serif;
      text-align: center;
    }

    main { padding: 2rem; }

    .line {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-wrap: wrap;
      gap: 0.2em;
    }

    img {
      width: 1.5em;
      height: 1.1em;
      object-fit: cover;
      vertical-align: middle;
    }
  </style>
</head>
<body>
  <main>
    <div>MY BODY IS A MACHINE THAT TURNS</div>
    <div class="line">
      <img src="javascript.jpg" alt="JavaScript">
    </div>
    <div>INTO</div>
    <div class="line">
      <img src="garbage.jpg" alt="Garbage">
    </div>
  </main>
</body>
</html>

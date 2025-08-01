<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hard Knox Life</title>
  <link rel="stylesheet" href="Index Page.css">
  <style>

/* Container for flexboxes */
.row {
  display: -webkit-flex;
  display: flex;
}

/* Create three equal columns that sits next to each other */
.column {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  padding: 10px;
}


/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media (max-width: 1000px) {
  .row {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
</style> 
</head>

<body>
  <header>
    <h1>Hard Knox Life</h1>
  </header>

  <hr>

  <fieldset>
    <legend><b>About This Site</b></legend>
    <em>
      <p>This page is where I'll practice the basics of HTML, JavaScript, and CSS as I learn. Expect simple updates as I get more comfortable adding new features.</p>
    </em>
  </fieldset>


  <hr>
  <div class="row">
  <div class="column">
    <fieldset>
    <legend><b>Bio</b></legend>
    <p>
      <ul>
        <li><a href="Bio2.html">View Bio</a></li>
      </ul>
    </p>
  </fieldset>
  </div>

  <div class="row">
  <div class="column">
  <fieldset>
    <legend><b>Frequently Visited Sites</b></legend>
    <ul>
      <li><a href="https://collider.com/">Movie News: collider.com</a></li>
      <li><a href="https://www.damage.com/">Repairable Salvaged Vehicles: damage.com</a></li>
      <li><a href="https://www.gamingbible.com/">Gaming News: gamingbible.com</a></li>
    </ul>
  </fieldset>
  </div>

  <div class="row">
  <div class="column">
  <fieldset>
    <legend><b>Epoxy Table Order Form Link</b></legend>
    <p>
    <ul>
      <li><a href="OrderForm/Epoxy Table Order Form.html">Order an Epoxy Table Here!</a></li>
    </ul>
    </p>
  </fieldset>
  </div>

  <div class="row">
  <div class="column">
  <fieldset>
    <legend><b>How-To Website</b></legend>
    <p>
      <ul>
        <li><a href="Mastery Website.html">View Intrest Website with How-to Tutorial (In Work)!</a></li>
      </ul>
    </p>
  </fieldset>
  </div>



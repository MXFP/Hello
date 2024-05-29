<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <script src="index.js" type="module"></script>
</head>
<body class="back">
  <nav>
    <div class="logo">
      <img src="images/H2.svg" alt="logo">
    </div>
    <div>
      <div class="menu">Menu</div>
      <ul class="menu-nav">
        <li><a href="index.html">Homepage</a></li>
        <li><a href="buy.html">Buy</a></li>
        <li><a href="order.html">Order</a></li>
        <li><a href="log.html">Log In</a></li>
      </ul>
  </div>
  </nav>
    <main>
        <section>
            <h1>Welcome to Hello Kitty store</h1>
            <p>Here we sell absolutely all Hello Kitty products</p>
        </section>
    </main>
    <div class="hero_image">
      <div class="hero_text_container">
        <h1 class="hero_text">Welcome to the Hello Kitty Store</h1>
        <p class="hero_text"> Looking for the perfect gift?</p>
        <a class="button_text" href="buy.html"> <button class="button_text"> Check out our Products! </button> </a>
      </div>
    </div>
    <div class="doll_of_month_container">
      <div class="doll_of_month_txtbox"> 
        <h2 class="doll_of_month_header"> Doll of the Month</h2>
        <p class="doll_of_month_p"> For this month of June, Hello Kitty Shop © will donate 70% of all proceeds 
          from this limited edition Ballroom Kitty doll to Make-A-Wish foundation to help fulfill the wishes of children with a critical illness.
          <a class="button_text" href="order.html"> <button class="button_text"> Purchase Now! </button> </a>
        </div>
    </div>
    <div class="stars_container">
        <div class="stars_textbox">
          <p class="stars_text"> "Amazing doll quality, each individually made with care!"</p>
        </div>
      </div>
      <footer>
        <div class="grid-container">
          <div class="grid-item item1"><p class="copyright_text">Hello Kitty Shop ©</p>
          </div>
</body>
<script>
  document.querySelector('.menu').addEventListener('click', () => {
    document.querySelector('.menu-nav').classList.toggle('inv');
  });
</script>
</html>

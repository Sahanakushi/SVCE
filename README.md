<!DOCTYPE html>
<html>
<head>
<title>SVCE Canteen</title>
<style>
/* Styles for login page and menu */
body {
  background-color: #f5f5f5;
  font-family: Arial, sans-serif;
  text-align: center;
}

.container {
  width: 500px;
  margin: 100px auto;
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 5px #ccc;
}

.logo {
  width: 150px;
  margin-bottom: 20px;
}

h1 {
  font-size: 24px;
  margin-bottom: 20px;
}
button {
  background-color: #007bff;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.menu-items {
  list-style: none;
  padding: 0;
}
.menu-item {
  margin: 10px 0;
  display: flex;
  align-items: center;
}

.menu-item img {
  width: 100px;
  margin-right: 10px;
}

.menu-item h2 {
  font-size: 18px;
  margin: 0;
}

.menu-item span {
  font-weight: bold;
  margin-left: 10px;
}
</style>
</head>
<body>
  <div class="container">
    <img src="C:\Users\sandh\OneDrive\Pictures\Camera Roll\pic\SVCE.jpg" alt="SVCE Logo" class="logo">
    <h1>Welcome to SVCE Canteen</h1>
    <button onclick="openMenu()">Enter Canteen</button>
  </div>
<div id="menu" style="display: none;">
    <h1>SVCE Canteen Menu</h1>
    <ul class="menu-items">
<h3> <b> Veg Items :) </b> </h3>
      <li class="menu-item">
        <img src="C:\Users\sandh\OneDrive\Pictures\Camera Roll\pic\Dosa.jpg" alt="Dosa">
        <h2>Masala Dosa</h2>
        <span>₹45</span>
      </li>
      <li class="menu-item">
        <img src="C:\Users\sandh\OneDrive\Pictures\Camera Roll\pic\ldli.jpg" alt="Idli">
        <h2>Sambar Idli</h2>
        <span>₹30</span>
      </li>
<li class="menu-item">
        <img src="C:\Users\sandh\OneDrive\Pictures\Camera Roll\pic\Appam.jpg" alt="Appam">
        <h2>Appam</h2>
        <span>₹55</span>
      </li>
<li class="menu-item">
        <img src="C:\Users\sandh\OneDrive\Pictures\Camera Roll\pic\Tea.jpg" alt="Tea">
        <h2>Tea</h2>
        <span>₹15</span>
      </li>
<li class="menu-item">
        <img src="C:\Users\sandh\OneDrive\Pictures\Camera Roll\pic\Lemon Rice.jpg" alt="Lemon Rice">
        <h2>Lemon Rice</h2>
        <span>₹45</span>
      </li>
      </ul>
</div>

  <script>
  function openMenu() {
    document.getElementById("menu").style.display = "block";
  }
  </script>
</body>
</html>


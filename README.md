<!DOCTYPE html>
<html>
  <head>
    <title>Barbershop & Cafe</title>
    <style>
      /* CSS styles */
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: olive-drab;
      }
      header {
        background-color: #333;
        color: white;
        padding: 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
      }
      header h1 {
        margin: 0;
        font-size: 36px;
      }
      nav ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
      }
      nav li {
        margin-right: 20px;
      }
      nav a {
        color: white;
        text-decoration: none;
        font-size: 20px;
        font-weight: bold;
        transition: color 0.3s;
      }
      nav a:hover {
        color: #ccc;
      }
      main {
        margin: 20px;
        display: flex;
        flex-wrap: wrap;
      }
      section {
        flex: 1;
        margin: 10px;
        padding: 20px;
        background-color: white;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        border-radius: 5px;
        min-width: 300px;
      }
      section h2 {
        margin-top: 0;
      }
      section p {
        margin-bottom: 0;
      }
      .cta {
        display: block;
        background-color: #333;
        color: white;
        padding: 10px;
        text-align: center;
        margin-top: 20px;
        border-radius: 5px;
        font-weight: bold;
        text-decoration: none;
        transition: background-color 0.3s;
      }
      .cta:hover {
        background-color: #444;
      }
      .qr-code {
        display: flex;
        flex-direction: column;
        align-items: center;
      }
      .qr-code img {
        max-width: 100%;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Barbershop & Cafe</h1>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Menu</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <header>
        <h2>Welcome</h2>
      </header>
      <section>
        <h2>Barbershop</h2>
        <p>We offer a range of haircuts and grooming services for men. Our experienced barbers will help you look and feel your best.</p>
        <a href="#" class="cta">Book an Appointment</a>
      </section>
      <section>
        <h2>Cafe</h2>
        <p>Enjoy a cup of coffee or a bite to eat in our cozy cafe. We offer a selection of sandwiches, pastries, and snacks.</p>
        <a href="#" class="cta">View Menu</a>
      </section>
      <section class="qr-code">
        <h2>Follow

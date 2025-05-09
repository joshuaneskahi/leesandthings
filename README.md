<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lee's & Things</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(to bottom right, #111, #2c2c2c, #444);
      color: #ccc;
      padding: 2rem;
    }
    h1, h2 {
      color: #aaa;
    }
    .section {
      max-width: 1200px;
      margin: 0 auto 4rem auto;
    }
    .card-container {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }
    .card {
      background: #1a1a1a;
      border: 1px solid #333;
      border-radius: 1rem;
      padding: 1.5rem;
      width: 280px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.5);
      text-align: center;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1rem;
    }
    .gallery img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 0.5rem;
      border: 1px solid #444;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      background: #1a1a1a;
      border: 1px solid #333;
      padding: 2rem;
      border-radius: 1rem;
    }
    input, textarea {
      background: #000;
      color: #ccc;
      border: 1px solid #444;
      padding: 0.75rem;
      border-radius: 0.5rem;
    }
    button {
      background: #444;
      color: #eee;
      border: none;
      padding: 0.75rem;
      border-radius: 0.5rem;
      cursor: pointer;
    }
    button:hover {
      background: #555;
    }
    footer {
      text-align: center;
      margin-top: 4rem;
      color: #666;
    }
  </style>
</head>
<body>

  <section class="section">
    <h1 style="text-align:center; font-size: 3rem;">Lee's & Things</h1>
    <p style="text-align:center;">Mechanic • Handyman • Jack of All Trades</p>
  </section>

  <section class="section card-container">
    <div class="card">
      <h2>Mechanic Services</h2>
      <p>From oil changes to full engine diagnostics, Lee's got you covered.</p>
    </div>
    <div class="card">
      <h2>Handyman Work</h2>
      <p>Repairs, installations, odd jobs—no task too small or too big.</p>
    </div>
    <div class="card">
      <h2>Other Services</h2>
      <p>Need help with something else? Lee can probably handle it.</p>
    </div>
  </section>

  <section class="section">
    <h2 style="text-align:center;">Photo Gallery</h2>
    <div class="gallery">
      <img src="https://cdn.pixabay.com/photo/2020/10/08/14/10/man-5638082_640.jpg" alt="Project 1"/>
      <img src="https://st4.depositphotos.com/12982378/22802/i/450/depositphotos_228020620-stock-photo-cropped-shot-auto-mechanic-rag.jpg" alt="Project 2"/>
      <img src="https://www.nextinsurance.com/wp-content/uploads/2022/01/jan-2022-19-802x454.jpg" alt="Project 3"/>
      <img src="https://www.upflip.com/wp-content/uploads/2024/09/Handyman-with-tools.jpg" alt="Project 4"/>
      <img src="https://www.bobvila.com/wp-content/uploads/2023/12/What-Does-a-Handyman-Do-1.jpg?strip=all&quality=85" alt="Project 5"/>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQHHitg6jE5vWZdCornzUuoNjM8s-dUkd3VLw&s" alt="Project 6"/>
    </div>
  </section>

  <section class="section" style="max-width: 600px;">
    <h2 style="text-align:center;">Contact Lee</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <input type="tel" placeholder="Your Phone Number" required />
      <textarea rows="5" placeholder="Scope of project or message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Lee's & Things. All rights reserved.</p>
  </footer>

</body>
</html>

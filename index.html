<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>United States of Africa</title>
  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  <!-- Icons -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
  <!-- Leaflet for Map -->
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
  <!-- Chart.js -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <!-- Styles -->
  <style>
    /* CSS Styles */
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #000;
      color: #fff;
    }
    header {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 1em 0;
      box-shadow: 0 4px 8px rgba(255, 255, 255, 0.1);
    }
    nav {
      background-color: #222;
      overflow: hidden;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      float: left;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      transition: background-color 0.3s;
    }
    nav a:hover {
      background-color: #444;
    }
    #country-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1em;
      padding: 1em;
    }
    .country-card {
      background-color: #111;
      padding: 1em;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(255, 255, 255, 0.1);
      text-align: left;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .country-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 16px rgba(255, 255, 255, 0.2);
    }
    .country-card img {
      width: 100%;
      border-radius: 10px;
    }
    .country-card h3 {
      margin-top: 0;
      color: #4CAF50;
    }
    .country-card p {
      margin: 0.5em 0;
      color: #ccc;
    }
    #map-container {
      width: 100%;
      height: 400px;
      margin: 1em 0;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(255, 255, 255, 0.1);
    }
    #news-feed {
      display: flex;
      flex-direction: column;
      gap: 1em;
      padding: 1em;
    }
    #challenges-solutions {
      padding: 1em;
    }
    .challenge {
      background-color: #111;
      padding: 1em;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(255, 255, 255, 0.1);
      margin-bottom: 1em;
    }
    .challenge h3 {
      color: #4CAF50;
    }
    #quiz-container, #forum-container {
      background-color: #111;
      padding: 1em;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(255, 255, 255, 0.1);
    }
    #back-to-top {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 50%;
      padding: 10px;
      cursor: pointer;
      display: none;
      transition: background-color 0.3s;
    }
    #back-to-top:hover {
      background-color: #45a049;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 1em 0;
      box-shadow: 0 -4px 8px rgba(255, 255, 255, 0.1);
    }
    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .fade-in {
      animation: fadeIn 1s ease-in;
    }
  </style>
</head>
<body>
  <header>
    <h1 class="fade-in">United States of Africa</h1>
  </header>
  <nav>
    <a href="#countries">Countries</a>
    <a href="#map">Map</a>
    <a href="#news">News</a>
    <a href="#challenges-solutions">Challenges & Solutions</a>
    <a href="#quiz">Quiz</a>
    <a href="#forum">Forum</a>
  </nav>
  <main>
    <section id="countries">
      <h2>Countries</h2>
      <div id="country-grid"></div>
    </section>
    <section id="map">
      <h2>Interactive Map</h2>
      <div id="map-container"></div>
    </section>
    <section id="news">
      <h2>Latest News</h2>
      <div id="news-feed"></div>
    </section>
    <section id="challenges-solutions">
      <h2>Challenges & Solutions</h2>
      <div class="challenge">
        <h3>Infrastructure</h3>
        <p><strong>Challenge:</strong> Poor road networks, limited railways, and inadequate air transport systems.</p>
        <p><strong>Solution:</strong> Invest in building roads, railways, and energy systems.</p>
      </div>
      <!-- Add more challenges here -->
    </section>
    <section id="quiz">
      <h2>Discover Your Perfect African Country</h2>
      <div id="quiz-container">
        <p>Take this quiz to find out which African country suits you best!</p>
        <button onclick="startQuiz()">Start Quiz</button>
      </div>
    </section>
    <section id="forum">
      <h2>Community Forum</h2>
      <div id="forum-container">
        <p>Join the discussion and share your experiences about Africa!</p>
        <textarea placeholder="Write your post here..."></textarea>
        <button onclick="postMessage()">Post</button>
      </div>
    </section>
  </main>
  <footer>
    <p>&copy; 2023 United States of Africa</p>
  </footer>
  <!-- Back to Top Button -->
  <button id="back-to-top" onclick="scrollToTop()"><i class="fas fa-arrow-up"></i></button>
  <!-- Scripts -->
  <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/axios@1.1.2/dist/axios.min.js"></script>
  <script>
    // API Keys
    const NEWSAPI_KEY = 'YOUR_NEWSAPI_KEY';

    // Fetch country data
    async function fetchCountries() {
      try {
        const response = await axios.get('https://restcountries.com/v3.1/region/africa');
        const countries = response.data;
        renderCountryCards(countries);
        initializeMap(countries);
      } catch (error) {
        console.error('Error fetching country data:', error);
      }
    }

    // Render country cards
    async function renderCountryCards(countries) {
      const grid = document.getElementById('country-grid');
      for (const country of countries) {
        const card = document.createElement('div');
        card.className = 'country-card fade-in';
        card.innerHTML = `
          <img src="${country.flags.svg}" alt="${country.name.common}">
          <h3>${country.name.common}</h3>
          <p><strong>Capital:</strong> ${country.capital}</p>
          <p><strong>Population:</strong> ${country.population}</p>
          <p><strong>Languages:</strong> ${Object.values(country.languages || {}).join(', ')}</p>
          <p><strong>GDP:</strong> $${country.gdp || 'N/A'}</p>
          <p><strong>President:</strong> ${country.president || 'N/A'}</p>
        `;
        grid.appendChild(card);
      }
    }

    // Initialize interactive map
    function initializeMap(countries) {
      const map = L.map('map-container').setView([0, 20], 3);
      L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
        attribution: '&copy; OpenStreetMap contributors'
      }).addTo(map);

      countries.forEach(country => {
        L.marker([country.latlng[0], country.latlng[1]]).addTo(map)
          .bindPopup(`<b>${country.name.common}</b><br>Capital: ${country.capital}`);
      });
    }

    // Fetch news articles
    async function fetchNews() {
      try {
        const response = await axios.get(`https://newsapi.org/v2/everything?q=Africa&apiKey=${NEWSAPI_KEY}`);
        const articles = response.data.articles;
        renderNews(articles);
      } catch (error) {
        console.error('Error fetching news:', error);
      }
    }

    // Render news feed
    function renderNews(articles) {
      const feed = document.getElementById('news-feed');
      articles.forEach(article => {
        const articleElement = document.createElement('div');
        articleElement.innerHTML = `
          <h3>${article.title}</h3>
          <p><a href="${article.url}" target="_blank">${article.source.name}</a></p>
        `;
        feed.appendChild(articleElement);
      });
    }

    // Quiz functionality
    function startQuiz() {
      alert("Quiz started! (Simulated for now)");
    }

    // Forum functionality
    function postMessage() {
      alert("Message posted! (Simulated for now)");
    }

    // Back to Top Button
    window.onscroll = function() {
      const backToTopButton = document.getElementById('back-to-top');
      if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
        backToTopButton.style.display = 'block';
      } else {
        backToTopButton.style.display = 'none';
      }
    };

    function scrollToTop() {
      document.body.scrollTop = 0;
      document.documentElement.scrollTop = 0;
    }

    // Initialize page
    fetchCountries();
    fetchNews();
  </script>
</body>
</html>

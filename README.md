<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>United Africa</title>
    <meta name="description" content="A website dedicated to uniting the nations of Africa.">
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000; /* Dark background */
            color: #fff; /* Light text */
            line-height: 1.6;
        }

        /* Full-Screen Hero Section */
        #hero {
            height: 100vh;
            background: url('https://via.placeholder.com/1920x1080') no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        #hero h1 {
            font-size: 4rem;
            margin: 0;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* Quotes Section */
        #quotes {
            padding: 40px 20px;
            text-align: center;
            background-color: #1a1a1a; /* Dark gray */
        }

        #quotes h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #FFD700; /* Gold color */
        }

        .quote {
            font-style: italic;
            margin: 20px 0;
            font-size: 1.2rem;
        }

        .quote-author {
            font-weight: bold;
            margin-top: 10px;
            color: #FFD700; /* Gold color */
        }

        /* Reason Section */
        #reason {
            padding: 40px 20px;
            text-align: center;
        }

        #reason h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #FFD700; /* Gold color */
        }

        #reason p {
            max-width: 800px;
            margin: 0 auto;
            font-size: 1.1rem;
        }

        /* Grid Layout for Country Profiles */
        #country-profiles {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .country-profile {
            background-color: #1a1a1a; /* Dark gray */
            padding: 20px;
            border-radius: 10px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: center;
        }

        .country-profile:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(255, 215, 0, 0.3); /* Gold shadow */
        }

        .country-profile img {
            width: 100px;
            height: auto;
            border-radius: 50%;
            margin-bottom: 15px;
        }

        .country-profile h3 {
            margin-top: 0;
            color: #FFD700; /* Gold color */
        }

        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
        }

        /* Back to Top Button */
        #back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #FFD700;
            color: #000;
            padding: 10px 15px;
            border-radius: 50%;
            text-decoration: none;
            display: none;
            z-index: 1000;
        }

        #back-to-top:hover {
            background-color: #fff;
        }

        /* Footer */
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section id="hero">
        <h1>United Africa</h1>
    </section>

    <!-- Quotes Section -->
    <section id="quotes">
        
        <div class="quote">
            "Unity is strength... when there is teamwork and collaboration, wonderful things can be achieved."
            <div class="quote-author">– Mattie Stepanek</div>
        </div>
        <div class="quote">
            "We must learn to live together as brothers or perish together as fools."
            <div class="quote-author">– Martin Luther King Jr.</div>
        </div>
        <div class="quote">
            "No one is too small to make a difference, and no nation is too big to unite for a common cause."
            <div class="quote-author">– Unknown</div>
        </div>
    </section>

    <!-- Reason Section -->
    <section id="reason">
        <h2>Why We Exist</h2>
        <p>
            Africa is a continent rich in culture, resources, and potential. Yet, its true strength lies in its unity. 
            Our mission is to foster collaboration, understanding, and development across all African nations. 
            By uniting our people, we can overcome challenges, celebrate our diversity, and build a brighter future for generations to come.
        </p>
    </section>

    <!-- Country Profiles Section -->
    <section id="country-profiles">
        <h2>Country Profiles</h2>
        <!-- Algeria -->
        <div class="country-profile">
            <img src="https://flagcdn.com/dz.svg" alt="Algeria Flag">
            <h3>Algeria</h3>
            <p><strong>Capital:</strong> Algiers</p>
            <p><strong>Population:</strong> 45.6 million</p>
            <p><strong>Official Language:</strong> Arabic</p>
            <p><strong>Currency:</strong> Algerian Dinar</p>
            <p><strong>Notable Fact:</strong> Largest country in Africa by land area.</p>
        </div>
        <!-- Angola -->
        <div class="country-profile">
            <img src="https://flagcdn.com/ao.svg" alt="Angola Flag">
            <h3>Angola</h3>
            <p><strong>Capital:</strong> Luanda</p>
            <p><strong>Population:</strong> 36.7 million</p>
            <p><strong>Official Language:</strong> Portuguese</p>
            <p><strong>Currency:</strong> Angolan Kwanza</p>
            <p><strong>Notable Fact:</strong> Rich in oil and diamonds.</p>
        </div>
        <!-- Benin -->
        <div class="country-profile">
            <img src="https://flagcdn.com/bj.svg" alt="Benin Flag">
            <h3>Benin</h3>
            <p><strong>Capital:</strong> Porto-Novo</p>
            <p><strong>Population:</strong> 13.7 million</p>
            <p><strong>Official Language:</strong> French</p>
            <p><strong>Currency:</strong> West African CFA</p>
            <p><strong>Notable Fact:</strong> Known for its vibrant culture and voodoo traditions.</p>
        </div>
        <!-- Botswana -->
        <div class="country-profile">
            <img src="https://flagcdn.com/bw.svg" alt="Botswana Flag">
            <h3>Botswana</h3>
            <p><strong>Capital:</strong> Gaborone</p>
            <p><strong>Population:</strong> 2.6 million</p>
            <p><strong>Official Language:</strong> English, Tswana</p>
            <p><strong>Currency:</strong> Botswana Pula</p>
            <p><strong>Notable Fact:</strong> One of the world’s largest diamond producers.</p>
        </div>
        <!-- Burkina Faso -->
        <div class="country-profile">
            <img src="https://flagcdn.com/bf.svg" alt="Burkina Faso Flag">
            <h3>Burkina Faso</h3>
            <p><strong>Capital:</strong> Ouagadougou</p>
            <p><strong>Population:</strong> 22.8 million</p>
            <p><strong>Official Language:</strong> French</p>
            <p><strong>Currency:</strong> West African CFA</p>
            <p><strong>Notable Fact:</strong> Known for its music and film industry.</p>
        </div>
        <!-- Burundi -->
        <div class="country-profile">
            <img src="https://flagcdn.com/bi.svg" alt="Burundi Flag">
            <h3>Burundi</h3>
            <p><strong>Capital:</strong> Gitega</p>
            <p><strong>Population:</strong> 12.6 million</p>
            <p><strong>Official Language:</strong> Kirundi, French</p>
            <p><strong>Currency:</strong> Burundian Franc</p>
            <p><strong>Notable Fact:</strong> One of the smallest and most densely populated countries in Africa.</p>
        </div>
        <!-- Cabo Verde -->
        <div class="country-profile">
            <img src="https://flagcdn.com/cv.svg" alt="Cabo Verde Flag">
            <h3>Cabo Verde</h3>
            <p><strong>Capital:</strong> Praia</p>
            <p><strong>Population:</strong> 598,000</p>
            <p><strong>Official Language:</strong> Portuguese</p>
            <p><strong>Currency:</strong> Cape Verdean Escudo</p>
            <p><strong>Notable Fact:</strong> An archipelago known for its beautiful beaches and music.</p>
        </div>
        <!-- Cameroon -->
        <div class="country-profile">
            <img src="https://flagcdn.com/cm.svg" alt="Cameroon Flag">
            <h3>Cameroon</h3>
            <p><strong>Capital:</strong> Yaoundé</p>
            <p><strong>Population:</strong> 28.6 million</p>
            <p><strong>Official Language:</strong> French, English</p>
            <p><strong>Currency:</strong> Central African CFA</p>
            <p><strong>Notable Fact:</strong> Known as "Africa in miniature" due to its diverse geography and culture.</p>
        </div>
        <!-- Central African Republic -->
        <div class="country-profile">
            <img src="https://flagcdn.com/cf.svg" alt="Central African Republic Flag">
            <h3>Central African Republic</h3>
            <p><strong>Capital:</strong> Bangui</p>
            <p><strong>Population:</strong> 5.5 million</p>
            <p><strong>Official Language:</strong> French, Sango</p>
            <p><strong>Currency:</strong> Central African CFA</p>
            <p><strong>Notable Fact:</strong> Rich in natural resources but one of the poorest countries in the world.</p>
        </div>
        <!-- Chad -->
        <div class="country-profile">
            <img src="https://flagcdn.com/td.svg" alt="Chad Flag">
            <h3>Chad</h3>
            <p><strong>Capital:</strong> N'Djamena</p>
            <p><strong>Population:</strong> 17.9 million</p>
            <p><strong>Official Language:</strong> French, Arabic</p>
            <p><strong>Currency:</strong> Central African CFA</p>
            <p><strong>Notable Fact:</strong> Home to Lake Chad, a vital water source for the region.</p>
        </div>
        <!-- Comoros -->
        <div class="country-profile">
            <img src="https://flagcdn.com/km.svg" alt="Comoros Flag">
            <h3>Comoros</h3>
            <p><strong>Capital:</strong> Moroni</p>
            <p><strong>Population:</strong> 852,000</p>
            <p><strong>Official Language:</strong> Comorian, Arabic, French</p>
            <p><strong>Currency:</strong> Comorian Franc</p>
            <p><strong>Notable Fact:</strong> An archipelago known for its fragrant vanilla and ylang-ylang.</p>
        </div>
        <!-- Congo (DRC) -->
        <div class="country-profile">
            <img src="https://flagcdn.com/cd.svg" alt="Congo (DRC) Flag">
            <h3>Congo (DRC)</h3>
            <p><strong>Capital:</strong> Kinshasa</p>
            <p><strong>Population:</strong> 102.3 million</p>
            <p><strong>Official Language:</strong> French</p>
            <p><strong>Currency:</strong> Congolese Franc</p>
            <p><strong>Notable Fact:</strong> The second-largest country in Africa by land area.</p>
        </div>
        <!-- Congo (Republic) -->
        <div class="country-profile">
            <img src="https://flagcdn.com/cg.svg" alt="Congo (Republic) Flag">
            <h3>Congo (Republic)</h3>
            <p><strong>Capital:</strong> Brazzaville</p>
            <p><strong>Population:</strong> 5.8 million</p>
            <p><strong>Official Language:</strong> French</p>
            <p><strong>Currency:</strong> Central African CFA</p>
            <p><strong>Notable Fact:</strong> Known for its rainforests and wildlife.</p>
        </div>
        <!-- Côte d'Ivoire -->
        <div class="country-profile">
            <img src="https://flagcdn.com/ci.svg" alt="Côte d'Ivoire Flag">
            <h3>Côte d'Ivoire</h3>
            <p><strong>Capital:</strong> Yamoussoukro</p>
            <p><strong>Population:</strong> 28.2 million</p>
            <p><strong>Official Language:</strong> French</p>
            <p><strong>Currency:</strong> West African CFA</p>
            <p><strong>Notable Fact:</strong> The world’s largest producer of cocoa beans.</p>
        </div>
        <!-- Djibouti -->
        <div class="country-profile">
            <img src="https://flagcdn.com/dj.svg" alt="Djibouti Flag">
            <h3>Djibouti</h3>
            <p><strong>Capital:</strong> Djibouti City</p>
            <p><strong>Population:</strong> 1.1 million</p>
            <p><strong>Official Language:</strong> French, Arabic</p>
            <p><strong>Currency:</strong> Djiboutian Franc</p>
            <p><strong>Notable Fact:</strong> Strategically located at the entrance to the Red Sea.</p>
        </div>
        <!-- Egypt -->
        <div class="country-profile">
            <img src="https://flagcdn.com/eg.svg" alt="Egypt Flag">
            <h3>Egypt</h3>
            <p><strong>Capital:</strong> Cairo</p>
            <p><strong>Population:</strong> 112.7 million</p>
            <p><strong>Official Language:</strong> Arabic</p>
            <p><strong>Currency:</strong> Egyptian Pound</p>
            <p><strong>Notable Fact:</strong> Home to the ancient pyramids and the Nile River.</p>
        </div>
        <!-- Equatorial Guinea -->
        <div class="country-profile">
            <img src="https://flagcdn.com/gq.svg" alt="Equatorial Guinea Flag">
            <h3>Equatorial Guinea</h3>
            <p><strong>Capital:</strong> Malabo</p>
            <p><strong>Population:</strong> 1.7 million</p>
            <p><strong>Official Language:</strong> Spanish, French, Portuguese</p>
            <p><strong>Currency:</strong> Central African CFA</p>
            <p><strong>Notable Fact:</strong> One of the smallest countries in Africa by population.</p>
        </div>
        <!-- Eritrea -->
        <div class="country-profile">
            <img src="https://flagcdn.com/er.svg" alt="Eritrea Flag">
            <h3>Eritrea</h3>
            <p><strong>Capital:</strong> Asmara</p>
            <p><strong>Population:</strong> 3.7 million</p>
            <p><strong>Official Language:</strong> Tigrinya, Arabic, English</p>
            <p><strong>Currency:</strong> Eritrean Nakfa</p>
            <p><strong>Notable Fact:</strong> Known for its Italian colonial architecture.</p>
        </div>
        <!-- Eswatini -->
        <div class="country-profile">
            <img src="https://flagcdn.com/sz.svg" alt="Eswatini Flag">
            <h3>Eswatini</h3>
            <p><strong>Capital:</strong> Mbabane</p>
            <p><strong>Population:</strong> 1.2 million</p>
            <p><strong>Official Language:</strong> Swazi, English</p>
            <p><strong>Currency:</strong> Swazi Lilangeni</p>
            <p><strong>Notable Fact:</strong> One of the last absolute monarchies in the world.</p>
        </div>
        <!-- Ethiopia -->
        <div class="country-profile">
            <img src="https://flagcdn.com/et.svg" alt="Ethiopia Flag">
            <h3>Ethiopia</h3>
            <p><strong>Capital:</strong> Addis Ababa</p>
            <p><strong>Population:</strong> 126.5 million</p>
            <p><strong>Official Language:</strong> Amharic</p>
            <p><strong>Currency:</strong> Ethiopian Birr</p>
            <p><strong>Notable Fact:</strong> The second-most populous country in Africa.</p>
        </div>
        <!-- Gabon -->
        <div class="country-profile">
            <img src="https://flagcdn.com/ga.svg" alt="Gabon Flag">
            <h3>Gabon</h3>
            <p><strong>Capital:</strong> Libreville</p>
            <p><strong>Population:</strong> 2.4 million</p>
            <p><strong>Official Language:</strong> French</p>
            <p><strong>Currency:</strong> Central African CFA</p>
            <p><strong>Notable Fact:</strong> Known for its rainforests and wildlife.</p>
        </div>
        <!-- Gambia -->
        <div class="country-profile">
            <img src="https://flagcdn.com/gm.svg" alt="Gambia Flag">
            <h3>Gambia</h3>
            <p><strong>Capital:</strong> Banjul</p>
            <p><strong>Population:</strong> 2.8 million</p>
            <p><strong>Official Language:</strong> English</p>
            <p><strong>Currency:</strong> Gambian Dalasi</p>
            <p><strong>Notable Fact:</strong> The smallest country on mainland Africa.</p>
        </div>
        <!-- Ghana -->
        <div class="country-profile">
            <img src="https://flagcdn.com/gh.svg" alt="Ghana Flag">
            <h3>Ghana</h3>
            <p><strong>Capital:</strong> Accra</p>
            <p><strong>Population:</strong> 33.5 million</p>
            <p><strong>Official Language:</strong> English</p>
            <p><strong>Currency:</strong> Ghanaian Cedi</p>
            <p><strong>Notable Fact:</strong> Known for its stable democracy and rich cultural heritage.</p>
        </div>
        <!-- Guinea -->
        <div class="country-profile">
            <img src="https://flagcdn.com/gn.svg" alt="Guinea Flag">
            <h3>Guinea</h3>
            <p><strong>Capital:</strong> Conakry</p>
            <p><strong>Population:</strong> 14.2 million</p>
            <p><strong>Official Language:</strong> French</p>
            <p><strong>Currency:</strong> Guinean Franc</p>
            <p><strong>Notable Fact:</strong> Rich in bauxite and other minerals.</p>
        </div>
        <!-- Guinea-Bissau -->
        <div class="country-profile">
            <img src="https://flagcdn.com/gw.svg" alt="Guinea-Bissau Flag">
            <h3>Guinea-Bissau</h3>
            <p><strong>Capital:</strong> Bissau</p>
            <p><strong>Population:</strong> 2.1 million</p>
            <p><strong>Official Language:</strong> Portuguese</p>
            <p><strong>Currency:</strong> West African CFA</p>
            <p><strong>Notable Fact:</strong> Known for its diverse ethnic groups and music.</p>
        </div>
        <!-- Kenya -->
        <div class="country-profile">
            <img src="https://flagcdn.com/ke.svg" alt="Kenya Flag">
            <h3>Kenya</h3>
            <p><strong>Capital:</strong> Nairobi</p>
            <p><strong>Population:</strong> 56.2 million</p>
            <p><strong>Official Language:</strong> Swahili, English</p>
            <p><strong>Currency:</strong> Kenyan Shilling</p>
            <p><strong>Notable Fact:</strong> Famous for its wildlife and the Maasai Mara National Reserve.</p>
        </div>
        <!-- Lesotho -->
        <div class="country-profile">
            <img src="https://flagcdn.com/ls.svg" alt="Lesotho Flag">
            <h3>Lesotho</h3>
            <p><strong>Capital:</strong> Maseru</p>
            <p><strong>Population:</strong> 2.3 million</p>
            <p><strong>Official Language:</strong> Sesotho, English</p>
            <p><strong>Currency:</strong> Lesotho Loti</p>
            <p><strong>Notable Fact:</strong> A landlocked country entirely surrounded by South Africa.</p>
        </div>
        <!-- Liberia -->
        <div class="country-profile">
            <img src="https://flagcdn.com/lr.svg" alt="Liberia Flag">
            <h3>Liberia</h3>
            <p><strong>Capital:</strong> Monrovia</p>
            <p><strong>Population:</strong> 5.4 million</p>
            <p><strong>Official Language:</strong> English</p>
            <p><strong>Currency:</strong> Liberian Dollar</p>
            <p><strong>Notable Fact:</strong> Founded by freed American slaves in the 19th century.</p>
        </div>
   

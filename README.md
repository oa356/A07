<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <title>San Joaquin Valley Town Hall</title>
    <link rel="shortcut icon" href="images/favicon.ico">
    <link rel="stylesheet" href="styles/normalize.css">
    <link rel="stylesheet" href="styles/main.css">
    <style>
        /* Reset selector */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body styling */
        html {
            background-color: white;
        }

        body {
            width: 600px;
            margin: 0 auto;
            border: 3px solid #931420;
            background-color: #fffded;
        }

        /* Header styling */
        header {
            padding: 1.5em 0 2em 0;
            border-bottom: 3px solid #931420;
            background: linear-gradient(30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
            text-align: center;
        }

        header img {
            padding: 0 30px;
        }

        /* Main content styling */
        main {
            padding: 0 30px;
        }

        h1 {
            border-top: 3px solid #931420;
            border-bottom: 3px solid #931420;
            padding: 10px 0;
            text-align: center;
        }

        /* Footer styling */
        footer {
            background-color: #931420;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        /* Blockquote styling */
        blockquote {
            font-style: italic;
        }

        /* Speakers heading styling */
        #speakers {
            border: 4px double #931420;
            border-radius: 10px;
            box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.3);
            padding: 10px;
            text-align: center;
        }
    </style>
</head>

<body>
    <header>
        <img src="images/town_hall_logo.gif" alt="Town Hall logo" height="80">
        <h2>San Joaquin Valley Town Hall</h2>
        <h3>Celebrating our <span class="shadow">75<sup>th</sup></span> Year</h3>
    </header>
    <nav id="nav_menu">
        <ul>
            <li><a href="../index.html">Home</a></li>
            <li><a href="speakers.html">Speakers</a></li>
            <li><a href="luncheons.html">Luncheons</a></li>
            <li><a href="tickets.html">Tickets</a></li>
            <li><a href="aboutus.html"> About Us</a>
                <ul>
                    <li><a href="#">Our History</a></li>
                    <li><a href="#">Board of Directors</a></li>
                    <li><a href="#">Past Speakers</a></li>
                    <li><a href="#">Contact Information</a></li>
                </ul>
            </li>
        </ul>
    </nav>
    <main>
        <section>
            <h2>Our Mission</h2>
            <p>San Joaquin Valley Town Hall is a non-profit organization that is run by an all-volunteer board of directors. Our mission is to bring nationally and internationally renowned, thought-provoking speakers who inform, educate, and entertain our audience! As one of our members told us:</p>
            <blockquote>&ldquo;Each year I give a ticket package to each of our family members. I think of it as the gift of knowledge...and that is priceless.&rdquo;</blockquote>
            <h1>Speaker of the Month</h1>
            <article>
                <h2>Fossil Threads in the Web of Life</h2>
                <img src="images/sampson_dinosaur.jpg" alt="Scott Sampson with Dinosaur">
                <h3>February<br>Scott Sampson</h3>
                <p>What's 75 million years old and brand spanking new? A teenage Utahceratops! Come to the Saroyan, armed with your best dinosaur roar, when Scott Sampson, Research Curator at the Utah Museum of Natural History, steps to the podium. Sampson's research has focused on the ecology and evolution of late Cretaceous dinosaurs and he has conducted fieldwork in a number of countries in Africa.</p>
                <p><a href="speakers/sampson.html"><b>Read more.</b></a>&nbsp;
                    <a href="speakers/sampson_video.html" target="_blank"><b>Or play video.</b></a>
                </p>
            </article>
            <h2>Our Ticket Packages</h2>
            <ul>
                <li>Season Package: $95</li>
                <li>Patron Package: $200</li>
                <li>Single Speaker: $25</li>
            </ul>
        </section>
        <aside>
            <h2 id="speakers">Speakers</h2>
		<h1>This season's guest speakers</h1>
		<h3>October<br><a href="speakers/brancaccio.html">David Brancaccio</a></h3>
		<img src="images/brancaccio75.jpg" alt="David Brancaccio photo">
		<h3>November<br><a href="speakers/sorkin.html">Andrew Ross Sorkin</a></h3>
		<img src="images/sorkin75.jpg" alt="Andrew Ross Sorkin photo">
		<h3>January<br><a href="speakers/chua.html">Amy Chua</a></h3>
		<img src="images/chua75.jpg" alt="Amy Chua photo">
        </aside>
    </main>
    <footer>
        <p>&copy; 2018, San Joaquin Valley Town Hall, Fresno, CA 93755</p>
    </footer>
</body>

</html>

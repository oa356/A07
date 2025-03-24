<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <title>San Joaquin Valley Town Hall</title>
    <link rel="stylesheet" href="styles/main.css">
    <style>
        body {
            width: 600px;
            margin: 0 auto;
            border: 3px solid #931420;
            background-color: #fffded;
            font-family: Arial, sans-serif;
        }

        html {
            background-color: white;
        }

        header {
            text-align: center;
            padding: 1.5em 0;
            background: linear-gradient(30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
            border-bottom: 3px solid #931420;
        }

        h1 {
            text-align: center;
            font-size: 1.5em;
            border-top: 3px solid #931420;
            border-bottom: 3px solid #931420;
            padding: 0.5em 0;
        }

        .content {
            padding: 20px;
        }

        blockquote {
            font-style: italic;
        }

        footer {
            background-color: #931420;
            color: white;
            text-align: center;
            padding: 1em 0;
            font-size: 0.8em;
        }

        .speakers h2 {
            border: 3px double #931420;
            border-radius: 10px;
            padding: 10px;
            text-align: center;
            box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);
        }

        .speaker {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }

        .speaker img {
            width: 60px;
            height: 60px;
            margin-right: 15px;
            border-radius: 5px;
        }

        .speaker a {
            font-weight: bold;
            text-decoration: none;
            color: #003366;
        }
    </style>
</head>

<body>
    <header>
        <img src="images/town_hall_logo.gif" alt="Town Hall logo" height="80">
        <h1>San Joaquin Valley Town Hall</h1>
        <p><em>Celebrating our <strong>75<sup>th</sup></strong> Year</em></p>
    </header>

    <div class="content">
        <h2>Our Mission</h2>
        <p>San Joaquin Valley Town Hall is a non-profit organization that is run by an all-volunteer board of directors. Our mission is to bring nationally and internationally renowned, thought-provoking speakers who inform, educate, and entertain our audience!</p>
        <blockquote>“Each year I give a ticket package to each of our family members. I think of it as the gift of knowledge...and that is priceless.”</blockquote>

        <h2>Our Ticket Packages</h2>
        <ul>
            <li>Season Package: $95</li>
            <li>Patron Package: $200</li>
            <li>Single Speaker: $25</li>
        </ul>

        <h1>This season's guest speakers</h1>
        <div class="speakers">
            <div class="speaker">
                <img src="images/toobin75.jpg" alt="David Brancaccio">
                <p><strong>October</strong><br><a href="#">David Brancaccio</a></p>
            </div>
            <div class="speaker">
                <img src="images/sorkin75.jpg" alt="Andrew Ross Sorkin">
                <p><strong>November</strong><br><a href="#">Andrew Ross Sorkin</a></p>
            </div>
            <div class="speaker">
                <img src="images/chua75.jpg" alt="Amy Chua">
                <p><strong>January</strong><br><a href="#">Amy Chua</a></p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2022 San Joaquin Valley Town Hall</p>
    </footer>
</body>

</html>

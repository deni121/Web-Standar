# Web-Standar
tampilan HTML dengan navbar menu dan isi body kolom Link

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .header {
            background-color: #6200ea;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .header h1 {
            margin: 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 10px;
        }
        .card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin: 10px 0;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .nav {
            display: flex;
            justify-content: space-around;
            background: #6200ea;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .highlight {
            color: #6200ea;
            font-weight: bold;
        }
        .btn {
            background: #6200ea;
            color: white;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            cursor: pointer;
        }
        .btn:hover {
            background: #3700b3;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Dashboard</h1>
        <p>Welcome, <span class="highlight">@username</span>! You have <span class="highlight">100</span> points.</p>
    </div>

    <div class="container">
        <div class="grid">
            <div class="card">
                <h2>Daily Check-In</h2>
                <p>Earn points by checking in daily.</p>
                <button class="btn">Check-In Now</button>
            </div>
            <div class="card">
                <h2>Invite Friends</h2>
                <p>Invite your friends to earn more points!</p>
                <button class="btn">Get Invite Link</button>
            </div>
            <div class="card">
                <h2>Play Drop Game</h2>
                <p>Have fun and earn points by playing games.</p>
                <button class="btn">Play Now</button>
            </div>
            <div class="card">
                <h2>Wallet</h2>
                <p>View your balance and transaction history.</p>
                <button class="btn">Go to Wallet</button>
            </div>
        </div>
    </div>

    <div class="nav">
        <a href="#">Home</a>
        <a href="#">Earn</a>
        <a href="#">Friends</a>
        <a href="#">Wallet</a>
    </div>
</body>
</html>


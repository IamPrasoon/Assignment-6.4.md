
<!DOCTYPE html>
<html>
<head>
    <title>CSS Positioning</title>
    <style>
        body { margin: 0; font-family: Arial; }
        nav {
            position: sticky;
            top: 0;
            background: navy;
            color: white;
            padding: 15px;
            z-index: 10;
        }
        section { height: 400px; padding: 20px; }
        .card {
            position: relative;
            background: lightblue;
            padding: 30px;
            margin: 20px;
        }
        .badge {
            position: absolute;
            top: 0;
            right: 0;
            background: red;
            color: white;
            padding: 5px;
        }
        .help {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: green;
            color: white;
            padding: 15px;
            z-index: 20;
        }
    </style>
</head>
<body>
    <nav>Home | About | Contact</nav>

    <section>
        <h1>Welcome</h1>
        <div class="card">
            <span class="badge">New</span>
            <h2>My Card</h2>
            <p>Learning CSS Positioning</p>
        </div>
    </section>

    <section>
        <h2>About Us</h2>
        <p>Scroll to test sticky navigation.</p>
    </section>

    <section>
        <h2>Contact</h2>
    </section>

    <a class="help" href="mailto:anandprasoon6@gmail.com">Help</a>
</body>
</html>

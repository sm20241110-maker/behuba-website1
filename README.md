# behuba-website1
Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>BehuBa | We Do It</title>

    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            background: #0f172a;
            color: #ffffff;
        }

        header {
            padding: 80px 20px;
            text-align: center;
            background: linear-gradient(135deg, #2563eb, #1e40af);
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.4rem;
            font-weight: 300;
            opacity: 0.9;
        }

        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: auto;
        }

        .about {
            text-align: center;
        }

        .about h2 {
            font-size: 2rem;
            margin-bottom: 15px;
            color: #60a5fa;
        }

        .about p {
            font-size: 1.1rem;
            line-height: 1.6;
            color: #e5e7eb;
        }

        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin-top: 40px;
        }

        .card {
            background: #1e293b;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-6px);
        }

        .card h3 {
            margin-bottom: 10px;
            color: #93c5fd;
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #020617;
            font-size: 0.9rem;
            color: #9ca3af;
        }
    </style>
</head>

<body>

<header>
    <h1>BehuBa</h1>
    <p>We Do It</p>
</header>

<section class="about">
    <h2>About Us</h2>
    <p>
        BehuBa is built on one simple belief — execution matters.
        From ideas to implementation, we take ownership and deliver
        results with clarity, commitment, and creativity.
    </p>

    <div class="services">
        <div class="card">
            <h3>Technology</h3>
            <p>Building secure, scalable, and modern digital solutions.</p>
        </div>

        <div class="card">
            <h3>Innovation</h3>
            <p>Turning ideas into real-world products and services.</p>
        </div>

        <div class="card">
            <h3>Execution</h3>
            <p>No excuses. No delays. We do what we promise.</p>
        </div>
    </div>
</section>

<footer>
    © 2026 BehuBa.in | We Do It
</footer>

</body>
</html>

# VAE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project Hub</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --card-bg: #161b22;
            --text-color: #c9d1d9;
            --accent-color: #58a6ff;
            --border-color: #30363d;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        header {
            text-align: center;
            margin: 4rem 0 2rem 0;
        }

        header h1 {
            font-size: 2.5rem;
            color: #ffffff;
            margin-bottom: 0.5rem;
            letter-spacing: -0.5px;
        }

        header p {
            color: #8b949e;
            font-size: 1.1rem;
        }

        .container {
            width: 90%;
            max-width: 900px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            padding: 1rem;
        }

        .card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 1.75rem;
            text-decoration: none;
            color: inherit;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            top: 0;
        }

        .card:hover {
            top: -4px;
            border-color: var(--accent-color);
            box-shadow: 0 8px 24px rgba(56, 139, 253, 0.15);
        }

        .card h2 {
            margin: 0 0 0.5rem 0;
            font-size: 1.4rem;
            color: #ffffff;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .card h2::after {
            content: "→";
            color: var(--accent-color);
            transition: transform 0.3s ease;
        }

        .card:hover h2::after {
            transform: translateX(5px);
        }

        .card p {
            margin: 0;
            color: #8b949e;
            font-size: 0.95rem;
            line-height: 1.5;
        }

        footer {
            margin-top: auto;
            padding: 2rem;
            color: #484f58;
            font-size: 0.85rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Project Dashboard</h1>
        <p>Welcome! Click on a card below to view my hosted files.</p>
    </header>

    <div class="container">

        <a href="file1.html" class="card">
            <h2>Project One</h2>
            <p>Change this description to explain what your first HTML file does.</p>
        </a>

        <a href="file2.html" class="card">
            <h2>Project Two</h2>
            <p>Change this description to explain what your second HTML file does.</p>
        </a>

        </div>

    <footer>
        Shared via GitHub Pages
    </footer>

</body>
</html>

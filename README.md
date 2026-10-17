<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Uriel Nexus Institute | Antoniou Universal Framework (AUF)</title>
    <style>
        :root {
            --bg-color: #0b0f19;
            --card-bg: #111827;
            --accent-purple: #8b5cf6;
            --accent-blue: #3b82f6;
            --accent-orange: #f97316;
            --text-main: #f3f4f6;
            --text-muted: #9ca3af;
            --border-color: #1f2937;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            padding: 20px;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 40px 0;
            border-bottom: 1px solid var(--border-color);
            margin-bottom: 40px;
        }
        h1 {
            font-size: 2.5rem;
            color: #fff;
            margin-bottom: 10px;
        }
        .subtitle {
            font-size: 1.1rem;
            color: var(--accent-purple);
            margin-bottom: 20px;
        }
        .badges {
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
            margin-top: 15px;
        }
        .badge {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            color: var(--text-muted);
        }
        section {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 30px;
            margin-bottom: 30px;
        }
        h2 {
            font-size: 1.5rem;
            color: var(--accent-blue);
            margin-bottom: 15px;
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 8px;
        }
        h3 {
            font-size: 1.2rem;
            color: var(--accent-orange);
            margin-top: 20px;
            margin-bottom: 10px;
        }
        p, li {
            color: var(--text-muted);
            margin-bottom: 10px;
        }
        ul {
            padding-left: 20px;
        }
        .formula {
            background: #030712;
            padding: 15px;
            border-left: 4px solid var(--accent-purple);
            font-family: monospace;
            color: #e5e7eb;
            margin: 15px 0;
            border-radius: 4px;
            overflow-x: auto;
        }
        .book-grid {
            display: grid;
            grid-template-columns

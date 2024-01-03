<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BNP PARIBAS - Accéder à mes Comptes</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/github-markdown-css@4.0.0/github-markdown.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .header {
            text-align: center;
            margin-bottom: 20px;
        }

        .header img {
            width: 100px;
            height: 100px;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
        }

        .form-group input {
            width: 100%;
            padding: 5px;
            border: 1px solid #ccc;
            border-radius: 3px;
        }

        .form-group button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 3px;
            cursor: pointer;
            font-size: 16px;
        }

        .form-group button:hover {
            background-color: #45a049;
        }

        .footer {
            text-align: center;
            margin-top: 20px;
        }

        .footer a {
            color: #333;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://www.bnpparibas.com/content/dam/paribas-digital-build/logo/logo-banque-paribas.png" alt="BNP PARIBAS">
        </div>

        <form>
            <div class="form-group">
                <label for="numero-client">Mon numéro client</label>
                <input type="text" id="numero-client" name="numero-client">
            </div>

            <div class="form-group">
                <label for="code-secret">Mon code secret (6 chiffres)</label>
                <input type="password" id="code-secret" name="code-secret">
            </div>

            <div class="form-group">
                <button type="submit">Accéder à mes Comptes</button>
            </div>
        </form>

        <div class="footer">
            <a href="#">Numéro client ou code secret oublié ?</a>
        </div>
    </div>
</body>
</html>

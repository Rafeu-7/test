<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lovely Questions</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(120deg, #f6d365, #fda085);
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            max-width: 400px;
            width: 100%;
        }
        h1 {
            color: #ff6f61;
        }
        .question {
            margin: 15px 0;
            font-size: 1.2em;
        }
        input[type="text"], textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #ff6f61;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        button:hover {
            background-color: #e0554d;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1> Questions for my Queen oishi ❤️</h1>
        <form>
            <div class="question">
                <label for="q1">1. Practical kora sesh? huhh</label>
                <textarea id="q1" rows="3" required></textarea>
            </div>
            <div class="question">
                <label for="q2">2. Bou tmi amake kotota valobasho? </label>
                <textarea id="q2" rows="3" required></textarea>
            </div>
            <div class="question">
                <label for="q3">3. Kemon laglo jaan site ta? </label>
                <textarea id="q3" rows="3" required></textarea>
            </div>
            <button type="submit">Submit Your Answers 💌</button>
        </form>
    </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prediction Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            text-align: center;
        }

        form {
            margin-bottom: 20px;
        }

        input[type="text"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 8px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        th {
            background-color: #f2f2f2;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>Prediction Website</h1>
        <form>
            <input type="text" placeholder="Enter your prediction...">
            <input type="submit" value="Submit Prediction">
        </form>
        <h2>Leaderboard</h2>
        <table>
            <tr>
                <th>User</th>
                <th>Accuracy</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>80%</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>75%</td>
            </tr>
            <tr>
                <td>Bob Johnson</td>
                <td>70%</td>
            </tr>
        </table>
    </div>
</body>

</html>

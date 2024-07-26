<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>End of Day Questionnaire</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .question {
            margin-bottom: 15px;
        }
        .question label {
            display: block;
            font-weight: bold;
            margin-bottom: 5px;
            color: #555;
        }
        .question textarea {
            width: 100%;
            height: 100px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
            resize: vertical;
        }
        .submit-btn {
            display: block;
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 4px;
            background-color: #28a745;
            color: #fff;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
        }
        .submit-btn:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>End of Day Questionnaire</h1>
        <form id="questionnaire-form">
            <div class="question">
                <label for="q1">Test Cases Executed:</label>
                <textarea id="q1" name="q1" placeholder="Your answer here..."></textarea>
            </div>
            <div class="question">
                <label for="q2">Tests Passed:</label>
                <textarea id="q2" name="q2" placeholder="Your answer here..."></textarea>
            </div>
            <div class="question">
                <label for="q3">Tests Failed:</label>
                <textarea id="q3" name="q3" placeholder="Your answer here..."></textarea>
            </div>
            <div class="question">
                <label for="q4">Bugs Created:</label>
                <textarea id="q4" name="q4" placeholder="Your answer here..."></textarea>
            </div>
            <div class="question">
                <label for="q5">Bugs Tested:</label>
                <textarea id="q5" name="q5" placeholder="Your answer here..."></textarea>
            </div>
            <div class="question">
                <label for="q6">Bugs Passed:</label>
                <textarea id="q6" name="q6" placeholder="Your answer here..."></textarea>
            </div>
            <div class="question">
                <label for="q7">Bugs Failed:</label>
                <textarea id="q7" name="q7" placeholder="Your answer here..."></textarea>
            </div>
            <div class="question">
                <label for="q8">Verifications:</label>
                <textarea id="q8" name="q8" placeholder="Your answer here..."></textarea>
            </div>
            <div class="question">
                <label for="q9">Defects:</label>
                <textarea id="q9" name="q9" placeholder="Your answer here..."></textarea>
            </div>
            <button type="submit" class="submit-btn">Submit</button>
        </form>
    </div>
</body>
</html>

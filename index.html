<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Teka-Teki Berhitung Level</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      text-align: center;
      background: linear-gradient(135deg, #b3e5fc, #e1bee7);
      padding-top: 50px;
    }
    .container {
      background: white;
      display: inline-block;
      padding: 40px;
      border-radius: 25px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      width: 300px;
    }
    input {
      padding: 10px;
      width: 120px;
      font-size: 16px;
      text-align: center;
      margin-top: 10px;
      border-radius: 8px;
      border: 1px solid #ccc;
    }
    button {
      margin-top: 15px;
      padding: 10px 25px;
      border: none;
      border-radius: 10px;
      background: #4a90e2;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background: #357ABD;
    }
    #feedback {
      margin-top: 15px;
      font-size: 18px;
      font-weight: bold;
    }
    .info {
      font-size: 14px;
      color: #555;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>🧮 Teka-Teki Berhitung</h1>
    <p class="info">Level: <span id="level">1</span> | Skor: <span id="score">0</span></p>
    <p id="question"></p>
    <input type="number" id="answer" placeholder="Jawabanmu...">
    <br>
    <button onclick="checkAnswer()">Cek Jawaban</button>
    <p id="feedback"></p>
  </div>

  <script>
    let level = 1;
    let score = 0;
    let num1, num2, operator, correctAnswer;

    function generateQuestion() {
      let maxNum = level * 10;
      num1 = Math.floor(Math.random() * maxNum) + 1;
      num2 = Math.floor(Math.random() * maxNum) + 1;
      operator = ['+', '-', '*'][Math.floor(Math.random() * 3)];
      correctAnswer = eval(`${num1}${operator}${num2}`);
      document.getElementById("question").textContent = `${num1} ${operator} ${num2} = ?`;
      document.getElementById("answer").value = "";
      document.getElementById("feedback").textContent = "";
    }

    function checkAnswer() {
      let userAnswer = parseInt(document.getElementById("answer").value);
      let feedback = document.getElementById("feedback");
      
      if (userAnswer === correctAnswer) {
        score += 10;
        feedback.textContent = "Benar! 🎉";
        feedback.style.color = "green";

        if (score % 50 === 0) {
          level++;
          feedback.textContent += ` Naik ke level ${level}! 🚀`;
        }
      } else {
        feedback.textContent = `Salah 😢 (Jawaban benar: ${correctAnswer})`;
        feedback.style.color = "red";
        if (score > 0) score -= 5;
      }

      document.getElementById("score").textContent = score;
      document.getElementById("level").textContent = level;
      setTimeout(generateQuestion, 1000);
    }

    generateQuestion();
  </script>
</body>
</html>

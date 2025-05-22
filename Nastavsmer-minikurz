<!DOCTYPE html>
<html lang="sk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Minikurz: Tvoje ciele</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 700px;
      margin: 40px auto;
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h1, h2 {
      text-align: center;
    }
    .task {
      display: none;
      margin-top: 20px;
    }
    .task.active {
      display: block;
    }
    .task label {
      display: block;
      margin-bottom: 10px;
      font-weight: bold;
    }
    input[type="text"], textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
      resize: vertical;
    }
    button {
      background: #007BFF;
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background: #0056b3;
    }
    .summary {
      white-space: pre-wrap;
      background: #f9f9f9;
      padding: 15px;
      border-radius: 5px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div id="intro" class="task active">
      <h1>🎯 Vitaj v minikurze!</h1>
      <p>Tento kurz ti pomôže nastaviť si ciele a konečne ich splniť. Kurz potrvá približne 1 hodinu. Klikni na „Pokračovať“.</p>
      <button onclick="nextTask()">Pokračovať</button>
    </div>

    <!-- Úlohy 1 až 15 -->
    <div id="task1" class="task">
      <h2>Úloha 1</h2>
      <label for="q1">Napíš 3 veci, ktoré ťa motivujú.</label>
      <textarea id="q1" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task2" class="task">
      <h2>Úloha 2</h2>
      <label for="q2">Aký cieľ si chceš splniť do 3 mesiacov?</label>
      <textarea id="q2" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task3" class="task">
      <h2>Úloha 3</h2>
      <label for="q3">Prečo je tento cieľ pre teba dôležitý?</label>
      <textarea id="q3" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task4" class="task">
      <h2>Úloha 4</h2>
      <label for="q4">Kto ťa môže podporiť?</label>
      <textarea id="q4" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task5" class="task">
      <h2>Úloha 5</h2>
      <label for="q5">Čo ti v tom môže brániť?</label>
      <textarea id="q5" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task6" class="task">
      <h2>Úloha 6</h2>
      <label for="q6">Ako by si prekonal tieto prekážky?</label>
      <textarea id="q6" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task7" class="task">
      <h2>Úloha 7</h2>
      <label for="q7">Rozdeľ cieľ na 3 menšie kroky.</label>
      <textarea id="q7" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task8" class="task">
      <h2>Úloha 8</h2>
      <label for="q8">Urči termín pre každý krok.</label>
      <textarea id="q8" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task9" class="task">
      <h2>Úloha 9</h2>
      <label for="q9">Čo spravíš ako prvé?</label>
      <textarea id="q9" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task10" class="task">
      <h2>Úloha 10</h2>
      <label for="q10">Ako sa odmeníš za pokrok?</label>
      <textarea id="q10" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task11" class="task">
      <h2>Úloha 11</h2>
      <label for="q11">Čo spravíš, keď stratíš motiváciu?</label>
      <textarea id="q11" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task12" class="task">
      <h2>Úloha 12</h2>
      <label for="q12">Ako si budeš merať pokrok?</label>
      <textarea id="q12" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task13" class="task">
      <h2>Úloha 13</h2>
      <label for="q13">Vytvor si pripomienku (notifikáciu, kalendár...)</label>
      <textarea id="q13" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task14" class="task">
      <h2>Úloha 14</h2>
      <label for="q14">Spomeň si na úspech, ktorý si už dosiahol.</label>
      <textarea id="q14" rows="4"></textarea>
      <button onclick="nextTask()">Ďalej</button>
    </div>

    <div id="task15" class="task">
      <h2>Úloha 15</h2>
      <label for="q15">Zhrnutie: Aký je tvoj plán na najbližší týždeň?</label>
      <textarea id="q15" rows="4"></textarea>
      <button onclick="showSummary()">Dokončiť kurz</button>
    </div>

    <div id="summary" class="task">
      <h1>🎉 Gratulujeme!</h1>
      <p>Dokončil si minikurz. Teraz máš plán a prvé kroky k dosiahnutiu svojich cieľov. Ulož si poznámky a začni konať ešte dnes!</p>
      <div class="summary" id="answers"></div>
    </div>
  </div>

  <script>
    let currentTask = 0;
    const totalTasks = 16; // 0 (intro) + 15 tasks

    function nextTask() {
      document.getElementById('task' + currentTask)?.classList.remove('active');
      document.getElementById('intro')?.classList.remove('active');
      currentTask++;
      if (currentTask <= 15) {
        document.getElementById('task' + currentTask).classList.add('active');
      }
    }

    function showSummary() {
      document.getElementById('task15').classList.remove('active');
      document.getElementById('summary').classList.add('active');
      const answersDiv = document.getElementById('answers');
      let summaryText = '';
      for (let i = 1; i <= 15; i++) {
        const answer = document.getElementById('q' + i).value;
        summaryText += `Úloha ${i}:\n${answer}\n\n`;
      }
      answersDiv.textContent = summaryText;
    }
  </script>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>XO Battle Game</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #10172a, #30245c);
    color: white;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

.game {
    width: 100%;
    max-width: 430px;
    text-align: center;
    background: #1d2540;
    padding: 30px 20px;
    border-radius: 25px;
    box-shadow: 0 15px 45px #0008;
}

h1 {
    font-size: 38px;
    color: #ffd166;
    margin-bottom: 10px;
}

.subtitle {
    color: #bdc8e8;
    margin-bottom: 25px;
}

.scoreboard {
    display: flex;
    justify-content: space-around;
    margin-bottom: 25px;
    gap: 10px;
}

.score {
    background: #303b60;
    padding: 12px;
    border-radius: 12px;
    flex: 1;
}

.score strong {
    display: block;
    font-size: 25px;
    margin-top: 5px;
}

.status {
    font-size: 19px;
    margin-bottom: 20px;
    color: #ffd166;
    min-height: 25px;
}

.board {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    margin: auto;
    max-width: 330px;
}

.cell {
    aspect-ratio: 1;
    border: none;
    border-radius: 15px;
    background: #34416b;
    color: white;
    font-size: 55px;
    font-weight: bold;
    cursor: pointer;
    transition: 0.2s;
}

.cell:hover:not(:disabled) {
    background: #465787;
    transform: scale(1.04);
}

.cell:disabled {
    cursor: default;
}

.cell.x {
    color: #55d6ff;
}

.cell.o {
    color: #ff8aab;
}

.cell.winner {
    background: #24865e;
}

.buttons {
    display: flex;
    gap: 10px;
    margin-top: 25px;
}

button.action {
    flex: 1;
    padding: 13px;
    border: none;
    border-radius: 12px;
    background: #ffd166;
    color: #19213a;
    font-weight: bold;
    cursor: pointer;
    font-size: 15px;
}

button.action:hover {
    background: #ffbb35;
}

.footer {
    margin-top: 25px;
    color: #aab5d4;
    font-size: 12px;
}
</style>
</head>

<body>

<div class="game">

    <h1>❌ XO BATTLE ⭕</h1>
    <p class="subtitle">Tic Tac Toe Challenge</p>

    <div class="scoreboard">
        <div class="score">
            Player X
            <strong id="scoreX">0</strong>
        </div>

        <div class="score">
            Draws
            <strong id="draws">0</strong>
        </div>

        <div class="score">
            Player O
            <strong id="scoreO">0</strong>
        </div>
    </div>

    <div class="status" id="status">
        Player X's Turn
    </div>

    <div class="board" id="board">
        <button class="cell"></button>
        <button class="cell"></button>
        <button class="cell"></button>
        <button class="cell"></button>
        <button class="cell"></button>
        <button class="cell"></button>
        <button class="cell"></button>
        <button class="cell"></button>
        <button class="cell"></button>
    </div>

    <div class="buttons">
        <button class="action" onclick="restartGame()">
            🔄 Restart
        </button>

        <button class="action" onclick="resetScores()">
            🏆 Reset Scores
        </button>
    </div>

    <p class="footer">
        XO BATTLE GAME | Created with HTML, CSS & JavaScript
    </p>

</div>

<script>
const cells = document.querySelectorAll(".cell");
const statusText = document.getElementById("status");

let currentPlayer = "X";
let gameActive = true;

let board = ["", "", "", "", "", "", "", "", ""];

let scoreX = 0;
let scoreO = 0;
let draws = 0;

const winningPatterns = [
    [0, 1, 2],
    [3, 4, 5],
    [6, 7, 8],
    [0, 3, 6],
    [1, 4, 7],
    [2, 5, 8],
    [0, 4, 8],
    [2, 4, 6]
];

cells.forEach((cell, index) => {
    cell.addEventListener("click", () => {
        if (board[index] !== "" || !gameActive) {
            return;
        }

        board[index] = currentPlayer;
        cell.textContent = currentPlayer;
        cell.classList.add(currentPlayer.toLowerCase());

        checkWinner();
    });
});

function checkWinner() {

    let winningPattern = null;

    for (let pattern of winningPatterns) {
        const [a, b, c] = pattern;

        if (
            board[a] !== "" &&
            board[a] === board[b] &&
            board[b] === board[c]
        ) {
            winningPattern = pattern;
            break;
        }
    }

    if (winningPattern) {

        gameActive = false;

        winningPattern.forEach(index => {
            cells[index].classList.add("winner");
        });

        statusText.textContent =
            "🎉 Player " + currentPlayer + " Wins!";

        if (currentPlayer === "X") {
            scoreX++;
            document.getElementById("scoreX").textContent = scoreX;
        } else {
            scoreO++;
            document.getElementById("scoreO").textContent = scoreO;
        }

        return;
    }

    if (!board.includes("")) {
        gameActive = false;
        draws++;

        document.getElementById("draws").textContent = draws;
        statusText.textContent = "🤝 It's a Draw!";
        return;
    }

    currentPlayer = currentPlayer === "X" ? "O" : "X";

    statusText.textContent =
        "Player " + currentPlayer + "'s Turn";
}

function restartGame() {

    board = ["", "", "", "", "", "", "", "", ""];

    currentPlayer = "X";
    gameActive = true;

    cells.forEach(cell => {
        cell.textContent = "";
        cell.className = "cell";
    });

    statusText.textContent = "Player X's Turn";
}

function resetScores() {

    scoreX = 0;
    scoreO = 0;
    draws = 0;

    document.getElementById("scoreX").textContent = 0;
    document.getElementById("scoreO").textContent = 0;
    document.getElementById("draws").textContent = 0;

    restartGame();
}
</script>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be My Valentine?</title>
    <style>
        body {
            background-color: #fce4ec;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
        }
        .container {
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border: 4px solid #f06292;
            max-width: 500px;
        }
        .hidden { display: none; }
        h1 { color: #d81b60; }
        .btn {
            padding: 15px 30px;
            margin: 10px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1.1em;
            transition: transform 0.2s;
        }
        #yesBtn { background-color: #4caf50; color: white; }
        #noBtn { background-color: #f44336; color: white; }
        .gift-container { display: flex; gap: 10px; justify-content: center; }
        .gift-card {
            border: 2px solid #f06292;
            padding: 20px;
            border-radius: 10px;
            cursor: pointer;
            background: #fff5f8;
        }
    </style>
</head>
<body>

    <div id="stage1" class="container">
        <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHp1eXF5amR2amN6bmJ6bmJ6bmJ6bmJ6bmJ6bmJ6bmJ6bmJ6JmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCZjdD1z/K676D2yL1jNqE/giphy.gif" width="150">
        <h1>Will you be my Valentine?</h1>
        <button id="yesBtn" class="btn" onclick="nextStage(3)">YES OF COURSE</button>
        <button id="noBtn" class="btn" onclick="nextStage(2)">NO THANK YOU</button>
    </div>

    <div id="stage2" class="container hidden">
        <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHp1eXF5amR2amN6bmJ6bmJ6bmJ6bmJ6bmJ6bmJ6bmJ6bmJ6JmVwPXYxX2ludGVybmFsX2dpZl9ieV9pZCZjdD1z/OPU6wUKARA60X0f9f1/giphy.gif" width="150">
        <h1>Try again please :(</h1>
        <button class="btn" style="background: #f06292; color: white;" onclick="nextStage(1)">Try Again</button>
    </div>

    <div id="stage3" class="container hidden">
        <h1 style="color: #4caf50;">Yay, you said yes!</h1>
        <p>I made these for you babe</p>
        <div class="gift-container">
            <div class="gift-card" onclick="alert('🌸 Here is your Rose Bouquet!')">Gift 1</div>
            <div class="gift-card" onclick="alert('💌 A Letter: You are my world!')">Gift 2</div>
            <div class="gift-card" onclick="alert('🎵 Scan the QR for your song!')">Gift 3</div>
        </div>
    </div>

    <script>
        function nextStage(stageNumber) {
            // Hide all stages
            document.querySelectorAll('.container').forEach(div => div.classList.add('hidden'));
            // Show the selected stage
            document.getElementById('stage' + stageNumber).classList.remove('hidden');
        }
    </script>
</body>
</html>

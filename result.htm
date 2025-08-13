<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Surprise!</title>
    <style>
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #fff;
        }
        #dogImage {
            max-width: 400px;
            animation: bounce 1s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
    </style>
</head>
<body>
    <img id="dogImage" src="1.jpg" alt="Funny Dog" style="display:none;">

    <script>
        window.onload = async function() {
            const img = document.getElementById("dogImage");
            img.style.display = "block";

            // Create AudioContext
            const AudioContext = window.AudioContext || window.webkitAudioContext;
            const audioCtx = new AudioContext();

            // Fetch audio
            const response = await fetch("3.mp3");
            const arrayBuffer = await response.arrayBuffer();
            const audioBuffer = await audioCtx.decodeAudioData(arrayBuffer);

            // Play audio
            const playSound = () => {
                const source = audioCtx.createBufferSource();
                source.buffer = audioBuffer;
                source.loop = true;
                source.connect(audioCtx.destination);
                source.start(0);
            };

            // Some browsers require a user interaction first
            if (audioCtx.state === 'suspended') {
                const resume = () => {
                    audioCtx.resume().then(playSound);
                    document.body.removeEventListener('click', resume);
                };
                document.body.addEventListener('click', resume);
            } else {
                playSound();
            }
        };
    </script>
</body>
</html>



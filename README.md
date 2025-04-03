# Prepare_halloween
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>할로원 의상</title>
    <style>
        body {
            text-align: center;
            font-size: 2rem;
            margin-top: 20%;
        }
    </style>
</head>
<body>
    <p id="message">🔮 올해 당신의 할로윈 의상은... 🔮</p>
    <button onclick="showRandomMessage()">눌러서 확인하기</button>

    <script>
        function showRandomMessage() {
            const messages = [
                "👻 유령",
                "🧛‍♂️ 드라큘라",
                "🧟 좀비",
                "🦇 배트맨",
                "🃏 조커",
                "🏹 헝거게임 캣니스",
                "🏴‍☠️ 캐리비안의 해적 잭 스패로우",
                "❄ 엘사(겨울왕국)",
                "🏰 백설공주",
                "🦸‍♀️ 미라벨(엔칸토)",
                "🏹 메리다(브레이브)",
                "🕷 스파이더맨",
                "💥 아이언맨",
                "⚡ 토르",
                "🦹‍♀️ 할리퀸",
                "🧙‍♂️ 해리포터 마법사",
                "🐉 드래곤",
                "🦄 유니콘",
                "🧝‍♀️ 엘프",
                "☠ 해골."
            ];
            document.getElementById("message").innerText = messages[Math.floor(Math.random() * messages.length)];
        }
    </script>
</body>
</html>

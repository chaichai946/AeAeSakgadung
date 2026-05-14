https://fonts.googleapis.com/css2?family=Kan<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>แอปดูดวง เอ๊ะ-เอ๊ะ จั๊กกะดึ๋ย</title>
    <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Kanit', sans-serif; background-color: #ffeb3b; text-align: center; padding: 20px; }
        .card { background: white; padding: 30px; border-radius: 20px; border: 5px solid #000; box-shadow: 10px 10px 0px #000; }
        h1 { color: #f44336; text-shadow: 2px 2px #ffc107; }
        .btn { background: #4caf50; color: white; padding: 15px 30px; border: none; border-radius: 50px; font-size: 20px; cursor: pointer; border-bottom: 5px solid #2e7d32; }
        .btn:active { transform: translateY(4px); border-bottom: none; }
        #result { margin-top: 20px; font-size: 24px; font-weight: bold; color: #3f51b5; min-height: 50px; }
    </style>
</head>
<body>
    <div class="card">
        <h1>🔮 แอปดูดวง <br> "เอ๊ะ-เอ๊ะ จั๊กกะดึ๋ย"</h1>
        <p>กวนๆ น่ารักๆ โดย ตาชัย (chaichai946)</p>
        <div id="result">ชะตาเจ้าเป็นเช่นไร?</div>
        <br>
        <button class="btn" onclick="randomFortune()">จิ้มเลย เพื่อดูชะตากรรม</button>
        <p style="margin-top:20px; font-size: 12px; color: gray;">
            คำเตือน: อย่าเชื่อ! ถ้าเชื่อให้กลับไปอ่านบรรทัดที่ 1 <br>
            โปรดใช้วิจารณญาณ เพราะคนทำยังไม่เชื่อเลย
        </p>
    </div>

    <script>
        function randomFortune() {
            const fortunes = [
                "วันนี้จะได้ลาภ... ลาภหมู ยืนกินอยู่หน้าปากซอย",
                "เนื้อคู่กำลังเดินทางมา... แต่รถติดอยู่แถวลาดพร้าว อีก 10 ปีเจอกัน",
                "วันนี้โชคดีมาก... ที่ยังหายใจอยู่",
                "ระวังจะได้เงินก้อน... ก้อนกรวดในกระเป๋าเสื้อ",
                "คนรักกำลังคิดถึง... คิดถึงหนี้ที่ติดเขาไว้",
                "วันนี้ทำอะไรก็รุ่ง... รุ่งริ่งนะ ไม่ใช่รุ่งเรือง",
                "สุขภาพแข็งแรง... แค่เดินขึ้นบันไดก็หอบแล้ว"
            ];
            const random = fortunes[Math.floor(Math.random() * fortunes.length)];
            document.getElementById('result').innerHTML = random;
        }
    </script>
</body>
</html>
it:wght@300;600&display=swap



<!DOCTYPE html>
<html lang="om">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MMA Dandii Video Conference</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: #87CEEB; /* Aqua Blue */
            color: white;
            text-align: center;
            padding: 15px 0;
        }
        .container {
            display: flex;
            flex: 1;
        }
        .clock {
            flex: 1;
            background-color: #e9f7fc;
            padding: 20px;
            border-right: 2px solid #87CEEB;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            text-align: center;
        }
        .main-content {
            flex: 3;
            text-align: center;
            padding: 20px;
        }
        .sidebar {
            flex: 1.5;
            background-color: #e9f7fc;
            padding: 20px;
            border-left: 2px solid #87CEEB;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .logo {
            margin: 20px auto 10px;
            width: 150px;
        }
        h3 {
            margin: 10px 0 20px;
            color: #333;
        }
        a {
            text-decoration: none;
            display: inline-block;
            background-color: #87CEEB;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 16px;
            width: 300px;
            text-align: center;
            transition: background-color 0.3s ease;
        }
        a:hover {
            background-color: #87CEEB;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #87CEEB;
            font-size: 14px;
            color: #777;
            margin-top: auto;
            border-top: 1px solid #ccc;
        }
        .calendar iframe {
            width: 100%;
            height: 400px;
            border: none;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h2>Mana Murtii Aanaa Dandii</h2>
    </header>

    <!-- Main Layout -->
    <div class="container">

        <!-- Clock Section -->
        <div class="clock">
            <h2>Yeroo</h2>
            <p id="time"></p>
        </div>

        <!-- Main Content Section -->
        <div class="main-content">
            <Marquee>Mana Murtii Aanaa Dandii</marquee>

            <h3>Viidiyoo Konfiransii Dhaddacha Hariiroo Hawaasa Jalqabuf Dhaddacha Armaan Gadii Cuqaasaa!</h3>

            <p><a href="https://meet.google.com/rua-wvoy-muq" target="_blank">Dhaddacha 1ffaa - Haariroo Hawaasaa</a></p>
            <p><a href="https://meet.google.com/miw-jahm-oqf" target="_blank">Dhaddacha 2ffaa - Haariroo Hawaasaa</a></p>
            <p><a href="https://meet.google.com/awe-nuhe-nyt" target="_blank">Dhaddacha 3ffaa - Haariroo Hawaasaa</a></p>
            <p><a href="https://meet.google.com/fgv-vxeg-mdb " target="_blank">Dhaddacha 4ffaa - Haariroo Hawaasaa</a></p>
            <p><a href="https://meet.google.com/xgn-vrug-znx" target="_blank">Dhaddacha 5ffaa - Haariroo Hawaasaa</a></p>
            <h4>Viidiyoo Konfiransii Dhaddacha Maatii Jalqabuf Dhaddacha Armaan Gadii Cuqaasaa!</h4>
            <p><a href="https://meet.google.com/wwa-wbxy-qrv " target="_blank">Dhaddacha Maatii </a></p>
            <h4>Viidiyoo Konfiransii Dhaddacha Yakkaa Jalqabuf Dhaddacha Armaan Gadii Cuqaasaa!</h4>     
            <p><a href="https://meet.google.com/mgy-vjyn-jzd " target="_blank">Dhaddacha 1ffaa - Yakkaa </a></P>
            <p><a href="" target="_blank">Dhaddacha 2ffaa - Yakkaa</a></p>
           </div>

        <!-- Sidebar with Online Calendar -->
        <div class="sidebar">
            <div class="calendar">
                <iframe src="https://calendar.google.com/calendar/embed?src=en.ethiopian%23holiday%40group.v.calendar.google.com&ctz=Africa%2FAddis_Ababa"></iframe>
            </div>
        </div>

    </div>

    <!-- Footer Section -->
    <footer>
       <Marquee>Mana Murtii Ol'aanaa Godina Shawaa Lixaa</Marquee>
    </footer>

    <script>
        function updateClock() {
            const now = new Date();
            const timeString = now.toLocaleTimeString('en-US', {
                hour12: true, // 12-hour format
                hour: '2-digit',
                minute: '2-digit',
                second: '2-digit',
            });
            document.getElementById('time').innerText = timeString;
        }

        updateClock();
        setInterval(updateClock, 1000);
    </script>


</body>
</html>

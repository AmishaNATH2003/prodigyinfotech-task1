# prodigyinfotech-task1
task-1 create responsive website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WdTASK1</title>
    <link rel="stylesheet" href="task1.css">
    <link rel="stylesheet" href="responsiveness.css">
</head>
<body>
    <header>
        <nav>
            <img src="StudyBuddy.jpg" alt="">
            <p class="nav_text">StudyBuddy</p>
            <i class="fa-solid fa-bars" id="bars" onclick=showmenu()></i>
            <div class="nav-links" id="navlinks">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Feture</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Feture</a></li>
                    <li><a href="#">About Us</a></li>
                </ul>
            </div>
            <i class="fa-solid fa-circle-xmark" id="cross" onclick=hidemenu()></i>
        </nav>
    </header>    

    <div id="filter"></div>
    <img src="Blockchain.jpg" alt="" id="banner">
    <div id="text">
        <h1>Blockchain</h1>
        <p>A system in which a record of transactions, especially those made in a cryptocurrency, is maintained across computers that are linked in a peer-to-peer network.</p>
        <button type="button">Click to Learn</button>
    </div>


    <script src="logics.js"></script>
</body>
</html>

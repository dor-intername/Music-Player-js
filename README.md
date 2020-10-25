# Music-Player-js
Music player built with javascript
<!DOCTYPE html>

<html>

    <head>

        <link rel="stylesheet" type="text/css" href="style.css">
        <script src="jquery.js"></script>
        <script src="script.js"></script>

        <title>Music Player</title>

    </head>

    <body>

        <div class="player-container">

            <div id="audio-img">

                <img class="cover" width="330px" height="200px">
            </div>
            <div id="audio-player">
                <div id="audio-info">
                    <span class="artist"></span> - <span class="title"></span>
                </div>
            </div>


            <input id="volum" type="range" min="0" max="10" value="5">

            <br>

            <div id="buttons">

                <button id="prev"></button>
                <button id="play"></button>
                <button id="pause"></button>
                <button id="stop"></button>
                <button id="next"></button>
            </div>

            <div class="clearfix"></div>

            <div id="tracker">
                <div id="progressbar">
                    <span id="progress"></span>
                </div>
                <span id="duration"></span>
            </div>
            <div class="clearfix"></div>

            <ul id="playlist">

                <li song= "Dua Lipa - Break My Heart.mp3" cover= "cover1.png" artist="Dua Lipa">Break My Heart</li>
                <li song= "Dua Lipa - Don't Start Now.mp3" cover= "cover4.jpg" artist="Dua Lipa">Don't Start Now</li>
                <li song= "The Weeknd - Blinding Lights.mp3" cover= "cover2.png" artist="The Weekend">Blinding Lights</li>
                <li song= "Years Around The Sun - Miles Away.mp3" cover= "cover3.jpg" artist="Years Around The Sun">Miles Away</li>
            </ul>

        <!--    <div class="buttons">

                <img src="pre-left.png" alt="" height="70px" width="70px">
                <img src="play.png" alt="" height="70px" width="70px">
                <img src="pre-right.png" alt="" height="70px" width="70px">
            </div>-->
        </div>

            

    </body>
</html>

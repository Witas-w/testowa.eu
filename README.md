#testowa.pl

        
<html>
    <head>
        <meta charset="utf-8">
        <title>testowa.pl</title>
        <style>
      
        body{
            background-color: rgb(26, 140, 66);
            color: white;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
       .site-nav-trigger{
          border: 0;
          border-radius: 5px ;
          
       }
       .site-menu{
           display: flex;
           box-sizing: border-box;
           position:absolute;
           top: 20px;
           right: 0;
           height:100%;
           width: 300px;
           background: #34b399;
           z-index: 3;
           transform: translateX(100%);
           transition: 0.3s transform ease-in-out;
       }
       .site-menu ul{
           padding: 0;
           list-style-type: none;
           margin:0 10px;
           display: flex;
           flex-wrap: wrap;
           align-content: flex-start;
           
       }
       .site-menu li{
           background: #ffffff;
           margin-top: 20px;
           color: black;
           border-radius: 5px;
           flex-basis: 100%;
           
       }
       .site-menu a{
           display: flex;
           padding: 10px;
           box-sizing: border-box;
           text-decoration: none;
           align-items: center;
           height: 100%;
           width: 100%;
           border-radius: 5px;
       }
       .site-menu a:hoover {
           color: white;
           background: red;
       }
       .site-menu-trigger:focus~.site-menu{
           transform: translateX(0);
       }
       
        .a {
           color: green; 
        }   
        h4 {
            
            font-size: 19px;
            float: left;
            margin-top: -1px;
            color: white;
        }
        nav {
         
          height: 20px;
          width: 100%;
          justify-content: flex-end;
          align-items:center;
          padding: 10px;
          box-sizing: border-box;
            display: flex;
        }
        
        a{
            color:black;
              text-decoration: none;
        }
        #i{
          float: left;
          margin-left: -100px;
          margin-top: 43px;
          z-index: 1;
          position: fixed;
        right: 295px;
        }
        #o{
            margin-left: 320px;
            margin-top: 39px;
            z-index: 2;
            position: absolute;
        }
        p{
            position: relativ;
            margin-top: 95px;
            margin-left: 287PX;
            margin-bottom: 25px;
            z-index: 2;
             width: 279px;
        }
        #pading{
            left: -92px;
            color: black;
            background-color: white;
            text-align: center;
            position: relative;
            z-index: 3;
        }
        ul {
            list-style-type: none;
            
        }
       
        </style>
    </head>
    <body>
    <h4><span class="a">Autor:</span> Jakub <br>
        Witkowski
    </h4>
 <nav classs="site-nav">
 <button class="site-nav-trigger">Menu</button>
 <div class="site-menu">
 <ul>

    <li> <a href="https://pl.wikipedia.org/wiki/Wikipedia:Strona_g%C5%82%C3%B3wna">Główna</a></li>
    <li> <a href="https://pl.wikipedia.org/wiki/Wikipedia:Strona_g%C5%82%C3%B3wna">O mnie</a></li>
   <li> <a href="https://pl.wikipedia.org/wiki/Wikipedia:Strona_g%C5%82%C3%B3wna">Blog</a></li>
     </ul>
     </div>
 </nav>
 
 <img id="i"src="https://www.kasandbox.org/programming-images/seasonal/xmas-scene-holly-border.png" width="286px">
 
 <h2 id="o">O Wrocławiu</h2>
 <p>Wrocławskie krasnale zjawisko społeczne obejmujące swoim zasięgiem Wrocław i okoliczne gminy, a wywierające wpływ na działania artystyczne realizowane w całej Polsce.

Niewielkie rzeźby krasnali, w liczbie stale rosnącej, są umieszczane we Wrocławiu sukcesywnie od 2005. Wywodzą się od malowanych w latach 80. XX wieku graffiti, a następnie happeningów organizowanych przez ruch „Pomarańczowej Alternatywy” ośmieszających w sposób pokojowy system komunistyczny. Po upadku PRL-u krasnale
uległy zapomnieniu aż do sierpnia 2005, kiedy to wrocławski rzeźbiarz Tomasz Moczek ustawił pięć pierwszych krasnali.

Figurki krasnali stały się integralną częścią przestrzeni miejskiej oraz zjawiskiem społecznym. Nowe postacie tworzone są przez artystów z całej Polski, a ich opiekunami są instytucje publiczne, firmy oraz osoby prywatne. Organizowane są specjalne wycieczki szlakiem krasnali, gry plenerowe, spektakle teatralne oraz wydawane mapy dla turystów chcących połączyć odnajdywanie kolejnych figurek ze zwiedzaniem Wrocławia.

Ponadto kopie krasnala Życzliwka stoją w Dreźnie, Reykjaviku, Wilnie, Guadadalajarze, Hradec Kralove i Lwowie, a w Waszyngtonie stoi krasnal Kościuszko.<br>
Źródło:<a href="https://pl.wikipedia.org/wiki/Wikipedia:Strona_g%C5%82%C3%B3wna">wikipedia</a>
</p>
 <p id="pading">Copyright by Jakub W</p>
 
 
    </body>
</html>

          

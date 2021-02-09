<!DOCTYPE html>
 <html> 
  <head> 
    <title>HTML-Aufbau</title> 
       <meta charset="UTF-8"/> 
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css"
            integrity="sha384mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWA"
      crossorigin="anonymous"
    />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    
    />
    <link rel="stylesheet" href="./assets/styles/main.css" />
        <meta  name = " description " content = "HTML-Aufbau " > 
        <meta  name = "keywords" content= "HTML, CSS, Web Entwicklung" > 
        <meta  name ="author" content ="Veronica" > 
                    <! - Basis-URL https://www.30daysofreact.com -> 
        <base href ="https://www.veronica0638"><target = "_blank"/>
                    <!-- Geht zur Taskleiste des Browsers --> 
    <title> 30 Tage HTML </title> <! - um externes CSS zu mögen ->

    <link rel= 'stylesheet' href= "" />
      <! - Inline-Styling ist sehr umfangreich. Wir können auch den internen Stil verwenden. 
            Wir können den Tag-Namen, die ID oder die Klasse verwenden, um ein Element auszuwählen. 
            ID ist eindeutig und Klasse ist für eine einzelne oder eine Gruppe von Elementen-->

     <!--Wenn wir nach ID auswählen, verwenden wir # gefolgt vom ID-Namen und wenn wir nach Klassennamen auswählen, verwenden wir. gefolgt von einem Klassennamen.-->
      
    <!----------------------------------------------------------------------------------------------------------------------------------------------
      title {
  color: rgb(221, 204, 204);
}

#menu {
  background: rgb(194, 199, 194);
}

#menu li {
  list-style: none;
  margin: 15px;
  display: inline-block;
}

a {
  color: white;
  text-decoration: none;
}
/* .section {
      } */

.section {
  margin: 50px;
  padding: 30px;
  border-radius: 5px;
}

#section-1 {
  background-color: rgb(177, 231, 177);
}

#section-2 {
  background-color: rgb(108, 238, 238);
}

#section-3 {
  background-color: rgb(97, 82, 163);
}

#section-4 {
  background-color: rgb(243, 195, 91);
}

/* CSS for Projects */

.box {
  width: 200px;
  height: 200px;
  display: inline-block;
  margin-bottom: 30px;
  margin-right: 25px;
  border-radius: 50%;
  text-align: center;
  line-height: 200px;
  font-size: 42px;
}

#box-1 {
  background-color: rgb(116, 226, 116);
}

#box-2 {
  background-color: yellow;
}

#box-3 {
  background-color: rgb(231, 118, 118);
}

#boxes {
  text-align: center;
}

#videos {
  text-align: center;
}

hr {
  height: 3px;
  background-color: gray;
}

/* icons style */

i {
  font-size: 32px;
  margin: 30px;
}

.fa-github-square {
  color:#333;
}

.fa-linkedin{
  color:#0077b5;
}

.fa-twitter-square{
  color:#1da1f2;
}
      
      ------------------------------------------------------------------------------------------------------------------------------------------>
      
      <style>
      .letter
                { 
        <font-size: 68px;    
        }
          
       #letter-h {
            color: #e34c26;
       } 
          
       #letter-t {
            color: #264de4;
       }
          
      #letter-m {
            color: #f0db4f;
       }
          
      #letter-l {
            color: #61dbfb;
       }
          
    </style> 
     <!-- Mit dem Skript-Tag JS-Code schreiben --> 
     <script> 
       -Konsole.log ( 'Welcome to JavaScript' ) 
    </script> 
      
  </head>
  <body> 
    <header> 
    <span  style="color: #e34c26";.letter> H </span> 
      <span  style="color: #264de4";.letter> T </span> 
      <span  style="color: #f0db4f";.letter> M </span> 
      <span  style="color: #61dbfb";.letter> L </span>
        
        <span class= "letter" id='letter-h'> </span> 
        <span class= "letter" id='letter-T'> </span> 
        <span class= "letter" id='letter-m'> </span> 
        <span class= "letter" id='letter-l'> </span > 
    </header> 
    <main> 
      <section> 
         
          <h1 id= "first-title" style= "color: saddlebrown; font-size: 90px; background:blue;">Die Bausteine ​​des Webs</h1>
          
        <p>Es gibt keine Website ohne HTML. Lernen Sie HTML und erstellen Sie Websites und Web Applikationen</p><br>
      </section> 
        <p> 
        <h2> Frontend Technologis </h2> 
            <ul> 
                <li> HTML </li> 
                <li> CSS </li> 
                <li>JavaScript</li> 
          </ul> 
        
        <p>Zehn am dichtesten bevölkerten Länder<p> 
        
        <ul>
            <ol> 
                
                <li>China</li>
                <li>Indien</li>
                <li>USA</li> 
                <li>Indonesien</li>
                <li>Brasil</li>
                <li>Pakistan</li>
                <li>Nigeria</li>
                <li>Bangladesch</li>
                <li>Russland</li> 
                <li>Japan</li>
                

            </ol> 
        </ul>
        
            <img src=' ./assets/images/html.png' alt=' HTML-Logo'><br>
            <img src=' ./assets/images/css_logo.png' alt='CSS Logo'><br>
            <img src=' ./assets/images/js_logo.png' alt='JS Logo'><br>
           
        
        <section><br>
        <nav>
          
          <Audio-Steuerelemente><br>
              <ul>                                                          
                  <Quelle><br>
             <h1><b>    bold Text</b></h1><br>
-            <h2><strong>WICHTIG</strong></h2><br>
-            <h3><i>    italic Text</i></h3><br>
-            <h4><em>   emphasized Text "Betonen Sie den Text!"</em></h4><br>
-            <mark>     Markierter Text</mark><br>
-            <small>     kleinerer Text</small><br>
-            <del> -    Gelöschter Text-</del><br>
-            <ins> -    Eingefügter Text-</ins><br>
-            <sub> -    Indexierter Text</sub><br>
-            <sup> -    Hochgestellter Text</sup><br>
-            <h5><pre>--Textraum beibehalten--</pre></h5><br>
             <h6><u>   underlined</u></h6><br>                                 
                                                                   
              </ul>
          </nav>
             </section>  
          <Quelle>
              
              
      <br>   
              
              <br>
                 
      <p><video src="www./assets/video/js-project.mp3"></video></p><br>
                                                       
              <button onclick="alert('Wilcome to 30 Days Of HTML')"> Klicken Sie hier </button><br></Quelle>
                                                              
            </ul>
            </nav> 
        
            <!-- Ein Tag verwendet das href-Attribut, um auf eine Linkressource abzuzielen --> 
                                                              
                    <section>                                          
               <ul>                                               
            <li><a href="https://www.federlesung.org/">WEB</a></li> 
            <li><a href= "https://twitter.com"></a></li> 
            <li><a href="https://github.com/vironica0638">GitHub</a><li>
             <li><a href= "https://twitter.com/">Twitter</a></li>    
             </ul>
            </section>  
                                                         
        
                                                    
    <footer> 
      <small> Copyright 2021 | Veronica </small> 
    </footer> 
  </body> 
</html>

<head>
        <title>MY FIRST JAVASCRIPT PROGRAM</title>
    <style>
        body{
            background-image: url(https://clipart-library.com/images/8TA6zo79c.jpg);
            text-align: center;
          
        }
        h2{
            font-size: xx-large;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            font-style: inherit;
            font-weight: 100;
            text-shadow: 2px 2px rgb(232, 100, 236);
            text-align: center;
            text-decoration: overline underline;
            font-size-adjust: inherit;
            font-style: italic;
           
        }
        p{
            font-size: x-large;
            margin: 50px;
            text-align: center ;
            border: solid;
            border-color: rgb(196, 86, 168);
            
        }
        #answer {
            font-size: xx-large;
            font-style: italic;
            margin-top: 30px;
        }
       

        
       
        
            
    </style>    
    <body>
        <h2>What Can JavaScript Do?</h2>
        <p id="demo">-JavaScript can change HTML content.</p>
        <h2 id="question">Is the sky blue?</h2>
        <button onclick="checkStatus('YES')">YES</button>
        <button onclick="checkStatus('NO')">NO</button>
        <div id="answer"></div>
        <script>
            // Javascipt code
            function checkStatus(status) {
                var answerElement = document.getElementById("answer");
                if (status === "YES") {
                    answerElement.textContent = "pano mo nasabi?";
                    answerElement.style.color = "green"
                } else if (status === "NO") {
                    answerElement.textContent = "wag kanang magpaliwanag!";
                    answerElement.style.color = "green"
                }
            }
        </script>
    </body>
   

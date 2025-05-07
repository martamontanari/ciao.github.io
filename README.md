# ciao.github.io
<html>
    <head>
        <script>
            function saluta(){
                nome = document.getElementById("nome");
                alert("ciao " + nome.value)
            }

        </script>

    </head>
    <body>
        <h1>HELLO WORLD</h1>
        nome: <input type = "text" value = "" id = "nome"/>
        <input type = "button" value = "saluta" onclick = "saluta()"/>
    </body>
</html>

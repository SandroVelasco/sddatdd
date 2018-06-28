<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
    $("#baixo").click(function(){
        $("#2").insertAfter("#1");
    });
    
    $("#cima").click(function(){
    	$("#2").insertBefore("#1");
    });
});

</script>
</head>
<body>

<button id="baixo" onclick="baixo()">Baixo</button>
<button id="cima" onclick="cima()">Cima</button>

<br><br>
<p id = "1">This is a paragraph.</p>
<p id = "2">This is another paragraph.</p>

</body>
</html>

Source: https://www.w3schools.com/jquery/html_insertbefore.asp

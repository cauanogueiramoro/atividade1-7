# atividade1-7
1-7
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Document</title>

</head>

<body>

    <script>
        function mult() {
            //window.alert("teste")
            var var1 = document.getElementById("val1");
            var var2 = document.getElementById("val2");
            //window.alert(var1.value + " " + var2.value)
            document.getElementById("resultado").innerText = var1.value * var2.value;
        }
    </script>

    <script>
        function cubo() {
            //window.alert("teste")
            var var1 = document.getElementById("val_x");
            //window.alert(var1.value + " " + var2.value)
            document.getElementById("res_cubo").innerText = var1.value * var1.value * var1.value
        }
    </script>

    <script>
        function celcios() {
            //window.alert("teste")
        
            var var1 = document.getElementById("celcios").value;
            document.getElementById("re_cel").innerText =  (var1 - 32) * 5/9;
            //window.alert(var1.value + " " + var2.value)

        }
    </script>

    <script>
        function triangulo() {
            //window.alert("teste")
            var var1 = document.getElementById("val10").value;
            var var2 = document.getElementById("val20").value;
            //window.alert(var1.value + " " + var2.value)
            document.getElementById("triangulo").innerText = var1 * var2 /2;
        }
    </script>

<script>
    function circulo() {
        //window.alert("teste")
        var raio = document.getElementById("raio").value;

        //window.alert(var1.value + " " + var2.value)
        document.getElementById("circulo").innerText = raio * raio * 3.14159 ;
    }
</script>

<script>
    function  desconto() {
        //window.alert("teste")
        var var1 = document.getElementById("val100").value;
        
        //window.alert(var1.value + " " + var2.value)
        document.getElementById("desconto").innerText = var1 * 0.05 ;
    }
</script>



    <script>
        function escreve6() {
            //window.alert("teste")
            var var1 = document.getElementById("val1");
            var var2 = document.getElementById("val2");
            //window.alert(var1.value + " " + var2.value)
            document.getElementById("resultado").innerText = var1.value + " " + var2.value;
        }
    </script>

    <script>
        function escreve7() {
            //window.alert("teste")
            var var1 = document.getElementById("val1");
            var var2 = document.getElementById("val2");
            //window.alert(var1.value + " " + var2.value)
            document.getElementById("resultado").innerText = var1.value + " " + var2.value;
        }

    </script>
    <div><h1>Multiplicação</h1>
        <input id="val1" value="1">
        <input id="val2" value="2">
        <button onclick="mult()">Multiplicação</button>
        <p id="resultado">XXXX</p>
    </div>
    <div><h1>Cubo</h1>
        <input id="val_x" value="1">        
        <button onclick="cubo()">Cubo de um número</button>
        <p id="res_cubo">XXXX</p>
    </div>

    <div><h1>celcios</h1>
        <input id="celcios" value="32">        
        <button onclick="celcios()">celcios</button>
        <p id="re_cel">XXXX</p>
    </div>

    <div><h1>triangulo</h1>
        <input id="val10" value="10">   
        <input id="val20" value="10">       
        <button onclick="triangulo()">area do triangulo</button>
        <p id="triangulo">XXXX</p>
    </div>

    <div><h1>circulo</h1>
        <input id="raio" value="10">   
           
        <button onclick="circulo()">area do circulo</button>
        <p id="circulo">XXXX</p>
    </div>

    <div><h1>5% de desconto</h1>
        <input id="val100" value="0">   
               
        <button onclick="desconto()">5% de desconto</button>
        <p id="desconto">XXXX</p>
    </div>

    <!-- <input id="val1" value="1">
    <input id="val2" value="2">
    <button onclick="escreve1()">Escrever</button>
    <button onclick="escreve2()">Escrever</button>
    <button onclick="escreve3()">Escrever</button>
    <button onclick="escreve4()">Escrever</button>
    <button onclick="escreve5()">Escrever</button>
    <button onclick="escreve6()">Escrever</button>
    <button onclick="escreve7()">Escrever</button>
    <p id="resultado">XXXX</p> -->


</body>


</html>

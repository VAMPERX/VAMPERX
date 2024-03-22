Olá a todos meu nome é VAMPEX eu sou um estudande de programação é eu estou quase arrancando os cabelos por conta desse código desgraçado, eu sou novato em programação comecei
esse mês e queria pedir ajuda de vocês para resolver esse código aqui de baixo!

A ideia era fazer um confirmação através do botão confirma para ele dizer se a pessoa poderia ou não viajar determinando de qual país ela venho, se ela fosse do brasil ia parecer
que a pessoa podia viajar mais caso fosse estrangeira ela teria o passaporte negado!

me ajudem por favor!


<body>
  
    <h1>Qual séria o seu país de origem?</h1>
    Digite apenas o país: <input type="texto" name="txn" id="txn"/>
    <input type="button" value="Confirma" onclick="updateButton()"/>
    <div id="res">
        <script>
            function updateButton() {
            var txn = window.document.querySelector('txn')
            var res =  window.document.getElementById('res')
            var n1 = Object(txn.value)
            if (txn.value === "Confirma") {
             txn.value = "Confirma";
             res.innerText = "Passaporte ATIVO você está liberada para passar!";
           } else {
            txn.value != "Confirma";
            res.innerText = "Passaporte NEGADO você está proibido de viajar!";
           }
            
        }
         </script>

</body>

<!---
VAMPERX/VAMPERX is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

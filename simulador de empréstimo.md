![image](https://github.com/anafabi1984/meurepositorio/assets/138622444/ee6aba18-8bb1-45a8-b6e8-7fffc8f4f87d)


<!DOCTYPE html>

<html lang="pt-br">

<head>

    <title>FSP Financeira</title>

    <meta charset="utf-8" />

    <meta name="viewport" content="width=device-width, initial-scale=1">

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.mim.js"></script>

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>

    <style type="text/css">

    .jumbotron{background:#b3b3ff; border-radius: 10px; text-align: center;}
    .container {background: #e6e6ff; padding: 10px 50px 150px 50px;}
    .rodape{text-align:center; margin: 0 auto;}
    
    </style>
</head>

    <script type="text/javascript">

        function simular(){
            
        var valemprest = 0;

        var valemprest=document.getElementById('valemprest').value;

        var qtdeparcela=document.getElementById('qtdeparcela').value;

            while( valemprest==0 || qtdeparcela==0 ||valemprest < 100 ){

                if (valemprest == 0){

                    alert("O valor do empréstimo deve ser diferente de zero !!!")

                }

                if (qtdeparcela == 0){

                alert(" A quantidade de parcelas deve ser diferente de zero  !!!")
                }

                if (valemprest < 100){

                alert("O valor do empréstimo DEVE ser a partir de R$ 100,00 !!!")

                }  
                else if (valemprest<100 && qtdeparcela==0){
                
                alert("O valor do empréstimo DEVE ser a partir de R$ 100,00 !!!")
              
                }
            
                    

                document.getElementById('btn-simular').addEventListener('click', simular);

            }

            var valorTotal = valemprest * 1.04;

            var valparcela = valorTotal / qtdeparcela;

            alert("Valor Total do empréstimo: R$ " + valorTotal.toFixed(2));

            alert("Valor da Parcela: R$ " + valparcela.toFixed(2));

            alert("OBRIGADO por escolher a FSP Financeira !!!");

            }

    </script>

</head>

<body>

    <div class="container-fluid">

    <div class="jumbotron">

    <h1>FSP Financeira</h1><br><br>

    <p><b>Simule seu empréstimo!</b></p>

    </div>

    <div class="row">

    <div class="col-sm-4">

    <p>Valor do empréstimo:</p>

    <input id="valemprest" type="text" class="form-control" />
    
    </div>
    
    <div class="col-sm-4">

    <p>Quantidade de parcelas:</p>

    <input id="qtdeparcela" type="text" class="form-control" />

</div>
</div>
   <br>
   <br>
   
    <div class="row">
      <div class="col-sm-12">
        <div class="rodape">
      
    <button type="button"  class="btn btn-lg btn-primary"  onclick="simular() ">Simular</button>

    <br><br><br><br><br><br><br><p> Contato (61)3000-0000
    </div>
       
    </div>

    </div>

    </div>
    </div>

</body>

</body>

</html>



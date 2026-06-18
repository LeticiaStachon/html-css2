CÓDIGO NO CODE PARA FAZER COR DE FUNDO DEGRADE 



<style>

&nbsp;       body { 

&nbsp;           background-image: linear-gradient(to right, white, blue);

&nbsp;       }

&nbsp;   </style>





-----------------------------------------------------------------------------------------







SE QUISER PARA ESQUERDA = 



<style>

&nbsp;       body { 

&nbsp;           background-image: linear-gradient(to left, white, blue);

&nbsp;       }

&nbsp;   </style>







-------------------------------------------------------------------------------------------







SE QUISER PRA CIMA =





<style>

&nbsp;       body { 

&nbsp;           background-image: linear-gradient(to top, white, blue);

&nbsp;       }

&nbsp;   </style>





Nesse caso fica meio feio, então você tem que fazer uma configuração global CSS, configurar a altura. 



<!DOCTYPE html>

<html lang="pt-br">

<head>

&nbsp;   <meta charset="UTF-8">

&nbsp;   <meta name="viewport" content="width=device-width, initial-scale=1.0">

&nbsp;   <title>Gradiente em CSS</title>

&nbsp;   <style>

&nbsp;       \* **{**

            **height: 100%;**

            **}**

&nbsp;       body { 

&nbsp;           background-image: linear-gradient(to right, white, blue);

&nbsp;       }

&nbsp;   </style>

</head>

<body>

&nbsp;   <h1>Testando Gradiente</h1>

&nbsp;   

</body>

</html>







----------------------------------------------------------------------------------------------



SE QUISER PRA BAIXO 



<style>
       body { 
           background-image: linear-gradient(to bottom, white, blue);
    }


</style>







---------------------------------------------------------------------------------------



DE LADO 



&nbsp;background-image: linear-gradient(45deg, #3198E2, #6D59C0, #B93590, #E33F5F, #FDD579);

&nbsp;           background-attachment: fixed;



MUDAR A COR DE LADO 



 background-image: linear-gradient(-45deg, #3198E2, #6D59C0, #B93590, #E33F5F, #FDD579);

            background-attachment: fixed;



NESSES DOIS CASOS SERIA O ANGULO





--------------------------------------------------------------------------------------------



CIRCULOS 



&nbsp;background-image: radial-gradient(circle, #3198E2, #6D59C0, #B93590, #E33F5F, #FDD579);

&nbsp;           background-attachment: fixed;



---------------------------------------------------------------------------------------



PORCENTAGEM QUE VOCÊ QUER QUE A COR FIQUE NA TELA 



background-image: linear-gradient(to right, #3198E2 1%, #6D59C0 2%, #B93590, #E33F5F, #FDD579);

&nbsp;          







EXEMPLO COM O CÓDIGO COMPLETO - 



<!DOCTYPE html>

<html lang="pt-br">

<head>

&nbsp;   <meta charset="UTF-8">

&nbsp;   <meta name="viewport" content="width=device-width, initial-scale=1.0">

&nbsp;   <title>Gradiente em CSS</title>

&nbsp;   <style>

&nbsp;       body { 

&nbsp;           background-image: linear-gradient(to right, white, blue);

&nbsp;       }

&nbsp;   </style>

</head>

<body>

&nbsp;   <h1>Testando Gradiente</h1>

&nbsp;   

</body>

</html>





------------------------------------------------------------------------------------

PARA FIXAR 





&nbsp;background-attachment: fixed;






<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsividade</title>
    <style>
        body {
            background-color: gray;
            
        }
        main {
            background-color: white;
            min-width: 280px;
            margin: auto;
            padding: 20px;
            border-radius: 10px;
            max-width: 800px;             
        }
      img {
            max-width: 100%;
            
        }
    </style>
</head>
<body>
    <main>
        <h1>Responsividade</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur debitis numquam obcaecati hic accusamus vitae sequi qui, culpa autem ex vel! Hic eaque, perferendis aspernatur distinctio voluptatum accusamus debitis dignissimos..</p>
        <picture>
            <source media="(max-width: 600px)" srcset="irina-blok-peq.jpg">
            <img src="imagens/irina-blok.jpg" alt="Imagem de Irina Blok" title="Responsividade">
        </picture>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur debitis numquam obcaecati hic accusamus vitae sequi qui, culpa autem ex vel! Hic eaque, perferendis aspernatur distinctio voluptatum accusamus debitis dignissimos..</p>
    </main>
</body>
</html>

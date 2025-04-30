<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário</title>
    
</head>
<body>
    <form action="http://10.111.211.110:8088/aula8_Exercicio.php"    method="post">
        <input type="hidden" name="prontuario" value="seu prontuario">

        <label for="nome"> <strong>Nome:</strong></label><br>
        <input type="text" name="nome_completo" placeholder="Escreva seu nome" required><br><br>

        <label for="tel"><strong>Celular:</strong></label><br>
        <input type="tel" name="celular" placeholder="(00) 00000-0000" required><br><br>

        <label for="email"><strong>E-mail:</strong></label><br>
        <input type="email" name="e-mail" placeholder="Seu@email.com" required><br><br>

        <label for="idade"><strong>Idade:</strong></label><br>
        <input type="number" name="idade" placeholder="18 " min="18" step="1" required><br><br>

        <label for="investimentos"><strong>Investimento:</strong></label><br>
        <input type="range" name="investimento" min="0" step="10" max="1000" value="0" required><br><br>

        <label for="nascimento"><strong>Data de nascimento:</strong></label><br>
        <input type="date" name="nascimento" max="2007-04-28" required><br><br>

        <label for="preferencia"><strong>Agendamento de reunião:</strong></label><br>
        <input type="datetime-local" name="preferencia" required><br><br>

        <label for="linkedin"><strong>Linkedin:</strong></label><br>
        <input type="url" name="linkedin" placeholder="https://https://br.linkedin.com"><br><br>

        <label for="cor_preferida"><strong>Cor preferida:</strong></label><br>
        <input type="color" name="cor_preferida" ><br><br>

        <label for="formacão"><strong>Formação:</strong></label><br><br>
        <input type="radio" required id="fundament" name="formacao" value="fundamental" checked>
        <label for="">Fundamental</label><br>

        <input type="radio" id="med" name="formacao" value="medio" checked>
        <label for="">Médio</label><br>

        <input type="radio" id="sup_ico" name="formacao" value="superior_icon" checked>
        <label for="">Superior incompleto</label><br>

        <input type="radio" id="sup_com" name="formacao" value="superior_com" checked>
        <label for="">Superior completo</label><br>

        <input type="radio" id="fundamental" name="formacao" value="pos" checked>
        <label for="">Pós-graduação </label><br><br>

        <input type="submit" value="Enviar" > <input type="reset" value="Limpar">
    </form> 

</body>
</html>

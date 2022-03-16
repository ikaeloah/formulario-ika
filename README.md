<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página teste</title>
</head>
<body>
    <div class="campo">
        <h1 id="título">Cadastro</h1>
        <p id="subtítulo">Complete as informações</p>
    </div>

    <form>
        <fieldset class="grupo">
            <div>
                <label for="Nome"><strong>Nome</strong></label>
                <input type="text" name="nome" id="nome" required>
            </div>

            <div>
                <labelm for="Sobrenome"><strong>Sobrenome</strong></label>
                <input type="text" name="sobrenome" id="sobrenome" required>
            </div>
        </fieldset>

        <div class="campo">
            <label for="Email"><strong>Email</strong></label>
            <input type="email" name="email" id="email" required>
        </div>

        <div class="campo">
            <label><strong>Qual seu gênero?</strong></label>
            <label>
                <input type="radio" name="devweb" value="Feminino">Feminino
            </label>
            <label>
                <input type="radio" name="devweb" valeu="Masculino">Masculino
            </label>
            <label>
                <input type="radio" name="devweb" value="Prefiro não informar">Prefiro não informar
            </label>
        </div>
        <div class="campo">
            <label for="sexualidade"><strong>Qual sua sexualidade?</strong></label>
            <select id="sexualidade">
                <option selected disabled value="">Selecione</option>
                <option>Bissexual</option>
                <option>Homossexual</option>
                <option>Heterossexual</option>
                <option>Pansexual</option>
                <option>Outras</option>
            </select>
        </div>
        
        <fieldset class="grupo">
        <div id="check">
            <label><strong>Selecione seus interesses:</strong></label><br><br>
            <input type="checkbox" id="interesse1" value="Política">
            <label for="interesse1">Política</label>
            <input type="checkbox" id="interesse2" value="Música">
            <label for="interesse2">Música</label>
            <input type="checkbox" id="interesse3" value="Cultura">
            <label for="interesse3">Cultura</label>
            <input type="checkbox" id="interesse4" value="Esportes">
            <label for="interesse4">Esportes</label>
            <input type="checkbox" id="interesse5" value="Religião">
            <label for="interesse5">Religião</label>
            <input type="checkbox" id="interesse6" value="Comida">
            <label for="interesse6">Comida</label>
            <input type="checkbox" id="interesse7" value="Dança">
            <label for="interesse7">Dança</label>
        </div>
    </fieldset>

    <div class="campo">
        <br>
        <label><strong>Conte um pouco sobre você:</strong></label>
        <textarea row="6" style="width: 26em" id="sobre você" name="sobre você"></textarea>
    </div>

    <button class="botão" type="submit">Concluído</button>

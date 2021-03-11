Readme


 #colocar os tipos certos,pq já faz a verificação do campo,pedindo @
por isso o uso de type no html

<br> para pular linha

fieldset delimitar area 

checked para deixar marcado essa opção ao carregar a página

for mostra para aoende esta indicando

required a pessoa não vai conseguir enviar,sem que esse campo esteja preenchido.

<textarea rows="6" style="width: 26em" id="experiencia" name="experiencia>"></textarea>

essa tag já estilizei dentro dela, coloquei o número de linhas que ela terá, e dentro de syle coloquei o que faria dentro do css.

type="submit"


tipo de botão que envia o formulário

O id vai servir para colocar o css, coloquei em algumas tags, mas falta colocar em outras. Como na h1

<strong> para deixar com enfase em negrito ,todos os labels títulos da página

fazer a ligação do arquivo html com o arquivo css

* asteristico seleciona todos os elementos da página de html
 selecionar a classe com ponto . , # para id


estrutura básica do html: 
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <div>
    <h1>Cadastros de DEVs</h1>
    <p>Complete as suas informações</p>
    <br>
  </div>

  <form>
    <fieldset>
      <div>
        <label>Nome</label>
        <input type="text" name="nome" id="nome">
      </div>

      <div>
        <label>Sobrenome</label>
        <input type="text" name="sobrenome" id="sobrenome">
      </div>

    <div> 
      <label>Email</label>
      <input type="email" name="email" id="email">
    </div>
   </fieldset> 

    <div>
      <label>De qual lado da aplicação você desenvolve?</label>
      <label>
        <input type="radio" name="devweb" value="front-end" checked>Front-end
      </label>
      <label>
        <input type="radio" name="devweb" value="back-end">Back-end
      </label>
      <label>
        <input type="radio" name="devweb" value="fullstack">Fullstack
      </label>
    </div>

    <div>
      <label>Senioridade</label>
      <select id="senioridade">
        <option selected disabled value="">Selecione</option>
        <option>Junior</option>
        <option>Pleno</option>
        <option>Senior</option>
      </select>
    </div>

    <fieldset>
      <div>
        <label>Selecione as Tecnologias que utiliza:</label>
        <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
        <label for="tecnologia1">HTML</label>
        <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
        <label for="tecnologia2">CSS</label>
        <input type="checkbox" id="tecnologia3" name="tecnologia3" value="JavaScript">
        <label for="tecnologia3">JavaScript</label>
        <input type="checkbox" id="tecnologia4" name="tecnologia4" value="React">
        <label for="tecnologia4">React</label>
        <input type="checkbox" id="tecnologia5" name="tecnologia5" value="Vue">
        <label for="tecnologia5">Vue</label>
        <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Python">
        <label for="tecnologia6">Python</label>  
      </div>
    </fieldset>

    <div>
      <br>
      <label>Conte um pouco da sua experiência</label>
      <textarea row="6" style="width: 26em" id="experiencia" name="experiencia>"></textarea>
    </div>

    <button type="submit">Concluído</button>
  </form>
  
</body>
</html>

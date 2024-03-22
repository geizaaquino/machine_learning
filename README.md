# machine_learning
## Cursos de machine learning

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Configurações do Azure ML</title>
</head>
<body>

<h2>Laboratório de Machine Learning</h2>
<p><a href="https://portal.azure.com">https://portal.azure.com</a></p>

<ol>
  <li>Criar um novo recurso e na barra de busca digitar "machine learning" e criar.</li>
  <li>Escolher um grupo de recursos. Se não houver, criar um.</li>
  <li>Preencher os campos necessários como nome (sem espaços), região e outras informações solicitadas.</li>
  <li>Na barra superior, escolher "Examinar-Criar" para validar as informações e, em seguida, clicar em "Criar".</li>
  <li>Ir para o recurso e definir o tipo de ativo de dados.</li>
  <li>Escolher "Launch Studio".</li>
  <li>Do lado esquerdo, escolher "ML automatizado" e "Novo trabalho automatizado" e criar.</li>
  <li>Em "ML", preencher as configurações básicas e avançar.</li>
  <li>Escolher o tipo de tarefa como "Regressão" e criar.</li>
  <li>Definir o nome, tipo de ativo de dados, descrição e tipo como "Tabular", e avançar.</li>
  <li>Escolher "Arquivos da Web" e avançar.</li>
  <li>Colocar a URL dos dados e avançar.</li>
  <li>Nas configurações, escolher a opção "Somente o primeiro arquivo tem cabeçalho".</li>
  <li>Examinar e depois criar.</li>
  <li>Em configurações de tarefa, escolher a coluna de destino.</li>
  <li>Em "Exibir definições de configuração", desmarcar todas as opções e, em "Modelos permitidos", selecionar "RandomForest" e "lightGBM".</li>
  <li>Avançar e conferir, e avançar novamente e enviar o trabalho de treinamento e aguardar a execução.</li>
  <li>Validar o experimento e selecionar o modelo clicando em "+Registro" e configurar.</li>
  <li>Em "Modelos", é possível obter muitas informações como métricas.</li>
  <li>Em "Pontos de extremidades", configurar e testar:</li>
</ol>

<pre>
{
  "input_data": {
    "columns": [
      "day",
      "mnth",
      "year",
      "season",
      "holiday",
      "weekday",
      "workingday",
      "weathersit",
      "temp",
      "atemp",
      "hum",
      "windspeed"
    ],
    "index": [],
    "data": []
  }
}
</pre>

</body>
</html>



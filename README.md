# machine_learning
## Cursos de machine learning

Laboratório de machine learning /br
(https://portal.azure.com)

1- Criar um novo recursos e no buscar digitar machine learning e criar 
2- Escolher um grupo de recursos se não tiver criar 
3- Preencher os campos como o nome que não pode ter espaço, a refião e o restante das informações manter 
4- Na barra superior escolher examinar-criar que irá validar as informaçãoes e depois clicar em criar.
5- Ir para o recurso e definir o tipo de ativo de dado.
6- Escolher lunch studio
7- Do lado esquerdo escolher Ml automatizado e novo trabalho automatizado e criar
8- Em Ml preencher as configurações básicas e avançar 
9- Escolher tipo de tarefa "Regressão" e criar
10- Definir  o nome, tipo de ativo de dados, descrição, e tipo "tabular" e avançar
11- Escolher arquivos da Web e avançar
12- Colocar a URL dos dados e avançar
13- Nas configurações escolher a opção "Somente o primeiro arquivo tem cabeçalho
14- Examinar e depois criar
15- Em configurações de tarefa escolher a coluna de destino
16- Em Exibir definições de configuração desmarcar todas as opções e em modelos permitidos selecionar RandomForest e lightGBM
17-  Avançar e conferir e avançar novamente e enviar trabalho de treinamento e aguardar a execução
18- Validar o experimento e selecionar modelo cliecando em +Registro e configurar
19- Em modelos é possivel obter muitas informações como métricas.
20 - Em posntos de extremidades, configurar e testar:

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


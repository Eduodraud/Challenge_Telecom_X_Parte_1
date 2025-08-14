# Challenge_Telecom_X_Parte_1
Challenge Telecom X: análise de evasão de clientes, da formação Modelagem de Dados com Python G8 - ONE
# Relatório
Esse trablho começou com a extrção dos dados, que foram extraídos do gith e nomeados como a variável 'url'. Para melhor visualização e extração dos dados foi utilizado o comando "pd.json_normalize()" o que possibilitou a visualização correta de todos os dados.
Após esse momento passei pelo primeiro desafio, avaliar possíveis dados com problemas, sendo eles do tipo NaN, ou dados em branco, linhas duplicadas e demais problemas que dificultaria as seguintes análises. Logo mais, foram selecionadas apenas as colunas que eram mais importantes para a análise de evasão. Criamos uma coluna chamada "Contas_Diarias" que foi definida da seguinte forma: (df_limpo['Contas_Diarias'] = df_relevante['account.Charges.Monthly'] / 30).
Após essa preparação foi possível prosseguir com as análise, avaliando a evasão e sua realção com diferentes variáveis, como idade, genero. Com isso foi finalizado a primeira parte do desafio Telecom X - Análise de Evasão de Clientes. 

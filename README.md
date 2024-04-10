https://www.kaggle.com/datasets/vstacknocopyright/electricity


Date: date between 7 May 1996 to 5 December 1998. Here normalized between 0 and 1 <br/>
Day: day of the week (1-7)<br/>
Period: time of the measurement (1-48) in half hour intervals over 24 hours. Here normalized between 0 and 1<br/>
NSWprice: New South Wales electricity price, normalized between 0 and 1<br/>
NSWdemand: New South Wales electricity demand, normalized between 0 and 1<br/>
VICprice: Victoria electricity price, normalized between 0 and 1<br/>
VICdemand: Victoria electricity demand, normalized between 0 and 1<br/>
transfer: scheduled electricity transfer between both states, normalized between 0 and 1<br/>

OBS:
1 a 48 : é referente a quantidade de períodos de meia hora ( 30 min ) durante o dia. É atualização de preços do NSW e VIC

& Class:  Up e Down nos preço durante o tempo 



Antes de fazer os gráficos organize os dados em variaveis por exemplo: titulo -> histórico de preço entre VIC e NSW durante o tempo ( 1996 a 98)<br/><br/>
Sugestões:<br/>
1.Saber o consumo de energia na Australia de 1996 a 1998<br/><br/>
2. Qual das duas regiões entre NSW e VIC ( ficam na região sudeste) teve maior demanda? E por quanto tempo? Qual dos precisou transferir a energia de uma região para outra, para suprir a demanda.<br/><br/>
3. Com base na ultima pergunta quais foram os dias que teve o aumento de consumo ou de valor na data específica e dia da semana.<br/><br/>
4. Quanto % teve a mudança de preço?<br/><br/>
5. Da para criar um gráfico de preço, seja subindo ou descendo durante o tempo?<br/><br/>
6. fazer dois gráficos na mesma tabela para demonstrar que teve influência.
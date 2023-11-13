# Irrigation-BETA
Projeto de irrigação automático utilizando o arduino como suporte ( Trabalho de IOT - SENAI - Curso técnico )

Este código monitora a umidade do solo, mandando um sinal ao NODE-red, podendo ver detalhadamente o nível de umidade do solo, convertendo o sinal em curva ou vendendo através de um medidor. Quando o solo chega a ficar seco, aciona a bomba peristática para irrigar o solo, isso quando a leitura estiver abaixo de "um valor mínimo determinado", e assim interrompido * a irrigacao quando a leitura chegar a um valor tempo definido para irrigar um vaso de 7l.

# Gestão_da_Informação
Gestão da Informação Parametrizando Dados Educacionais


Gestão da Informação 04.03.24 - ESTÁGIO
Gestão da Informação 05.03.24 WYDEN
Gestão da Informação 06.03.24 ANIMA



Retificar no dia 04.03.24 ESTÁCIO:
*****Realizar 07.03.24*********************
#cursos_horários.id ----- Esse campo fica vazio
#Chaveamento (external_id) ----- Este recebe o campo SKU
#Informação Complementar (Subtítulo do card) --- Deixar o separador do desconto como (,) e não (.)
#Duração-tipo --- Sempre é SEMESTRE
#Parcelas --- Sempre multiplicar 'Duração do Curso' por 6
#Valor da mensalidade/Valor total do curso ---- Separador de milhar tem que ser com (.) e Separador de decimal por (,)
#Desconto exclusivo Edupass (%) --- Porcentagem tem que vir no formato de centena (100,00%) e Não Decimal (1.00%)
#Categoria --- SEMPRE GRADUAÇÃO
#Tipo - O Mesmo que 'Categoria'
#Cidade ---- Recebe o valor de Município
#Modalidade - EAD sempre é em CAPSLOCK
#Turno - Colocar o acento em Flexível

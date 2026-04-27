# Programa-para-sal-rio-
ganho_por_hora = float(input('Quanto você ganha por hora?'))
horas_por_mes = float(input('Quantas horas trabalha por mês?'))

salario_bruto = ganho_por_hora * horas_por_mes
IR = salario_bruto * 0.11
INSS = salario_bruto * 0.08
Sindicato = salario_bruto * 0.05
salario_liquido = salario_bruto - IR - INSS - Sindicato
dias_de_trabalho = horas_por_mes / 20

print(f'O salário bruto do mês é: R${salario_bruto}')
print(f'Você trabalha {dias_de_trabalho} dias por mês')
print(f'O desconto do IR é: R${IR}')
print(f'O desconto do INSS é: R${INSS}')
print(f'O desconto do Sindicato é: R${Sindicato}')
print(f'O salário líquido do mês é: R${salario_liquido}')

# Altera-es-incrementais-de-Vari-veis
Este repositório contém exemplos práticos sobre como realizar alterações em variáveis utilizando diferentes abordagens em Python. Os exemplos demonstram como adicionar itens a listas e somar valores a variáveis numéricas, ilustrando duas formas comuns de realizar essas operações.


# Alterações de Variáveis

Estrutura:

- variavel = variavel + outro_valor

ou então

- variavel += outro_valor

Exemplo: vamos adicionar às variáveis criadas o Produto IPad, 500 vendas
"""



lista = ['mac', 'iphone']
vendas = [100, 200]
#adicionando IPad na lista
lista = lista + ['Ipad']
print(lista)


soma_vendas = 300
#adicionando na soma a quantidade de IPad
soma_vendas += 500 #1 forma de fazer
print(soma_vendas)




email = 'Esse mês vendemos um total de {} produtos, sendo:\n{} unidades de {}\n{} unidades de {}'.format(soma_vendas, vendas[0], lista[0], vendas[1], lista[1])
#adicionando no fim do texto o Ipad
email = email + '\n{} unidades de Ipad'.format(500)  #2 forma de fazer

print(email)

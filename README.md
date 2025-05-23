# tipos-de-servicos-nuvem

Descrição
O Azure oferece diferentes modelos de serviço em nuvem, que indicam quem é responsável por gerenciar cada parte da tecnologia: o cliente ou a plataforma. Neste desafio, você vai relacionar cada tipo de serviço com a sua descrição.

Entrada
A entrada será um dos seguintes tipos de serviço:

IaaS
PaaS
SaaS
FaaS
Saída
A saída será a descrição correspondente:

Infraestrutura como serviço
Plataforma como serviço
Software como serviço
Função como serviço, baseada em eventos

# Recebe a entrada do usuário e armazena na variável "entrada":
entrada = input()

# Função responsável por receber um conceito e retornar sua respectiva descrição:
def descrever_servico(servico):
  if servico == "IaaS":
    return "Infraestrutura como serviço"

# COMPLETE AQUI: Preencha corretamente cada conceito, considerando as descrições abaixo: 
  elif servico == "PaaS":
    return "Plataforma como serviço"
  elif servico == "SaaS":
    return "Software como serviço"
  elif servico == "FaaS":
    return "Função como serviço, baseada em eventos"

print(descrever_servico(entrada))

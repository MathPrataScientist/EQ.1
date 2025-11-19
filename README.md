# EQ.1
Este projeto é um pequeno programa em Python capaz de interpretar e resolver equações lineares de uma variável usando a biblioteca SymPy.

# Funcionalidades

Interpretação automática de equações digitadas pelo usuário.

Suporte a multiplicação implícita, como:

2x+3=7

3(x-4)=12

Reconhecimento de expressões simbólicas complexas.
Resolução de equações lineares usando o solve() do SymPy.
Tratamento básico de erros para entradas inválidas.

O programa entende expressões como:
2x+3=7
3(x-4)=12
5x-9=3x+11
(x/2)+7=20

#Como funciona
O usuário digita uma equação no formato expressão = expressão.
O programa separa os lados da equação.
Usa o SymPy Parser com transformações que permitem multiplicação implícita.
Cria um objeto Eq() representando a equação.
Resolve para a variável x.

# Requisitos
Antes de rodar o programa, instale as dependências:
pip install sympy

# Como executar

Basta rodar o script:
python nome_do_arquivo.py
Digite uma equação quando o programa solicitar:
Digite a equação: 2x+3=7


Saída:
Equação interpretada: Eq(2*x + 3, 7)
Solução encontrada:
x = 2

# RentSmart — R.M Imóveis

Calculadora de aluguel para imobiliária (apartamento, casa, estúdio) com regras de negócio por tipo de imóvel, taxa contratual parcelável e projeção mensal em CSV.

## Problema
Calcular o aluguel manualmente para diferentes tipos de imóvel (apartamento, casa, estúdio) com regras variadas (quartos, garagem, desconto por crianças, vagas extras) e uma taxa contratual parcelável é propenso a erros e trabalhoso.

## Solução
Programa em Python orientado a objetos que coleta os dados do imóvel via terminal, aplica as regras de negócio de cada tipo e gera um orçamento detalhado + arquivo `projecao_locacao.csv` com a projeção de 12 meses.

## Funcionalidades
- Cálculo automatizado para Apartamento, Casa e Estúdio.
- Regras: quartos, garagem, desconto de 5% sem crianças, vagas extras no estúdio.
- Taxa contratual de R$ 2.000,00 parcelável em 1 a 5 vezes.
- Geração automática de `projecao_locacao.csv` (12 meses).
- Orientação a Objetos (herança e polimorfismo).

## Stack
- Python 3.x (sem dependências externas)

## Como rodar
```powershell
python main.py
```
Siga as instruções interativas no terminal.

## Estrutura
```
RentSmart_Projeto_Completo/
└── main.py
```

## Autor
Lucas Barbosa Pedro — [@lucass1108](https://github.com/lucass1108)
## Consolidação das planilhas

Metodologia:

Planilha final: A planilha final possui 30710 exemplares registrados e 36 colunas, entre elas:
- **Número de tombo (sem o epipeto)**
- **Sexo**
- **Estado do material**
- **Classe**
- **Família**
- **Gênero**
- **Espécie**
- **Autor da espécie**
- **Material tipo**
- **Primeiro nome determinador**
- **Nome do meio determinador**
- **Último nome determinador**
- **Data de determinação**
- **Preparação do material**
- **Dia**
- **Mês**
- **Ano**
- **Local de coleta**
- **Coletor primeiro nome**
- **Coletor nome do meio**
- **Coletos último nome**
- **Altitude**
- **Continente**
- **País**
- **Estado**
- **Município**
- **Coordenadas (6 colunas)**
- **Localidade 2**
- **Localidade**
- **Localidade original**
- **Coletor**
- **Observação**
- **Data de coleta**

Link para o arquivo final consolidado:

# Formatações necessárias

## Formatação dos campos relacionados a localidade
No campo localidade original vinham dados sobre a localidade, cidade e estado (sempre nessa ordem). Foi utilizado um código em Python para separar esses dados em três colunas (localidade, cidade e estado). Os munícipios presentes na planilha de localidade foram comparados com os munícpios presentes em uma planilha do IBGE, quando o munícipio não constava dentro dessa planilha do IBGE ele era deletado da planilha. Após isso a informação município era retirada do campo de localidade.

## Formatação dos campos relacionados a coletores
Na planilha antiga os coletores vinham todas em uma mesma coluna separados por ", / - e". Todos os coletores foram separados para identificação de coletores únicos. Os coletores após separados e postos em uma planilha separada passaram pelo programa open refine para que fosse identificado quais nomes diferentes poderiam pertencer a um mesmo coletor. Essa relação foi então enviada para a Ornitologia de modo que eles escolhessem a forma como cada coletor deveria ser chamado. A coluna única de coletores foi substituida por 9 colunas, sendo que 3 para cada autor (primeiro nome, nome do meio e último nome).

## Formatação em coordenadas

## Formatação no campo data
As datas eram dividas em colunas para dia, mês e ano. Foram concatenadas em uma coluna única onde as as informações eram separadas por "/". Quando algum dado se encontrava ausente era preenchido com 00 (dia e mês) ou 0000 (ano). 

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
No campo localidade original vinham dados sobre a localidade, cidade e estado (sempre nessa ordem). Foi utilizado um código em Python para separar esses dados em três colunas (localidade, cidade e estado). Os munícipios presentes na planilha de localidade foram comparados com os munícpios presentes em uma planilha do IBGE, quando o munícipio não constava dentro dessa planilha do IBGE ele era deletado da planilha.

## Organização original dos dados
Originalmente a coleção se dividia em 60 pastas, uma para cada família, e dentro destas pastas haviam diferentes planilhas para cada gênero, dentro destas planilhas para cada gênero tinham guias para cada espécie. Dentro das guias tinhamos as informações sobre todos os materiais daquela determinada espécie.

```mermaid
graph LR
A(Pasta com família) --> B(Planilha com gênero)
B --> C(Guias com as espécies)
```

As planilhas possuiam o número de colunas variável, sendo em média 13 colunas contendo:
- **Número de tombo**
- **Sexo**
- **Estado**
- **Localidade**
- **Coordenadas** (Dividida em 4 colunas)
- **Dia**
- **Mês**
- **Ano**
- **Coletor**
- **Observação**

Em alguns casos tinham colunas de **Altitude** e **Localidade 2**, o número de colunas para coordenadas podia ser 2 ao invés de 5.

## Problemas encontrados após a consolidação

**Caprimulgidae**
Nas planilhas de *Caprimulgus rufus, Chordeiles seicocaudatus, Hydropsalis* e *Macropsalis* existem dados do gênero *Eleothreptus*.

**Coerebidae**
Gênero *Coereba* sem nenhum lote.

**Cracidae**
Lotes de diferentes espécies sem número de tombo:
- *Crax blumenbachii* sem 1
- *Ortalis motmot* sem 1
- *Ortalis superciliaris* sem 2
- *Penelope jacquaçu* sem 1
- *Penelope obscura* sem 1
- *Penelope jacucaca* sem 1
- *Penelope ochrogaster* sem 1
- *Penelope pileata* sem 2
- *Pipile cujubi* sem 1

**Formicariidae**
As espécies *Neoctantes niger, Myrmochanes hemileucus, Clyoctantes atrogularis, Cercomacra nigricans, Cercomara carbonária, Clyoctantes atrogularis, Grallaria guamaltensis, Myrmeciza pelzeni, Myrmeciza hyperythra, Myrmeciza goeldii,
Myrmeciza melanoceps, Myrmothera simplex, Myrmotherula ambígua, Myrmotherula klagesi, Myrmotherula cherriei, Myrmotherula sunensis, Myrmotherula behni, Percnostola schistacea, Percnostola caurensis, Rhegmatorhina cristata, Rhegmatorhina melanosticta, Thamnophilus cryptoleucus, Thamnophilus insignis* e *Terenura humeralis* possuem planilhas mas não existem lotes registrados.
Os gêneros *Mymochanes, Necotantes* e *Skutchia* não possuem registros de lotes, mas tem planilha.
Lotes MNRJ 44037 (*Myrmeciza loricata*), MNRJ 38032 e MNRJ 38033 (*Myrmotherula haematonota*), MNRJ 23666 (*Thamnophilus doliatus*) estão com a fonte em vermelho.
Os lotes MNRJ 39455 e MNRJ 39456 (*Pyriglena atra*) estão com o estado em vermelho.

**Furnariidae**
*Anabarethia amaurotis* com número de tombo faltando os primeiros caracteres.
MNRJ 30354 (*Craniolecuca vulpina*) em vermelho, MNRJ 42738 (*Synallaxis cinerea*), MNRJ 34970 (*Synallaxis infuscata*) e MNRJ 15282 (*Synallaxis frontalis*)
Dentro do gênero *Spartanoica* tem uma aba de *A. luizae*. Não incluí por não saber gênero nem
família.
*Synallaxis ruficapilla* tem um lote sem número de tombo.

**Icteridae**
*Caccius chrysopterus* tem o lote MNRJ 26214 repetido com dados iguais, os dois registros estão em vermelho.
MNRJ 7676 (*Cacicus solitarius*) em vermelho *Gymnostinops bifascatius, Macroagelanius imthurni, Ocyalus latirostris* sem lote.

**Parulidae**
*Basileuterus flavelous* é desta família, mas estava em diferentes planilhas de outras
famílias.
O gênero *Myioborus* e a espécies *Basileuterus bivittatus* não tem lote.

**Passeridae**
*Passer domesticus* se divide em duas guias dentro da planilha, as duas com formatação diferente, porém dados iguais.

**Picidae**
MNRJ 8798, MNRJ 22811, MNRJ 24847, MNRJ 25193, MNRJ 25330, MNRJ 25331, MNRJ 26385, MNRJ 26677, MNRJ 26707, MNRJ 26708, MNRJ 26709, MNRJ 26927, MNRJ 27429, MNRJ 29165, MNRJ 29461, MNRJ 31076, MNRJ 32751, MNRJ 35718, MNRJ 38533, MNRJ 39613, MNRJ 39637 (*Dryocopus lineatus*); MNRJ 5028, MNRJ 5029, MNRJ 5899, MNRJ 29552, MNRJ 29553, MNRJ 29554, MNRJ 29555, MNRJ 32101, MNRJ 32754, MNRJ 32755, MNRJ 37740 (*Melanerpes cruentatus*); MNRJ 5156, MNRJ 5157, MNRJ 5159, MNRJ 5162, MNRJ 5163, MNRJ 5423, MNRJ
5424, MNRJ 5426, MNRJ 5428, MNRJ 5429, MNRJ 42261, MNRJ 42262, MNRJ 42976, MNRJ 42977, MNRJ 42992, MNRJ 42994, MNRJ 42966 estão com lotes em vermelho.

**Psittacidae**
Dentro de Psittacidae tem uma pasta com o nome Psittacidae antigos, incluir nas planilhas?

**Ramphastidae**
MNRJ 3862 (*Ramphastos vitellinius*); MNRJ 10460, MNRJ 10588, MNRJ 10589, MNRJ 10590, MNRJ 10592, MNRJ 10593, MNRJ 10595, MNRJ 10596, MNRJ 10598,
MNRJ 10599, MNRJ 10605, MNRJ 10607, MNRJ 10611, MNRJ 10612, MNRJ 35228 (*Pteroglossus bitorquatus*).

**Spheniscidae**
*Eudypter pachyrimphus* não tem dados.

**Steatornithidae**
A espécie na planilha do gênero *Steatornis* está marcada como *A. caripensis* não adicionei na planilha geral por não saber a família.

**Thraupidae**
Gêneros *Conothraupis, Cyanicterus, Mitrospingus sem dados.
Espécies Euphonia finschi, Nemosia rourei, Piranga olivacea, Piranga lucoptera, Tachyphonus nattereri, Tangara punctata, Tangara guttata, Tangara nigrocincta, Thraupis sayaca, Thraupis cyanoptera, Thraupis ornata, Thraupis palmarum, Thraupis
bonariensis* estão com planilhas sem dados.

**Tyranidae**
Tem uma linha em *Elaenia chiriquenis* vazia.
Dois lotes de *Onychorhynchus coronatus* sem número de tombo. *Myiophobus, Syristes sibilator* sem lotes.

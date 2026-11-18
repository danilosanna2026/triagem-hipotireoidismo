# Dados

`hypothyroid.csv` tem 3.772 pacientes e 30 colunas (exames de tireoide, medicações, indicadores clínicos e o rótulo `binaryClass`).

**Origem.** UCI Machine Learning Repository, base Thyroid Disease, arquivo `hypothyroid`, registros do Garavan Institute (Sydney, Austrália) doados por Ross Quinlan. https://archive.ics.uci.edu/dataset/102/thyroid+disease

**Observações sobre o arquivo.**
- Valores ausentes aparecem como `?` (6.064 células, incluindo a coluna `TBG`, que está 100% vazia).
- O rótulo `binaryClass` vem invertido em relação ao nome: `N` é o paciente com hipotireoidismo e `P` é o paciente sem a doença. A comparação das medianas dos exames que mostra isso está na seção 1 do notebook.
- Há uma idade de 455 anos (erro de digitação) e 61 linhas duplicadas, tratadas na seção 2.
- O UCI informa que Quinlan suspeita que esta base possa ter sido corrompida depois de chegar ao repositório.
- A base não traz identificação pessoal dos pacientes.

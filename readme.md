# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name: Cars

## Table columns:
- id | BIGINT PK AI
- produttore | VARCHAR(100) | NOTNULL
- modello | VARCHAR(30) | NOTNULL
- cilindrata | MEDIUMINT | NULL
- cavalli | MEDIUMINT | NULL
- alimentazione | VARCHAR(30) | NULL
- cambio | VARCHAR(20) | NOTNULL
- Km | MEDIUMINT | NOTNULL 
- anno | YEAR | NOTNULL
- colore | VARCHAR(30) | NOTNULL
- optional | TEXT | NULL
- prezzo | DECIMAL(3,2) | NULL

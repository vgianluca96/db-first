
# Cars Database

## Table name

- macchine_usate

## Table columns

- id | PK, BIGINT, AUTOINCREMENT, UNIQUE, NOT NULL
- marca | VARCHAR(20), NOT NULL
- modello | VARCHAR(100), NOT NULL
- prezzo | DOUBLE(9,2), NULL
- potenza | SMALLINT, NULL
- cavalli | SMALLINT, NULL
- km_percorsi | MEDIUMINT, NULL
- anno | YEAR, NULL
- colore | VARCHAR(20), NULL
- alimentazione | VARCHAR(20), NULL
- trazione | VARCHAR(20), NULL
- optional | TEXT, NULL
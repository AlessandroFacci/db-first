# Database First

## Consegna

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!
Esempio:
COLONNA | TIPO | ATTRIBUTI
-- | -- | --
marca | varchar(50) | NOT NULL
modello | varchar(50) | NOT NULL
ecc..

#### BONUS: nomi colonne in inglese

## Tabella

| COLONNA         | TIPO        | ATTRIBUTI                   |
| --------------- | ----------- | --------------------------- |
| id              | BIGINT      | PRIMARY KEY, AUTO INCREMENT |
| brand           | VARCHAR(20) | NOT NULL                    |
| model           | VARCHAR(20) | NOT NULL                    |
| dors            | TINYINT     | UNSIGNED, NULL              |
| exchange        | VARCHAR(20) | NULL                        |
| fuel            | VARCHAR(20) | NULL                        |
| mileage         | INT         | UNSIGNED, NULL              |
| year            | YEAR        | UNSIGNED, NULL              |
| color           | VARCHAR(20) | NULL                        |
| car body        | VARCHAR(20) | NULL                        |
| weight          | FLOAT(7,3)  | UNSIGNED, NULL              |
| price           | FLOAT(10,2) | UNSIGNED, NOT NULL          |
| description     | TEXT        | NULL                        |
| power           | FLOAT(5,2)  | UNSIGNED, NULL              |
| salesperson     | VARCHAR(20) | NULL                        |
| conditions      | VARCHAR(20) | NULL                        |
| previous owners | TINYINT     | UNSIGNED, NULL              |
| photo           | VARCHAR     | NULL                        |

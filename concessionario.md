# db-first
- Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

# Cars table

- id | TINYINT, PK, AI, NOT NULL, UNIQUE
- brand | VARCHAR(25), NOT NULL
- model | VARCHAR(25), NOT NULL
- version | VARCHAR(25), NULL
- registration date | DATE, NOT NULL
- plate_number | CHAR(7), NOT NULL, UNIQUE <!--italian plate -->
- fuel_type | VARCHAR(15), NOT NULL
- km | MEDIUMINT, NOT NULL
- cover_image | VARCHAR(255)
- shift | VARCHAR(15), NOT NULL
- seats_count | TINYINT, NULL
- horse_power | SMALLINT, NULL
- kw | SMALLINT, NULL
- neo_drivers | TINYINT, NULL
- price | MEDIUMINT, NOT NULL
- doors count | TINYINT, NULL
- color | VARCHAR(20), NOT NULL
- intern_color | VARCHAR(20), NULL 
- intern_material | VARCHAR(20), NULL
- condition | VARCHAR(25), NULL
- previous_owners_count | TINYINT, NULL
- ?emission_class | VARCHAR (10), NULL
- available_for_pick-up | TINYINT, DEFAULT(0)
- note | TEXT(255), NULL

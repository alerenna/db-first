## Database 

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
- come visto in classe fai un file readme.md
- inserisci nome della tabella,
- inserisci le colonne per definire il modello
- assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna
- PUSHA

## Name: cars

- id BIGINT - Primary key - NOT NULL
- brand - VARCHAR(100) - NOT NULL
- model - VARCHAR(100) - NOT NULL
- year - YEAR - NOT NULL
- mileage - SMALLINT - NOT NULL
- fuel_type - VARCHAR(10) - NULL
- transmission VARCHAR(50) - NULL
- engine_displacement INTEGER - NULL
- power VARCHAR(50) - NULL
- color VARCHAR(50) *si potrebbe anche pensare ad un'altra tabella con gli ID e i colori disponibili
- doors TINYINT - NULL
- seats  TINYINT - NULL
- emission_class VARCHAR(50) - NULL
- price DECIMAL(10, 2) - NULL
- is_available TINYINT(1) - NULL - DEFAULT(1)
- description TEXT - NULL
- created_at DATETIME - NOT NULL
- updated_at DATETIME - NOT NULL
- image-url VARCHAR(255) - NULL
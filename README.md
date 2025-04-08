## Database 

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
- come visto in classe fai un file readme.md
- inserisci nome della tabella,
- inserisci le colonne per definire il modello
- assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna
- PUSHA

## Name: cars

- id BIGINT - Primary key
- brand - VARCHAR(100)
- model - VARCHAR(100)
- year - YEAR
- mileage - SMALLINT
- fuel_type - VARCHAR(10)
- transmission VARCHAR(50)
- engine_displacement INTEGER
- power VARCHAR(50)
- color VARCHAR(50) *si potrebbe anche pensare ad un'altra tabella con gli ID e i colori disponibili
- doors TINYINT
- seats  TINYINT
- emission_class VARCHAR(50)
- price DECIMAL(10, 2)
- is_available TINYINT(1)
- description TEXT
- created_at DATETIME
- updated_at DATETIME
- image-url VARCHAR(255)
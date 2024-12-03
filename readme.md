# DB structure
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# Table name
 - Veicoli_usati


 # Table structure
- ID | BIGINT - AUTO INCREMENT - PK(UNIQUE) - NOT NULL
- Marca | VARCHAR(50) -  NOT NULL
- Modello | VARCHAR(100) - NOT NULL
- Anno | YEAR NOT NULL
- Data_acquisto | DATE NOT NULL
- Colore | VARCHAR(30) NULL
- Chilometraggio | INT UNSIGNED
- Prezzo | DECIMAL(12,2)
- Carburante | VARCHAR(15)
- Potenza_cv | INT UNSIGNED
- Cambio | VARCHAR(50)
- Tipologia | VARCHAR (50)
- Numero_porte | TINYINT UNSIGNED
- Numero_posti | TINYINT UNSIGNED
- Foto_veicolo | VARCHAR(255)
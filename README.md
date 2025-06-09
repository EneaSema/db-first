Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

| NAME                       | TIPO                                                | VARIABILI     | CARATTERISTICHE  |
| -------------------------- | --------------------------------------------------- | ------------- | ---------------- |
| ID                         | INT                                                 | NOT NULL, A.I | PRIMARY KEY      |
| ------                     | ------                                              | -----------   | ---------------- |
| NOME CITTA' CONCESSIONARIO | VARCHAR(50)                                         | NOT NULL      | INDEX            |
| ------                     | ------                                              | -----------   | ---------------- |
| ANNO IMMATRICOLAZIONE      | DATE                                                | NOT NULL      | INDEX            |
| ------                     | ------                                              | -----------   | ---------------- |
| MODELLO                    | VARCHAR(20)                                         | NOT NULL      | INDEX            |
| -------------------        | --------------------------------------------------- | -----------   | ---------------- |
| TIPO                       | VARCHAR(20)                                         | NOT NULL      |
| ------                     | ------                                              | -----------   | ---------------- |
| IMP. ALIMENTAZIONE         | ENUM(Benz., diesel, gpl, metano, elettrica, ibrida) | NOT NULL      | INDEX            |
| ------                     | ------                                              | -----------   | ---------------- |
| KM                         | INT                                                 | NOT NULL      |
| ------                     | ------                                              | -----------   | ---------------- |
| PREZZO                     | SMALLINT                                            | NOT NULL      | INDEX            |
| ------                     | ------                                              | -----------   | ---------------- |
| CONDIZIONI AUTO            | ENUM(Pess, buone, ottime)                           | NOT NULL      | INDEX            |
| ------                     | ------                                              | -----------   | ---------------- |
| STATO AUTO VENDITA'        | ENUM(Pres, vend)                                    | NOT NULL,     |
| ------                     | ------                                              | -----------   | ---------------- |

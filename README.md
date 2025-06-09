Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

| NAME                 | TYPE                                                | VARIABILS     | CHARACTHERS      |
| -------------------- | --------------------------------------------------- | ------------- | ---------------- |
| ID                   | INT                                                 | NOT NULL, A.I | PRIMARY KEY      |
| ------               | ------                                              | -----------   | ---------------- |
| NAME'S CITY DEALER   | VARCHAR(250)                                        | NOT NULL      |                  |
| ------               | ------                                              | -----------   | ---------------- |
| YEAR OF REGISTRATION | DATE                                                | NOT NULL      | INDEX            |
| ------               | ------                                              | -----------   | ---------------- |
| MODEL                | VARCHAR(250)                                        | NOT NULL      | INDEX            |
| -------------------  | --------------------------------------------------- | -----------   | ---------------- |
| TYPE                 | VARCHAR(250)                                        | NOT NULL      |
| ------               | ------                                              | -----------   | ---------------- |
| POWER SYSTEM         | ENUM(Benz., diesel, gpl, metano, elettrica, ibrida) | NOT NULL      | INDEX            |
| ------               | ------                                              | -----------   | ---------------- |
| KM                   | MEDIUMINT                                           | NOT NULL      |
| ------               | ------                                              | -----------   | ---------------- |
| PLATE                | CHAR(7)                                             | NOT NULL      |
| ------               | ------                                              | -----------   | ---------------- |
| NUM. OF OWNERS       | TINYINT                                             | NOT NULL      |                  |
| ------               | ------                                              | -----------   | ---------------- |
| LAST OWNER           | VARCHAR(50)                                         | NOT NULL      |
| ------               | ------                                              | -----------   | ---------------- |
| PRICE                | DECIMAL(10,5)                                       | NOT NULL      | INDEX            |
| ------               | ------                                              | -----------   | ---------------- |
| CAR CONDITIONS       | ENUM(Pess, buone, ottime)                           | NOT NULL      | INDEX            |
| ------               | ------                                              | -----------   | ---------------- |
| AVAILABLE            | BOOL                                                | NOT NULL,     | INDEX            |
| ------               | ------                                              | -----------   | ---------------- |

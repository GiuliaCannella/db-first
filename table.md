# MACCHINE USATE

| colonna             | tipo    | attributi       |
| ------------------- | ------- | --------------- |
| id                  | bigint  | primary-key     |
| nome auto           | varchar | not null        |
| chilometri fatti    | int     | not null        |
| nome azienda        | varchar | not null        |
| marca auto          | varchar | not null        |
| targa               | varchar | not null unique |
| immatricolazione    | varchar | not null        |
| prezzo auto         | float   | not null        |
| foto                | varchar | null            |
| numero porte        | char    | not null        |
| descrizione auto    | text    | not null        |
| ultimo proprietario | varchar | not null        |
| colore              | varchar | not null        |
| nazionalità         | char    | not null        |

**diploma**

| id  | diploma_name | city       |
| --- | ------------ | ---------- |
| 1   | Radiologie   | Paris      |
| 2   | Infirmerie   | Toulouse   |
| 3   | Cardiologie  | Strasbourg |
| 4   | Chirurgie   | Lile      |
| 5   | Orthopédie    | Paris      |
| 6   | Urgentisme    | Paris      |

---
**doctor**

| id  | surname  | firstname | job          | efficiency |
| --- | -------- | --------- | ------------ | ---------- |
| 1   | MAMADOU  | Momo      | radiologue   | 10         |
| 2   | LAMARK   | Fred      | urgentiste   | 10         |
| 3   | CAMUS    | Albert    | chirurgien   | 10         |
| 4   | LAUBERGE | Claude    | orthopédiste | 10         |

---
**patient**

| id  | surname   | firstname | dolor | entry_date |
| --- | --------- | --------- | ----- | ---------- |
| 1   | ZEMOUR    | Eric      | 10    | 20/04/19   |
| 2   | COLOMBO   | Zizou     | 5     | 22/04/19   |
| 3   | LAPERUCHE | Zaz       | 10    | 20/04/19   |
| 4   | CIRAIL    | Canelle   | 10    | 20/04/19   |

---
**skills**

| id  | iddoctor | iddiploma |
| --- | -------- | --------- |
| 1   | 1        | 1         |
| 2   | 1        | 6         |
| 3   | 2        | 6         |
| 4   | 2        | 3         |
| 5   | 3        | 4         |
| 6   | 4        | 5         |

---
**folders**

| id  | iddoctor | idpatient |
| --- | -------- | --------- |
| 1   | 1        | 1         |
| 2   | 1        | 2         |
| 3   | 2        | 2         |
| 4   | 3        | 3         |
| 5   | 4        | 4         |

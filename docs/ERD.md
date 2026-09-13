+-------------+
|    USERS    |
+-------------+
| id (PK)     |
| nama        |
| email       |
| password    |
| created_at  |
+-------------+
       |
       | 1
       |
       | N
+------------------+
|   TRANSACTIONS   |
+------------------+
| id (PK)          |
| user_id (FK)     |
| category_id (FK) |
| type             |
| amount           |
| description      |
| transaction_date |
| created_at       |
+------------------+
       |
       | N
       |
       | 1
+--------------+
|  CATEGORIES  |
+--------------+
| id (PK)      |
| name         |
+--------------+


+-------------+
|    USERS    |
+-------------+
| id (PK)     |
+-------------+
       |
       | 1
       |
       | N
+----------------------+
|     SIMULATIONS      |
+----------------------+
| id (PK)              |
| user_id (FK)         |
| title                |
| scenario_type        |
| current_amount       |
| percentage_change    |
| duration_month       |
| predicted_saving     |
| created_at           |
+----------------------+

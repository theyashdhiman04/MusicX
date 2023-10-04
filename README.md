# MusicX — SQL Music Store Analysis

SQL-based analysis of an online music store dataset: schema, queries, and business insights.

---

## Summary

| | |
|---|---|
| **Goal** | Answer business questions and support growth decisions |
| **DBMS** | PostgreSQL (or any SQL-compatible) |
| **Tools** | PgAdmin4 |

---

## Setup

1. Create a database.
2. Create tables from the schema below.
3. Import CSVs from the [`dataset`](dataset) folder.

**PostgreSQL:** Restore [`music_store_db_backup`](music_store_db_backup) to skip manual creation.

---

## Schema

![Schema Diagram](MusicDatabaseSchema.png)

---

## Questions Answered

- Most popular genres, artists, and songs?
- Average prices by music type?
- Most popular countries for music purchases?

Full list and implementations: [`analysis.sql`](analysis.sql)

---

## Results (high level)

| | |
|---|---|
| **Top genre** | Rock |
| **Top artist** | Queens |
| **Top song** | War Pigs |
| **Avg. album price** | $1 |
| **Top country** | United States |

---

## Conclusion

The project answers the target business questions. Findings can drive marketing and product choices.

---

## Tech

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

---

## License

Free to use for learning and building your own SQL projects.

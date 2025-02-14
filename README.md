# 🦫 BEAVER: An Enterprise Benchmark for Text-to-SQL

### Updates
- 01/19/2025: 191 queries and 463 tables across 6 databases are all available.
- 10/28/2024: A subset of 49 queries and 99 tables is available.

If you find our data or the paper helpful, please cite the paper
```
@article{chen2024beaver,
  title={BEAVER: An Enterprise Benchmark for Text-to-SQL},
  author={Chen, Peter Baile and Wenz, Fabian and Zhang, Yi and Kayali, Moe and Tatbul, Nesime and Cafarella, Michael and Demiralp, {\c{C}}a{\u{g}}atay and Stonebraker, Michael},
  journal={arXiv preprint arXiv:2409.02038},
  year={2024}
}
```

### Datasets
- `dev.json` includes
  - natural language question, gold SQL statement
  - tables and join keys used in the gold SQL statement
  - column mappings from topics mentioned in the user question to columns used in the gold SQL statement.
- `dev_tables.json` includes the table schema, and key-foreign-key relationships.
  - join keys for tables in database `dw` can be found in `dw_join_keys.json`.
- [Google drive folder](https://drive.google.com/drive/folders/19bRoRxgWQLcJN3LTxwgev0xTahunjPIR?usp=drive_link) includes the anonymized database content.
  - `nw_sql.zip` includes the MySQL dump files for each non-`dw` database.

### Setup
- We use Oracle Database for executing the queries in database `dw`, so the most reliable approach is to download the free oracle database on your machine and import the data. But we are working on ways to make this process easier.
- For queries involving non-`dw` databases, we use MySQL database. We provided the MySQL dump files in the above Google drive folder.

### Contact
Your support in improving this dataset is greatly appreciated! If you have any questions or feedback, please send an email to peterbc@mit.edu.

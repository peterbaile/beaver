# 🦫 BEAVER: An Enterprise Benchmark for Text-to-SQL

### Updates
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
- `queries.json` includes the natural language question and the gold SQL statement.
- `schema/` includes the schema of tables.
<!-- - Anonymized database content will come soon -->
- [Google drive folder](https://drive.google.com/drive/folders/19bRoRxgWQLcJN3LTxwgev0xTahunjPIR?usp=drive_link) includes the anonymized database content for the gold tables and columns. Anonymization of other tables and columns will come soon.

### Setup
- We use Oracle Database for executing the queries, so the most reliable approach is to download the free oracle database on your machine and import the data. But we are working on ways to make this process easier.

### Contact
Your support in improving this dataset is greatly appreciated! If you have any questions or feedback, please send an email to peterbc@mit.edu.

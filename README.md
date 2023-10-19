# PDF Buddy
an application which allows you to store vectors from pdf embedding in neo4j db and ask question about the pdf files

---

## Predispositions

- You need to put some pdf files inside the ``/pfds`` folder

---
## How to run
- Start neo4j database with docker

```docker-compose up```

- run script from root folder to create vectors from pdfs and store them in neo4j

```python3 load_pfds.py ```

---
## Addition info
- running on ```python 3.9```

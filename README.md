# Newman-run

Run multiple postman collections along with predefined configs using a single feed file. Reduces command-line arguments since reporting (allure, JSON, CLI, and HTML) is embedded internally

link: <https://nareshnavinash.github.io/newman-run/>

---

Run newman

```bash
newman run collections/Postman\ Echo\ Request.postman_collection.json -e environments/My\ Environment.postman_environment.json
```

Run Newman-run

```bash
newman-run -f ./feeds/feed.json
```

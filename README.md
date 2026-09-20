# 🗄️ Решения по базам данных для юридических компаний

Обзор архитектур, технологий и подходов к хранению юридических данных (2025–2026).

**🔗 Открыть:** https://lexxsamotlor-byte.github.io/legal-db-solutions/

## Что внутри

- Традиционные SQL: MS SQL Server, PostgreSQL, Oracle, SQLite, Platform V Pangolin, SQLBase
- Векторные БД для RAG: pgvector, Qdrant, LanceDB, Milvus, ChromaDB, Astra DB
- Графовые и NoSQL: Neo4j, MarkLogic, Azure Cosmos DB, Cloud Firestore
- DMS и платформы: iManage, NetDocuments, Clio, Centerbase, HighQ, Sidebar
- Сводная таблица сравнения и рекомендации по размеру фирмы

## Как залить

```powershell
cd C:\Project_Vurden
git add README.md
git commit -m "Add README"
git push "https://$($env:GITHUB_LOGIN):$($env:GITHUB_TOKEN)@github.com/$($env:GITHUB_LOGIN)/legal-db-solutions.git" main

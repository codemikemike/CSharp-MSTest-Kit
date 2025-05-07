# 🧪 CSharp Unit Test Templates

Et bibliotek med genanvendelige C# unit tests skrevet med [MSTest](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-mstest). Formålet er at spare tid, følge best practices og sikre kvalitet i dine fremtidige projekter.

---

## 🧠 Formål

Dette repository er skabt for at:

- Genbruge veldokumenterede testskabeloner i nye C#-projekter
- Øve og fastholde god testkultur med **Arrange–Act–Assert**
- Lære og demonstrere best practices i testdækning og struktur
- Skabe en personlig testværktøjskasse

---

## ✅ Indhold

Testeksemplerne dækker blandt andet:

- CRUD-operationer (Create, Read, Update, Delete)
- Repositories med XML-persistens
- Exception handling (kommende)
- Filhåndtering (kommende)
- Refleksionsbaserede tests
- Negativ testning (fx med `null` og fejl-GUIDs)

---

## 📁 Struktur

```plaintext
/
├── TestGettingReal/
│   ├── RepositoryTests.cs
│   └── ...
├── .gitignore
├── README.md
└── LICENSE

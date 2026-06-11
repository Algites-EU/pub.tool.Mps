# <Project Name>

Short description of the project.

> Public Algites MPS tools.

---

## 📦 Overview

This project contains:
- publicly usable tools from the area of JetBrains MPS (Meta-Programming-System),
- Is used either for core MPS improvement or tools for other algites libraries 
  and application,
- Is intended for MPS developers and for the consumers of those products.

Example:
This repository contains the implementations and assemblies of various simple tools
extending the Algites ecosystem of the usage of Meta-Programming-System.

---

## 🧱 Modules & Structure

General structure of repository contains

```
.
├── README.md
├── core - contains the tools, which are working directly with the MPS core without any extensions of the languages, etc.
|          ├── README.md
|          └── documentation - contains teh MPS project for documentation tools
├── ...

```

---

## 🚀 Build

### Gradle

```bash
./gradlew build
```

---

## 🔄 Continuous Integration (Algites CI)

This repository uses the **Algites unified GitHub Actions CI pipeline** (build/test/publish rules are centralized).

For exact usage and naming of the branches to utilize fully the defined possibilities, see
https://github.com/Algites-EU/pub.gov.Algites/specs/

---

## 📥 Usage

Describe: TBD
- how to consume the library/tool,
- example dependency coordinates,
- or how to run the application.

Example (Maven): TBD

```xml
<dependency>
  <groupId>eu.algites...</groupId>
  <artifactId>...</artifactId>
  <version>...</version>
</dependency>
```

---

## 🛠 Development

Typical workflow:

```bash
git clone https://github.com/Algites-EU/pub.tool.Mps.git
cd <repo>
./gradlew build
```

---

## 🤝 Contributing

Contributions are welcome.

Please:
- open an issue to discuss changes,
- follow the Algites coding and naming standards,
- ensure CI passes before submitting a PR.

---

## 📜 License

This project is licensed under the terms of the license specified in the `LICENSE` file.

---

## 🌍 About Algites

Algites develops platforms, tools, and applications based on strong governance,
modeling, and automation principles.

See:
- https://github.com/Algites-EU/pub.gov.Algites/tree/main/specs

---

**© Algites**

## 📚Correção | Primeira Avaliação de DIAW

    Esse projeto é a correção para a PRIMEIRA AVALIAÇÃO DE DIAW. 

---

## 📁 Estrutura do projeto

```
📁 CandidatosTSE
│
├── 📁 src
│   └── 📁 main
│       │
│       ├── ☕ java
│       │   └── 📦 com.example.CandidatosTSE
│       │       │
│       │       ├── 🚀 application
│       │       │   └── CandidatosTseApplication.java
│       │       │       └── Classe principal da aplicação Spring Boot
│       │       │
│       │       ├── 🎮 controller
│       │       │   └── CandidatosTseController.java
│       │       │       └── Controlador e rota da tela única de candidatos
│       │       │
│       │       ├── 🧩 model
│       │       │   └── Candidato.java
│       │       │       └── Representa um candidato lido do CSV do TSE
│       │       │
│       │       └── ⚙️ service
│       │           └── CandidatosTseService.java
│       │               └── Serviço responsável por carregar, tratar e filtrar os candidatos
│       │
│       └── 📁 resources
│           │
│           ├── 📊 data
│           │   └── 📁 candidatos
│           │       └── consulta_cand_2026_MG.csv
│           │           └── Base de dados oficial do TSE (candidatos de MG, 2026)
│           │
│           ├── 🎨 static
│           │   │
│           │   ├── 🎨 css
│           │   │   └── style.css
│           │   │       └── Estilização da tela de candidatos
│           │   │
│           │   └── 🖼️ images
│           │       └── 📁 candidatos
│           │           └── Fotos oficiais dos candidatos (padrão FMG<sq>_div.jpg)
│           │
│           └── 🌐 templates
│               └── index.html
│                   └── Tela única com filtros e listagem dos candidatos
│
└── 📄 pom.xml
    └── Dependências e configurações do Maven
```

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT — veja o arquivo [LICENSE](LICENSE) para mais detalhes.

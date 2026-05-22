# 🚗 RideUFC — App de Carona Universitária

> Projeto Integrado em Engenharia de Software — UFC Campus Quixadá

Aplicativo mobile Android para compartilhamento de caronas entre estudantes da Universidade Federal do Ceará, Campus Quixadá. Conecta motoristas e passageiros de forma segura, organizada e gratuita.

---

## 👥 Equipe

| Matrícula | Nome | GitHub |
|-----------|------|--------|
| Ênio Fernandes de Assis e Silva| [@eninhokkj ](https://github.com/eninhokkj) |

---

## 📌 Links das Ferramentas

| Ferramenta | Link |
|------------|------|
| 📋 Protótipo (Figma) | [https://drive.google.com/drive/u/0/folders/1yFWGKUZiN7gtz1GfDq5OzEPvmfk9kSvS] |
| 📄 Documento de Requisitos | [https://drive.google.com/drive/u/0/folders/1V4rkzOTfXrL9U5nDPps-7tyBzDkwJ7Gy] |
| 🏗️ Documento de Arquitetura | [https://drive.google.com/drive/u/0/folders/1PaTEckVmRwb_a4Dhi82sib7V7Im9lIZj] |
| 📊 Backlog / Gestão de Projeto | [https://drive.google.com/drive/u/0/folders/1imVZ2nDtT5jaEAT08znSPayYC0m66TGX] |

---

## 🛠️ Tecnologias

**Front-end (Mobile)**
- Kotlin + Jetpack Compose
- Padrão MVVM + Clean Architecture
- Room (cache local)
- Firebase Cloud Messaging (notificações push)

**Back-end**
- Java + Spring Boot
- API REST com autenticação JWT
- PostgreSQL

---

## 📁 Estrutura do Projeto

```
rideufc/
├── frontend/          # App Android (Kotlin + Jetpack Compose)
│   └── app/src/main/
│       ├── data/      # Repositórios, datasources, Room
│       ├── ui/        # Screens, ViewModels, Components, Theme
│       └── utils/     # Constantes e funções auxiliares
├── backend/           # API REST (Java + Spring Boot)
│   └── src/main/java/
│       ├── auth/      # Módulo de autenticação
│       ├── user/      # Módulo de usuários
│       ├── ride/      # Módulo de caronas
│       └── rating/    # Módulo de avaliações
└── docs/              # Documentação do projeto
```

---

## 🚀 Como Executar

### Pré-requisitos
- Java 17+
- Android Studio Hedgehog ou superior
- PostgreSQL 15+

### Back-end
```bash
cd backend
./mvnw spring-boot:run
```

### Front-end
Abra a pasta `frontend/` no Android Studio e execute no emulador ou dispositivo físico.

---

## 📅 Sprints

| Sprint | Período | Foco |
|--------|---------|------|
| Sprint 1 | 18/05 – 01/06 | Cadastro, Login, Publicação e Busca de Caronas |
| Sprint 2 | 01/06 – 15/06 | Solicitação, Avaliação, Perfil de Usuário |
| Sprint 3 | 15/06 – 28/06 | Notificações Push, ajustes e validação |
| Apresentação | 29/06 – 06/07 | Apresentação final |

---

## 📜 Licença

Este projeto é desenvolvido para fins acadêmicos na UFC Campus Quixadá.

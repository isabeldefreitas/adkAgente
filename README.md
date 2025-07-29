# 🤖 myC3PO - Agente Inteligente com ADK

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Python](https://img.shields.io/badge/python-3.10+-blue)

Este projeto é uma implementação de um agente inteligente desenvolvido com base no **ADK (Agent Development Kit)**, seguindo como guia o vídeo:  
📺 **[Crie um Agente de IA com o Google ADK em 5 Minutos!](https://youtu.be/NkIZgBvA6G4?si=GlTcgD_8aA2JjBDy)**

O agente foi apelidado de **myC3PO** — uma homenagem ao droide de protocolo de Star Wars 🤖✨.

---

## 🧠 Descrição do Projeto

O agente **myC3PO** foi criado para:

- Simular percepções e ações em um ambiente controlado;
- Tomar decisões com base em lógica ou regras;
- Servir como experimento para estudar agentes autônomos simples com Python.

Características:

- Arquitetura modular;
- Uso de `.env` para configuração;
- Projeto gerenciado com `pyproject.toml` e o gerenciador de pacotes `uv`.

---

## 📁 Estrutura do Projeto

```bash
📦myc3po
 ┣ 📂myc3po
 ┃ ┣ 📜.env               # Variáveis de ambiente
 ┃ ┣ 📜__init__.py        # Inicialização do pacote
 ┃ ┗ 📜agent.py           # Código principal do agente
 ┣ 📜.gitignore           # Ignora arquivos sensíveis
 ┣ 📜.python-version      # Versão Python usada
 ┣ 📜pyproject.toml       # Gerenciador de dependências
 ┗ 📜uv.lock              # Lockfile do uv

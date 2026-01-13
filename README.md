# PostGIS + PostgreSQL em Container

## 📌 Visão Geral

Este projeto fornece uma **aplicação de banco de dados PostgreSQL com extensão PostGIS**, executando em **container** para **provisionamento rápido e padronizado de infraestrutura de dados geoespaciais**.

A solução utiliza a **imagem oficial do PostGIS/PostgreSQL**, amplamente adotada e mantida pela comunidade, garantindo compatibilidade, segurança e facilidade de manutenção.

O foco do projeto é atender cenários de:
- Ambientes de **desenvolvimento**
- **Homologação**
- Laboratórios técnicos
- Infraestrutura inicial para produção (com ajustes adicionais)

---

## 🧱 Tecnologias Utilizadas

- **PostgreSQL** – Banco de dados relacional
- **PostGIS** – Extensão geoespacial para PostgreSQL
- **Docker / Docker Compose** – Orquestração de containers
- **Podman / Podman Compose** – Alternativa rootless e compatível com Docker

---

## 🚀 Objetivo do Projeto

Padronizar e simplificar o **setup de um banco de dados geoespacial**, reduzindo o tempo de provisionamento e eliminando dependências diretas no sistema operacional do host.

Com poucos comandos, é possível subir um ambiente funcional de PostGIS pronto para uso.

---

## ⚙️ Variáveis de Ambiente

As variáveis sensíveis **não devem ser versionadas**.

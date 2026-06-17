# 🧠 Arquitetura da Solução

## 📌 Visão Geral

A solução utiliza o SharePoint como plataforma principal para armazenamento e recuperação de documentos, aproveitando seus recursos nativos de indexação e busca.

---

## 🏗️ Componentes

### 📁 Armazenamento
- Bibliotecas de documentos no SharePoint
- Integração com Microsoft Teams

### 🏷️ Metadados
Cada documento possui atributos estruturados:
- Autor
- Tipo de documento
- Área
- Data de modificação

### 🔍 Busca
- Indexação automática do SharePoint
- Busca por palavras-chave
- Filtros aplicados via interface

---

## 🔄 Fluxo da Informação

Upload do documento → Classificação com metadados → Indexação automática → Busca → Acesso ao documento

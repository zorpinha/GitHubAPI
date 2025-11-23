# 📌 MVP - [Nome do Projeto]

## 🎯 Objetivo do MVP
Este repositório documenta o **Sprint 1 de 2025**, cujo objetivo foi **coletar, tratar e analisar dados estratégicos sobre o mercado de importação de smartphones no Brasil**, com base em informações oficiais e visualizações no Power BI.  

---

## 📝 Descrição da Solução

## 🧩 Etapa 1 — Conversão e Tratamento de Dados  


Após o download dos arquivos brutos do **Comex Stat**, foi desenvolvido um **código flexível no Google Colab** para realizar:  
- A **leitura automática** dos arquivos CSV originais;  
- A **transcrição e padronização** dos campos;  
- A **junção dos anos de 2021 a 2025** em uma única base consolidada.  

🔹 **Objetivo:** estruturar uma base limpa e pronta para análise no Power BI.  


📦 **Fontes de dados:**  
- [Comex Stat — Portal Oficial](https://comexstat.mdic.gov.br/pt/home)  
- [Arquivo Google Colab (.zip)](https://github.com/user-attachments/files/22854187/Conversao.de.dados.zip)

  


---

## 📈 Etapa 2 — Montagem do Dashboard no Power BI  

Com a base tratada, o dashboard foi desenvolvido em **quatro páginas** que representam diferentes perspectivas da análise de importação automotiva no Brasil.  

Atualmente, o projeto encontra-se em **fase de protótipo visual**.


---


## 👥 Personas / Usuários-Alvo
- Marcos: Analise do mercado de exportações do fundo do vale.  
---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| Marcos | Uma visualização e tratamento dos dados de exportação.         | Alta       | 5 pontos   |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 1  | Relatório do backlog	 | Concluído |
| 2  | Verificar qual orientador e se o Coorientador está correto | Concluído |
| 3 | tradução dos arquivos de exportação	 | Concluído |
| 4 | Mindset digital a ser definido no final do projeto, mas atualmente entender como podemos definir  | Concluído |
| 5  | Download Dos Arquivos de Exportação	 | Concluído |
| 6 | Junção dos arquivos de Exportação	 | Concluído |
| 7 | Construção do PoweBI   | Concluído |
| 8 | Analisar os dados e todas as planilhas de exportação | Concluído |
| 9 | Atualizarmos sobre o projeto e objetivo do Projeto | Concluído |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário execute o backlog de produto do cliente.
- O sistema deve registrar um Dashboard inicial.
- Métricas coletadas: Exportação e Importação.

---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP: 2
- Feedback qualitativo: Positivo

---

## 🚀 Próximos Passos
- Melhorias solicitadas pelo cliente
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências

<details>
<summary>📷 Visualizar prévia do código no Google Colab</summary>

![Prévia do Colab](https://github.com/user-attachments/assets/14d03e36-9278-4439-83b1-43bdd5cf1eeb)

</details>

<details> 
  <summary> Veja mais do DashBoard </summary>

### 🟦 1ª Página — Visão Geral  
Resumo dos principais indicadores de desempenho, incluindo **volume total importado**, **valor FOB** e **preço médio por KG**.  

<img width="1316" height="738" alt="Dashboard página 1" src="https://github.com/user-attachments/assets/b6440b81-c60f-431a-a3bd-9cba9b2d283b" />

---

### 🟧 2ª Página — Análise Temporal  
Visualização da **evolução mensal e anual das importações**, permitindo identificar tendências e sazonalidades.  

<img width="1317" height="740" alt="Dashboard página 2" src="https://github.com/user-attachments/assets/1355b33a-8adf-4325-9a8f-faa7c550a22f" />

---

### 🟨 3ª Página — Produtos e Categorias  
Análise detalhada por **NCM e descrição de produto**, com ranking dos **10 itens mais importados**.  

<img width="1315" height="741" alt="Dashboard página 3" src="https://github.com/user-attachments/assets/738f7695-90ec-4bd7-9fbd-69ace1ea1b97" />

---

### 🟩 4ª Página — Distribuição Geográfica  
Mapa interativo exibindo a **origem das importações por país**, destacando os **principais parceiros comerciais**.  

<img width="1315" height="736" alt="Dashboard página 4" src="https://github.com/user-attachments/assets/362b3a87-7dd3-45a7-8207-02fd3ac1cda5" />

</details>

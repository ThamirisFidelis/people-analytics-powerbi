# 📊 Dashboard de People Analytics (Power BI)

Este projeto consiste em um dashboard analítico focado em Recursos Humanos (People Analytics), projetado para apoiar a tomada de decisões estratégicas de lideranças e gestores de departamento. 

O painel apresenta indicadores críticos de movimentação de pessoal, distribuição demográfica e taxas de rotatividade.

---

## 🖥️ Visualização do Dashboard

### Página 1: Painel de Indicadores
*(Substitua esta linha pela sua imagem após o upload)*
![Dashboard de People Analytics](images/dashboard.png)

### Página 2: Documentação e Arquitetura do Projeto
*(Substitua esta linha pela sua imagem após o upload)*
![Documentação do Projeto](images/documentacao.png)

---

## 🛠️ Tecnologias e Técnicas Utilizadas

*   **Ferramenta Principal:** Microsoft Power BI Desktop
*   **Modelagem de Dados:** Arquitetura Star Schema (Estrela) com tabelas Fato (`fFuncionarios`) e Dimensões (`dCargosDepartamentos`, `dCalendario`).
*   **Tratamento de Dados (ETL):** Power Query (M) para limpeza de nulos, transformação de faixas etárias e estruturação de colunas de apoio.
*   **Linguagem DAX (Medidas Principais):**
    *   **Saldo Acumulado de Ativos (Headcount):** Utilização de `REMOVEFILTERS` para criar uma curva temporal acumulada real, desvinculada das flutuações das datas de admissão.
    *   **Taxa de Turnover (%):** Cálculo dinâmico de rotatividade mensal e anual.
*   **UX/UI Design:** Aplicação de paleta de cores corporativa neutra, cartões flutuantes com sombras suaves para alívio visual e menus interativos de segmentação (filtros por Ano e Gênero).

---

## 📁 Estrutura do Repositório

*   `/images`: Capturas de tela utilizadas na documentação.
*   `Dashboard_People_Analytics.pbix`: Arquivo original do Power BI para download e análise.
*   `Dashboard_People_Analytics.pdf`: Versão estática exportada para visualização direta.

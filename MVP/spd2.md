<h1>ㅤㅤㅤㅤㅤMVP Sprint 2 - API 1º Semestre Logística</h1>

--- 

<h2> 🎯 Objetivo do MVP:  </h2>
  <h3> Requisitos Funcionais:</h3>
    - Base de dados integrada, limpa e funcional. </br> 
    - Construção entre a base de dados NCM e SH4. </br> 
    - Dashboard: Melhoria do desing e identidade de layout do projeto. </br> 
    - Repositório: Atualização do repositório remoto (GitHub) E versionamento da documentação da Sprint 2. </br> 

---

<h2> 🏹 Tasks: </h2>
  <h3> 1ª Fase: A Base (Leonardo/Nikolas)</h3>
    • Expansão da Base de Dados (Python): Mudar o código para buscar dados de toda a Região Metropolitana (RMVP) e do Estado de SP, não apenas SJC. Sem isso, não existe o "Comparador".
    • Cruzamento NCM x SH4 (O "Tradutor"): Unir as tabelas de códigos com os nomes reais dos produtos e categorias (Manufaturados vs. Commodities). Isso é o que vai permitir criar filtros que as pessoas entendam.
  <h3> 2ª Fase: A Estrutura (Rodrigo/Victor)</h3>
    • Criação do Menu Lateral e Novas Páginas: Criar o sistema de botões para navegar entre "Resumo", "Comparativo de Cidades" e "Produtos".
    • Configuração dos Filtros Globais: Colocar o filtro de cidade e o filtro de período (meses/anos) que funcione em todas as telas ao mesmo tempo.
  <h3> 3ª Fase: A Inteligência (Kauan/Nikolas)</h3>
    • Módulo de Benchmarking (O Comparador): Criar o mapa interativo de SP e a tabela que coloca SJC ao lado de outras cidades para ver quem vende mais.
    • Cálculo de Valor Agregado: Criar a conta de "Preço por Tonelada" no Power BI para identificar quais produtos são mais valiosos.
    • Visão de Modais e Parceiros: Adicionar os gráficos que mostram por onde a carga sai (avião, navio, caminhão) e para quais países ela vai.
  <h3> 4ª Fase: O Acabamento (Willian)</h3>
    • Revisão de Design e Textos: Checar se as fontes estão legíveis e se os botões funcionam bem.
    • Teste de Responsividade: Garantir que o dashboard abra e funcione bem em telas de tamanhos diferentes, como celulares ou tablets.

---
    
<h2> 🔑 User Stories (Backlog do MVP) </h2>
 
| ID | User Story | Prioridade | Estimativa (Story Points) |
| :--- | :--- | :--- | :--- |
| US1 | Como analista de mercado, quero visualizar os principais países parceiros das cidades selecionadas para compreender o alcance global da logística local. | Alta 🔴 | 5 pontos |
| US2 | Como analista de dados, quero extrair e limpar as bases brutas do MDIC via Python para garantir a confiabilidade dos dados que alimentarão o sistema. | Média 🟡 | 3 pontos |
| US3 | Como gestor de estratégia comercial, quero analisar o preço médio por KG para identificar categorias de maior valor agregado. | Média 🟡 | 3 pontos |
| US4 | Como diretor de desenvolvimento economico, quero que o processamento em Python normalize os dados por setor industrial para sustentar métricas precisas. | Baixa 🟢 | 2 pontos |
| US5 | Como analista de comércio exterior, quero cruzar o volume exportado com a via de transporte para identificar necessidades de infraestrutura regional. | Alta 🔴 | 5 pontos |

---

<h2> 🗃️ Evidências: </h2>

<img width="1733" height="824" alt="image" src="https://github.com/user-attachments/assets/6f9adba7-b54f-49f3-8fd2-ab0588b75558" />




<h2 align="center">
  <a href="https://drive.google.com/file/d/1nMSy1DpSXaL_urXNzNYKMKVrDCKx1xe7/view?usp=sharing">Link para o arquivo - 🗃️</a>
</h2>

<h2 align="center">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiNGQxZjY5MjEtNjY2MS00ZGE3LWI1OTItNjI2NWFkNTIwYzZjIiwidCI6ImVhYmU2NGM1LTY4ZjUtNGE3Ni04MzAxLTk1NzdhNjc5ZTQ0OSIsImMiOjR9">Link para o dashboard - 🗃️</a>
</h2>

---

<h2> 💡 Funcionalidades desenvolvidas: </h2>

- Mapa para melhor seleção dos países que mais contribuíram com a exportação e importação dos municípios
- Filtros do tipo: Pais, Munícipio, SH4, Ano, Trimestre e Mês.
- Indicadores como: FOB/KG, FOB ($) e KG LIQ. 

<h2> 🚩 Pontos de melhoria: </h2>

- Adicionar mais munícipios.
- Mais meios de interagir com o dashboard como: Novos filtros
- Aumentar a escala dos dados.


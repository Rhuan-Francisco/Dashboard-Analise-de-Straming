# 📊 Dashboard Power BI – Análise de Plataformas de Streaming

## 📖 Sobre o projeto

Este projeto foi desenvolvido no **Power BI** utilizando um **dataset fictício de serviços de streaming**, criado para simular um cenário próximo ao mercado real.

O objetivo foi construir um dashboard analítico capaz de transformar dados em informações estratégicas, auxiliando na identificação de oportunidades de investimento em novos conteúdos. A análise considera indicadores de avaliação, popularidade, engajamento e tendência, permitindo comparar diferentes plataformas, países, gêneros e períodos de lançamento.

---

## 🎯 Objetivo

Responder perguntas de negócio como:

* Quais países produzem os conteúdos mais bem avaliados?
* Quais gêneros apresentam maior potencial de investimento?
* Existe relação entre popularidade e tendência?
* Conteúdos mais longos tendem a gerar maior engajamento?
* Como os indicadores variam entre plataformas de streaming?

---

## 🖥️ Dashboard

> **📷 Coloque aqui o print do dashboard**

---

## 📈 Principais indicadores

O dashboard apresenta os seguintes KPIs:

* 📚 Total de conteúdos disponíveis;
* ⭐ Nota média dos conteúdos;
* 👥 Índice médio de engajamento;
* 🔥 Índice médio de tendência.

---

## 📊 Análises desenvolvidas

Além dos KPIs, o dashboard permite visualizar:

* 🌍 Nota média por país de origem;
* 🎭 Ranking dos gêneros mais populares;
* ⏱️ Comparativo entre faixas de duração, apresentando a nota média e o índice de popularidade de cada grupo;
* 📉 Evolução temporal da **Popularidade × Tendência**, possibilitando identificar se conteúdos populares permanecem em evidência ao longo do tempo.

---

## 🎛️ Filtros interativos

Para tornar a análise mais dinâmica, o dashboard conta com segmentações que permitem filtrar os dados por:

* 📅 Ano de lançamento;
* 🎬 Tipo de conteúdo (Filme ou Série);
* 📺 Plataforma de streaming;
* 🎭 Gênero.

Todos os gráficos e indicadores são atualizados automaticamente conforme os filtros selecionados, proporcionando uma análise personalizada.

---

## 💡 Principais insights que podem ser obtidos

Com este dashboard é possível identificar:

* Os países com maior média de avaliação;
* Os gêneros mais populares;
* As plataformas com melhor desempenho em diferentes indicadores;
* A relação entre engajamento, popularidade e tendência;
* O impacto da duração dos conteúdos na avaliação e na popularidade.

---

## 🛠️ Tecnologias utilizadas

* 📊 Power BI
* 📂 Power Query
* 📈 Modelagem de Dados
* 📐 DAX
* 📋 Storytelling com Dados

---

## 🗂️ Dicionário de Dados

| Coluna               | Descrição                                                                           |
| -------------------- | ----------------------------------------------------------------------------------- |
| **content_id**       | Identificador único de cada filme ou série.                                         |
| **title**            | Nome do filme ou série.                                                             |
| **type**             | Tipo de conteúdo (Filme ou Série).                                                  |
| **genre**            | Gênero principal do conteúdo.                                                       |
| **platform**         | Plataforma de streaming onde o conteúdo está disponível.                            |
| **country**          | País de origem da produção.                                                         |
| **language**         | Idioma original do conteúdo.                                                        |
| **release_year**     | Ano de lançamento.                                                                  |
| **duration_minutes** | Duração do conteúdo em minutos.                                                     |
| **rating**           | Nota média atribuída pelos usuários (escala semelhante ao IMDb).                    |
| **votes**            | Quantidade de avaliações recebidas.                                                 |
| **weighted_rating**  | Nota ponderada considerando a média das avaliações e o número de votos.             |
| **engagement_score** | Índice de engajamento baseado na duração do conteúdo e na quantidade de avaliações. |
| **popularity_score** | Índice de popularidade calculado a partir da nota e do número de avaliações.        |
| **trending_score**   | Indicador que representa o nível de tendência do conteúdo no momento.               |

---

## 🚀 Conclusão

Este projeto demonstra a aplicação de conceitos de análise de dados e Business Intelligence na construção de um dashboard interativo, transformando dados em informações estratégicas para apoiar decisões relacionadas ao mercado de streaming. Além de explorar técnicas de visualização de dados, o projeto evidencia a importância da escolha de indicadores relevantes para facilitar a interpretação e a geração de insights.

# 🏠 Dashboard Imobiliária – Power BI + Python

Este projeto foi desenvolvido como parte de um **desafio de criação de dashboard** com base em **dados comerciais de uma imobiliária**. O objetivo principal foi simular um ambiente de dados reais para análise de desempenho de vendas, conversões e canais de aquisição de leads.

---

## 📌 Tecnologias Utilizadas

* [x] Power BI (visualização interativa)
* [x] Python com Pandas e NumPy (tratamento e simulação de dados)
* [x] Google Colab (ambiente de desenvolvimento)
* [x] Faker (geração de dados fictícios)
* [x] OpenPyXL (exportação para Excel)

---

## ⚙️ Etapas do Desenvolvimento

1. **Importação e instalação de bibliotecas**

   * Instalação no Colab com `pip install pandas faker openpyxl`
   * Obs: O erro `@title` é específico de células do Colab e não deve ser usado fora de lá — o correto é iniciar o código com `!pip install ...` quando necessário.

2. **Simulação e tratamento de dados**

   * Criação de hierarquia (diretoria → líder → corretor)
   * Geração de leads com datas, canais, conversão, comissão, motivo de não conversão etc.

3. **Exportação dos dados**

   * Exportação do dataset completo e vendas confirmadas para `.xlsx`
   * Automatização da geração dos arquivos

4. **Construção do dashboard no Power BI**

   * Análise de taxa de conversão, desempenho por corretor e tempo de fechamento
   * Filtros interativos por canal, diretoria e período

---

## 🧠 Aprendizados

* Criação de datasets realistas com o Faker
* Uso de lógica condicional para simular jornadas de clientes
* Automatização da exportação de dados tratados
* Conexão e modelagem de dados no Power BI para visualização dinâmica

---

## 📁 Arquivos Disponíveis

* `vendas_imobiliaria_jan_mai_2025.xlsx`: Base completa simulada
* `vendas_confirmadas_jan_mai_2025.xlsx`: Vendas com imóveis realmente negociados
* Link com gerador: [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I326blx4Y7mrByMXLPznqrW5qrEDlR2k?usp=sharing)
* `dashboard.pbix`: Arquivo do Power BI com o dashboard interativo

---

## 📊 Resultado Final

O dashboard foi projetado para fornecer **insights estratégicos sobre a performance comercial da imobiliária**, com foco em:

* Conversões por canal
* Performance por corretor
* Tempo médio de fechamento
* Receita e comissionamento



# 📊 Análise de Vendas - Olist

Este projeto tem como objetivo realizar uma análise exploratória dos dados de vendas da empresa **Olist**, utilizando Python, Pandas, Matplotlib e outras ferramentas de análise de dados.

---

## 📁 Sobre o Projeto

A Olist é uma plataforma que conecta pequenos lojistas a grandes marketplaces. O conjunto de dados foi disponibilizado publicamente no [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), e traz informações reais sobre transações de e-commerce no Brasil.

Este projeto busca responder perguntas de negócio e extrair insights valiosos a partir dos dados.

---

## 🎯 Objetivos da Análise

- Calcular a porcentagem de pedidos com atraso.
- Analisar o tempo médio, mínimo e máximo de entrega.
- Verificar a distribuição de vendas por mês.
- Identificar os meios de pagamento mais utilizados.
- Verificar a média de avaliação (review score) para pedidos com e sem atraso.
- Criar gráficos e relatórios visuais com os resultados.

---

## 🧰 Tecnologias Utilizadas

- Python 3
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook
- Git e GitHub
- Git LFS (para arquivos CSV grandes)

---

## 📦 Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/diegojlfigueredo/analise-olist.git
   ```

2. Navegue até a pasta do projeto:
   ```bash
   cd analise-olist
   ```

3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## 📈 Resultados

Os principais insights extraídos da análise incluem:

- **7,87%** dos pedidos foram entregues com atraso.
- O **tempo médio de entrega** foi de **12 dias**, com mínimo de **0** e máximo de **209 dias**.
- A forma de pagamento mais usada foi **cartão de crédito**, seguida por **boleto**.
- Clientes que tiveram pedidos **sem atraso** avaliaram melhor (média de **4,21**) do que aqueles com pedidos **atrasados** (média de **2,56**).

Mais detalhes podem ser visualizados no arquivo: [`relatorio_olist.md`](relatorio_olist.md)

---

## 👤 Autor

**Diego J. L. Figueredo**  
Estudante de Análise de Dados e Python  
[LinkedIn](https://www.linkedin.com/in/diego-juliano-lima-figueredo-7112816a/)  
[GitHub](https://github.com/diegojlfigueredo)

---

## 📜 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e compartilhar com os devidos créditos.

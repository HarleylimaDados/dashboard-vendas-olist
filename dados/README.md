# Dados

O dashboard usa o **[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)**, publicado pela Olist no Kaggle. São dados reais e anonimizados de ~100 mil pedidos feitos entre 2016 e 2018.

Os CSVs **não estão neste repositório** por causa do tamanho (~120 MB). O arquivo `.pbix` já contém os dados importados, então não é preciso baixá-los só para visualizar o dashboard.

## Para refazer o tratamento do zero

1. Baixe o dataset no link acima e descompacte.
2. Coloque os 9 arquivos `.csv` nesta pasta (`dados/`):
   - `olist_customers_dataset.csv`
   - `olist_geolocation_dataset.csv`
   - `olist_order_items_dataset.csv`
   - `olist_order_payments_dataset.csv`
   - `olist_order_reviews_dataset.csv`
   - `olist_orders_dataset.csv`
   - `olist_products_dataset.csv`
   - `olist_sellers_dataset.csv`
   - `product_category_name_translation.csv`
3. No Power BI Desktop, em **Arquivo → Opções → Arquivo atual → Configurações regionais**, deixe a localidade como **Inglês (Estados Unidos)**. Os CSVs usam ponto como separador decimal.
4. Em **Transformar dados → Configurações da fonte de dados**, aponte as fontes para a sua pasta.

Licença e termos de uso: ver a página do dataset no Kaggle.

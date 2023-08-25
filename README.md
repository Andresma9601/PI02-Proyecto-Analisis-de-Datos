# # Análisis de Datos de Criptomonedas

Este repositorio contiene scripts y funciones en Python para recopilar, analizar y visualizar datos de criptomonedas utilizando la API CoinGecko.

## Descripción de los Códigos

### Recopilación de Datos

- `get_coin_list(coins_ids)`: Obtiene detalles de una lista de monedas específicas.
- `get_coin_price_min(coins_ids, vs_currency, years)`: Obtiene los precios mínimos de monedas en un período.
- Otras funciones para obtener datos de mercado, categorías, volúmenes, etc.

### Análisis y Combinación

- `get_platform(coin_ids)`: Obtiene información sobre las plataformas asociadas con las monedas.
- `get_development(coin_ids)`: Obtiene datos de desarrollo relacionados con las monedas.
- `get_links(coin_ids)`: Obtiene enlaces relacionados con las monedas.
- `get_defi_info(coin_ids)`: Obtiene información DeFi relacionada con las monedas.
- `get_adoption(coin_ids)`: Obtiene datos de adopción relacionados con las monedas.
- `get_max_supply(coin_ids)`: Obtiene datos de la cantidad máxima de suministro de las monedas.
- `get_ranks(coin_ids)`: Obtiene el rango de mercado de las monedas.
- `get_market_caps(coin_ids, days)`: Obtiene las capitalizaciones de mercado de las monedas en un período.
- `get_volume(coin_ids, days)`: Obtiene los volúmenes de las monedas en un período.
- `get_coin_market_data(ids, vs_currency)`: Obtiene datos de mercado de las monedas.

## Combinación de Datos

- Uso de las funciones `merge` y `concat` para combinar DataFrames con diferentes atributos.
- Ejemplos de cómo las funciones de combinación se utilizan para un análisis más completo.

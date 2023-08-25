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

# Variables en el DataFrame Resultante

A continuación se presenta una descripción de las variables presentes en el DataFrame resultante:

1. `id_x`: ID único de la criptomoneda.
2. `symbol_x`: Símbolo de la criptomoneda.
3. `name_x`: Nombre de la criptomoneda.
4. `coin_id`: ID de la criptomoneda.
5. `adoption`: Porcentaje de adopción de la criptomoneda.
6. `Max Supply`: Cantidad máxima de suministro de la criptomoneda.
7. `Rank`: Clasificación de la criptomoneda en términos de capitalización de mercado.
8. `market_cap_x`: Capitalización de mercado de la criptomoneda.
9. `volume`: Volumen de transacciones de la criptomoneda.
10. `id`: ID único de la criptomoneda.
11. `image`: URL de la imagen de la criptomoneda.
12. `current_price`: Precio actual de la criptomoneda.
13. `market_cap_rank`: Clasificación de la criptomoneda en términos de capitalización de mercado.
14. `fully_diluted_valuation`: Valoración completamente diluida de la criptomoneda.
15. `total_volume`: Volumen total de transacciones de la criptomoneda.
16. `high_24h`: Precio más alto en las últimas 24 horas.
17. `low_24h`: Precio más bajo en las últimas 24 horas.
18. `price_change_24h`: Cambio de precio en las últimas 24 horas.
19. `price_change_percentage_24h`: Cambio de precio en porcentaje en las últimas 24 horas.
20. `market_cap_change_24h`: Cambio en la capitalización de mercado en las últimas 24 horas.
21. `market_cap_change_percentage_24h`: Cambio en la capitalización de mercado en porcentaje en las últimas 24 horas.
22. `circulating_supply`: Suministro circulante de la criptomoneda.
23. `total_supply`: Suministro total de la criptomoneda.
24. `max_price`: Precio máximo histórico de la criptomoneda.
25. `ath_change_percentage`: Cambio porcentual desde el precio máximo histórico (ATH).
26. `ath_date`: Fecha del precio máximo histórico.
27. `min_price`: Precio mínimo histórico de la criptomoneda.
28. `atl_change_percentage`: Cambio porcentual desde el precio mínimo histórico (ATL).
29. `atl_date`: Fecha del precio mínimo histórico.
30. `last_updated`: Fecha y hora de la última actualización de datos.
31. `forks`: Número de forks del repositorio de código de la criptomoneda.
32. `stars`: Número de estrellas del repositorio de código de


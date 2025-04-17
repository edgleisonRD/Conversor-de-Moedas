# Conversor-de-Moedas
Este projeto é um Conversor de Moedas em Java, que consome dados da API ExchangeRate para obter taxas de câmbio em tempo real. Ele foi desenvolvido utilizando boas práticas de separação de responsabilidades, com classes dedicadas para requisições HTTP, manipulação de JSON e armazenamento de dados.
A aplicação faz uma requisição à API para buscar taxas de câmbio com base no dólar americano (USD) e salva os valores obtidos em um arquivo exchange_rates.json, permitindo consultas futuras.
Objetivos:
Consumir uma API externa de conversão de moedas.
Processar os dados usando Gson para manipulação de JSON.
Organizar o código de forma modular, utilizando record e boas práticas de design.


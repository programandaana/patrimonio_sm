# Scrollytelling – Guia de Unidades de Conservação Estaduais do Pará

Visualização em narrativa (*scrollytelling*) das Unidades de Conservação (UCs) Estaduais do Pará. Ao rolar a página, os cartões são ativados em ordem cronológica e o mapa centraliza a UC correspondente.

![Demonstração](demo.gif)

## Funcionalidades

* Integra GeoJSON (polígonos) e CSV (metadados).
* Ordenação pela data de criação da UC.
* Cartões com Nome, Ato de Criação, Data, Resumo e Link.
* Mapa Leaflet destacando a UC ativa.
* Layout responsivo.

## Estrutura dos dados

* `unidades_estaduais_para.geojson` — polígonos das UCs (`name`).
* `unidades_conservacao_resumo_conciso.csv` — `Nome`, `Ato de Criação`, `Data de Criação` (DD/MM/AAAA), `Link`, `ResumoBreve`.

## Tecnologias

Leaflet, IntersectionObserver API, HTML/CSS/JS.

## Como executar

Acesse: **[https://ngeo-ideflor-bio.github.io/guia-uc-para/](https://ngeo-ideflor-bio.github.io/guia-uc-para/)**

## Observações

* A ordenação depende de datas válidas no formato DD/MM/AAAA.
* Nomes no GeoJSON/CSV devem coincidir para a junção.

## Licença

MIT.
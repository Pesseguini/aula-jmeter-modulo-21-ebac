# Teste de Desempenho - Módulo 21 (EBAC)

Repositório dedicado à entrega do exercício de Teste de Performance utilizando **JMeter** e **BlazeMeter**, aplicando massa de dados parametrizada.

## 🚀 Cenário do Teste
* **Aplicação Alvo:** BlazeDemo (`blazedemo.com`)
* **Usuários Virtuais (VUs):** 50 VUs
* **Duração Total:** 10 minutos (600 segundos)
* **Ramp-up:** 3 minutos (180 segundos)
* **Massa de Dados:** Parametrização via arquivo CSV (`dados-blaze-demor.csv`) com 11 colunas mapeadas.

## 📊 Resultados e Evidências
O teste foi executado com sucesso na nuvem via BlazeMeter, atingindo os seguintes indicadores:
* **Taxa de Erro:** 0.00% (100% de sucesso nas requisições)
* **Tempo Médio de Resposta:** 225.45 ms
* **Percentil 90 (90%th):** 265 ms

### Prints de Execução
Summary
<img width="1334" height="504" alt="image" src="https://github.com/user-attachments/assets/3239315d-ecc2-40fe-9b62-5d2f7dd9b1bd" />

Request Stats
<img width="1341" height="506" alt="image" src="https://github.com/user-attachments/assets/e9c46617-1b8e-4f2a-9f4a-6cbbf4f7700e" />

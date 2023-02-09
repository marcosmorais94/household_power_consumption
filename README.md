![power-tower-power-line-tower-transmission-tower](https://user-images.githubusercontent.com/91103250/217671409-f9085cc4-0cf8-4381-bfdb-3347e2d576b2.jpg)


# Análise Preditiva - Consumo de Energia Elétrica
Este repositório tem objetivo o uso de aprendizagem não supervisionada para identificar clusters em uma base relacionada ao consumo doméstico de energia elétrica em um período de 4 anos. Os dados foram coletados entre Dez/2006 e Nov/2010 (total de 47 meses) de uma casa localizada em Sceaux, França.

Fonte dos dados: https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption

### Dicionário de Dados

| Atributo  | Descrição | Métrica |
| ------------- | ------------- | ------------- |
| date | Data que foi coletada a amostra  | dd/mm/yyyy |
| time |  Hora que foi coletada a amostra | hh:mm:ss |
| global_active_power |  potência ativa média global por minuto | Quilowatt |
| global_reactive_power | potência reativa média global por minuto  | Quilowatt |
| voltage | tensão média por minuto  | volt |
| global_intensity | intensidade atual média global por minuto  | ampere |
| sub_metering_1 |  Corresponde à cozinha, contendo principalmente uma máquina de lavar louça, um forno e um micro-ondas (as placas eléctricas não são eléctricas, mas sim a gás). | Quilowatt-hora |
| sub_metering_2 | Corresponde à lavanderia, contendo máquina de lavar, secadora, geladeira e luminária. | Quilowatt-hora |
| sub_metering_3 |  Corresponde a um aquecedor eléctrico e um ar condicionado. | Quilowatt-hora |

| | |
| ------------- | ------------- |
| Total de Registros | 2.075.259  |
| Total de Atributos | 9  |

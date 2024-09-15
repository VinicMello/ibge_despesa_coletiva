## **Machine Learning e Visão Computacional**

### [IBGE - Despesa Coletiva](https://basedosdados.org/dataset/a1b6d2b6-4aa6-47e7-a517-8a21b28b7254?table=6f548e6a-5649-4ee3-bb0d-a46ca8efd4b6)

## Documentação Base de Dados

### Campo: sigla_uf
- **Tipo**: string
- **Descricao**: Sigla da Unidade da Federação.

### Campo: situacao
- **Tipo**: int64
- **Descricao**: Situação do Domicílio.

### Campo: id_estrato
- **Tipo**: int64
- **Descricao**: Identificador dos estratos do plano amostral da pesquisa.

### Campo: id_unidade_primaria_amostragem
- **Tipo**: int64
- **Descricao**: Código da Unidade Primária de Amostragem.

### Campo: id_domicilio
- **Tipo**: int64
- **Descricao**: Identificador do Domicílio.

### Campo: id_unidade_consumo
- **Tipo**: int64
- **Descricao**: Identificador da Unidade de Consumo.

### Campo: id_quadro
- **Tipo**: int64
- **Descricao**: Número do quadro que o item de despesa/aquisição foi registrado.

### Campo: id_codigo_5_bd
- **Tipo**: int64
- **Descricao**: Código de 5 dígitos do item.

### Campo: id_codigo_7_bd
- **Tipo**: int64
- **Descricao**: Código de 7 dígitos do item.

### Campo: V9001
- **Tipo**: int64
- **Descricao**: Código do tipo de despesa/aquisição.

### Campo: V9002
- **Tipo**: int64
- **Descricao**: Forma de aquisição.

### Campo: V9004
- **Tipo**: float64
- **Descricao**: Código do local de aquisição.

### Campo: V9005
- **Tipo**: float64
- **Descricao**: Quantidade final consumida em kwh, apenas para o item energia elétrica.

### Campo: V9010
- **Tipo**: float64
- **Descricao**: Último mês que a respectiva despesa/aquisição foi realizada pela Unidade de Consumo, no período de referência.

### Campo: V9011
- **Tipo**: float64
- **Descricao**: Número de meses que a despesa/aquisição foi realizada pela Unidade de Consumo, no período de referência.

### Campo: V9012
- **Tipo**: float64
- **Descricao**: Estado do produto adquirido pela Unidade de Consumo, no período de referência.

### Campo: V1905
- **Tipo**: float64
- **Descricao**: Tipo de serviço doméstico contratado pela Unidade de Consumo, no período de referência.

### Campo: indicador_imputacao_valor
- **Tipo**: int64
- **Descricao**: Indica se o valor da despesa/aquisição foi imputado.

### Campo: indicador_imputacao_qtd
- **Tipo**: float64
- **Descricao**: Indica se a quantidade consumida em kwh foi imputada.

### Campo: fator_anualizacao
- **Tipo**: int64
- **Descricao**: Número utilizado para anualizar as despesas/aquisições, em função do período de referência.

### Campo: deflator
- **Tipo**: float64
- **Descricao**: Fator de multiplicação para o tratamento do efeito inflacionário (Data de Referência - 5 de janeiro de 2018) sobre os valores monetários e não monetários.

### Campo: V8000
- **Tipo**: float64
- **Descricao**: Valor da despesa/aquisição realizada pela Unidade de Consumo no período de referência.

### Campo: V1904
- **Tipo**: float64
- **Descricao**: Valor da despesa com 'INSS e Outras Contribuições Recolhida' realizada pela Unidade de Consumo, no período de referência.

### Campo: V8000_deflacionado
- **Tipo**: float64
- **Descricao**: Valor da despesa/aquisição deflacionado (Data de Referência - 5 de janeiro de 2018).

### Campo: V1904_deflacionado
- **Tipo**: float64
- **Descricao**: Valor da despesa com 'INSS e Outras Contribuições Recolhidas' deflacionado (Data de Referência - 5 de janeiro de 2018).

### Campo: renda_total
- **Tipo**: float64
- **Descricao**: Valor do rendimento bruto total mensal da Unidade de Consumo.

### Campo: peso
- **Tipo**: float64
- **Descricao**: Fator de expansão atribuído ao domicílio pertencente a uma Unidade Primária de Amostragem.

### Campo: peso_final
- **Tipo**: float64
- **Descricao**: Fator de expansão (peso) ajustado às estimativas populacionais de 15 de janeiro de 2018, segundo cada UF e pós estratos definidos.


# hacka_carref

O objetivo neste notebook foi a comprovação da criação de modelos de propensão a compras de determinados grupos de produtos através do histórico de compras do cliente

As bases utilizadas aqui foram: EVE_BUFFER_CCI_MANU_HCKT, EVE_BUFFER_ATC_MANU_HCKT.

Utilizamos o setor de produtos em ambas tabelas para realizar a união, juntando setores similares.

Para o desenvolvimento dos modelos foi utilizado o perído de 202005 a 202007 para as variáveis explicativas e 202008 como alvo - e na validação, o período de 202006 a 202008 para as explicativas e 202009 para a captura do alvo.



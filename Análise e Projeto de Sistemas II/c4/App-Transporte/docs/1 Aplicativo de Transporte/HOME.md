# 1 Aplicativo de Transporte

![diagram](https://www.plantuml.com/plantuml/svg/0/VLNDRjj64BuRy3jCUP80sRhar5DaMOaTsAvWomXwCaQxOsK1SeVPMT9DYhvBWnoC5EYfw1FmnOfPaXBbdq8NQkVR-MQ--Tct4Z74giWF3tvotkIL9VWKOoa_JwS17uutBdwgrfLGCEmZ-NXik9YY3GvzdLTbDPs_ELhcwEFjvSKqnqWIf_CtTtFs4PsdS5mcvuS75xDVVxbTtNqyNvtTNIpUBwvEHsCzNr8GzYEJE_AH9f3Dswzi0jbj0Tqv6BGeCQ1by0nOvivWT3KVP-EjZpAGHBGS9f0j-s-ueL2xvf7LuIL73auYlkeFFbS49OjK23KrVvigPoX3yqyP7CF8O0WCN471aOqpEKKS3sEWGgF02MIBzajftrNUEFRDj-1Om29qg7JnyE3cYqGgxXQ_nT5iUVxnvfGyne1-0jciTB0xK5zBZSr1ycDPG7WT213cLsTW2OopQ9llBB0EA2ud5rWIpu1bZTxm1B9U6hXt7hrHRA88R4W4bIIGeRKho4TbP86kF0AavX8ts1bB3Ed6Ldbwnai5kbnvdHwXnhiuqhDzLY1VErOh9MldUy0yu52OT7diwtd2bRSOleomB5S1lPGSKeVDTjMs175hoiRm--410C2sVVNk_erBNhkSOEPjO6UpINPDQEBHbLgrQI5RKYXSfDH9B519rHLULNO2ezSJwGiodW2g65G0eC1zvPl7vbzAlLFc6F6UGz6sptwu3xHMAN7ZFC83hVluai3DjtHigNNEhQm8Q0ldnSM0pMFpdS4oI5UXalBzRdsgZfjai-MvnjNEKFAWR1-mRdkVWoT3NHew1fXhZxO9yps5Y65RGTclYFuhKGGtgO-1WBpXWhn5WL79GLDGcFRVopqnXkH5E7V6APNAAZl2VlF8-8NyhAfvejEYFjg1cmtpr76Ccq2YgSv2WL_9usuu0-MfQmJszNc1w88tyfnCJxkfVqxJGhISbNMws10eKIQLrTRy2IWb6PtFsFmmtfdsXYKXNtDUjwFzf7xT76c8rvItCw2bXkoQFbSa4SvMgsMVXK9It_q_95cJe1VDNq2m41Ee6vaFfoVp5x2T9a_nM_WV6gNYjwz7EwwtWcfMo-1DU6RRxkfsQWQMnFzq5vzKOZhHzt3zDdrFWRnnE5YAFMuRNuzzXrzti1xL6OVFsCBN3g76dCDmIG_f-wMgkZjn4TlrkKiocNVlwytbQfbjNNVxTnyyZE0rkFxUahVfUVyF)

**Nível 2: Diagrama de Container**

Esse diagrama apresenta os elementos internos do sistema e a forma como comunicam-se entre si. 
Em especial esse sistema possui um interface mobile para os clientes e prestadores de serviço e uma interface Web para a Empresa.
Uma API faz a comunicação entre as interfaces com os usuários, os sistemas externos e os bancos de dados que persistem os dados.

**Escopo**: Software para conectar passageiros e remetentes de pequenas encomendas com motoristas e entregadores.

**Elementos Primários**: Containers: Página Web, Aplicativo Mobile Android, API da Aplicação, Banco de dados Aplicação, Banco de dados Logs.
Elementos de Suporte: Empresa, Cliente, Prestador de Serviço, Sistema E-mail, Serviço Financeiro, API WSDenatran.

**Público Alvo**: Desenvolvedores do sistema.

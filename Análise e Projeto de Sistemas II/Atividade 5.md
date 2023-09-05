# HISTÓRIAS DE USUÁRIOS:

## Guilherme
1. Como prestador de serviço, eu gostaria de poder visualizar o valor que receberei de um serviço antes de aceitá-lo, para que possa decidir se é viável realizá-lo.<br>

    #### RF - Ordenar as solicitações de transporte por valor
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Ordenar as solicitações de transporte disponíveis por valor em ordem decrescente.|
    | Why?   | Para que o prestador de serviço possa visualizar primeiro as solicitações que oferecem um valor maior.|
    | Who?   | O prestador de serviço.|
    | When?  | Quando o prestador de serviço estiver visualizando os serviços disponíveis. |
    | Where? | No aplicativo, na pagina de selecionar um serviço, selecionando a função de ordenar por valor decrescente. |
        Descrição: Quando o prestador de serviço estiver visualizando os serviços disponíveis, ele poderá ordenar as solicitações de transporte disponíveis por valor em ordem decrescente para que possa visualizar primeiro as solicitações que oferecem um valor maior, selecionando a função de ordenar por valor decrescente, na página de selecionar um serviço.

    #### RN - Ordenar solicitações de transporte
    Descrição: A funcionalidade de ordenar as solicitações por valor estará disponível após pagamento de taxa.<br>
    Referência requisitos:
    - RF - Ordenar as solicitações de transporte por valor.

    #### RNF - Ordem de apresentação de solicitações de transporte
    Descrição: Por padrão os serviços são ordenados na tela do prestador de serviço pela data e hora da solicitação.

2. Como cliente, eu gostaria de visualizar o valor de um serviço antes confirmar a contratação, para que possa decidir se vou contratá-lo ou não.<br>
    #### RNF - Exibição valor do serviço para o cliente
    Descrição: O valor do serviço deve ser exibido para o usuário antes de ele o contratar.

    #### RF - Aderir a clube de benefícios
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Aderir ao clube de benefícios.|
    | Why?   | Para obter descontos em serviços contratados, mediante pagamento de mensalidade.|
    | Who?   | O usuário cliente.|
    | When?  | Quando desejar aderir ao clube de benefícios. |
    | Where? | No aplicativo ou página da web, na página principal. |
        Descrição: No aplicativo ou página da web, o usuário cliente poderá aderir ao clube de benefícios para obter descontos em serviços contratados, mediante pagamento de mensalidade, quando ele desejar aderir ao clube de benefícios.

    #### RN - Oferta de clube de benefícios
    Descrição: Será ofertado aos usuários clientes a possibilidade de adesão a clube de benefícios mediante a uma assinatura mensal. Essa adesão garante aos usuários descontos nos serviços contratados.<br>
    Referência requisitos:
    - RF - Aderir a clube de benefícios.

    #### RN - Beneficio sobre os serviços ao aderir ao plano de assinatura
    O cliente terá desconto de 2% do valor do serviço se aderir ao clube de benefícios.<br>
    Referência requisitos:
    - RF - Aderir a clube de benefícios

3. Como usuário cliente do sistema, eu gostaria de visualizar quais prestadores de serviço estão disponíveis na área, para saber se o serviço que desejo pode ser atendido.<br>
   
    #### RNF - Localização do usuário
    Descrição: A localização atual do usuário deve ser obtida através do receptor de GPS do aparelho no qual o usuário está logado.

    #### RNF - Exibição de serviços disponíveis
    Descrição: São exibidos para o usuário cliente os prestadores de serviço que atendem num raio de 15km da sua localização atual.
 
## João Felipe
4. Como um usuário cliente do sistema gostaria de compartilhar a localização de meu transporte para que possa informar mais pessoas de onde estou ou onde esta a carga do transporte.<br>

    #### RF - Compartilhar a localização de trajeto com alguém.
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Compartilhar a localização deste transporte com alguém.|
    | Why?   | Para que o usuário cliente possa informar a alguém sua posição geográfica atualizada.|
    | Who?   | O usuário cliente.|
    | When?  | Após o início do transporte. |
    | Where? | No aplicativo ou pagina web. |
        Descrição: Após o início do transporte, o usuário cliente poderá compartilhar a localização deste transporte com alguém, através do aplicativo ou página web, para que possa informar a alguém sua posição geográfica atualizada. 

    #### RF - Reportar um desvio de rota compartilhada
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Reportar um desvio de rota.|
    | Why?   | Para que informe a administração do sistema que o motorista não seguiu a rota prevista.|
    | Who?   | A pessoa que abrir a localização compartilhada pelo usuário cliente.|
    | When?  | Após receber um compartilhamento de uma localização. |
    | Where? | No aplicativo ou pagina web. |
        Descrição: Após receber um compartilhamento de uma localização, se a pessoa que está acompanhando este transporte ver que o motorista não está seguindo com o plano da rota ele pode reportar um desvio de rota.
   
    #### RN - Compartilhamento de rotas
    Descrição: A funcionalidade de acompanhar uma rota compartilhada e reportar um desvio só poderá ser compartilhada com outros usuários do sistema.<br>
    Referência requisitos:
    - RF - Compartilhar a localização de trajeto com alguém.
    - RF - Reportar um desvio de rota compartilhada.

    #### RNF - Visualização de dados da rota compartilhada
    Descrição: Para quem recebe o compartilhamento de rota deve ser mostrada somente a localização geográfica atual do prestador de serviço, nome dele e o modelo e a placa do veículo.
   
5. Como usuário cliente do sistema eu gostaria de saber as informações básicas e as avaliações do prestador de serviço, para que eu possa saber o máximo possível sobre a pessoa que irá prestar um serviço.<br>

    #### RF - Visualizar o perfil do prestador de serviço
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Visualizar o perfil do prestador de serviço.|
    | Why?   | Para que o usuário cliente possa verificar as avaliações e as informaçoes do prestador de serviço.|
    | Who?   | O usuário cliente.|
    | When?  | Após o prestador de serviço aceitar o transporte. |
    | Where? | No aplicativo ou pagina web. |
        Descrição: Após o prestador de serviço aceitar o transporte, o usuário cliente poderá visualizar o perfil do prestador de serviço para que possa verificar as avaliações e as informaçoes do prestador de serviço.

    #### RF - Cancelar um transporte
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Cancelar um transporte.|
    | Why?   | Para que o usuário cliente, caso julgue necessário, possa cancelar o transporte.|
    | Who?   | O usuário cliente.|
    | When?  | Após o prestador de serviço aceitar o transporte. |
    | Where? | No aplicativo ou página web. |
        Descrição: Após o prestador de serviço aceitar o transporte, e caso o usuário cliente ache necessário cancelar o transporte, ele tenha essa possibilidade, que deve ser feita no aplicativo ou página web.
   
    #### RN - Obrigatoriedade de informar motivo de cancelamento
    Descrição: Caso o cliente cancele a corrida, deverá informar o motivo, para que seja avaliado pelos administradores do sistema. Caso a motivação esteja em desacordo com as politicas da empresa será aplicada uma multa em 10% do valor da corrida, a qual deverá ser paga antes que possa solicitar outra corrida.<br>
    Referência requisitos:
    - RF - Cancelar um transporte.

    #### RNF - Notificação de cancelamento ao prestador de serviço
    Descrição: Quando o cliente cancelar a corrida, o prestador de serviço receberá uma notificação relatando o cancelamento. 

6. Como um prestador de serviço do sistema, gostaria de ver as avaliações recentes do usuário cliente, para que eu tenha mais informações sobre o histórico de problemas desse cliente com outros prestadores de serviço.<br>

    #### RF - Visualizar o perfil do usuário cliente
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Visualizar o perfil do usuário cliente.|
    | Why?   | Para que o prestador de serviço possa verificar as avaliações e as informações do usuário cliente.|
    | Who?   | O prestador de serviço.|
    | When?  | Após o prestador de serviço aceitar o transporte ou antes de iniciar o transporte. |
    | Where? | No aplicativo ou pagina web, nas informações do transporte ou ao visualizar mais informações sobre um serviço disponível. |
       Descrição: O prestador de serviço, pelo aplicativo ou pagina web, nas informações do transporte ou ao visualizar mais informações sobre um serviço disponível, poderá visualizar o perfil do usuário cliente para que possa verificar as avaliações e as informações do usuário cliente após ou antes de iniciar o transporte.

    #### RF - Avaliar o cliente
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Avaliar o cliente.|
    | Why?   | Para que fique registrado no perfil do usuário cliente as avaliações feitas pelos prestadores de serviço contratados.|
    | Who?   | O prestador de serviço.|
    | When?  | Após o transporte ser finalizado. |
    | Where? | No aplicativo ou página web, na página de avaliar um serviço contratado. |
        Descrição: Após o transporte ser finalizado, o prestador de serviço poderá avaliar o usuário cliente para que fique registrado no perfil dele as avaliações feitas pelos prestadores de serviço contratados, por meio do aplicativo ou pagina web, na página de avaliar um serviço contratado.
   
   #### RF - Cancelar um transporte aceito
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Cancelar o transporte aceito.|
    | Why?   | Caso o prestador de serviço ache necessário.|
    | Who?   | O prestador de serviço.|
    | When?  | Após o transporte ser aceitado. |
    | Where? | No aplicativo, na página de informações do transporte contratado.|
        Descrição: Apos o transporte ser aceitado, caso o prestador de serviço ache necessario, ele pode cancelar um transporte contratado por um usuário cliente, na página de informações do transporte contratado do aplicativo.
   
    #### RN - Obrigatoriedade de informar motivo de cancelamento
    Descrição: Caso o prestador de serviço cancele a corrida, deverá informar o motivo do cancelamento, para que seja avaliado pelos administradores do sistema. Caso o motivo viole as politicas da empresa, poderá gerar uma multa para o prestador de serviço.<br>
    Referência requisitos:
    - RF - Cancelar um transporte aceito.


    #### RNF - Notificação de cancelamento por prestador de serviço
     Descrição: Quando o prestador de serviço cancelar um transporte, o usuário cliente ira receber uma notificação relatando o cancelamento.

 ## João Gustavo 

7. Como usuário do sistema, eu gostaria que tivesse uma opção de chamar mais de um carro ao mesmo tempo, para eu ir com o grupo de amigos ao mesmo tempo para o role.
   #### RF - Solicitar mais de um veículo
   | **5W** | **Resposta**                                        |
   | ------ | --------------------------------------------------- |
   | What?  | Solicitar mais de um veículo.|
   | Why?   | Quando exceder o número máximo de pessoas do primeiro veículo.|
   | Who?   | O usuário cliente.|
   | When?  | Ao fazer um pedido de transporte para mais de um passageiro.|
   | Where? | No aplicativo ou página da web, na página de solicitar um transporte de passageiros. |
        Descrição: Ao fazer um pedido de transporte para mais de um passageiro, pelo aplicativo ou página da web na página de solicitar um transporte, usuário cliente pode solicitar mais de um veículo. 

   #### RF - Escolher categoria de veículo.
   | **5W** | **Resposta**                                        |
   | ------ | --------------------------------------------------- |
   | What?  | Escolher qual categoria de veículo usuário quer.|
   | Why?   | Selecionar uma categoria de veículos que se adeque a sua necessidade e orçamento. |
   | Who?   | O usuário cliente. |
   | When?  | Ao solicitar um transporte.|
   | Where? | No aplicativo ou página da web, na página de solicitar um transporte. |
        Descrição: Ao solicitar um transporte, na página de solicitar um transporte o usuário cliente deve escolher qual categoria de veículo usuário quer, para selecionar uma categoria de veículos que se adeque a sua necessidade e orçamento.

   #### RNF- Informar número de passageiros
   Descrição: Ao solicitar um transporte de pessoas deve-se, obrigatoriamente, informar a quantidade de passageiros que serão transportados.

   #### RNF - Mínimo de passageiros para solicitar mais de um veículo
   Descrição: Para solicitar mais de um veículo é necessário que o número de passageiros seja superior a capacidade de um veículo da categoria escolhida pelo cliente.

   #### RNF - Número máximo de passageiros por veículo
   Descrição: Só é possível transportar o número máximo de passageiros autorizado pela documentação do veículo.

8. Como Prestador de serviço, eu gostaria que tivesse uma opção no sistema que mostrasse os melhores locais para prestar serviço sendo paga, para eu otimizar meus serviços.

   #### RF - Verificar valor base por região e horário.
   | **5W** | **Resposta**                                        |
   | ------ | --------------------------------------------------- |
   | What?  | Verificar valor base por região e horário.|
   | Why?   | Para decidir onde e quando prestar seus serviços. |
   | Who?   | O prestador de serviço. |
   | When?  | A qualquer momento. |
   | Where? | No aplicativo ou página da web, na página de verificar histórico do valor base. |
        Descrição: A qualquer momento, o prestador de serviço pode verificar o valor base por região e horário para decidir onde e quando prestar seus serviços, através de uma página especifica no aplicativo ou página da web.

    #### RN - Disponibilidade do valor base por região e horário
    Descrição: Para verificar o valor base da região e horário, é necessário que o prestador de serviço compre essa funcionalidade.<br>
    Referência requisitos:
    - RF - Verificar valor base por região e horário.

    #### RNF - Período de cálculo do valor base por região e horário
    Descrição: O valor exibido é calculado com base na média das 24hrs de determinada área.

9. Como usuário do sistema, gostaria que tivesse uma opção para que eu pague a mais para o motorista vir em um local em que os outros não estão indo por motivo de suspeita ou quando eu desejar prioridade de atendimento, para eu não perder tempo.
    #### RF - Adicionar um valor extra
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Adicionar um valor extra. |
    | Why?   | Para obter prioridade de atendimento. |
    | Who?   | Usuário cliente. |
    | When?  | No momento de solicitar o transporte. |
    | Where? | Pelo aplicativo na página de solicitar um transporte. |
        Descrição: No momento de solicitar o transporte, o usuário cliente pode Adicionar um valor extra para obter prioridade de atendimento através do aplicativo na página de solicitar um transporte.

    #### RN - Valor mínimo para adicionar um valor extra
    Descrição: O valor mínimo deve ser maior que a metade do valor original do transporte.

## João Pedro Gaspar
10. Como usuário eu gostaria de acessar o meu histórico de corridas para que eu possa ver minhas últimas corridas.<br>

    #### RF - Criação de histórico de corridas.
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | O aplicativo deve fornecer uma seção de "Histórico de Corridas" onde o usuário pode visualizar detalhes de suas corridas anteriores, como data, hora, origem, destino, valor e informações do motorista. |
    | Why?   | Para que os usuários possam revisar e rastrear suas viagens anteriores, bem como verificar os detalhes das transações. |
    | Who?   | Todos os usuários registrados no aplicativo que realizaram corridas. |
    | When?  | Os usuários podem acessar seu histórico de corridas a qualquer momento, desde que tenham realizado pelo menos uma corrida. |
    | Where? | O histórico de corridas deve estar disponível dentro do aplicativo, acessível a partir do menu principal. |
        Descrição: O aplicativo deve ter uma seção de "Histórico de Corridas" que permita que o usuário visualize informações de corridas anteriores, incluindo data, hora, origem, destino, valor e informações do motorista.

    #### RNF - Ordenação cronológica decrescente
    Descrição: O histórico de corridas deve ser apresentado em ordem cronológica decrescente, com as corridas mais recentes no topo da lista.<br>
    
    #### RNF - Carregamento Instantâneo da Página
    Descrição: Independentemente da quantidade de corridas no histórico do usuário, a página de histórico de corridas deve ser carregada em até 5 segundos após o acionamento da função.

11. Como usuário gostaria de ter opção de favoritar rotas para que facilite na hora de utilizar o aplicativo.<br>
    #### RNF - Atalho para as rotas favoritas
    Descrição: Os favoritos devem ser acessíveis por meio de um botão de acesso direto na tela de início.

    #### RF - Disponibilidade para favoritar corridas
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | O aplicativo deve permitir que o usuário adicione rotas frequentes aos "Favoritos" para facilitar a seleção durante a solicitação de corridas futuras. |
    | Why?   | Para melhorar a experiência do usuário, economizando tempo na seleção de rotas frequentes.|
    | Who?   | Todos os usuários registrados no aplicativo. |
    | When?  | Os usuários podem adicionar rotas aos Favoritos a qualquer momento. |
    | Where? | A funcionalidade de adicionar rotas aos Favoritos deve estar disponível na interface principal do aplicativo. |
        Descrição: Para facilitar a seleção durante a solicitação de corridas futuras, o aplicativo deve permitir que o usuário adicione rotas frequentes aos "Favoritos".

    #### RF - Adicionar preferências a uma rota favorita
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | O aplicativo permite que o usuário escolha quais rotas prefere e adicione informações como pontos de referência ou preferências de pagamento relacionadas a cada rota preferida. |
    | Why?   | Para que os usuários personalizem suas rotas favoritas de acordo com suas preferências, tornando a experiência de solicitação de corridas mais conveniente e eficiente.|
    | Who?   | Todos os usuários registrados no aplicativo que desejam personalizar suas rotas favoritas. |
    | When?  | A qualquer momento. |
    | Where? | No aplicativo, na tela de gerenciamento de rotas favoritas. |
        Descrição: O usuário pode escolher quais rotas prefere e adicionar informações como pontos de referência ou preferências de pagamento relacionadas a cada rota preferida.<br>
    
12. Como usuário gostaria de ter opção de ter um chat com o prestador de serviços para que possamos nos comunicar, e evitar imprevistos.<br>

     #### RF - Chat com o prestador de serviços
    | **5W** | **Resposta**                                        |
    | ------ | --------------------------------------------------- |
    | What?  | Chat bidirecional entre o usuário e o prestador de serviços durante o período da corrida. |
    | Why?   | Para permitir comunicação direta e relevante entre o usuário e o motorista, facilitando a coordenação da corrida. |
    | Who?   | Todos os usuários registrados no aplicativo e os motoristas parceiros. |
    | When?  | Apenas durante o período da corrida, a partir de quando o motorista aceitar a solicitação e está a chegada ao destino. |
    | Where? | O chat deve estar disponível na interface do aplicativo durante uma corrida ativa. |
        Descrição: O aplicativo deve oferecer uma funcionalidade de chat bidirecional entre o usuário e o prestador de serviços durante o período da corrida.

    #### RN - Regras do chat
    Descrição: O chat deve ser usado apenas para se comunicar sobre assuntos relacionados à corrida, como direções, atrasos, alterações no destino ou outras informações relevantes para a viagem. Comunicações inadequadas ou abusivas podem resultar em ações disciplinares.<br>
    Referência Requisitos:
    - RF - Chat com o prestador de serviços.

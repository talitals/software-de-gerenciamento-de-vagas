<h1>Estacione bem</h1>
<h2>Especificação de requisitos</h2>
<b>1. Introdução</b><br><br>
<b>1.1. Propósito do Documento de Requisitos</b>
<p>Este documento descreve os requisitos para o desenvolvimento de um aplicativo de controle de estacionamento. O aplicativo visa facilitar a gestão e monitoramento dos espaços de estacionamento em um determinado local.
</p>
<b>1.2. Público Alvo</b>
<p>Usuários que possuem veículos automotores.
</p>
<b>2. Descrição Geral do Produto</b>
<p>O objetivo do software seria garantir ao estabelecimento segurança aos usuários, ofertando um lugar seguro, e sua funcionalidade seria: agendamento de horário, cadastramento de usuários, pagamento diários, mensal, e quinzenal, e o nosso público seria proprietário de veículos automotores, a necessidade de implementação seria agilidade ao escolher o local e segurança da implementação.</p>
<b>2.1. Situação Atual</b>
<p>Percebemos a necessidade de um sistema, devido a dificuldade de encontrar estacionamento capazes de dar um conforto ao usuário quanto a segurança, agilidade e confiabilidade e também a modalidade de reserva antecipada.</p>
<b>2.2. Objetivos do Produto </b>
<p>O software irá resolver a dificuldade de encontrar vagas próximas ao destino do usuário, trazendo assim a comodidade de reserva dentro do conforto de sua casa.</p>
<b>2.3. Benefícios do Projeto </b>
- Agendamento prévio;<br>
- Conforto;<br>
- Segurança;<br>
- Praticidade;<br>
- Pagamento pelo App;<br><br>
<b>3. Requisitos Específicos</b><br><br>
<b>3.1. Requisitos Funcionais</b><br>
RF 01- Registro de Usuários: O sistema deve permitir que os usuários se cadastrem com nome, e-mail e senha.
Deve haver opção para recuperação de senha.<br>
RF 02- Reserva de Vagas: Os usuários devem poder visualizar a disponibilidade de vagas de estacionamento.
Os usuários devem poder reservar uma vaga por um determinado período de tempo.
As reservas devem ser confirmadas por e-mail.<br>
RF 03- Check-in e Check-out: Os usuários devem poder fazer check-in ao ocupar uma vaga.
Os usuários devem poder fazer check-out ao liberar uma vaga.
O sistema deve calcular e registrar o tempo de permanência do veículo.<br>
RF 04- Pagamento: O sistema deve calcular o valor do estacionamento com base no tempo de permanência.
Os usuários devem poder realizar o pagamento através do aplicativo.
Deve ser enviado um recibo por e-mail após o pagamento.<br>
RF 05- Histórico de Estacionamento: Os usuários devem poder visualizar seu histórico de estacionamento e pagamentos.<br><br>
<b>3.2. Requisitos Não Funcionais</b><br>
RNF 01- Desempenho: O sistema deve ser capaz de lidar com um grande volume de usuários simultaneamente.
O tempo de resposta do sistema deve ser rápido, especialmente durante o processo de reserva e pagamento.<br>
RNF 02- Segurança:
Todas as transações de pagamento devem ser seguras e criptografadas.
O acesso às informações dos usuários deve ser restrito e protegido.<br>
RNF 03- Usabilidade:
A interface do aplicativo deve ser intuitiva e fácil de usar.
O aplicativo deve ser responsivo e funcionar bem em dispositivos móveis.<br><br>
<b>3.3. Regras de Negócio</b><br>
RN 01- Tarifas de Estacionamento:
A tarifa de estacionamento será calculada com base no tempo de permanência do veículo.
O preço por hora será definido pela administração do estacionamento.<br>
RN 02- Reservas e Cancelamentos:
As reservas só serão válidas se forem confirmadas pelo usuário através do pagamento.
Os usuários podem cancelar uma reserva até 15 minutos antes do horário de check-in.<br>
RN 03- Responsabilidade do Usuário:
Os usuários são responsáveis por garantir que as informações de seu veículo estejam corretas durante o check-in.
Os usuários devem respeitar as regras e regulamentos do estacionamento.<br><hr>

<h2>História de usuário para o usuário  do estacionamento</h2>
<ul>
  <h3>1) Registro de usuário</h3>
<p><b>Como/Sendo:</b> usuário </p>
<p><b>Quero/Posso:</b> me cadastrar no aplicativo fornecendo meu nome, e-mail e senha </p>
<p><b>Para:</b> utilizar os serviços de reserva de vagas de estacionamento </p></br>
  
<h3>Cenário de aceitação:</h3>

<p><b>Dado que:</b> estou na tela de registro do aplicativo </p>
<p><b>Quando:</b> preencho todos os campos obrigatórios com informações válidas </p>
</p><b>E:</b> clico no botão de cadastro <p>
<p><b>Então:</b> devo receber uma confirmação de que meu cadastro foi realizado com sucesso. </p></br>


<h3>2) Reserva de vaga de estacionamento</h3>
<p><b>Como/Sendo:</b> usuário </p>
<p><b>Quero/Posso:</b> poder reservar uma vaga de estacionamento por um período específico de tempo através do aplicativo </p>
<p><b>Para:</b>  garantir um local quando chegar ao meu destino</p></br>

<h3>Cenário de aceitação:</h3>
<p><b>Dado que:</b> estou na tela de visualização de vagas de estacionamento </p>
<p><b>Quando:</b> escolho uma vaga disponível e seleciono o período de reserva desejado </p>
</p><b>E:</b> confirmo a reserva <p>
<p><b>Então:</b> devo receber um e-mail de confirmação da reserva. </p></br>
</li>



<h3>3) Check-in no estacionamento</h3>
  <p><b>Como/Sendo:</b> usuário </p>
<p><b>Quero/Posso:</b> fazer check-in no aplicativo ao ocupar uma vaga de estacionamento </p>
<p><b>Para:</b> registrar minha entrada no estacionamento</p></br>
  
  
<h3>Cenário de aceitação:</h3>
<p><b>Dado que:</b> estou na tela de check-in do aplicativo </p>
<p><b>Quando:</b> chego ao estacionamento e seleciono a opção de check-in </p>
<p><b>Então:</b> devo receber uma confirmação de que meu check-in foi registrado com sucesso. </p></br>

<h3>4) Check-out no estacionamento</h3>
 
<p><b>Como/Sendo:</b> usuário </p>
<p><b>Quero/Posso:</b> fazer check-out no aplicativo ao liberar uma vaga de estacionamento </p>
<p><b>Para:</b> registrar minha saída e calcular o tempo de permanência do meu veículo.</p></br>


<h3>Cenário de aceitação:</h3>
<p><b>Dado que:</b> estou na tela de check-out do aplicativo </p>
<p><b>Quando:</b> ao sair do estacionamento, seleciono a opção de check-out </p>
<p><b>Então:</b> devo receber o cálculo do valor e ser direcionado a tela de pagamento. </p></br>

<h3>5) Pagamento pelo estacionamento</h3>
<p><b>Como/Sendo:</b> usuário </p>
<p><b>Quero/Posso:</b> poder realizar o pagamento pelo estacionamento através do aplicativo, com base no tempo de permanência do meu veículo </p>
<p><b>Para:</b> agilizar o processo e evitar o uso de dinheiro físico.</p></br>
  
<h3>Cenário de aceitação:</h3>
<p><b>Dado que:</b> estou na tela de pagamento do aplicativo </p>
<p><b>Quando:</b> selecionei o período de permanência do meu veículo e confirmo o pagamento </p>
<p><b>Então:</b> devo receber um recibo por e-mail após a conclusão bem-sucedida do pagamento. </p></br>
  

</br>
<hr>
<h2>História de usuário para o proprietário do estacionamento</h2>


<h3>6) Acesso ao painel de controle</h3>
<p><b>Como/Sendo:</b> proprietário do estacionamento </p>
<p><b>Quero/Posso:</b> ter acesso a um painel de controle com informações sobre a ocupação atual das vagas e as reservas feitas </p>
<p><b>Para:</b> monitorar e gerenciar o espaço de estacionamento de forma eficiente. </p></br>

<h3>Cenário de aceitação:</h3>
<p><b>Dado que:</b> estou logado na conta de proprietário do estacionamento no aplicativo </p>
<p><b>Quando:</b> acesso o painel de controle </p>
<p><b>Então:</b> devo ver informações atualizadas sobre a ocupação das vagas e as reservas feitas no estacionamento. </p></br>

<h3>7) Acesso as tarifas no painel de controle</h3>

<p><b>Como/Sendo:</b> proprietário do estacionamento </p>
<p><b>Quero/Posso:</b> ter a capacidade de definir e ajustar as tarifas de estacionamento através do aplicativo </p>
<p><b>Para:</b> acompanhar as demandas do mercado e otimizar a receita. </p></br>

<h3>Cenário de aceitação:</h3>
<p><b>Dado que:</b> estou logado na conta de proprietário do estacionamento no aplicativo </p>
<p><b>Quando:</b>  acesso as configurações de tarifas de estacionamento </p>
<p><b>Então:</b> devo conseguir definir e ajustar as tarifas com facilidade. </p></br>


<h3>8) Acesso aos relatórios de utilização do estacionamento</h3>
<p><b>Como/Sendo:</b> proprietário do estacionamento </p>
<p><b>Quero/Posso:</b> acessar relatórios detalhados sobre a utilização do estacionamento ao longo do tempo, incluindo informações sobre ocupação, receitas e tendências de uso, </p>
<p><b>Para:</b> tomar decisões estratégicas informadas. </p></br>
  
<h3>Cenário de aceitação:</h3>
<p><b>Dado que:</b> estou logado na conta de proprietário do estacionamento no aplicativo </p>
<p><b>Quando:</b> acesso a seção de relatórios </p>
<p><b>Então:</b> devo ver relatórios detalhados sobre a ocupação, receitas e tendências de uso do estacionamento. </p></br>


</ul>
</hr>


### Tipos de redes:

LAN- (LOCAL AREA NETWORK) interligam computadores dentro de um mesmo espaço físico (escola ou empresa), permitindo a troca de informações entre os dispositivos, baixo range, muito fluxo de dados;

MAN- (METROPOLITAN AREA NETWORK) conecta diversas redes dentro de algumas dezenas de km (uma empresa com escritórios distantes, tv a cabo), pode ser pública ou privada, comunicação por voz e dados;

SAN- (STORAGE AREA NETWORK) restritas a fazer a comunicação de um servidor e outros computadores(computação em nuvem);

PAN- (PERSONAL AREA NETWORK) comunicação de dispositivos dentro de uma distância bastante limitada (bluetooth);

WAN- (WIDE AREA NETWORK) abrange uma área maior que a WAN, como um país ou continente (internet), satélites e cabos óticos transoceânicos;

WMAN- (wireless) versão sem fio da MAN;

WLAN- LAN sem fio, conectado na internet (ambientes residenciais e lugares públicos);

WWAN- com alcance ainda maior que a rede WAN e sem fio, mas é mais sujeita a ruídos (operadoras móveis de celular);

### Modelos de comunicação:

Fonte: gerar os dados (computador)

Transmissor: converter o sinal (modem)

Sistema de transmissão: transmitir os dados (Rede de telefone)

Receptor: converter os sinais recebidos em dados (dados da fonte)

Destino: receber os dados (servidor)

### Tarefas de um sistema de comunicação:

Sistema de transmissão: uso eficiente das facilidades de transmissão, que são tipicamente compartilhadas por vários dispositivos;

Endereçamento: indicar o destinatário da transmissão;

Geração do sinal:  Especifica como o sinal será codificado para transmissão

Conexão (interfacing): um dispositivo deve interfacear (se conectar fisicamente) com o sistema de comunicação

Escolha de rotas (routing): O sistema de transmissão pode possuir vários caminhos diferentes para acessar o mesmo dispositivo destino;

Gerenciamento da troca de dados: Configuração do sistema, monitoração do status, reação a falhas e sobrecarga;

### Broadcast:

Uma rede compartilhada com um campo de endereço e um destinatário(enviar uma mensagem no grupo da sala) Usada em redes de pequena escala;

### Rede ponto-a-ponto(P2P)

Conjunto de comunicações entre máquinas, como uma rede de computador compartilhada com uma impressora, redes de larga escala;

### Internetworking:

Conjunto de redes interconectadas (lan, wan, man), a interligação é realizada por um conjunto de programas padronizados de comunicação (protocolos);

### Modelo OSI:

O **OSI (Open Systems Interconnection)** é o primeiro modelo padrão de comunicação entre sistemas de computadores e redes, ele faz uso de sete camadas para garantir essa conversa.

**7. Camada de aplicação**: Oferece protocolos que permitem que um software envie e receba informações significativas para os usuários. Por isso, é altamente usada por itens como navegador de internet e cliente de e-mail. Alguns exemplos: [HTTP](https://tecnoblog.net/responde/o-que-e-http/), FTP, POP e [DNS](https://tecnoblog.net/responde/qual-o-melhor-dns-e-por-que/).

**6. De apresentação**: Essa camada faz a preparação dos dados para a camada de aplicações. Ou seja, garante que as informações possam ser usadas e faz toda a criptografia.

**5. De sessão**: É aqui que o modelo OSI cria os canais de comunicação entre dispositivos. Como o próprio nome diz, essa camada é responsável por abrir sessões e garantir que tudo esteja funcional para que dados possam ser transferidos.

**4. De transporte:** A camada de transporte pega os dados e os quebra em segmentos. Em seguida, na parte final, junta tudo novamente para que as informações alcancem a camada de sessão. Ela transmite através de protocolos como o TCP e UDP.

**3. De rede:** A responsabilidade dessa camada é a de transmitir dados entre um host a outro em diferentes  redes. Do mesmo modo, é válido apontar que outra importante função é a de cuidar dos pacotes de roteamento, selecionando o caminho mais curto para isso.

**2. De enlace de dados:** É nesta parte que ocorre a conexão entre dois nós conectados fisicamente 
em uma rede. Essa camada do modelo OSI é composta por duas partes: o controle de enlace lógico (LLC), que identifica e checa erros; e o media access control (MAC), que usa endereços MAC para conectar e definir permissões nos dispositivos.

**1. Camada física:** Essa camada é uma das mais importantes do modelo OSI. Isso porque ela é responsável pela ligação de cabos físicos ou sem fio entre toda a rede. Outra característica é que a transmissão dos dados brutos é feita a partir daqui.

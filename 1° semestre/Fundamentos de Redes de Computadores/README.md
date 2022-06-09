# Introdução a rede de computadores e histórico da internet

*	As redes de computadores surgiram no final da década de 60, o objeto dessas redes era conectar as grandes máquinas da época, que eram máquinas valvuladas.
*	Surgiu por conta da guerra fria, a disputa econômica entre duas potencias mundiais fazia com que qualquer avanço tecnológico fosse atrativo e atraísse investimento governamental.
*	Os protocolos são regras que organizam as informações e permitem que elas sejam deslocadas de maneira correta. Ex: TCP/IP, atuam em níveis diferentes para resolver diferentes problemas de comunicação.
*	A internet começou a ser usada comercialmente no início da década de 90.

Antes do surgimento da Internet, as redes de comunicação, como as redes de telefonia fixa convencional, eram baseadas no conceito da comutação de circuitos.

Na época, a grande inovação foi a mudança de paradigma para a comutação de pacotes, que facilitou a conectividade e a rápida expansão das redes de computadores para uma escala global.

## Comutação de circuitos:

Na comutação de circuitos, é necessário o estabelecimento prévio de um circuito físico entre a origem e o destino antes da transmissão da informação propriamente dita.

![ex_comutacao_de_circuitos](https://user-images.githubusercontent.com/61008693/172952458-c3404f84-7d28-4729-9ef7-56b77bf04636.png)

### EX:

O usuário A deseja estabelecer uma ligação telefônica com o usuário B, localizado em outra cidade.

Ao digitar o número do telefone do usuário B com o respectivo DDD, a central telefônica local conectada ao aparelho do usuário A inicia um processo de sinalização pela rede telefônica até que um caminho físico (circuito) seja estabelecido da rede do terminal A ao terminal telefônico do usuário B.

Ao atender o telefone, o usuário B confirma a utilização desse circuito. A partir daí, a conversa (troca de informação entre os usuários A e B) pode ser efetuada.

![comutaca_de_circuitos_telefone](https://user-images.githubusercontent.com/61008693/172957013-a32e8295-7333-495e-bb70-b697fe3cce0f.png)

## Comutação de pacotes:

Nesse tipo de comutação, a informação é dividida em conjuntos de dados chamados pacotes, que também carregam a informação de identificação da origem e do destino dentro da rede.
Assim, os pacotes são encaminhados individualmente e de forma independente, cada ponto intermediário analisa as informações do pacote e decide por onde encaminhá-lo dentro da rede, até que ele alcance o destino.

#### ATENÇÃO:
Na Comutação de pacotes, não existem as fases 1 e 3 descritas anteriormente, que compreendem o estabalecimento prévio de um circuito antes da transmissão dos dados e a desconexão ou o encerramento do circuito estabelecido ao final da comunicação.

![comutacao_de_pacotes](https://user-images.githubusercontent.com/61008693/172957429-7a788bb6-05b4-47e9-9aa7-ecfe00bae219.png)

#### ATENÇÃO: 
Observe que cada pacote pode seguir um caminho diferente, de forma que a ordem de chegada ao destino não é preservada. Cabe assim ao nó destino "B" rearrumar os pacotes na sequência correta para recuperar completamente a informação original transmitida por "A".

## IoT:

* É ligada ao conceito _interconexão_ digital de objetos comuns do nosso dia a dia ligados à rede e internet, esses objetos contêm sensores de comunicação e são capazes de coletar, compartilhar e receber dados.
* **Ex de equipamentos:** Geladeira, micro-ondas, porta de casa, coleira do pet, qualquer objeto que possa se conectar a internet com alguma finalidade.
*	A tecnologia 5g daria um salto na internet das coisas por conta da taxa de transmissão que promete ser 100x mais que as atuais no mercado e um tempo de resposta menor (amplificação de conectividade de dispositivos da rede).
*	**Pontos positivos:** ela vai permitir conectividade entre as coisas, capacidade de transmissão de dados entre as coisas, desenvolvimento de outros aplicativos. 
*	**Pontos negativos:** maior de necessidade de desenvolver mecanismos de segurança.

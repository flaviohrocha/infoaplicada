# Segurança da Informação

## Princípios

- **Confidencialidade:** propriedade que limita o acesso a informação tão somente às entidades legítimas, ou seja, àquelas autorizadas pelo proprietário da informação.

- **Integridade:** propriedade que garante que a informação manipulada mantenha todas as características originais estabelecidas pelo proprietário da informação, incluindo controle de mudanças e garantia do seu ciclo de vida (nascimento, manutenção e destruição).

- **Disponibilidade:** propriedade que garante que a informação esteja sempre disponível para o uso legítimo, ou seja, por aqueles usuários autorizados pelo proprietário da informação.

- **Autenticidade:** Entende-se por autenticidade a certeza absoluta de que um objeto (em análise) provém das fontes anunciadas.

- **Irretratabilidade (não-repúdio):** Impossibilidade de negar a autoria em relação a uma transação anteriormente feita. Garantia de que a informação não será negada.


## Ameaças
 
- **Ambientais e Defeitos de Hardware:** Inundações, incêndios, panes elétricas. São as situações onde não há como prever a ocorrência. Para minimizar os danos causados recomenda-se utilizar as técnicas de cópias de segurança ou backup.

- **Hacker:** Usuário que modifica softwares e hardwares com o intuito de aprimorá-los ou disponibilizar novas funcionalidades;

- **Cracker:** Usuário que se utiliza de códigos maliciosos para obter informações privilegiadas, causar danos ou adquirir recursos.

- **Desatualizações:** Programas desatualizados podem apresentar brechas de segurança que podem ser utilizados por hackers ou crackers.

- **Usuários:** Usuários descontentes (com intenção de causar danos) ou usuários leigos (falta de conhecimento técnico) podem levar os sistemas a falhas de segurança.

- **Spam:** Spam é o termo usado para se referir aos e-mails não solicitados, que geralmente são enviados para um grande número de pessoas. Quando o conteúdo é exclusivamente comercial, este tipo de mensagem também é referenciada como UCE (do inglês Unsolicited Commercial E-mail).

    - Prejuízos advindos da ação de Spam:

        - Não recebimento de e-mails. Acúmulo da caixa postal.
        - Gasto desnecessário de tempo.
        - Aumento de custos.
        - Perda de produtividade.
        - Divulgação de Conteúdo impróprio ou ofensivo.
        - Prejuízos financeiros causados por fraude.

- **Ataques:** Tentativa, bem ou mal sucedida, de acesso ou uso não autorizado a um programa ou computador.

- **Malwares:** Do Inglês Malicious software (software malicioso).Termo genérico que se refere a todos os tipos de programa que executam ações maliciosas em um computador. Exemplos de códigos maliciosos são os vírus, worms, bots, cavalos de tróia, rootkits, etc.

- **Fraudes e Golpes:** Ações que visam obter vantagens e informações de outros usuários.


### Malwares

- **Vírus:** Programa ou parte de um programa de computador, normalmente malicioso, que se propaga infectando, isto é, inserindo cópias de si mesmo e se tornando parte de outros programas e arquivos de um computador. O vírus depende da execução do programa ou arquivo hospedeiro para que possa se
tornar ativo e dar continuidade ao processo de infecção.

- **Vírus de Macro:** São vírus que se utilizam de macros criadas em linguagem Visual Basic for Applications (VBA), linguagem essa disponível para utilização nos aplicativos do Microsoft Office e algumas outras aplicações. O VBA possui acesso à maioria das funções do sistema operacional e suporta execução automática de código quando um documento é aberto. Tal arquitetura torna relativamente simples a construção de vírus informáticos, conhecidos popularmente como vírus de macro.

- **Worms:** Programa capaz de se propagar automaticamente através de redes, enviando cópias de si mesmo de computador para computador. Diferente do vírus, o worm não embute cópias de si mesmo em outros programas ou arquivos e não necessita ser explicitamente executado para se propagar. Sua propagação se dá através da exploração de vulnerabilidades existentes ou falhas na configuração de
softwares instalados em computadores.

- **Cavalo de Tróia (Trojan):** Programa, normalmente recebido como um "presente" (por exemplo, cartão virtual, álbum de fotos, protetor de tela, jogo, etc), que além de executar funções para as quais foi aparentemente projetado, também executa outras funções normalmente maliciosas e sem o conhecimento do usuário.

- **Keyloggers:** Programa capaz de capturar e armazenar as teclas digitadas pelo usuário no teclado de um computador. Normalmente, a ativação do keylogger é condicionada a uma ação prévia do usuário, como por exemplo, após o acesso a um site de comércio eletrônico ou Internet Banking, para a captura de senhas bancárias ou números de cartões de crédito.


- **Screenloggers:** Forma avançada de keylogger, capaz de armazenar a posição do cursor e a tela apresentada no monitor, nos momentos em que o mouse é clicado, ou armazenar a região que circunda a posição onde o mouse é clicado.

- **Spyware:** Termo utilizado para se referir a uma grande categoria de software que tem o objetivo de monitorar atividades de um sistema e enviar as informações coletadas para terceiros. Podem ser utilizados de forma legítima, mas, na maioria das vezes, são utilizados de forma dissimulada, não autorizada e maliciosa.

- **Adware:** Do Inglês Advertising Software. Software especificamente projetado para apresentar propagandas. Constitui uma forma de retorno financeiro para aqueles que desenvolvem software livre ou prestam serviços gratuitos. Pode ser considerado um tipo de spyware, caso monitore os hábitos do usuário, por exemplo, durante a navegação na Internet para direcionar as propagandas que
serão apresentadas.

- **Backdoors:** Programa que permite a um invasor retornar a um computador comprometido. Normalmente este programa é colocado de forma a não ser notado.

- **Rootkit:** Rootkit é um tipo de software, muitas das vezes malicioso, projetado para esconder a existência de certos processos ou programas de métodos normais de detecção e permitir contínuo acesso privilegiado a um computador. Quando algum sistema operacional efetua um pedido de leitura de um arquivo, o rootkit intercepta os dados que são requisitados e faz uma filtragem dessa informação, deixando o sistema ler apenas arquivos não infectado. Desta forma, o antivírus ou qualquer outra ferramenta ficam impossibilitados de encontrar o arquivo malicioso.

- **Sniffing:** sniffing, em rede de computadores, é o procedimento realizado por uma ferramenta conhecida como Sniffer (também conhecido como Packet Sniffer, Analisador de Rede, Analisador de Protocolo, Ethernet Sniffer em redes do padrão Ethernet ou ainda Wireless Sniffer em redes wireless). Esta ferramenta, constituída de um software ou hardware, é capaz de interceptar e registrar o tráfego de dados em uma rede de computadores. Conforme o fluxo de dados trafega na rede, o sniffer captura cada pacote e eventualmente decodifica e analisa o seu conteúdo.

O sniffing pode ser utilizado com propósitos maliciosos por invasores que tentam capturar o tráfego da rede com diversos objetivos, dentre os quais podem ser citados, obter cópias de arquivos importantes durante sua transmissão, e obter senhas que permitam estender o seu raio de penetração em um ambiente invadido ou ver as conversações em tempo real.

- **Botnet:** Uma botnet é uma coleção de agentes de software ou bots que executam autonomamente e automaticamente. O termo é geralmente associado com o uso de software malicioso, mas também pode se referir a uma rede de computadores utilizando software de computação distribuída. As principais motivações para levar alguém a criar e controlar botnets são o reconhecimento e o ganho financeiro.

Quanto maior a botnet, mais admiração seu criador pode reivindicar entre a comunidade underground. Poderá ainda alugar os serviços da botnet para terceiros, usualmente mandando mensagens de spam ou praticando ataques de negação de serviço contra alvos remotos. Devido ao grande número de computadores comprometidos, um volume grande de tráfego pode ser gerado.


### Fraudes e Golpes

- **Phishing:** Também conhecido como phishing scam ou phishing/scam. Mensagem não solicitada que se passa por comunicação de uma instituição conhecida, como um banco, empresa ou site popular, e que procura induzir usuários ao fornecimento de dados pessoais e financeiros. Inicialmente, este tipo
de mensagem induzia o usuário ao acesso a páginas fraudulentas na Internet.

Atualmente, o termo também se refere à mensagem que induz o usuário à instalação de códigos maliciosos, além da mensagem que, no próprio conteúdo, apresenta formulários para o preenchimento e envio de dados pessoais e financeiros.

- **Engenharia social:** Método de ataque onde uma pessoa faz uso da persuasão, muitas vezes abusando da ingenuidade ou confiança do usuário, para obter informações que podem ser utilizadas para ter acesso não autorizado a computadores ou informações.

- **Pharming:** Pharming é o termo atribuído ao ataque baseado na técnica DNS cache poisoning (envenenamento de cache DNS) que, consiste em corromper o DNS (Sistema de Nomes de Domínio ou Domain Name System) em uma rede de computadores, fazendo com que a URL (Uniform Resource Locator ou Localizador Uniforme de Recursos) de um site passe a apontar para um servidor diferente do
original.

### Agentes de Segurança

- **Controle de Acesso:** O controle de acesso, na segurança da informação, é composto dos processos de autenticação, autorização e auditoria. Neste contexto o controle de acesso pode ser entendido como a habilidade de permitir ou negar a utilização de um objeto (uma entidade passiva, como um sistema ou arquivo) por um sujeito (uma entidade ativa, como um indivíduo ou um processo). A autenticação identifica quem acessa o sistema, a autorização determina o que um usuário autenticado pode fazer, e a auditoria diz o que o usuário fez.

- **Antivírus:** Programa ou software especificamente desenvolvido para detectar, anular e eliminar de um computador vírus e outros tipos de código malicioso.

- **Anti-spam:** Procedimentos técnicos contra o spam. O principal deles é o uso de filtro de mensagens.

- **Firewalls:** Dispositivo constituído pela combinação de software e hardware, utilizado para dividir e controlar o acesso entre redes de computadores.

- **Proxy:** Servidor que atua como intermediário entre um cliente e outro servidor. Normalmente é utilizado em empresas para aumentar a performance de acesso a determinados serviços ou permitir que mais de uma máquina se conecte à Internet.

Proxies mal configurados podem ser abusados por atacantes e utilizados como uma forma de tornar anônimas algumas ações na Internet, como atacar outras redes ou enviar spam.

- **VPN:** Rede Particular Virtual (Virtual Private Network - VPN) é uma rede de comunicações privada normalmente utilizada por uma empresa ou um conjunto de empresas e/ou instituições, construída em cima de uma rede de comunicações pública (como por exemplo, a Internet). VPNs seguras usam protocolos de criptografia por tunelamento que fornecem a confidencialidade, autenticação e integridade necessárias para garantir a privacidade das comunicações requeridas.

Quando adequadamente implementados, estes protocolos podem assegurar comunicações seguras através de redes inseguras.

- **Código QR (QR Code):** Código QR é um código de barras em 2D que pode ser facilmente escaneado usando a maioria dos celulares modernos equipados com câmera. Esse código é convertido num pedaço de texto (interativo), um endereço URL, um número de telefone, uma localização geográfica, um e-mail, um contato e outros.

## Criptografia

- **Criptografia:** Ciência e arte de escrever mensagens em forma cifrada ou em código. É parte de um campo de estudos que trata das comunicações secretas. É usada, dentre outras finalidades, para: autenticar a identidade de usuários; autenticar transações bancárias; proteger a integridade de transferências eletrônicas de fundos, e proteger o sigilo de comunicações pessoais e comerciais.

- **Criptografia Simétrica:** Os algoritmos de chave simétrica (também chamados de Sistemas de Chave Simétrica, criptografia de chave única, ou criptografia de chave secreta) são uma classe de algoritmos para a criptografia, que usam chaves criptográficas relacionadas para a operações de cifragem ou decifragem (ou cifra/decifra, ou cifração/decifração). A chave de cifragem pode ser idêntica à de decifragem ou poderá existir uma transformação simples entre as duas chaves. 

As chaves, na prática, representam um segredo, partilhado entre duas ou mais partes, que podem ser usadas para manter um canal confidencial de informação. Usa-se uma única chave, partilhada por ambos os interlocutores, na premissa de que esta é conhecida apenas por eles.

- **Criptografia Assimétrica:** criptografia assimétrica é um método de criptografia que utiliza um par de chaves: uma chave pública e uma chave privada. A chave pública é distribuída livremente para todos os correspondentes via e-mail ou outras formas, enquanto a chave privada deve ser conhecida apenas pelo seu dono. Num algoritmo de criptografia assimétrica, uma mensagem cifrada com a chave pública pode somente ser decifrada pela sua chave privada correspondente.

- **Certificado Digital:** Arquivo eletrônico, assinado digitalmente, que contém dados de uma pessoa ou instituição, utilizados para comprovar sua identidade.

- **Assinatura Digital:** Código utilizado para verificar a integridade de um texto ou mensagem. Também pode ser utilizado para verificar se o remetente de uma mensagem é mesmo quem diz ser.

- **Infraestrutura de Chaves Públicas (PKI):** Uma Infraestrutura de Chaves Públicas, cujo sigla é ICP, é um órgão ou iniciativa pública ou privada que tem como objetivo manter uma estrutura de emissão de chaves públicas, baseando-se no princípio da terceira parte confiável, oferecendo uma mediação de credibilidade e confiança em transações entre partes que utilizam certificados digitais. 

A principal função do ICP é definir um conjunto de técnicas, práticas e procedimentos a serem adotados
pelas entidades a fim de estabelecer um sistema de certificação digital baseado em chave pública. A infra-estrutura de chaves públicas do Brasil, definida pela Medida Provisória No 2.200-2, de 24 de Agosto de 2001, é denominada Infra-Estrutura de Chaves Públicas Brasileira, ou ICP-Brasil.

- **Autoridade Certificadoras:** (acrónimo: CA, do inglês Certification Authority, ou AC): é o terceiro confiável que emite um certificado.Existem Autoridades de Certificação de dois tipos: as Autoridades de Certificação de Raiz (ou Autoridades de Certificação Superiores ou ainda Autoridades de Certificação de Maior Nível), que regulam a emissão de certificados, e as Autoridades de Certificação Intermediárias (ou Autoridades de Certificação Inferiores ou ainda Autoridades de
Certificação de Menor Nível).

- **Autoridade de Registro:** (acrônimo AR, vem do inglês Registration Authority) é um dos elementos de uma PKI, ou talvez o mais importante. Esta é o intermediário entre Autoridade de Certificação e o Cliente (aquele que pede o certificado). Ou seja, é a entidade que acolhe os pedidos de emissão de certificados digitais.

## Backup

- **Backup:** Cópia de segurança. Pode ser realizada no computador Local, em rede ou em dispositivos armazenáveis removíveis.

- **Normal:** Copia todos os arquivos. O atributo de arquivo é desmarcado. 
    
- **Backup de Cópia:** Copia todos os arquivos, independente da marcação. Não desmarca os atributos de arquivo.

- **Incremental:** Copia todos os arquivos com atributo de arquivo marcado e os desmarca.

- **Diferencial:** Copia todos os arquivos com atributo de arquivo marcado e não os desmarca.

- **Backup diário:** Copia todos os arquivos que sofreram alteração no dia de execução do backup. Os atributos de arquivo não são desmarcados.
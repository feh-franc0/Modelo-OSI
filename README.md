# Modelo OSI

Modelo Osi foi criado para compatibilidade 

Modelo de referência OSI
7-Aplicação
6-Apresentação
5-Sessão
4-Transporte
3-Rede
2-Enlace
1-Física


1.Camada de Aplcação Modelo OSI [camada 7]:
   Integração Usuario com a Rede,unica camada que o usuario consegue mexer diretamente
   Qualquer coisa que o usuario consiga mexer é camada de aplicação
   -recebe os dados que o usuario quer enviar
   
  
   PROTOLOS QUE ESTÃO NA CAMADA DE APLICAÇÃO:
      -HTTP
      -FTP
      -DNS
      -DHCP
      -TFTP
      
      
2.Camada de Apresentação Modelo OSI [camada 6]:
   Traduz os dados que o usuario quer enviar para alguma linguagem entendida pela rede, emissor e receptor...
   Camada responsavel pela codificacção,criptogradia,semantica,sintaxe e etc
   Forma a estrutura do que sera enviada de acordo com a codificação do formato as informaçõs caso não esteja claro ainda,ex: .txt .doc 
   
   CODIFICAÇÕES MAIS COMUNS:
      -ASCII
      -EBCDIC
      -CRIPTOGRAFIA = ex: HTTPS, usa 2 formas de criptografia(SSL e TLS)->Apresentação[camada 6]
      
      
3.Camada de Sessão do modelo OSI [camada 5]:
    Estabelece um sessão de comunicação entre os dois lados que querem se falar.
    Sessão igual de cinema = vai definir a hora que a transmissão vai começar, qual o tempo de duração dessa sessão e a hora que vai acabar essa transmissão
    -Não tem envio de dados,, apenas a hora que vai começar e finalizar a transmissão
    Camada que diz o inicio,controle e fechamento de sessões
   
   QUEM ESTA PRESENTE NA CAMADA DE SESSÃO?
      existe um protocolo muito comum que é o:
      - SIP -> protocolo que inicia sessão
      
      
      
4.Camada de transporte do Modelo OSI [camada 4]:
    Responsavel por segmentar/separar os dados
    EX: vai pegar 20b e separar em pequenas caixas que contem partes pequenas desses 20gb,para assim ser enviado pelo rede sem conjestionar a rede
    -ainda NÃO esta empacotando os dados para enviar.
    
    
    EX: pega 20 pedaços e separa em apenas 1
    
    :::::
    :::::    .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 
    
    
    
5.Camada de Rede do Modelo OSI [camada 3]:
    Empacota os dados na hora de fazer a transmissão
    Pega o dado que foi segmentado/separado e vai empacotar esse dado para fazer o envio
    
        º  ->  |º|
   
    ENDEREÇAMENTO IP é ultilizado para identificar esses pacotes, identifica via IP o seu IP e será enviado ou recebido algo para esse IP
    IGUAL UM PACOTE DE CORREIO TENDO O REMETENTE E O DESTINATORIO ISSO TUDO USANDO O PROTOCOLO TCP/IP
    
  
  
6.Camada de Enlace/link-de-dados do Modelo OSI [camada 2]:      -CAMADA FÍSICA
    Determina a tecnologia que será usada para os dados serem enviados
    Wifi - camada de enlace determina que vai usar onde de radio para envio
    Cabeado - camada de enlace determina que vai usar o ethernet para o envio
    satele - ... vai terminar a tecnologia que o satelete usa e etc...
    
    Determina a tecnologia de comunicação que vai ser ultilizada para realizar a Transmissão desses dados atravez das redes.
    
    -Essa camada de Enlace tem uma Subdivisão ela é a unica camada do modelo OSI que tem duas divisoes, que é a sub-camada LLC e a sub-camada MAC
    
    
    TEMOS NO ENLACE TAMBEM O ENQUADRAMENTO:
        Caixa que a tecnologia vai determinar aquele lugar onde os dados vao ser colocados para que possam ser fisicamente enviados atraves de cabo ou atraves de Wi-fi e etc
        é como se fosse um pacote mas o pacote é lógico e o quadro é algo fisico relacionado a tecnologia na hora do envio.
        -Junto com o quadro temos o endereço MAC
            ->MAC = Controle de Acesso de Mídia
            ->Endereço que é utilizado para poder identificar fisicamente as placas de redde na hora que acontece uma comunicação
            
        a placa de rede tem um endereço IP e um endereço MAC que é uma identificação fisica e local
        
        
        
7.Camada física do Modelo OSI [camada 1]:      -CAMADA FÍSICA
    -Na hora do envio de dados a camada física é quem vai transformar realmente tudo aquilo que a gente quer enviar em algo Físico, para assim andar pelos cabos,wifi,ondas de radio e etc
        
     
    





   
   

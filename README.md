<!DOCTYPE html>
<html lang="pt">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>redes</title>
    <style>
        body {
            background-color: rgba(117, 117, 117, 0.689);
            text-align: justify;
            margin: 4%;
            font-size: 18px;
        }

        h1,
        h2 {
            text-transform: capitalize;
        }

        a:visited {
            color: ivory;
        }

        a:hover {
            color: maroon;
        }

        a {
            cursor: pointer;
        }
    </style>
</head>

<body>
    <h1>evolução das redes</h1>
    <p>
        Antes da criação do conceito das redes de computadores, algumas tecnologias
        foram desenvolvidas favorecendo o surgimento deste conceito. Estas tecnologias
        consistiram no teleimpressor, a Mondothèque e no modem. Os principais componentes destas máquinas consistiam em
        um teclado, um transmissor, um receptor,
        uma fita e uma impressora. Os teleimpressores evoluíram do sistema de telégrafos. A Figura apresenta este
        dispositivo sendo utilizado durante a Segunda Guerra Mundial pelas forças aliadas contra o eixo.
    </p>
    <p>
        O sistema sAgE (Semi-Automatic Ground Enviroement) foi desenvolvido pela
        IBM para detectar bombardeiros russos durante a Guerra Fria.
    </p>
    <h3>Anos 1960</h3>
    <p>
        Durante a década de sessenta, alguns acontecimentos chave contribuíram significativamente para o surgimento das
        redes de computados como conhecemos
        hoje. Dentre estes acontecimentos, podemos mencionar o surgimento do conceito de redes de computadores, avanços
        na comunicação via satélite, o surgimento
        do primeiro padrão universal para permitir a troca de dados entre máquinas fabricadas por diferentes empresas, a
        criação da primeira rede de computadores,
        a ArPANET, e a conexão dos primeiros computadores nesta rede.
    </p>
    <h2> hosts</h2>
    <p>
        uma rede é formada por um conjunto de módulos processadores (MPs) capazes de trocar informações e compartilhar
        recursos. Interligados por um sistema de comunicação</p>
    <p>
        LAN (Local Area Network)
        Rede interligando equipamentos dentro de uma organização
        MAN (Metropolitan Area Network)
        Rede interligando equipamentos espalhados dentro de uma cidade
        WAN (Wide Area Network)
        Rede interligando equipamentos espalhados entre cidades
        WLAN (Wireless LAN) WLAN (Wireless LAN)
        Rede local baseada em comunicação sem fio (wireless)
        PAN (Personal Area Network) PAN (Personal Area Network)
        Rede de “área pessoal” (geralmente utilizada para controle de dispositivos IoT)
    </p>
    <h2>classificação de redes</h2>
    <p> Simplex: o enlace é utilizado apenas em um dos dois possíveis sentidos de
        transmissão.
        Half-duplex: o enlace é utilizado em dois possíveis sentidos de transmissão,
        porém apenas um por vez.
        Full-duplex: o enlace é utilizado nos dois possíveis sentidos de transmissão
        simultaneamente.
    </p>
    <h2>Encapsulamento</h2>
    <p>Na transmissão, partindo da camada mais
        alta, os cabeçalhos correspondentes são
        adicionados ao conjunto de forma sucessiva,
        até a camada mais baixa. Isto se chama de
        encapsulamento de dados.
    </p>
    <h2> modelo tcp/ip</h2>
    <p>
        Aplicação: suporta as aplicações de rede
        ftp, smtp, http
        transferência de dados hosthost
        tcp, udp
        Rede: roteamento de datagramas da
        origem ao destino
        ip, protocolos de roteamento
        com a rede: transferência de
        dados entre elementos vizinhos da rede
        ppp, ethernet
        Física: bits “nos fios dos canais
    </p>
    <p>
        Uma série de outras nomenclaturas são utilizadas para descrever outros tipos
        de redes, quanto a extensão geográfica que as mesmas atuam. A seguir é
        possível conhecer algumas:
        WMAN – rede de área metropolitana sem-fio, destina-se principalmente
        a operadores de telecomunicações.
        WWAN – rede de longa distância sem-fio, são comumente utilizadas para
        criação de redes de transmissão celular.
        RAN – considerada uma subcategoria de uma MAN, uma RAN (Regional
        Area Network), corresponde a uma rede de computadores de uma região
        geográfica específica.
        CAN – uma CAN (Campus Area Network) corresponde a uma rede de
        computadores formada por computadores dispostos em edifícios, prédios,
        campus, entre outros (MENDES, 2007).
    </p>
    <a href="topologia.html">topologia de redes de computadores</a>
    <a href="IP.html">TCP/IP</a>
</body>

</html>

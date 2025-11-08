<a href="https://pi-hole.net">
    <img src="https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/PiHoleb.png" width="600px" alt="PiHoleb.png">
</a>

# Lista de Bloqueio (Blocklist) para Pi-hole 
Neste repositório encontram-se listas de bloqueios personalizados para o serviço PiHole. (Pi-hole é um aplicativo para bloqueio de anúncios e rastreadores na Internet que atua como um serviço de DNS). Você pode usar em serviços semelhantes, AdGuard, Ublock, Hosts em geral.

## Porque usar esta listas de DNS/hosts 🔍
Este projeto visa unificar listas de bloqueio de DNS adicionando contribuições e colaborações da comunidade, removendo falsos positivos, mantendo-os livres de bugs, com qualidade e  otimizados. Convido você a me ajudar nesta tarefa.

## Detalhes das listas de bloqueios (BlackLists) - UPDATE DIA 28/07/2025 📖
| Nome da Lista      | Breve Descrição                                     | Número de entradas | RAW                                                                                      |
|--------------------|-----------------------------------------------------|--------------------|------------------------------------------------------------------------------------------|
| Ads and trackers   | Bloqueia anúncios e rastreadores                    | 822.208            | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Adsandtrackers.txt) | 
| Mining pages       | Bloqueia páginas e serviços de mineração            | 34.539             | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Miningpages.txt)    | 
| Pages with porn    | Bloqueia páginas com conteúdo XXX Porn              | 2.072.810          | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Pornpages.txt)      | 
| Telemetry          | Bloqueia telemetria do SO Windows e outros Sistemas | 7.933              | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Telemetry.txt)      |
| Pages Malicious    | Bloqueia domínios com vírus                         | 169.600            | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Malicious.txt)      |
| Block Ransomware   | Bloqueia domínios com ransomware                    | 1.904              | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/ransomware.txt)     |
| Block Spam         | Bloqueia domínios com e-mail spam                   | 209.320            | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/spam.mails.txt)     |
| Block App TikTok   | Bloqueia aplicativo TikTok                          | 9.645              | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/tiktok.txt)         |
| Block App Facebook | Bloqueia aplicativo Facebook                        | 24.634             | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/facebook.txt)       |
| Block App WhatsApp | Bloqueia aplicativo WhatsApp                        | 475                | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/whatsapp.txt)       |
| Block Ads Youtube  | Bloqueia anúncios do youtube                        | 41.125             | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/youtube.txt)        |
| Block Bets         | Bloqueia anúncios do youtube                        | 211174             | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Bets.txt)           |

# Listas Externas (Blocklist) para Pi-hole 
Neste repositório encontram-se listas de outros projetos com listas de bloqueios personalizados para o serviço PiHole.

## Projetos com Listas de bloqueios (BlackLists) 📖
| Nome da Lista                | Breve Descrição                | RAW                                                              |
|------------------------------|--------------------------------|------------------------------------------------------------------|
| Firebog                      | Várias Listas de Bloqueios     | [list](https://firebog.net)                                      |
| Block List Project           | Várias Listas de Bloqueios     | [list](https://github.com/blocklistproject/Lists)                | 
| DNS Blocklist                | Várias Listas de Bloqueios     | [list](https://github.com/hagezi/dns-blocklists/)                |
| Avoidthehack                 | Várias Listas de Bloqueios     | [list](https://avoidthehack.com/best-pihole-blocklists)          | 
| Pi-hole Blocklists           | Várias Listas de Bloqueios     | [list](https://github.com/topics/pihole-blocklists)              | 
| The Big Blocklist Collection | Várias Listas de Bloqueios     | [list](https://github.com/sefinek24/PiHole-Blocklist-Collection) |
| Awesome Privacy              | Listas com foco em Privacidade | [list](https://github.com/pluja/awesome-privacy)                 |
| Blocklists                   | Listas Midia Social, Jogos     | [list](https://github.com/nickoppen/pihole-blocklists)           |
| RegEx Filters                | Filtros RegEX                  | [list](https://github.com/slyfox1186/pihole-regex)               |

## Bloqueando casas de apostas brasileiras regulamentadas - (Expressão RegEX) 📖:
As casas de apostas regulamentadas em território brasileiro possuem seus domínios terminados em **bet.br**. Pensando nisso, foi criado uma pequena e poderosa RegEX para bloqueá-las.

Para isso, acesse o painel de controle, do lado esquerdo clique em `Group Management`, vá até `Domains` e clique em `RegEX Filter`.

Por fim, basta criar um novo RegEX Filter com o valor **`*.bet.br`** e tipo **RegEX Deny**, como demonstrado abaixo.

![betbr-regex-block](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/betbr-regex-blocker.gif)


## Pré-requisitos 📋
Você só precisa ter o serviço Pi-Hole instalado, consulte o site oficial para mais detalhes.

<a href="https://pi-hole.net"><img src="https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/pi-hole.png" alt="Pi-Hole" width="100px" /><br>
https://pi-hole.net

## Como instalar e usar? 🔧
Na tabela descritiva cada lista de bloqueio tem um link RAW, esse endereço deve ser copiado e depois adicionado às listas de bloqueio nas configurações do host pi-hole.<br>

1. Acesse o painel de controle, do lado esquerdo clique em `Group Management` e depois em `Adlist`.  
![Imagen 1](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/group_management.png)
2. Uma vez dentro, cole a `URL` no campo `Address` e pressione o botão `Add` para adicioná-lo. (Repita para cada lista que queremos adicionar)  
![Imagen 2](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/address_add.png)
4. No painel esquerdo clique em `Tools` e depois em `Update Gravity`, dentro da aba pressione o botão `Update`.  
![Imagen 3](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/tools_update_gravity_update.png)  
Observação: Caso der erro ou lentidão na atualiação via interface web, atualizar com o comando "pihole -g" via terminal.

## Como colaborar com a lista de bloqueio 🙋
Seu apoio me ajudará a manter o projeto em andamento e manter listas atualizadas e com qualidade. Você pode apoiar de várias maneiras:
- Enviar falsos positivos
- Enviar nova url para bloquear
- Compartilhe com outros usuários

## Autor ✒️
Este repositório é público e todos podem usufruir sem moderação!

## Isenção de responsabilidade 🚨
As listas de bloqueio disponibilizadas são `arquivos de hosts` para bloquear o acesso a domínios/sites. Se você não sabe como funciona, leia a seção de instalação e uso. Tente isso por sua conta e risco, não me responsabilizo por qualquer dano, perda ou problema causado.

## Licença 📄
O conteúdo deste repositório está licenciado sob [MIT License](https://github.com/zangadoprojets/pi-hole-blocklist/blob/main/LICENSE). 

<a href="https://pi-hole.net/"><img src="https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/PiHoleb.png" width="600px" /><br/><br/>

# Lista de Bloqueio (Blocklist) para Pi-hole 
Neste repositório encontram-se listas de bloqueios personalizados para o serviço PiHole. (Pi-hole é um aplicativo para bloqueio de anúncios e rastreadores na Internet que atua como um serviço de DNS). Você pode usar em serviços semelhantes, AdGuard, Ublock, Hosts em geral.
<br/><br/>
## Porque usar esta listas de DNS/hosts 🔍
Este projeto visa unificar listas de bloqueio de DNS adicionando contribuições e colaborações da comunidade, removendo falsos positivos, mantendo-os livres de bugs, com qualidade e  otimizados. Convido você a me ajudar nesta tarefa.
<br/><br/>
## Detalhes das listas de bloqueios (BlackLists) 📖
|Nome da Lista|Breve Descrição|Número de entradas|RAW|
|:-:|:-:|:--:|:--:|
Ads and trackers | Bloqueia anúncios e rastreadores | 675.276 | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Adsandtrackers.txt) | 
Mining pages | Bloqueia páginas e serviços de mineração| 34.539 | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Miningpages.txt) | 
Pages with porn | Bloqueia páginas com conteúdo XXX Porn | 2.060.397 | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Pornpages.txt) | 
Windows telemetry | Bloqueia toda a telemetria do SO Windows | 1.012 | [list](https://github.com/zangadoprojets/pi-hole-block-list/raw/main/Windowstelemetry.txt) |
Block Ads Youtube | Bloqueia anúncios do youtube | 16844 | [list](https://raw.githubusercontent.com/kboghdady/youTube_ads_4_pi-hole/master/youtubelist.txt) |
<br/>  

# Listas Externas (Blocklist) para Pi-hole 
Neste repositório encontram-se listas de outros projetos com listas de bloqueios personalizados para o serviço PiHole.
<br/><br/>
## Projetos com Listas de bloqueios (BlackLists) 📖
|Nome da Lista|Breve Descrição|RAW|
|:-:|:-:|:--:
Block List Project | Várias Listas de Bloqueios | [list](https://github.com/blocklistproject/Lists) | 
Avoidthehack | Várias Listas de Bloqueios| [list](https://avoidthehack.com/best-pihole-blocklists) | 
Pi-hole Blocklists | Várias Listas de Bloqueios | [list](https://github.com/topics/pihole-blocklists) | 
Firebog | Várias Listas de Bloqueios | [list](https://firebog.net/) |
<br/>  


## Pré-requisitos 📋
Você só precisa ter o serviço Pi-Hole instalado, consulte o site oficil para mais detalhes.

<a href="https://pi-hole.net/"><img src="https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/pi-hole.png" alt="Pi-Hole" width="100px" /><br/>
https://pi-hole.net/
<br/><br/>

## Como instalar e usar? 🔧
Na tabela descritiva cada lista de bloqueio tem um link RAW, esse endereço deve ser copiado e depois adicionado às listas de bloqueio nas configurações do host pi-hole.<br/>

1º Acesse o painel de controle, do lado esquerdo clique em `Group Management` e depois em `Adlist`.<br/><br/>
![Imagen 1](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/group_management.png)<br/><br/><br/>
2º	Uma vez dentro, cole a `URL` no campo `Address` e pressione o botão `Add` para adicioná-lo. (Repita para cada lista que queremos adicionar)<br/><br/>
![Imagen 2](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/address_add.png)<br/><br/><br/>
3º	No painel esquerdo clique em `Tools` e depois em `Update Gravity`, dentro da aba pressione o botão `Update`.<br/><br/>
![Imagen 3](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/readme_imagens/tools_update_gravity_update.png)<br/><br/>

## Como colaborar com a lista de bloqueio 🙋
Seu apoio me ajudará a manter o projeto em andamento e manter listas atualizadas e com qualidade. Você pode apoiar de várias maneiras:
- Enviar falsos positivos
- Enviar nova url para bloquear
- Compartilhe com outros usuários
<br/>

## Autor ✒️
Este repositório é público, foi utilizado com base o repositório [Amdr0meda](https://github.com/Amdr0meda/Blocklist_Pi_Hole).
<br/><br/>

## Isenção de responsabilidade 🚨
As listas de bloqueio disponibilizadas são `arquivos de hosts` para bloquear o acesso a domínios/sites. Se você não sabe como funciona, leia a seção de instalação e uso. Tente isso por sua conta e risco, não me responsabilizo por qualquer dano, perda ou problema causado.
<br/><br/>

## Licença 📄
O conteúdo deste repositório está licenciado sob [MIT License](https://github.com/zangadoprojets/pi-hole-blocklist/blob/main/LICENSE). 
<br/><br/>

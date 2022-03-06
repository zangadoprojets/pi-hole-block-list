# Blocklist para Pi-hole
Neste repositório encontram-se listas de bloqueios personalizados para o serviço PiHole. (Pi-hole é um aplicativo para bloqueio de anúncios e rastreadores na Internet que atua como um sumidero de DNS). Você pode usar em serviços semelhantes, AdGuard, Ublock, Hosts em geral.
<br/><br/>
## Porque usar esta listas de DNS/hosts 🔍
Este projeto visa unificar listas de bloqueio de DNS adicionando contribuições e colaborações da comunidade, removendo falsos positivos, mantendo-os livres de bugs, com qualidade e  otimizados. Convido você a me ajudar nesta tarefa.
<br/><br/>
## Detalhes das listas de bloqueios (BlackLists) 📖
|Nome da Lista|Breve Descrição|Número de entradas|RAW|
|:-:|:-:|:--:|:--:|
Ads and trackers | Bloqueia anúncios e rastreadores | 675.276 | [list](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/Ads%20and%20trackers.txt) | 
Mining pages | Bloqueia páginas e serviços de mineração| 34.539 | [list](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/Mining%20pages.txt) | 
Pages with porn | Bloqueia páginas com conteúdo XXX Porn | 2.048.596 | [list](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/Porn%20pages.txt) | 
Windows telemetry | Bloqueia toda a telemetria do SO Windows | 1.012 | [list](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/Windows%20telemetry.txt) |
<br/>  

## Pré-requisitos 📋
Você só precisa ter o serviço Pi-Hole instalado, consulte o site oficil para mais detalhes.

![Pi-Hole](https://github.com/zangadoprojets/pi-hole-block-list/tree/main/readme_imagenes/logo-pi-hole.png)<br/><br/>

https://pi-hole.net/
<br/><br/>

## Como instalar e usar? 🔧
Na tabela descritiva cada lista de bloqueio tem um link RAW, esse endereço deve ser copiado e depois adicionado às listas de bloqueio nas configurações do host pi-hole.<br/>

1º Acesse o painel de controle, do lado esquerdo clique em `Group Management` e depois em `Adlist`.<br/><br/>
<img src="https://github.com/zangadoprojets/pi-hole-block-list/tree/main/readme_imagenes/group_management.png"/><br/><br/><br/>
2º	Uma vez dentro, cole a `URL` no campo `Address` e pressione o botão `Add` para adicioná-lo. (Repita para cada lista que queremos adicionar)<br/><br/>
![Imagen 2](https://github.com/zangadoprojets/pi-hole-block-list/tree/main/readme_imagenes/address_add.png)<br/><br/><br/>
3º	No painel esquerdo clique em `Tools` e depois em `Update Gravity`, dentro da aba pressione o botão `Update`.<br/><br/>
![Imagen 3](https://github.com/zangadoprojets/pi-hole-block-list/tree/main/readme_imagenes/tools_update_gravity_update.png)<br/><br/>

## Como colaborar com a lista de bloqueio 🙋
Seu apoio me ajudará a manter o projeto em andamento e manter listas atualizadas e com qualidade. Você pode apoiar de várias maneiras:
- Enviar falsos positivos
- Enviar nova url para bloquear
- Compartilhe com outros usuários
<br/>

## Autor/es ✒️
Este repositório é público, algumas partes das listas pertencem a outros internautas, que permitem a reutilização e modificação.
<br/><br/>

## Isenção de responsabilidade 🚨
As listas de bloqueio disponibilizadas são `arquivos de hosts` para bloquear o acesso a domínios/sites. Se você não sabe como funciona, leia a seção de instalação e uso. Tente isso por sua conta e risco, não me responsabilizo por qualquer dano, perda ou problema causado.
<br/><br/>

## Licencia 📄
O conteúdo deste repositório está licenciado sob [GNU General Public License v3.0](https://github.com/zangadoprojets/pi-hole-block-list/blob/main/LICENSE).
<br/><br/>
# BANDERSNATCH

## Descrição
Este projeto tem como objetivo reproduzir as tecnologias utilizadas pela Netflix no filme interativo [Black Mirror: Bandersnatch](https://www.youtube.com/watch?v=VNw9DAwp2Kk), com o intuito de criar uma experiência de vídeo interativo similar.

## Visão Geral
Para alcançar esse objetivo, foram desenvolvidas as seguintes etapas:

1. **Pré-processamento de Vídeos:** Foi desenvolvido um script para automatizar o pré-processamento dos arquivos de vídeo, incluindo renderização em múltiplas resoluções e análise de metadados e codecs utilizando as ferramentas [FFmpeg](https://ffmpeg.org/) e [FFprobe](https://ffmpeg.org/).
2. **Player de Vídeo Personalizado:** Utilizando a biblioteca [video.js](https://videojs.com/), criamos um player de vídeo moderno e personalizado, inspirado no layout da Netflix.
3. **Carregamento Sob Demanda:** Implementamos a lógica para carregar pedaços de vídeo sob demanda, de acordo com as escolhas do usuário.
4. **Experiência de Vídeo Interativo:** Desenvolvemos a lógica necessária para criar uma experiência de vídeo interativo similar à da Netflix, permitindo que o usuário tome decisões que influenciam a trama.

## Setup
Siga as etapas abaixo para configurar o ambiente de desenvolvimento:

1. Faça o clone deste repositório e acesse o diretório do projeto.
2. Certifique-se de ter o Node.js e o NPM instalados em seu sistema.
3. Execute o comando `npm install` para instalar as dependências do projeto.
4. Faça o download dos binários do [FFmpeg e FFprobe](https://ffbinaries.com/downloads) e coloque-os no diretório `bin`.
5. Execute o script `script.sh` para realizar o pré-processamento dos arquivos de vídeo.
6. Por fim, inicie a aplicação com os comandos `npm run dev` e `npm run assets`.

## Créditos
- Workshop, skeleton do projeto e vídeos utilizados de [Erick Wendel](https://github.com/ErickWendel/jsexpert01-skeleton-ew)


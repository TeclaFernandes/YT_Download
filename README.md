# YouTube Video and Audio Downloader

Este é um aplicativo de desktop desenvolvido em Python usando Tkinter para permitir que os usuários baixem vídeos e áudios do YouTube diretamente para seu computador. Ele oferece a possibilidade de escolher a resolução do vídeo ou baixar apenas o áudio. A interface gráfica é simples e amigável, utilizando imagens de logos para facilitar a navegação.

## Pré-requisitos

- Python 3.x
- Bibliotecas Python:
  - `pyperclip`
  - `tkinter`
  - `threading`
  - `pytube`
  - `PIL` (Pillow)

Você pode instalar as bibliotecas necessárias com o seguinte comando:

```bash
pip install pyperclip pytube pillow
```
## Instalação

1. Clone o repositório ou baixe o código-fonte.
2. Instale as dependências necessárias utilizando pip. install -r requirements.txt.
3. Execute o código:

```bash
python yt_downloader.py
```
O aplicativo abrirá uma janela gráfica onde você pode inserir o URL do vídeo do YouTube e selecionar a qualidade ou optar por baixar o áudio apenas.

## Funcionalidades

- Baixar Vídeos/Áudios: Escolha a qualidade do vídeo ou baixe apenas o áudio.
- Interface Gráfica (GUI): Usando o Tkinter para uma experiência amigável.
- URLs: Você pode colar a URL do YouTube para baixar diretamente o vídeo ou áudio.
- Escolha do Diretório: Defina o local onde deseja salvar o arquivo baixado.
- Status de Download: Acompanhe o progresso do download com a atualização do status na interface.

## Detalhes de Implementação

- Resoluções de Vídeo Disponíveis: 144p, 360p, 720p, e a opção de Áudio Apenas.
- Threading: Para garantir que a interface não congele durante o download, foi implementado um sistema de threading que executa o download em segundo plano.
- Validação: Caso o URL não seja inserido corretamente, o aplicativo exibe uma mensagem de erro.

## Como Usar

1. URL do Vídeo: Cole o URL do vídeo do YouTube na caixa de texto.
2. Escolher Qualidade: Selecione a qualidade do vídeo ou "Áudio Apenas".
3. Salvar em: Clique no botão "Save To" para escolher onde o arquivo será salvo.
4. Download: Clique em "Download" para iniciar o processo de download.
5. Status: Acompanhe o status do download diretamente na interface.

## Imagens
- Logo do YouTube: Um logo do YouTube é exibido na parte superior da interface.
- Botão de Download: Um ícone de botão de download também é exibido.

## Licença

Este projeto é de código aberto sob a licença MIT. Consulte o arquivo LICENSE para mais informações.

```bash
Este README.md fornece uma visão geral do projeto, como instalar e usar o aplicativo, além de destacar as funcionalidades e detalhes técnicos da implementação.
```
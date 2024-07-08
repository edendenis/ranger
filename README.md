# Como configurar/instalar o `ranger` no Linux Ubuntu

## Resumo

Neste documento estão contidos os principais comandos e configurações para instalar/configurar o `ranger` no Linux Ubuntu.

## _Abstract_

_This document contains the main commands and settings for installing/configuring `ranger` on Linux Ubuntu._

## Revisão(ões)/Versão(ões)

|Revisão número|Data da revisão|Descrição da revisão|Autor da revisão|
|:-:|:-:|:-|:-|
|0|25/10/2023|<ul><li>Revisão inicial/criação do documento.</li></ul>|Eden Denis F. da S. L. Santos|

### Descrição

#### `ranger`

O ranger é um gerenciador de arquivos baseado em texto que funciona dentro do terminal. Ele oferece uma interface de usuário em modo texto com um layout em três painéis: o painel à esquerda mostra o conteúdo do diretório pai, o painel do meio mostra o conteúdo do diretório atual e o painel da direita fornece uma pré-visualização do arquivo ou diretório selecionado. O ranger é escrito em Python e é altamente configurável. Ele oferece várias funcionalidades, como a capacidade de pré-visualizar arquivos, navegar entre diretórios de forma eficiente e executar operações comuns de gerenciamento de arquivos (como copiar, colar, mover e excluir).

O ranger é especialmente útil para pessoas que passam muito tempo no terminal e desejam um gerenciador de arquivos que se integre bem com outras ferramentas de linha de comando.

## 1. Configurar/Instalar o `ranger` no Linux Ubuntu [1]

Para instalar o `ranger` no Linux Ubuntu, você pode seguir estas etapas:

1. Abra o terminal. Você pode fazer isso pressionando: `Ctrl + Alt + T`

2. Certifique-se de que seu sistema esteja atualizado.

    2.1 Buscar as atualizações disponíveis para os pacotes que estão instalados em seu sistema. Digite o seguinte comando e pressione `Enter`: `sudo apt update -y`

    2.2 Para ver a lista de pacotes a serem atualizados, digite o seguinte comando e pressione `Enter`:  `sudo apt list --upgradable`

    2.3 Realmente atualizar os pacotes instalados para as suas versões mais recentes, com base na última vez que você executou `sudo apt update -y`. Digite o seguinte comando e pressione `Enter`: `sudo apt upgrade -y`

3. Instalar PlayOnLinux: Agora, instale o PlayOnLinux com o seguinte comando: `sudo apt install ranger -y`

4. Depois de instalado, você pode abrir o PlayOnLinux a partir do menu de aplicativos ou executando `ranger` no terminal.

## 1.1 Código completo

Para instalar o `ranger` no Linux Ubuntu sem precisar digitar linha por linha, você pode seguir estas etapas:

1. Abra o terminal. Você pode fazer isso pressionando: `Ctrl + Alt + T`

2. Digite o seguinte comando e pressione `Enter`:

```
sudo apt update -y
sudo apt upgrade -y
sudo apt install ranger -y
ranger
```

## Referências

[1] OPENAI. ***O que é o ranger?:*** https://chat.openai.com/c/3db2bbed-aa23-4044-a67e-425d0a3f6bee (texto adaptado). Acessado em: 25/10/2023 13:21.

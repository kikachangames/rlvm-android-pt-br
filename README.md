# O que é rlvm?

O rlvm (RealLive Virtual Machine) é um reimplementação em código aberto da engine RealLive, usada nas visual novels da Key/VisualArt’s (Kanon, AIR, CLANNAD, Little Busters! etc).
Para maiores informações sobre as VNs suportadas e código fonte, acesse: https://github.com/eglaysher/rlvm.

# rlvm-android
Port do rlvm para Android. Maiores informações em: https://github.com/xyzz/rlvm-android.

# rlvm-android-pt-br
![AIR rodando no Android](img/air_tablet.jpg)

Modificação do port para facilitar a aplicação dos patches de tradução pt-br da [Taiyaki Club](https://taiyakiclub.wordpress.com/) e [Kikachan Games](https://kikachangames.github.io/projetos/).

## Implementações
- Fonte modificada embutida.
- Atualização de sdk para rodar em versões mais atuais do Android.

## Jogos suportados
- Kanon
- AIR
- CLANNAD

## Como usar
- Instale o .apk.
- Nas configurações do Android, dê permissão para o rlvm acessar as pastas.
- Abra o rlvm e selecione a pasta onde estão os arquivos do jogo.

## Bugs conhecidos
Kanon e AIR usam a mesma fonte modificada. Então, na prática, você pode usar uma mesma versão do rlvm para rodar o patch de ambas as tradução.
CLANNAD utiliza outra fonte e você precisará da versão específica para rodar o patch. Certamente o android não irá permitir a instalação de dois .apk. Nesse caso, seja paciente, termine um jogo antes de iniciar outro :relaxed:.

:warning: Abrir outras VNs com nossos apk modificados irão ocasionar em erros nos textos, já que embutimos fonte com substituição de caracteres para suportar acentuação.

## Quero desenvolver minha própria versão do rlvm
Dê uma olhada em https://github.com/AndnixSH/APKToolGUI.

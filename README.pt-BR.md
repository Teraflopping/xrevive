# xrevive

### [**English**](README.md) · [**Deutsch**](README.de.md) · [**Français**](README.fr.md) · [**Español**](README.es.md) · [**Italiano**](README.it.md) · **Português (Brasil)** · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · [**简体中文**](README.zh-CN.md)

Um launcher para PC de jogos do Xbox original recompilados com o [Xrecomp](https://github.com/Teraflopping/Xrecomp), com serviços online do revival da Xbox Live em [xb.live](https://xb.live).

## Baixar v0.1.14

[Baixar para Windows x64](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_x64-setup.exe) · [Baixar para Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_amd64.AppImage) · [Todos os instaladores e notas de versão](https://github.com/Teraflopping/xrevive/releases/latest)

Os executáveis dos jogos hospedados atualmente suportam **Windows x64**. No Linux eles podem rodar via Wine ou Proton (experimental). Os pacotes para macOS ainda não jogam.

## Recursos

- Adicione sua própria ISO ou pasta do jogo extraída e baixe o executável correspondente. O xrevive usa a versão Release do jogo quando existe, e pergunta antes de instalar uma versão Beta ou Alpha. Dumps region-free, com media patch, renomeados ou reassinados de um jogo suportado também são reconhecidos.
- Veja qualquer jogo Release, Beta ou Alpha antes de instalar: atividade, atualizações, rankings, conquistas, addons e a contagem ao vivo de jogadores e lobbies, com o botão **INSTALL** na própria página.
- Verificação automática de atualizações dos jogos e do launcher. As atualizações de jogos removem os executáveis antigos que substituem, e os downloads vêm de um servidor perto de você e continuam de onde pararam se a conexão cair.
- Entre com o xb.live (começando pelo online de Midnight Club 3) e veja amigos, lobbies ao vivo, eventos da comunidade e rankings. Se o xb.live estiver fora do ar, os jogos ainda abrem offline.
- Gerencie os jogos instalados: jogar, abrir os arquivos locais, desinstalar e a aba DLC/Addons, onde cada mod tem um botão On/Off e os créditos de quem fez. **▶ PLAY** abre o jogo com os mods ativados, e os addons continuam funcionando após atualizações do jogo.
- Aba Saves com backup, restauração, importação, conversão de save de PS2 e editores de save para Midnight Club 3 e NINJA GAIDEN Black.
- O cache de shaders fica com o jogo, então só a primeira abertura compila os shaders.
- Mensagens de erro claras que explicam o que deu errado e como resolver, incluindo um botão **Allow xrevive in Windows Security** quando o Acesso controlado a pastas bloqueia uma instalação.
- Espanhol, italiano e árabe disponíveis em Configurações > Idioma; em árabe a janela toda fica da direita para a esquerda.
- Adicione jogos instalados ao Steam (Configurações ou biblioteca), com capas e Steam Input no Deck.
- Verificação de sistema para Windows 8.1+ e Direct3D 11, com opção de Jogar mesmo assim.
- Os saves do XB Online da antiga pasta `XBL-Hosted` são copiados para a pasta de saves normal de cada jogo quando você aperta Play. Saves existentes nunca são substituídos e nada é apagado; depois de conferir seus saves, você mesmo pode apagar `SaveData\XBL-Hosted`.

## Você traz os jogos

O xrevive não inclui ISOs nem arquivos dos jogos. Use seus próprios arquivos. Esta versão baixa executáveis publicados em vez de compilar os jogos localmente; jogos sem executável disponível podem ser extraídos para uso futuro.

O launcher e o instalador para Windows têm assinatura Authenticode. As atualizações do launcher são assinadas com a chave de atualização do xrevive. Os pacotes para macOS não são notarizados, então avisos de segurança podem aparecer na primeira instalação no macOS.

---

O xrevive é um projeto de fãs, sem afiliação ou endosso da Microsoft.

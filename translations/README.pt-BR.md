# xrevive

### [**English**](../README.md) · [**Deutsch**](README.de.md) · [**Français**](README.fr.md) · [**Español**](README.es.md) · [**Italiano**](README.it.md) · **Português (Brasil)** · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · [**日本語**](README.ja.md) · [**简体中文**](README.zh-CN.md)

Um launcher para PC de jogos do Xbox original recompilados com o [Xrecomp](https://github.com/Teraflopping/Xrecomp), com serviços online do revival da Xbox Live em [xb.live](https://xb.live).

## Baixar

[Baixar para Windows x64](https://github.com/Teraflopping/xrevive/releases/latest) · [Baixar para Linux (AppImage)](https://github.com/Teraflopping/xrevive/releases/latest) · [Todos os instaladores e notas de versão](https://github.com/Teraflopping/xrevive/releases/latest)

Os executáveis dos jogos hospedados atualmente suportam **Windows x64**. No Linux eles podem rodar via Wine ou Proton (experimental). Os pacotes para macOS ainda não jogam.

## Recursos

- Adicione sua própria ISO ou pasta do jogo extraída e baixe o executável correspondente. O xrevive usa a versão Release do jogo quando existe, e pergunta antes de instalar uma versão Beta ou Alpha. Dumps region-free, com media patch, renomeados ou reassinados de um jogo suportado também são reconhecidos. Um jogo instalado pela Beta ou Alpha passa para a versão Release por atualização assim que houver uma para a sua cópia.
- Veja qualquer jogo Release, Beta ou Alpha antes de instalar: atividade, atualizações, rankings, conquistas, addons e a contagem ao vivo de jogadores e lobbies, com o botão **INSTALL** na própria página.
- Verificação automática de atualizações dos jogos e do launcher. As atualizações de jogos removem os executáveis antigos que substituem, e os downloads vêm de um servidor perto de você e continuam de onde pararam se a conexão cair.
- Entre com o xb.live (começando pelo online de Midnight Club 3), adicione amigos pela gamertag e veja lobbies ao vivo, eventos da comunidade e avisos do XB Online. Se o xb.live estiver fora do ar, os jogos ainda abrem offline.
- Gerencie os jogos instalados: jogar, abrir os arquivos locais, desinstalar e a aba DLC/Addons, onde cada mod tem um botão On/Off e os créditos de quem fez. **▶ PLAY** abre o jogo com os mods ativados, e os addons continuam funcionando após atualizações do jogo.
- Aba Saves na página de cada jogo com backup, restauração, importação, **Mover…** para uma pasta que você escolher, conversão de save de PS2 (sem precisar de perfil do Xbox) e editores de save para Midnight Club 3 e NINJA GAIDEN Black.
- Saves importados do xemu funcionam mesmo se outro console os assinou: saves de NINJA GAIDEN Black e outros com formato conhecido são reassinados para este PC e listados como não verificados.
- Trilhas sonoras personalizadas: uma tela de Música para criar trilhas e adicionar músicas em MP3, FLAC, Ogg, WAV, M4A ou AAC que todo jogo suportado toca (Midnight Club 3 a partir da atualização 1.0.7).
- Title updates do XB Online e DLCs são instalados automaticamente enquanto o jogo está fechado, e a lista de Add-ons de cada jogo mostra o title update com um botão de ligar/desligar. Jogar online exige o title update: se ele estiver faltando ou desligado, o Play pergunta se você quer baixá-lo (ou ligá-lo de novo) ou jogar offline desta vez.
- Um jogo com DLC na loja do XB Online lista o conteúdo na aba DLC/Addons com Baixar e Remover, e o jogo encontra o DLC na próxima vez que abrir.
- Configurações por jogo no menu do jogo: tela cheia, resolução, VSync, proporção de tela, brilho, contraste, saturação, anti-aliasing, limite de FPS e DirectX 12, DirectX 11 ou Vulkan. Midnight Club 3 também tem sua própria lista de idiomas, incluindo os addons de tradução em português, russo e árabe.
- Tempo de jogo de cada jogo, e EXEs dos jogos que mantêm o mesmo nome entre atualizações, para os perfis do Painel de Controle da NVIDIA continuarem aplicados.
- Nas Configurações você escolhe se fechar a janela deixa o xrevive rodando na bandeja ou fecha o programa. Jogos que reiniciam no title update continuam aparecendo como em jogo, com o tempo de jogo e a sessão online mantidos.
- Configurações > Inspetor de disco lê o título, o title ID, a versão e a região de uma imagem de disco e copia um relatório pronto para colar num bug report.
- O cache de shaders fica com o jogo, então só a primeira abertura compila os shaders.
- Mensagens de erro claras que explicam o que deu errado e como resolver, incluindo um botão **Allow xrevive in Windows Security** quando o Acesso controlado a pastas bloqueia uma instalação.
- Escolha entre 10 idiomas em Configurações > Idioma: inglês, alemão, francês, espanhol, italiano, português do Brasil, russo, árabe, japonês e chinês simplificado. Em árabe a janela toda fica da direita para a esquerda.
- Adicione jogos instalados ao Steam (Configurações ou biblioteca), com capas e Steam Input no Deck.
- Personalize seus jogos: clique com o botão direito em um jogo e abra Gerenciar para escolher seu próprio banner e ícone (PNG ou JPEG). Sem isso, a lista de jogos mostra o ícone de save de cada jogo, tirado do default.xbe, e o Adicionar ao Steam usa a mesma arte.
- Verificação de sistema para Windows 8.1+ e Direct3D 11, com opção de Jogar mesmo assim.
- Os saves do XB Online da antiga pasta `XBL-Hosted` são copiados para a pasta de saves normal de cada jogo quando você aperta Play. Saves existentes nunca são substituídos e nada é apagado; depois de conferir seus saves, você mesmo pode apagar `SaveData\XBL-Hosted`.

## Você traz os jogos

O xrevive não inclui ISOs nem arquivos dos jogos. Use seus próprios arquivos. Esta versão baixa executáveis publicados em vez de compilar os jogos localmente; jogos sem executável disponível podem ser extraídos para uso futuro.

O launcher e o instalador para Windows têm assinatura Authenticode. As atualizações do launcher são assinadas com a chave de atualização do xrevive. Os pacotes para macOS não são notarizados, então avisos de segurança podem aparecer na primeira instalação no macOS.

---

O xrevive é um projeto de fãs, sem afiliação ou endosso da Microsoft.

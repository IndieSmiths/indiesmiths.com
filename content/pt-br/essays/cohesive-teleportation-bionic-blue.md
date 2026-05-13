authors: Kennedy Richard S. Guerra
author-urls: https://kennedyrichard.com/pt-br
keywords: teletransporte
          bionic blue
          desenvolvimento de jogos
          design de jogos
          escrita
          escrita para jogos
description: Ensaio sobre como garantimos que o teletransporte no jogo 2D de plataforma Bionic Blue funcionasse bem com os outros elementos do jogo, sem atrapalhar o design, o jogar e a história/escrita, contribuindo para que o mundo do jogo se tornasse mais crível.
publish-date: 2026-05-13
include-comment-section: True

# Tornando o teletransporte coeso no jogo Bionic Blue

Como um mantenedor de projetos de código aberto com alguns projetos, não é fácil encontrar tempo para deixar todos os elementos de jogo coesos. Mas, às vezes tenho de arriscar não alcançar prazos específicos em favor de deixar o mundo do jogo só um pouquinho mais crível. Hoje queria compartilhar como tentei fazer isso para a ação de teletransportar para dentro e para fora da área da missão (nível).

Como visto abaixo, a primeira coisa que acontece no início duma missão é o Blue teletransportando para a área da missão. Note a antena parabólica próximo ao ponto onde ele aterriza.

<img class="mx-auto d-block" alt="GIF animado mostrando Blue teletransportando para a área da missão próximo a uma antena parabólica." src="https://i.imgur.com/yC9XleP.gif" />

Ao longo da área da missão, Blue encontra outras antenas parabólica e isso é o que acontence quando ele as toca:

<img class="mx-auto d-block" alt="GIF animado mostrando Blue alcançando uma nova antena parabólica na área da missão. Depois de tocá-la, um rótulo/legenda indicando que se trata de um checkpoint é mostrado por alguns segundos." src="https://i.imgur.com/qpMrfFC.gif" />

Em outras palavras, as antenas claramente servem como checkpoints.

Isso é reforçado sempre que a missão reinicia depois que Blue morre:

<img class="mx-auto d-block" alt="GIF animado mostrando Blue avançando na área da missão, morrendo, então depois que a tela escurece a missão reinicia com o Blue teletransportando para a área de missão próximo a uma antena parabólica." src="https://i.imgur.com/jeKOOlC.gif" />

Este detalhe parece trivial, mas pense assim: se personagens pudessem teletransportar para dentro e fora da área da missão sempre e em qualquer lugar que quisessem, por que eles não fariam isso para escapar de ameaças ou teletransportar taticamente próximo a um inimigo desavisado?

É por isso que pensei que seria importante tornar o ato de teletransportar dependente de pontos específicos e decidi que uma antena parabólica seria o mecanismo perfeito para isso.

Além disso, somente a primeira antena parabólica está ligada quando o Blue entra na área da missão. Isso também explica o porquê do personagem não poder teletransportar direto para a área do chefão e ter de avançar por todo o nível a fim de ativar as outras antenas parabólicas, para que possa teletransportar para mais perto do objetivo da próxima vez que a missão reiniciar.

Depois de derrotar o chefão, o personagem também não teletransporta para fora da área imediatamente. Como o teletransporte depende de antenas parabólicas, Blue retorna só um pouquinho a fim de acessar a antena parabólica situada fora da área do chefão, que também foi colocada lá a fim de que Blue pudesse reiniciar a missão bem na entrada da área do chefão caso fosse derrotado pelo chefão.

<img class="mx-auto d-block" alt="GIF mostrando Blue próximo a um robô derrotado. Então ele retorna andando para a antena parabólica que fica do lado de fora do prédio do chefão, depois de passar por algumas comportas e teletransporta para fora da área da missão." src="https://i.imgur.com/m8ncYpI.gif" />


## Palavras finais

Em conclusão, a existência e posicionamento das antenas parabólicas como equipamentos de teletransporte serve não apenas ao design de jogo, mas também à história/escrita, ajudando a fazer o mundo um pouco mais coeso/crível.

Como bônus, deixo as seguintes perguntas para você refletir, algo de que pretendo tratar num texto futuro: e a respeito da escrita/história por trás da morte e reinício da missão? O personagem é imortal? Ele volta no tempo? Deveria o personagem reconhecer que morreu? Ele sequer é ciente disso?

Como sempre, termino pedindo que considere apoiar o projeto. Você pode encontrar links para o [Patreon](https://patreon.com/KennedyRichard), GitHub [sponsors](https://github.com/sponsors/KennedyRichard), [Apoia.se](https://apoia.se/kennedyrichard) e outros serviços adicionais como esses [on this page](https://indiesmiths.com/pt-br/doe).

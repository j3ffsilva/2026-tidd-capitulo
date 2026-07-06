# Estilo de escrita — guia de verificação

Este documento consolida as decisões de estilo tomadas durante a escrita de
`capitulo.md`. Serve para checar qualquer revisão futura deste texto ou de
outros textos do mesmo autor — inclusive por outra IA que não tenha
acompanhado o processo. Não é teoria: cada regra aqui veio de uma decisão
concreta tomada durante a escrita, com exemplo real do que foi corrigido.

## Referência de voz

O autor está desenvolvendo um estilo próprio, inspirado em Bill Bryson e Ruy
Castro, com sobriedade adaptada ao tema (racismo) e ao veículo (capítulo de
livro acadêmico comemorativo). Nem tudo que os dois autores fazem cabe aqui
sem ajuste — mas o instinto de decisão deles é a referência para qualquer
dúvida de estilo que as regras abaixo não cubram.

**Heurística de decisão, quando surgir uma dúvida nova**: perguntar como
Bryson ou Castro decidiriam. Na prática, isso costuma significar:

1. Mostrar em vez de anunciar.
2. Nunca usar palavra difícil por vaidade.
3. Toda palavra tem que pagar aluguel (se não faz trabalho, corta).
4. Um bom exemplo se gasta uma vez só — não repetir a mesma ilustração ou
   anedota duas vezes no mesmo texto.

## Regra central: mostrar, não anunciar

O maior vício a evitar é o texto anunciar o que vai fazer, em vez de fazer.
Sinais de que uma frase está anunciando em vez de mostrando:

- Começa com "é interessante notar que", "vale destacar", "vale reforçar",
  "cabe ressaltar", "não seria interessante saber se".
- Usa a construção "O que X é Y" como muleta ("o que esses estudos mostram é
  que...", "o que existe até aqui é...", "o que todos esses casos têm em
  comum é..."). Quase sempre dá para cortar o "o que... é" e ir direto ao
  verbo.
- Rotula o que a frase seguinte vai fazer ("essa lógica não dissolve o
  problema, ela o confirma" é aceitável porque *mostra* a virada; "esse
  último ponto revelou algo que a análise não capturaria sozinha" é
  anúncio, porque descreve o efeito da frase em vez de só produzir o efeito).

**Exemplos reais corrigidos neste capítulo:**

| Antes (anúncio) | Depois (mostra) |
|---|---|
| "Não seria interessante saber se o conceito de 'negro' está se aproximando..." | "O conceito de 'negro' pode estar se aproximando..." |
| "Colocadas em prosa, essas são perguntas do tipo: a baixa associação..." | "A baixa associação..." (a pergunta começa direto) |
| "O motivo é mais sutil do que parece à primeira vista, e vale a pena separar em duas camadas." | "O motivo tem duas camadas." |
| "Há algo de simbólico em contar essa trajetória num livro que celebra..." | (cortado inteiro — o paralelo already mostra o simbolismo sozinho) |
| "O que todos esses casos têm em comum é o mesmo: uma palavra..." | "Todos esses casos compartilham o mesmo objeto: uma palavra..." |

## Vícios de escrita a caçar em qualquer revisão

1. **Travessões (—).** Não usar. Cada função tem substituto: aposto
   explicativo → parênteses ou vírgula; pausa antes do fecho → dois-pontos;
   enumeração solta → vírgula. Meta: zero travessões no texto final.
2. **Anglicismos por calco** (ex.: "sólido", "robusto" usados como em
   inglês para ideias abstratas). Vocabulário técnico inevitável (embeddings,
   corpus, arquitetura) não conta como anglicismo — é vocabulário do ofício,
   desde que explicado.
3. **Palavras e adjetivos vazios** — os que somem sem fazer falta: "de
   fato", "verdadeiro", "central" (quando não distingue nada), "importante"
   usado como preenchimento em vez de qualificação real. Teste: se a frase
   funciona igual sem a palavra, ela sai.
4. **Frases de "lacração"** — fechos de parágrafo com a arquitetura "não é
   X, é Y" usada como floreio. Usar no máximo uma ou duas vezes no texto
   inteiro, guardadas para onde o efeito realmente importa (o fecho da
   conclusão, por exemplo). Se aparece em quase todo parágrafo, é tique, não
   estilo.
5. **Clichês de transição** — "nesse sentido", "no fundo", "ao mesmo tempo",
   "cabe destacar". Cortar sempre que aparecerem; quase nunca fazem falta.
6. **Vocabulário burocrático/institucional** — linguagem de relatório de
   projeto ou de template de TCC: "referencial teórico" (→ "ideia"),
   "instrumental teórico" (→ "teoria"), "nesse desenho" (→ "aqui"),
   "resultado agregado" (→ "saldo"), "objeto comum" (→ "o que X têm em
   comum"). Soam a documento institucional, não a alguém contando uma
   história.
7. **Repetição de vocabulário sem variação** — palavras-âncora do texto
   (ex.: "vizinhos", "pergunta", "instrumento") podem se repetir quando
   carregam sentido real, mas variar a frase evita cansaço. Atenção especial
   a metáforas: usar a mesma palavra (ex.: "mapa") para duas metáforas
   diferentes no mesmo texto confunde mais do que reforça — nesse caso,
   trocar uma delas por sinônimo ("pistas", em vez de reusar "mapa").
8. **"Isso" como sujeito de frase** — calco de "this means that...", "this
   is...". Ex.: "Isso significa que o resultado é..." Nomear o sujeito real
   em vez de apontar para trás com "isso": "O resultado, na prática, é...".
   "Isso" como objeto ou em expressões idiomáticas ("por isso", "chamar
   isso de", "quanto mais isso acontece") é português normal e não conta
   como vício — o problema é só "isso" abrindo frase como sujeito genérico.
9. **Dois-pontos em excesso na estrutura "afirmação: explicação"** — usado
   uma vez por parágrafo ou mais, vira cadência monótona. Reservar
   dois-pontos para três funções legítimas: introduzir lista real, introduzir
   citação direta, ou marcar o timing de uma piada/fecho de analogia. Fora
   isso, variar entre ponto final, vírgula ou conector ("porque", "já que").
   Meta prática: não deixar mais de ~1 dois-pontos a cada 2-3 parágrafos.

## Humor: tipos e onde cabem

O autor está introduzindo humor de forma controlada, não espontânea. Cinco
tipos, cada um com zona de uso preferencial:

| Tipo | Referência | Onde cabe |
|---|---|---|
| Ironia de justaposição institucional | Ruy Castro | Contradições de instituições (ex.: jornal com comitê de inclusão e coluna "bingo dos privilégios" no mesmo período) |
| Understatement seco | Bryson | Deixar um número ou fato falar sozinho, com um comentário mínimo e calmo |
| Desinflar jargão técnico | Bryson | Explicações de conceito técnico — mostrar que o nome chique esconde algo banal |
| Analogia habitada | Bryson | Ao usar uma metáfora (foto, mapa, cidade), ficar mais um instante dentro dela com um detalhe concreto |
| Comentário lúdico em território neutro | Ambos | Exemplos especulativos sem carga sensível (marca, consumo, tecnologia) — zona de maior liberdade |

**Zona proibida, sempre**: nenhum humor sobre o racismo em si, sobre quem
sofre com ele, ou que trate argumentos de terceiros (mesmo os mais
questionáveis) como matéria de chacota. A ironia mira a contradição factual
de uma instituição ou o exagero de um jargão técnico — nunca o sofrimento ou
a identidade de alguém.

**Zona sem humor, sempre**: o fecho institucional/dedicatório do capítulo
(considerações finais que remetem à celebração dos 20 anos do programa).
Humor ali desarma o peso que o texto passou o capítulo inteiro construindo.

## Regras específicas deste projeto (confidencialidade)

Estas regras existem porque o capítulo descreve uma segunda etapa de
pesquisa ainda não publicada:

- **Nunca nomear a arquitetura/modelo em desenvolvimento.** Sempre por
  perífrase: "uma nova etapa do projeto Zumbi", "uma arquitetura em
  desenvolvimento no laboratório".
- **Sem notação matemática** (nada como `w@t`, `R_t(w)`).
- **Nenhum número, corpus específico ou detalhe de mecanismo** do trabalho
  não publicado — nem em tom especulativo. Isso inclui métricas de
  validação, nomes de palavras-teste usadas internamente, tamanho de
  corpus interno, nomes de checkpoints ou detalhes de arquitetura.
- **Modo condicional sempre que o assunto for a etapa não publicada**
  ("poderia", "permitiria"), nunca presente declarativo que soe como
  resultado já obtido ("o modelo mostra", "os dados revelam").
- **Exemplos de apoio só da literatura pública** (Hamilton et al. 2016,
  Garg et al. 2018, Kulkarni et al. 2015, Steen et al. 2023, Dixon 2000) —
  nunca os exemplos usados nos documentos internos do laboratório (mesmo
  sem citar o projeto pelo nome, um exemplo muito específico pode ser
  reconhecível a quem conhece o material).

## Citação e referências

- Formato ABNT.
- Quando uma citação (ex.: coluna de opinião) foi conhecida apenas através
  de outro artigo, e não verificada na fonte primária, usar `*apud*` e
  manter isso registrado — não fingir verificação direta.
- Preferir o título real da fonte primária (quando disponível na
  bibliografia do artigo original) em vez de descrições genéricas como
  "[Coluna]".

## Estrutura do capítulo (para referência, não regra de estilo)

O capítulo segue um funil: pergunta concreta → ampliação para o problema
geral → volta ao caso concreto → fechamento que reabre a agenda geral antes
do fecho institucional. Detalhes da tese e da estrutura completa estão em
`tmp/planejamento-raiox.md`.

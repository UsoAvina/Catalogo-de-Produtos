# Changelog — Site Avina

Registro de versões do projeto. Sempre que um arquivo de código for
atualizado, uma nova entrada é adicionada aqui, e o arquivo principal
(`index.html`) recebe um cabeçalho com o número da versão, data/hora e a
descrição da mudança.

---

**V21** — Corrigido de vez o desalinhamento dos números: a fonte
Cormorant Garamond não suporta os recursos de OpenType usados
anteriormente (lining/tabular nums), então aquele ajuste não tinha efeito
visual. Agora todos os preços do site (cards do catálogo, zoom de fotos,
modal de compra, resumo do checkout e carrinho lateral) usam uma fonte
serifada com algarismos padronizados (Georgia), garantindo alinhamento
consistente em qualquer lugar que apareça um valor em R$.

**V20** — Corrigido bug no campo "Celular para contato": ao digitar, o
cursor não era reposicionado após a formatação automática, fazendo alguns
celulares selecionarem parte do número digitado — se a pessoa continuasse
digitando, essa parte selecionada era sobrescrita, corrompendo o número
final enviado no pedido. Agora o cursor é mantido na posição correta a
cada tecla digitada.

**V19** — Ajustes de tipografia em todo o site: peso da fonte aumentado
(Cormorant Garamond ficava fina/apagada) para todo o texto, inputs, selects
e botões; algarismos padronizados para "lining nums" tabulares em todo o
site, corrigindo o desalinhamento visual dos números causado pelos
algarismos old-style da fonte; texto de apoio "Confirme seus dados..." da
tela de checkout escurecido para melhor destaque.

**V18** — Ajustes na tela de "Finalizar pedido" e na mensagem do WhatsApp:
mensagem agora começa direto na saudação (sem linha de título); marcador
"▪" (que ainda dava erro em alguns aparelhos) trocado por "➤"; linha em
branco adicionada antes da lista de itens; números do resumo do pedido
agora alinhados (colunas numéricas tabulares); labels dos campos do
formulário com fonte maior e mais escura; campo "Celular para contato"
agora formata automaticamente no padrão (xx) xxxxx-xxxx enquanto o
cliente digita.

**V17** — Mensagem do WhatsApp padronizada: emojis (📦🛍️💰💳🚚📍📱) trocados
por símbolos simples e universalmente compatíveis (▪ para títulos de seção,
- para itens da lista, ➤ para campos de dados), corrigindo o erro de
codificação (losango com interrogação) que aparecia em alguns aparelhos ao
abrir o link do WhatsApp.

**V16** — 08/09/2026 02:29
Adicionado cabeçalho de controle de versão no topo do `index.html`
(título, data/hora, descrição da última mudança e número da versão) e
criado este changelog centralizado.

**V15** — Favicon + ícone de tela inicial (iPhone/Android) + `manifest.json`.

**V14** — Textos da tela de "Finalizar pedido" aumentados (rótulos, campos,
resumo do pedido e total).

**V13** — Mensagem do WhatsApp com formato final mesclado (saudação com
emoji, nome do produto em negrito, abreviação "Tam:", endereço só quando
aplicável).

**V12** — Mensagem do WhatsApp reorganizada: negrito nos rótulos, ícones
por seção, separador de milhar no preço, título de identificação.

**V11** — Fluxo de checkout completo: tela de dados finais do cliente
(nome, pagamento, entrega, celular, endereço) e envio automático do
pedido formatado para o WhatsApp da loja.

**V10** — Sistema de produtos por tag + CSV: catálogo passa a ser
controlado pelo arquivo `produtos.csv` e pela pasta `fotos/`, com
descoberta automática de imagens por tag. Criados `produtos.csv` de
exemplo e o guia `COMO-ATUALIZAR-PRODUTOS.md`. Arquivo principal
renomeado para `index.html`.

**V9** — Preço aumentado em todas as telas do site (cartão, zoom, modal
de compra).

**V8** — Preço e botões "Comprar" / "Adicionar ao Carrinho" aumentados.

**V7** — Cada produto passa a ficar dentro de um cartão delimitado
(fundo, borda e leve sombra ao passar o mouse).

**V6** — Faixa de filtros refinada: mais fina, texto maior, marcação
discreta (fundo suave) no item ativo em vez de sublinhado.

**V5** — Fonte Cormorant Garamond aplicada em todo o site (antes só nos
nomes dos produtos).

**V4** — Faixa de filtros com destaque: fundo escuro sólido, texto maior
e com mais contraste.

**V3** — Logo da Avina incorporada diretamente no código em base64 (fundo
removido, recortada).

**V2** — Tentativa de logo via link do Google Drive (não funcionou —
Google bloqueia esse tipo de link direto).

**V1** — Modelo inicial do site: catálogo estilo revista, logo central,
carrinho, filtros por categoria, zoom de fotos, modal de compra e
carrinho lateral.

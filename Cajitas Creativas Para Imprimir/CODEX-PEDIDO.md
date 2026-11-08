# Pedido de imagens ao Codex — Cajitas Creativas Para Imprimir

Gerado de `padronizacao/CODEX-PEDIDO.modelo.md`. O Codex produz **exatamente** estas 22 imagens (formatos definidos no manifesto, PNG), com o **nome** e na **pasta** indicados. Regras globais e regra de prova social: ver o modelo.

## Manifesto
```json
{
  "produto": "Cajitas Creativas Para Imprimir",
  "slug": "cajitas-creativas-para-imprimir",
  "idioma": "es-LATAM",
  "paleta": {
    "primary": "#b5542e"
  },
  "imagens": [
    {
      "slot": "hero",
      "tipo": "mockup",
      "arquivo": "cajitas-creativas-para-imprimir.png",
      "destino": "mockups/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-hero"
    },
    {
      "slot": "adv",
      "tipo": "foto-tema",
      "arquivo": "imagem-fundo.png",
      "destino": "mockups/",
      "tamanho": "1440x1080",
      "fundo": "manter",
      "prompt_ref": "P-adv"
    },
    {
      "slot": "bono-1",
      "tipo": "mockup",
      "arquivo": "bono-1.png",
      "destino": "mockups/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-bono-1"
    },
    {
      "slot": "bono-2",
      "tipo": "mockup",
      "arquivo": "bono-2.png",
      "destino": "mockups/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-bono-2"
    },
    {
      "slot": "bono-3",
      "tipo": "mockup",
      "arquivo": "bono-3.png",
      "destino": "mockups/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-bono-3"
    },
    {
      "slot": "bono-4",
      "tipo": "mockup",
      "arquivo": "bono-4.png",
      "destino": "mockups/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-bono-4"
    },
    {
      "slot": "bono-5",
      "tipo": "mockup",
      "arquivo": "bono-5.png",
      "destino": "mockups/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-bono-5"
    },
    {
      "slot": "super-1",
      "tipo": "mockup",
      "arquivo": "super-bono-1.png",
      "destino": "mockups/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-super-1"
    },
    {
      "slot": "super-2",
      "tipo": "mockup",
      "arquivo": "super-bono-2.png",
      "destino": "mockups/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-super-2"
    },
    {
      "slot": "bundle",
      "tipo": "bundle",
      "arquivo": "mockup-all.png",
      "destino": "mockups/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-bundle"
    },
    {
      "slot": "testimonio-1",
      "tipo": "prova-social",
      "arquivo": "whatsapp-carolina.png",
      "destino": "html/img/",
      "tamanho": "760x1559",
      "fundo": "manter",
      "prompt_ref": "P-testimonio-1"
    },
    {
      "slot": "testimonio-2",
      "tipo": "prova-social",
      "arquivo": "whatsapp-diego.png",
      "destino": "html/img/",
      "tamanho": "760x1559",
      "fundo": "manter",
      "prompt_ref": "P-testimonio-2"
    },
    {
      "slot": "testimonio-3",
      "tipo": "prova-social",
      "arquivo": "whatsapp-lucia.png",
      "destino": "html/img/",
      "tamanho": "760x1559",
      "fundo": "manter",
      "prompt_ref": "P-testimonio-3"
    },
    {
      "slot": "ob-1",
      "tipo": "capa-orderbump",
      "arquivo": "capa_orderbump-1.png",
      "destino": "orderbump/produto1/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-ob-1"
    },
    {
      "slot": "ob-2",
      "tipo": "capa-orderbump",
      "arquivo": "capa_orderbump-2.png",
      "destino": "orderbump/produto2/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-ob-2"
    },
    {
      "slot": "ob-3",
      "tipo": "capa-orderbump",
      "arquivo": "capa_orderbump-3.png",
      "destino": "orderbump/produto3/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-ob-3"
    },
    {
      "slot": "ob-4",
      "tipo": "capa-orderbump",
      "arquivo": "capa_orderbump-4.png",
      "destino": "orderbump/produto4/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-ob-4"
    },
    {
      "slot": "combo",
      "tipo": "combo",
      "arquivo": "capa_combo_de_oro.png",
      "destino": "orderbump/produto5/",
      "tamanho": "1080x1080",
      "fundo": "branco",
      "prompt_ref": "P-combo"
    },
    {
      "slot": "criativo-1",
      "tipo": "criativo",
      "arquivo": "criativo-1.png",
      "destino": "criativos/",
      "tamanho": "1080x1080",
      "fundo": "manter",
      "prompt_ref": "P-criativo-1"
    },
    {
      "slot": "criativo-2",
      "tipo": "criativo",
      "arquivo": "criativo-2.png",
      "destino": "criativos/",
      "tamanho": "1080x1080",
      "fundo": "manter",
      "prompt_ref": "P-criativo-2"
    },
    {
      "slot": "criativo-3",
      "tipo": "criativo",
      "arquivo": "criativo-3.png",
      "destino": "criativos/",
      "tamanho": "1080x1920",
      "fundo": "manter",
      "prompt_ref": "P-criativo-3"
    },
    {
      "slot": "criativo-4",
      "tipo": "criativo",
      "arquivo": "criativo-4.png",
      "destino": "criativos/",
      "tamanho": "1080x1920",
      "fundo": "manter",
      "prompt_ref": "P-criativo-4"
    }
  ]
}
```

## Prompts completos

### P-hero · hero

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Cajitas Creativas Para Imprimir", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-adv · adv

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1440x1080, PNG, paleta principal #b5542e. Produza fotografia ilustrativa paisagem sobre "Plantillas de cajitas listas para imprimir en casa, recortar y armar en minutos. Cajitas con ventana, dulceras y de regalo para cumpleaños, bodas y detalles, aunque nunca hayas hecho una manualidad.", sem livros, telas ou dispositivos. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-bono-1 · bono-1

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Guía de Impresión y Armado Perfecto", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-bono-2 · bono-2

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Kit de Etiquetas y Tarjetas de Regalo", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-bono-3 · bono-3

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Catálogo de Ideas de Decoración", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-bono-4 · bono-4

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Guía de Colores y Combinaciones", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-bono-5 · bono-5

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Plantillas de Moños y Lazos de Papel", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-super-1 · super-1

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Cajitas para Cada Ocasión: Guía de Temporada", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-super-2 · super-2

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Presenta y Ofrece tus Cajitas con Estilo", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-bundle · bundle

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Todo lo que recibes: Cajitas Creativas Para Imprimir", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-testimonio-1 · testimonio-1

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 760x1400, PNG, paleta principal #b5542e. Produza conversa informativa fictícia em formato de WhatsApp sobre "Cajitas Creativas Para Imprimir". A pessoa apenas pergunta sobre o conteúdo e recebe resposta factual; não afirma compra, uso ou resultado. Sem status e com horários naturais e espaçados. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-testimonio-2 · testimonio-2

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 760x1400, PNG, paleta principal #b5542e. Produza conversa informativa fictícia em formato de WhatsApp sobre "Cajitas Creativas Para Imprimir". A pessoa apenas pergunta sobre o conteúdo e recebe resposta factual; não afirma compra, uso ou resultado. Sem status e com horários naturais e espaçados. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-testimonio-3 · testimonio-3

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 760x1400, PNG, paleta principal #b5542e. Produza conversa informativa fictícia em formato de WhatsApp sobre "Cajitas Creativas Para Imprimir". A pessoa apenas pergunta sobre o conteúdo e recebe resposta factual; não afirma compra, uso ou resultado. Sem status e com horários naturais e espaçados. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-ob-1 · ob-1

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Bolsas de Regalo para Imprimir", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-ob-2 · ob-2

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Sobres y Tarjetas de Invitación", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-ob-3 · ob-3

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Cajas para Envíos y Pedidos", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-ob-4 · ob-4

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Planner de Eventos y Pedidos", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-combo · combo

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza mockup editorial profissional de "Combo de Oro", com fundo branco liso e margem segura. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-criativo-1 · criativo-1

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza criativo publicitário 1:1 destacando "Cajitas Creativas Para Imprimir, variante criativa 1", sem preço e sem promessa. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-criativo-2 · criativo-2

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza criativo publicitário 1:1 destacando "Cajitas Creativas Para Imprimir, variante criativa 2", sem preço e sem promessa. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-criativo-3 · criativo-3

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza criativo publicitário 1:1 destacando "Cajitas Creativas Para Imprimir, variante criativa 3", sem preço e sem promessa. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.

### P-criativo-4 · criativo-4

Crie uma imagem em espanhol LATAM para o produto "Cajitas Creativas Para Imprimir". Formato 1080x1080, PNG, paleta principal #b5542e. Produza criativo publicitário 1:1 destacando "Cajitas Creativas Para Imprimir, variante criativa 4", sem preço e sem promessa. Não inclua preço, desconto, promessa de resultado, prazo milagroso, marca de terceiros, rosto real identificável, conteúdo sexual, religioso ou de apostas. Texto curto, correto e legível.


> O Codex NÃO faz: galeria (print do PDF no `concluir`) nem checkout (Canva).

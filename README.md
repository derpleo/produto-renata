# produto-renata — pasta-lote

Pasta-lote de produtos (irmã de `produto-joao`). **Todo o trabalho deste lote acontece AQUI**
(não mais no staging `claude-produtos/produto/`). Entrega final no **modelo antigo**
(`Página de Vendas/`, `Produto Principal/`, `Order Bumps/`, `Criativos/`, `Checkout/`, `_extras/`).

## Mineração de origem
Rodada **`../../claude-produtos/mineracao-2026-11-07/`** (RadarAds.pro + verificação de link).
Diferenciação **dispensada** (repetição com Fábrica/joao autorizada). Critério: link verificado no ar.

## Os 5 produtos — estado atual (07/11/2026)
Fase **BUILD (landing + materiais) FEITA e verificada.** Landing (`--prompts --layout --cta` = TUDO
PASSA) + materiais (PDFs Gamma + planilhas .xlsx locais), 0 falhas de integridade. Formato por item:
guías = PDF; ferramentas (inventário/KPIs/agenda/checklists) = planilha .xlsx (dashboard local, grátis).

| # | Produto (es-LATAM) | Tema | Landing | Materiais | Tipo |
|---|---|---|---|---|---|
| 1 | El Arte de Tratar con Personas Difíciles | Azul pizarra | ✅ | 12 PDF | guías |
| 2 | Del Caos al Control Logístico | Azul petróleo | ✅ | 8 PDF + 4 xlsx | guías + planilhas |
| 3 | Cajitas Creativas para Imprimir | Terracota | ✅ | 12 PDF | guías |
| 4 | Laminado de Cejas Profesional | Rosa-vino | ✅ | 10 PDF + 2 xlsx | guías + planilhas |
| 5 | Automaquillaje Base Perfecta | Rosa malva | ✅ | 12 PDF | guías |

Total: 54 PDFs + 6 planilhas. Custo Gamma do lote ≈ 3.624 créditos.
Check-in de conformidade (07/11): sem vídeo, sem professor/experto falso, sem número inflado, sem
renda/cura garantida. Ajuste aplicado: super bônus de renda do Cajitas suavizado.

## Próximos passos (sob comando explícito)
1. **Imagens** (Codex) via `orquestrador` (handoff dos 22 slots por produto).
2. **Conclusão** (`concluir` → `pronto` → `para-modelo-antigo.sh`) → entrega no modelo antigo.
3. (Checkout Canva ¡FELICITACIONES!, trilha manual.)

# Waves Lab

MVP do primeiro game do Waves Lab para a persona **Serralheiro**.

## Fluxo

1. Abertura: “Só quem trabalha com isso sabe.”
2. Pergunta 1: maior dor — disco acabar rápido x retrabalho.
3. Ramificação real:
   - Abrasivos: velocidade x durabilidade → tipo de disco mais usado.
   - Solda/retrabalho: causa do retrabalho → processo mais usado.
4. Resultado personalizado.
5. Benchmark: só exibirá percentuais quando houver base real suficiente.
6. Próximo passo: teste comparativo ou indicação comercial.

## Tracking preparado

O front-end já dispara eventos `WavesLabStart`, `WavesLabAnswer`, `WavesLabComplete` e `WavesLabCTA` para `dataLayer`/`fbq` quando esses scripts estiverem instalados. Também registra uma cópia local no navegador para testes.

## Próximas integrações

- banco de dados para consolidar respostas reais;
- dashboard/benchmark;
- WhatsApp comercial;
- Meta Pixel/Conversions API;
- testes comparativos por produto.

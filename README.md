# Minhas Contas

App mobile (PWA) para controlar contas do mês: o que já foi pago e o que está a vencer.

## Funcionalidades

- Contas **fixas** (recriadas todo mês) e **extras**
- Marcar como paga com um toque
- Progresso do mês por **quantidade** de contas (valor opcional)
- Alertas de atrasadas e vencendo em breve
- Tema claro / escuro
- Backup exportar / importar JSON
- Instalável na tela inicial do celular

## Como usar

### No computador

Abra `index.html` no navegador, ou sirva a pasta:

```bash
npx --yes serve .
```

### No celular (PWA)

1. Hospede o projeto (GitHub Pages, Netlify, etc.) ou use a mesma rede com um servidor local
2. Abra o link no Chrome/Safari
3. **Adicionar à tela inicial**

## Estrutura

- `index.html` — app completo
- `manifest.json` + `service-worker.js` — PWA
- `icone-app.png` / `icon-*.png` — ícones

Os dados ficam salvos no aparelho (`localStorage`).

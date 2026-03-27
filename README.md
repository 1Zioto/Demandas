# Vipe Demandas

Sistema de gerenciamento de demandas de desenvolvimento da Vipe Transportes.

## Deploy no Vercel

Este projeto é um site estático puro — sem build necessário.

```bash
vercel --prod
```

Na configuração do projeto, garanta:
- **Framework Preset:** Other
- **Output Directory:** public
- **Build Command:** (vazio)
- **Install Command:** (vazio)

## Estrutura

```
public/
  index.html   ← app completo em um único arquivo
vercel.json    ← aponta outputDirectory para public/
```

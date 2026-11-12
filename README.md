# Curta Mais Poa 2.0

Aplicativo de turismo e vida urbana de Porto Alegre/RS (Android, iOS e Web), com mapa 3D realista estilo "jogo": o usuário se move a pé, de carro, Uber ou patinete e descobre lotação de locais, eventos e ofertas em tempo real, conforme seu perfil.

## Estrutura
| Pasta | Conteúdo |
|---|---|
| `apps/web-prototype` | Protótipo navegável (abra `index.html` no navegador) |
| `apps/mobile` | App real: Expo + React Native + TypeScript (Android, iOS e Web) |
| `apps/merchant-portal` | Portal do comerciante (divulgar serviços, eventos, ofertas) |
| `services/api` | API (Node + TypeScript + PostgreSQL/PostGIS) |
| `packages/shared` | Tipos compartilhados (POI, Evento, Perfil) |
| `data` | Dados de exemplo (`pois.json`) |
| `docs` | Visão, arquitetura, design system, roadmap |

## Rodando o protótipo
Abra `apps/web-prototype/index.html`. Sem instalação.

## Publicar no GitHub
```bash
git init && git add . && git commit -m "Curta Mais Poa 2.0 - estrutura inicial"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/curta-mais-poa.git
git push -u origin main
```

> Os dados de lotação e eventos do protótipo são fictícios, apenas para demonstração.

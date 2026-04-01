# GeoCalor Portal

Portal web estático do projeto **GeoCalor** — LAGAS/UnB, listando todos os dashboards interativos desenvolvidos no projeto.

## Sobre

Este portal replica o esquema visual do site [LAGAS/UnB](https://lagas.sites.homologa.unb.br/) e centraliza os links para todos os painéis do projeto GeoCalor, incluindo o novo painel integrado desenvolvido em Python/Dash.

## Dashboards disponíveis

| Dashboard | Link | Tecnologia |
|---|---|---|
| **GeoCalor Dash — Painel Integrado** | https://geocalor-dash.onrender.com | Python/Dash |
| Página Inicial e Membros | https://dash-inicio.onrender.com | Python/Dash |
| Temperaturas | https://dash-temp.onrender.com | Python/Dash |
| Ondas de Calor | https://pibic-analise-ondas.onrender.com | Python/Dash |
| Eventos Extremos | https://pibic-extremo.onrender.com | Python/Dash |
| Sistemas de Alerta | https://sistemas-de-alertas.onrender.com | Python/Dash |
| SIH – Internações | https://saude-sih.onrender.com | Python/Dash |
| Saúde Mental (SIA) | https://saude-mental-sia-s9ro.onrender.com | Python/Dash |
| SRAG | https://saude-srag-data.onrender.com | Python/Dash |

## Estrutura

```
geocalor-portal/
├── index.html              # Página principal do portal
├── assets/
│   ├── css/
│   │   └── style.css       # Estilos (esquema visual LAGAS/UnB)
│   └── img/
│       ├── lagasLogo.png   # Logo LAGAS
│       ├── unb.png         # Logo UnB
│       ├── fiocruz.jpg     # Logo Fiocruz
│       ├── cnpq.png        # Logo CNPq
│       ├── pagina_inicial.png
│       ├── temperaturas.png
│       ├── ondas_calor.png
│       ├── extremos.png
│       ├── sistemas_alertas.png
│       ├── sih.png
│       ├── sia.png
│       └── srag.png
└── README.md
```

## Deploy (GitHub Pages)

Este portal pode ser publicado gratuitamente via GitHub Pages:

1. Acesse **Settings → Pages** no repositório
2. Em **Source**, selecione `main` / `/ (root)`
3. Clique em **Save**

O portal estará disponível em: `https://Diegoricardox.github.io/geocalor-portal/`

## Referências

- Porto, B. et al. (2024). [PLOS ONE, 19(1), e0295766](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0295766)
- Porto, B. et al. (2025). [Zenodo](https://zenodo.org/records/15102791)

## Créditos

**Desenvolvimento:** Diego Ricardo Xavier | OCS/ICICT/Fiocruz  
**Projeto:** LAGAS — Laboratório de Geografia, Ambiente e Saúde | UnB  
**Financiamento:** CNPq — PIBIC/UnB 2023–2024

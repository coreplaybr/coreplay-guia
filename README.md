# coreplay-guia

Guia de instalação da **CorePlay TV** (IPTV) na Smart TV Samsung e LG, TV Box Android, celular e computador, publicado com MkDocs no Read the Docs.

Site: [coreplay.vc](https://coreplay.vc/?utm_source=github&utm_medium=referral&utm_campaign=blog_da) · Planos a partir de R$ 24,90 · Teste Grátis de 6 horas

## Páginas

- [Smart TV Samsung e LG](docs/smart-tv-samsung-lg.md)
- [TV Box Android](docs/tv-box-android.md)
- [Celular](docs/celular.md)
- [Computador](docs/computador.md)
- [Perguntas frequentes](docs/perguntas-frequentes.md)

## Gerar o site localmente

```bash
python -m venv .venv
. .venv/bin/activate
pip install -r docs/requirements.txt
mkdocs serve      # pré-visualização em http://127.0.0.1:8000
mkdocs build      # gera a pasta site/
```

## Read the Docs

O arquivo `.readthedocs.yaml` (versão 2) já está configurado para build com MkDocs. Basta importar o repositório no Read the Docs.

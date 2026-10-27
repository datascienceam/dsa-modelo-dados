# dsa-modelo-dados
[TEMA]

## O que há aqui

- `scripts/`: scripts de coleta e tratamento
- `catalog.yml`: catálogo de datasets (fonte, URL, formato, licença, observações)
- `notebooks/`: exemplos de uso em Jupyter
- `data/sample/`: amostras pequenas para teste (os dados completos não ficam no Git)

## Fontes

[FONTE]

A lista completa e atualizada está em [`catalog.yml`](catalog.yml).

## Como usar

```bash
git clone https://github.com/datascienceam/dsa-modelo-dados.git
cd dsa-modelo-dados
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt

python scripts/[script.py]
```


Os arquivos baixados ficam em `data/raw/` e o resultado tratado, em formato
Parquet, em `data/processed/`. Ambos são ignorados pelo Git.

## Metodologia

[METODOLOGIA]

## Licenças

- **Código:** MIT (ver `LICENSE`).
- **Dados:** pertencem às fontes originais e seguem as respectivas
  licenças e termos de uso, registrados no `catalog.yml`. Cite sempre a
  fonte primária.

## Como contribuir

Contribuições são bem-vindas: novas fontes no catálogo, correções nos
scripts e exemplos em notebooks. Abra uma *issue* para discutir ou envie
um *pull request*. Novas fontes devem trazer URL, formato, licença e uma
nota de metodologia.

## Sobre a comunidade

A Data Science Amazônia é uma comunidade aberta, sem fins lucrativos, que
explora o potencial científico, acadêmico e tecnológico da Amazônia por
meio de ciência de dados e inteligência artificial.
Instagram: [@datascienceamazonia](https://instagram.com/datascienceamazonia)

# Revisão Sistemática — Bactérias com Potencial Antifúngico

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15899985.svg)](https://doi.org/10.5281/zenodo.15899985)

Este repositório contém os dados curados e os scripts utilizados na análise de uma revisão sistemática sobre o uso de bactérias com atividade antifúngica em contextos agrícolas e alimentares.

## 📑 Objetivo

Investigar, sistematizar e analisar publicações científicas que descrevem o potencial antifúngico de bactérias, utilizando um conjunto de critérios e filtros para curadoria dos dados. O repositório visa garantir a reprodutibilidade das análises realizadas e facilitar o compartilhamento com a comunidade científica.

## 🗂️ Estrutura do Repositório

```
RevisaoSistematica_BacteriasAntifungicas/
│
├── data/                         # Dados utilizados na análise
│   └── dados_limpos.xlsx        # Planilha de dados curados extraídos dos artigos
│
├── scripts/                     # Notebooks e scripts de análise
│   └── analise_visual_revisao.ipynb
│
├── LICENSE                      # Licença do código (MIT)
├── requirements.txt            # Pacotes necessários para reproduzir a análise
└── README.md                    # Este arquivo
```

## 📊 Dados

O arquivo `data/dados_limpos.xlsx` contém os registros extraídos manualmente de artigos científicos, organizados com as seguintes colunas principais:
- Título do artigo
- Autor(es)
- Ano
- Bactéria(s) investigada(s)
- Potencial antifúngico (positivo, negativo ou inconclusivo)
- Agente(s) fúngico(s) alvo
- Origem da bactéria
- Tipo de estudo
- Mecanismo antifúngico descrito

> 📌 Os dados estão compartilhados sob a licença [MIT License](LICENSE).

## 🧪 Execução da Análise

O notebook principal `scripts/analise_visual_revisao.ipynb` realiza:
- Leitura e validação da planilha de dados
- Geração de estatísticas descritivas
- Visualização gráfica (frequência, coocorrência, distribuição por ano)

### ▶️ Como executar

1. Clone o repositório:
```bash
git clone https://github.com/marcioabrm/RevisaoSistematica_BacteriasAntifungicas.git
cd RevisaoSistematica_BacteriasAntifungicas
```

2. Crie um ambiente virtual (opcional, mas recomendado):
```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Execute o notebook:
```bash
jupyter notebook scripts/analise_visual_revisao.ipynb
```

## 📜 Licença

- Código e scripts estão sob a licença [MIT License](LICENSE)
- Dados científicos curados estão sob [MIT License](LICENSE)

## 📊 Dados

Os dados curados utilizados nesta análise estão disponíveis em formato `.xlsx` neste repositório e também foram arquivados na plataforma Zenodo, com o seguinte DOI:

🔗 [https://doi.org/10.5281/zenodo.15899985](https://doi.org/10.5281/zenodo.15899985)


## 🤝 Contribuição

Contribuições são bem-vindas! Se você identificar erros, sugestões ou quiser expandir a análise, sinta-se à vontade para abrir uma *issue* ou *pull request*.

---

**Autor**: Márcio de A. Moreira  
**Contato**: [github.com/marcioabrm](https://github.com/marcioabrm)

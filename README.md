# Dashboard DCSPT - GitHub Pages

Este pacote foi preparado para publicação direta no GitHub Pages.

## Ficheiros necessários

Coloca estes dois ficheiros na mesma pasta/repositório:

```text
index.html
inputdcspt_All.xlsx
```

Depois ativa o GitHub Pages no repositório. Quem abrir o link verá diretamente os resultados; não há seletor de ficheiro nem parâmetro para carregar outro Excel.

## Como atualizar dados

Para atualizar os resultados, substitui apenas o ficheiro:

```text
inputdcspt_All.xlsx
```

Mantém o mesmo nome do ficheiro e a estrutura da primeira folha do Excel. O dashboard lê automaticamente a primeira folha e deteta:

- dados das UCs: ID, UC, semestre, curso, área e outros metadados disponíveis;
- colunas de docentes: colunas com valores de preferência entre 1 e 5.

## Dependência externa

O `index.html` usa a biblioteca SheetJS a partir de CDN para ler o Excel no browser. Em GitHub Pages isto funciona normalmente com ligação à internet.

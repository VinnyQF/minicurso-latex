# minicurso-latex

Repositório contendo o minicurso de LaTeX lecionado na Unijorge como parte do curso de férias realizado em fevereiro de 2026.

## Navegação Básica

O repositório está organizado da seguinte forma:

### Código Fonte
Código fonte utilizado para o desenvolvimento dos PDFs deste projeto.

#### Passos para Compilação

##### Pré-requisitos
Para compilar os documentos deste repositório, é necessário ter uma distribuição LaTeX instalada:

- TeX Live (Linux / Windows)
- MacTeX (macOS)

Além disso, garanta que a sua distribuição tenha todos os pacotes presentes no código fonte instalados.

##### Compilação padrão

Para gerar o PDF a partir do arquivo principal (`.tex`), utilize:

```bash
pdflatex main.tex
```

Caso o documento tenha algum arquivo `bibtex` para referências bibliográficas:

``` bash
pdflatex main.tex 
bibtex main 
pdflatex main.tex 
pdflatex main.tex
```

Alternativamente, uma IDE como TexStudio ou Overleaf (IDE online), deve ser capaz de compilar esses documentos.
### PDFs
Todo o conteúdo já em formato PDF, para fácil acesso e consulta.

### Materiais para Consulta
- [Documentação oficial da classe abntex2](https://br.mirrors.cicku.me/ctan/macros/latex/contrib/abntex2/doc/abntex2.pdf)
- [Espelho alternativo da documentação abntex2](https://uenf.br/posgraduacao/matematica/wp-content/uploads/sites/14/2017/09/abntex2.pdf)
- [Documentação do pacote abntex2cite](https://tug.ctan.org/macros/latex/contrib/abntex2/doc/abntex2cite.pdf)
- [Template oficial de conferências da SBC](https://github.com/cezarlamann/sbc-latex-template)

## Espelho do Material
[Link para o Proton Drive da disciplina](https://drive.proton.me/urls/59D9KC9WE0#ourbr9aktHC2)

# 📄 RMarkdown Templates

[![Acessar Versão Web](https://img.shields.io/badge/gh--pages-Visualizar%20Site-blue?logo=github)](https://github.com/costandrad/template-solucionario-rmd/tree/gh-pages)

Bem-vindo ao repositório de templates de arquivos RMarkdown!
Este repositório contém modelos customizados que utilizam um arquivo LaTeX (template.tex) para formatação, permitindo a geração de documentos bem estruturados com suporte à execução de código tanto em R quanto em Python — ideal para análises reprodutíveis e relatórios técnicos.

## 🌱 Origem e Melhorias

Este repositório é um fork do projeto original de [iandrade-uft/template-solucionario-rmd](https://github.com/iandrade-uft/template-solucionario-rmd).

As principais melhorias implementadas incluem:
* 📁 Reorganização da estrutura de pastas
* ⚙️ Suporte completo a código R e Python dentro dos arquivos .Rmd

## 📂 Estrutura do Código Científico

```bash

.
├── output/ # Documentos gerados
│ ├── template_using_python.pdf
│ └── template_using_r.pdf
│
├── src/ # Arquivos-fonte
│ ├── template_using_python.Rmd
│ └── template_using_r.Rmd
│
└── template.tex # Template LaTeX

```


## 🚀 Como Usar
```bash
# Compilar no RStudio ou via CLI:

rmarkdown::render("src/template_using_r.Rmd")  # Para versão R

rmarkdown::render("src/template_using_python.Rmd")  # Para versão Python
```

## 🌐 Website GH Pages

A página de apresentação deste projeto está disponível na branch [gh-pages](https://github.com/costandrad/template-solucionario-rmd/tree/gh-pages).

## 📄 Licença

MIT - Veja [LICENSE](https://license.txt/).


## 🧑‍💻 Autor

### Igo da Costa Andrade

<p align="left"> 
  <a href="https://costandrad.github.io/"> 
    <img src="https://img.shields.io/badge/GitHub%20Pages-gray?logo=github" alt="Github Pages">   
  </a> 
  <a href="mailto:costandrad@gmail.com"> 
    <img src="https://img.shields.io/badge/Email-white?logo=gmail" alt="Email"> 
  </a> 
  <a href="http://lattes.cnpq.br/9812776894168057"> 
    <img src="https://img.shields.io/badge/Lattes-blue?logo=google-scholar&logoColor=white" alt="Lattes"> 
  </a> 
</p>
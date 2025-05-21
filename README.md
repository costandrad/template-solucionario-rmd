# 📄 RMarkdown Templates

Bem-vindo ao repositório de templates de arquivos RMarkdown!
Este repositório contém modelos customizados que utilizam um arquivo LaTeX (template.tex) para formatação, permitindo a geração de documentos bem estruturados com suporte à execução de código tanto em R quanto em Python — ideal para análises reprodutíveis e relatórios técnicos.

## 🌱 Origem e Melhorias

Este repositório é um fork do projeto original de [iandrade-uft/template-solucionario-rmd](https://github.com/iandrade-uft/template-solucionario-rmd).

As principais melhorias implementadas incluem:

 * 📁 Reorganização da estrutura de pastas, com separação clara entre ativos estáticos, código-fonte e arquivos gerados;

 * 🌐 Inclusão de uma página HTML (index.html) para apresentação do projeto via GitHub Pages;

 * ⚙️ Suporte completo a código R e Python dentro dos arquivos .Rmd.

## 📂 Estrutura do Repositório

    .
    ├── assets/                         # Recursos estáticos para a página HTML
    │   ├── css/                        # Estilos CSS
    │   ├── img/                        # Imagens utilizadas
    │   └── js/                         # Scripts JavaScript
    │
    ├── vendor/                         # Dependências de terceiros (se aplicável)
    │
    ├── output/                         # Documentos gerados
    │   ├── template_using_python.pdf   # PDF gerado com código em Python
    │   └── template_using_r.pdf        # PDF gerado com código em R
    │
    ├── src/                            # Arquivos-fonte dos documentos
    │   ├── template_using_python.Rmd   # RMarkdown com código em Python
    │   └── template_using_r.Rmd        # RMarkdown com código em R
    │
    ├── template.tex                    # Template LaTeX usado na formatação final
    ├── index.html                      # Página de apresentação (GH Pages)
    ├── .gitignore                      # Arquivo de exclusão do Git
    ├── LICENSE.txt                     # Licença do projeto
    └── README.md                       # Este arquivo de documentação

## 🚀 Como Usar

Para usar os templates deste repositório, siga os passos abaixo:

1. Clone o repositório:

        git clone https://github.com/costandrad/template-solucionario-rmd.git

2. Acesse o diretório clonado:

        cd template-solucionario-rmd

3. Escolha e edite um dos arquivos .Rmd:

3.1 Para Python: 

        src/template_using_python.Rmd

3.2 Para R: 
        
        src/template_using_r.Rmd

4. Compile o documento no RStudio ou usando o `rmarkdown::render()`  no console do R.


## 📄 Licença

Este projeto está licenciado sob a licença MIT.
Confira o arquivo LICENSE.txt para mais informações.

## 📬 Contato

Autor: Igo da Costa Andrade
<p align="left">


  <a href="mailto:costandrad@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-white?logo=gmail&width=200&height=36" alt="Email" style="vertical-align:top;">
  </a>


</p>

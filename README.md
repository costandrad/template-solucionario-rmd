# 📄 RMarkdown Templates

Bem-vindo ao repositório de templates de arquivos RMarkdown!
Este repositório contém modelos customizados que utilizam um arquivo LaTeX (template.tex) para formatação, permitindo a geração de documentos bem estruturados com suporte à execução de código tanto em R quanto em Python — ideal para análises reprodutíveis e relatórios técnicos.
🌱 Origem e Melhorias

Este repositório é um fork do projeto original de iandrade-uft/template-solucionario-rmd.

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

    Clone o repositório:

git clone https://github.com/costandrad/template-solucionario-rmd.git

Acesse o diretório clonado:

    cd template-solucionario-rmd

    Escolha e edite um dos arquivos .Rmd:

        Para Python: src/template_using_python.Rmd

        Para R: src/template_using_r.Rmd

    Compile o documento no RStudio ou usando o rmarkdown::render() no console do R.


## 📄 Licença

Este projeto está licenciado sob a licença MIT.
Confira o arquivo LICENSE.txt para mais informações.

## 📬 Contato

Autor: Igo da Costa Andrade
E-mail: costandrad@gmail.com
GitHub Pages: https://costandrad.github.io/

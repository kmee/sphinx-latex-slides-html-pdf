# sphinx-latex-slides-html-pdf
Imagem usada para gerar material de treinamento em Slides, HTML e PDF

Usando:

docker pull kmee/sphinx-latex-slides-html-pdf (docker hub)
docker run --rm -v /home/mileo/Projects/Treinamento/oca-days-2020-odoo-developer:/docs kmee/sphinx-latex-slides-html-pdf  make slides latexpdf html dir=docs

OU

docker pull ghcr.io/kmee/sphinx-latex-slides-html-pdf:main
docker run --rm -v /home/mileo/Projects/Treinamento/oca-days-2020-odoo-developer:/docs ghcr.io/kmee/sphinx-latex-slides-html-pdf:main  make slides latexpdf html dir=docs

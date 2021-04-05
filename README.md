# Detectron for PPT files

------

Aluno: **Nilton Monteiro**

Orientador: **Cristian Muñoz**

------

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

[Link para o código](https://github.com/niltonmalves/DetectronPPT.git). 

------

Resumo:

Muita informação está contida nas apresentações realizadas nas empresas. Resultado de pesquisas, novas descobertas, além de outros dados importantes são condensadas em slides para servir de guia em palestras dentro das corporações.

Este conteúdo pode ser catalogado e utilizado em ferramentas de buscas.

Uma ferramenta para extrair o conteúdo dessas apresentações seria util para esta tarefa.

O objetivo desse trabalho é reconhecer imagens, textos, equações, tabelas, títulos e listas, em slides.

O reconhecimento de textos é uma tarefa que já é bem realizada pelo Detectron2. Porém, classificar um texto pertencente à um gráfico, como uma legenda por exemplo, é um dos desafios que pretendemos resolver. Identificar o titulo do slide, ajuda a identificar o contexto da apresentação.

Criamos uma base de dados com imagens de slides, classificando as seis entidades de interesse e usamos o Detectron2 para treinar e fazer as inferências.

------

Matrícula: 191.671.046

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
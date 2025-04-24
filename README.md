# desvweb_html
Repositório Aula HTML em desenvolvimento web 


Exercícios:
Estrutura Curricular em HTML
Antes de começar a trabalhar nas tarefas de HTML, crie um repositório no GitHub com um nome apropriado para o projeto (por exemplo, estrutura-html). Em seguida, faça o clone desse repositório localmente para organizar e versionar o código das tarefas. Dessa forma, será possível continuar o trabalho em diferentes momentos e em diferentes dispositivos, sem perder o progresso.Lembre-se de commitar frequentemente e de enviar suas atualizações para o GitHub, garantindo que todo o trabalho esteja seguro e acessível.



Tarefa 01:  Crie uma página HTML contendo o seu currículo (CV). Esta página deve conter:
A estrutura básica de um documento HTML (fornecida nos slides sobre HTML).
Pelo menos dois parágrafos contendo a BIO do estudante e informações adicionais.
Pelo menos uma imagem.
Pelo menos um link.
Pelo menos uma tabela. c
Pelo menos uma lista.




Tarefa 02:  Introdução aos elementos básicos de texto (cabeçalhos e parágrafos).  
Crie uma página HTML (grade_cabecalhos.html) com estrutura básica de um documento HTML e utilize corretamente as tags de cabeçalhos (<h1>, <h2>, <h3>) e parágrafos (<p>) com a grade curricular do curso de Ciência da Computação da UFFS.
Utilize a seguinte organização hierárquica:
<h1> para o nome do curso: Ciência da Computação
<h2> para o nome de cada semestre (por exemplo: 1º Semestre)
<h3> para o nome de cada disciplina daquele semestre
<p> para apresentar a ementa básica da disciplina (faça um resumo com suas palavras ou copie do site).
Lembretes: 
O código HTML deve estar indentado e organizado para facilitar a leitura.
Certifique-se de que as tags estejam corretamente abertas e fechadas e que os elementos estejam aninhados adequadamente. 
Você pode acessar a grade curricular do curso no seguinte link: https://cc.uffs.edu.br/grade/


Tarefa 03: Estruturação de dados em tabela
Crie uma página HTML (grade_tabela.html) com estrutura básica de um documento HTML que apresente a grade curricular do curso de Ciência da Computação da UFFS utilizando uma tabela (<table>).
Utilize a seguinte organização:
Use a tag <table> para criar a tabela.  
Use as tags <tr> para definir as linhas da tabela.  
A primeira linha da tabela deve conter os cabeçalhos das colunas, utilizando as tags <th>: "Semestre" "Disciplina" "Ementa"
As demais linhas (<tr>) devem conter os dados de cada disciplina, utilizando as tags <td> para as células de dados: número do semestre, nome da disciplina e ementa básica da disciplina.
Desafio Extra – Mesclagem de Linhas:
Para cada grupo de disciplinas do mesmo semestre, use o atributo rowspan para que o número do semestre ocupe apenas uma célula mesclada verticalmente, cobrindo todas as disciplinas daquele semestre.
Lembretes: 
O código HTML deve estar indentado e organizado para facilitar a leitura.
Utilização adequada das tags de tabela (<table>, <tr>, <th>, <td>).  
Certifique-se de que as tags estejam corretamente abertas e fechadas e que os elementos estejam aninhados adequadamente. 
Você pode acessar a grade curricular do curso no seguinte link: https://cc.uffs.edu.br/grade/





Tarefa 04: Organização hierárquica com listas
Crie uma página HTML (grade_listas.html) que apresente a grade curricular do curso de Ciência da Computação da UFFS utilizando listas HTML (<ul> e <ol>).
Utilize a seguinte organização:
Utilize uma lista ordenada (<ol>) para representar os semestres do curso (1º Semestre, 2º Semestre, etc.).  
Utilize um título com <h2> indicando a fase (ex.: 1ª Fase, 2ª Fase, etc.).
Uma lista não ordenada (<ul>) contendo os nomes das disciplinas dessa fase.
Para cada disciplina:
Use um item de lista (<li>) com:
Um título com <h3> para o nome da disciplina.
Em seguida, adicione o conteúdo da ementa:
Se a ementa apresentar vários tópicos separados por ponto ou em formato de lista, utilize uma nova lista não ordenada (<ul>) com cada item em uma <li>.
Se a ementa for um texto único e contínuo, utilize um parágrafo (<p>).
Lembretes: 
O código HTML deve estar indentado e organizado para facilitar a leitura.
Certifique-se de que as tags estejam corretamente abertas e fechadas e que os elementos estejam aninhados adequadamente. 
Você pode acessar a grade curricular do curso no seguinte link: https://cc.uffs.edu.br/grade/


Tarefa 05: Integração e navegação entre as páginas, além de introdução a imagens.
Crie uma nova página HTML chamada index.html, que funcione como a página inicial do projeto. Essa página deve conter links para as outras três páginas HTML criadas nas tarefas anteriores e também apresentar informações visuais e organizacionais sobre o curso.
Utilize a seguinte organização:
Utilize links internos (<a>) para acessar as seguintes páginas:
grade_cabecalho.html
grade_tabela.html
grade_listas.html
Adicione um link externo para o site do curso de Ciência da Computação https://cc.uffs.edu.br (Este link deve abrir em uma nova aba do navegador).
Adicione a tag para imagem do logo da UFFS, mas deixe o caminho propositalmente incorreto, com o objetivo de verificar o funcionamento do atributo alt.
Adicione também a imagem do curso de Ciência da Computação (https://cc.uffs.edu.br/images/logo/CC-logo-com-background.svg)
Utilize o atributo alt nas tags <img> para fornecer descrições das imagens.  
Seja criativo! Experimente diferentes formas de apresentar os elementos com clareza e estética.
Lembretes: 
O código HTML deve estar indentado e organizado para facilitar a leitura.
Certifique-se de que as tags estejam corretamente abertas e fechadas e que os elementos estejam aninhados adequadamente. 



# tcc-bi

<!-- antes de enviar a versão final, solicitamos que todos os comentários, colocados para orientação ao aluno, sejam removidos do arquivo -->
# Título do Trabalho

#### Aluno: [André de Oliveira Salles](https://github.com/link_do_github)
#### Orientador: [Felipe Borges](https://github.com/FelipeBorgesC).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

<!-- para os links a seguir, caso os arquivos estejam no mesmo repositório que este README, não há necessidade de incluir o link completo: basta incluir o nome do arquivo, com extensão, que o GitHub completa o link corretamente -->
- [Link para o código](https://github.com/link_do_repositorio). <!-- caso não aplicável, remover esta linha -->

- [Link para a monografia](https://link_da_monografia.com). <!-- caso não aplicável, remover esta linha -->

- Trabalhos relacionados: <!-- caso não aplicável, remover estas linhas -->
    - [Nome do Trabalho 1](https://link_do_trabalho.com).
    - [Nome do Trabalho 2](https://link_do_trabalho.com).

---

### Resumo

<!-- trocar o texto abaixo pelo resumo do trabalho, em português -->

O projeto teve como objetivo utilizar uma rede neural para prever o valor futuro da produção de biodiesel a partir dos dados de produção de anos anteriores para cada região do Brasil. 
Os dados foram obtidos na plataforma de dados abertos do governo federal (link). 
O modelo foi gerado a partir de uma combinação de uma camada de rede lstm e de outra camada de rede bidirecional.
O resultado foi capaz de captar a tendência das séries de cada região, porém as nuâncias da rede não foram determinadas.

### 1. Introdução

Explicação sobre rede neurais (lstm e bidirecional).
Explicação sobre séries temporais
Comentário geral sobre as bibliotecas
COmentário sobre o Colab
Comentário sobre produção de biodiesel

### 2. Modelagem

Os dados da produção de biodiesel foram extraídos utilizando o comando 'read_me' da biblioteca pandas.

Houve uma manipulação dos dados para listar e, posteriormente, agregar os dados categorizados por ano, mês e região do Brasil. 

Após uma manipulação das datas, com o objetivo de visualizar o comportamento da produções ao longo do tempo para cada região, foi utilizada a biblioteca matplotlib para exibí-los.

Para separar os dados em treino e teste, foi utilizada a função 'train_test_split' da biblioteca Sklearn. Como a ordenação dos dados é importante para séries temporais, não houve o parâmetro shuffle, que troca a ordem dos dados, foi definido como falso.

Para normalizar os dados, foi utilizada a função train_test_split da biblioteca MinMaxScaler do Scikit Learn.

Para cada região, foi utilizada a função TimeseriesGenerator para associar 4 valores sequenciais de produção de biodiesel, associados ao próximo valor da série temporal.

### 3. Resultados

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin pulvinar nisl vestibulum tortor fringilla, eget imperdiet neque condimentum. Proin vitae augue in nulla vehicula porttitor sit amet quis sapien. Nam rutrum mollis ligula, et semper justo maximus accumsan. Integer scelerisque egestas arcu, ac laoreet odio aliquet at. Sed sed bibendum dolor. Vestibulum commodo sodales erat, ut placerat nulla vulputate eu. In hac habitasse platea dictumst. Cras interdum bibendum sapien a vehicula.

Proin feugiat nulla sem. Phasellus consequat tellus a ex aliquet, quis convallis turpis blandit. Quisque auctor condimentum justo vitae pulvinar. Donec in dictum purus. Vivamus vitae aliquam ligula, at suscipit ipsum. Quisque in dolor auctor tortor facilisis maximus. Donec dapibus leo sed tincidunt aliquam.

### 4. Conclusões

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin pulvinar nisl vestibulum tortor fringilla, eget imperdiet neque condimentum. Proin vitae augue in nulla vehicula porttitor sit amet quis sapien. Nam rutrum mollis ligula, et semper justo maximus accumsan. Integer scelerisque egestas arcu, ac laoreet odio aliquet at. Sed sed bibendum dolor. Vestibulum commodo sodales erat, ut placerat nulla vulputate eu. In hac habitasse platea dictumst. Cras interdum bibendum sapien a vehicula.

Proin feugiat nulla sem. Phasellus consequat tellus a ex aliquet, quis convallis turpis blandit. Quisque auctor condimentum justo vitae pulvinar. Donec in dictum purus. Vivamus vitae aliquam ligula, at suscipit ipsum. Quisque in dolor auctor tortor facilisis maximus. Donec dapibus leo sed tincidunt aliquam.

---

Matrícula: 191.671.006

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*



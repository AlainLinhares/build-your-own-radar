## Build-your-own-radar

Biblioteca que gera um radar interativo, inspirado em [thoughtworks.com/radar](https://www.thoughtworks.com/radar). Foi extendida, adaptada e ajustada para o contexto da Globo, usando como referência o seguinte [repositório](https://github.com/thoughtworks/build-your-own-radar).

Essa biblioteca é responsável por gerar um serviço responsável por renderizar as informações de um radar no navegador através de componentes e bibliotecas visuais.

## Carregar Radar

Antes de mencionar sobre como carregar um radar na bibloteca, faz-se necessário informar sobre o arquivo [*IntegratioGuide.md*](https://github.com/AlainLinhares/build-your-own-radar/blob/tech-radar-adapted/IntegrationGuide.md) que é o guia que orienta o passo a passo para funcionamento e configuração do serviço da biblioteca.

Esse radar é gerado através da formatação, inserção e estruturação de um arquivo csv que exista na estrutura interna de pastas do proejto. Esse arquivo é chamado de *tech-radar.csv*, que está no seguinte caminho: *dist/assets*.

O formato esperado é o seguinte:

| name          | ring   | quadrant               | isNew | description                                             |
|---------------|--------|------------------------|-------|---------------------------------------------------------|
| Composer      | adopt  | tools                  | TRUE  | Although the idea of dependency management ...          |
| Canary builds | trial  | techniques             | FALSE | Many projects have external code dependencies ...       |
| Apache Kylin  | assess | platforms              | TRUE  | Apache Kylin is an open source analytics solution ...   |
| JSF           | hold   | languages & frameworks | FALSE | We continue to see teams run into trouble using JSF ... |

Caso a formatação não seja obedecida o serviço irá mostrar uma tela de erro indicando falhas no processo de carregamento. 


## Alterações no Conteúdo do Radar

Durante o processo de inserção de dados, será muito comum que alterações de conteúdo, de estrutura ou até mesmo sugestões aconteçam. Para isso, quando houver essas necessidades, sugerimos como prática adotar o seguinte processo: alterar o arquivo csv (*tech-radar.csv*, fazer o upload para o servidor na branch escolhida e abrir o Pull Request para a branch principal. Dessa forma, os times conseguirão melhor analisar e discutir sobre as sugestões levantadas. 

É importante salientar que as dúvidas farão parte principalmente no inicio do processo de uso da biblioteca. E com isso, vem a importância da abertura do canal de comunicação para que inclusive sejam levantados pontos construtivos de melhorias. Contudo, e por isso, abaixo é listado as pessoas do time da Thoughtworks que trabalharam nesse processo de extensão e adequeção do código.

## Equipe de Desenvolvimento
  - Alain Linhares (alain.linhares@thoughtworks.com)
  - Guilherme Silveira (guilherme.silveira@thoughtworks.com)
  - Weberton Rafael Silva (weberton.silva@thoughtworks.com)

Porém, fora esses pessoas ainda tiveram ainda os que contribuiram no desenvolvimento da biblioteca principalmente. É possível ver os outros nomes no arquivo [*CONTRIBUTORS.md*](https://github.com/AlainLinhares/build-your-own-radar/blob/tech-radar-adapted/CONTRIBUTORS.md)






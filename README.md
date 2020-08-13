# TrabalhoEngenhariaDeSoftware
## Apresentação 
A apresentação final está arquivo Apresentação 03.pdf </br>
## Modelagem
A modelagem foi feita no Drawio do Google Drive e foi exportada em xml, e pode ser importada no próprio sistema </br>
- No arquivo MVc está presente o diagrama de classes completo</br>
- No arquivo Modelagem está presente: parte do diagrama de classes, os componentes e os diagramas de sequência</br> 

## Requisitos
### Requisitos funcionais 
RF001 - O sistema pode ler arquivos de imagem de um diretório em lote ou de forma unitária </br>
RF002 - Desenhar retângulo para marcação do objeto de interesse na imagem </br>
RF003 - Selecionar o retângulo para realizar manipulação do retângulo </br>
RF004 - Editar retângulos de marcação através da translação dos pontos do mesmo </br>
RF005 - Mover o retângulo para outra localização através de drag e drop após seleção do retângulo</br>
RF006 - Permitir apagar retângulos quando o usuário errar a área a ser marcada  </br>
RF007 - Criar cópias do retângulo para marcar outros objetos com a mesma proporção </br>
RF008 - Salvar os pontos dos retângulo em um arquivo de saída  </br>
RF009 - Selecionar o tipo de arquivo de saída em um dos formatos disponíveis </br>
RF010 - Permitir que o usuário possa iniciar a anotação da próxima imagem presente na pasta através de um botão na interface ou atalho no teclado</br>
RF011 - Permitir que o usuário possa retornar para o processo de anotação da  imagem anterior na pasta  através de um botão na interface ou atalho  no teclado</br>
RF012 - Permitir salvar automático  </br>
RF013 - Relacionar uma classe (rótulo) ao retângulo identificando o objeto marcado  </br>
RF014 - Poder alterar o rótulo do objeto, em caso de erro durante anotação do objeto selecionado </br>
RF015 - Aplicar função de zoom para o usuário poder aproximar ou afastar imagem, permitindo melhor visualização de características que o interesse </br>
RF016 - Ajustar imagem a janela do programa. Ajusta a imagem de modo que suas dimensões, sem perder sua proporção, estejam de acordo com as dimensões da janela do programa  onde a imagem é exibida </br>
RF017 - Ajustar comprimento da imagem ao comprimento da janela do programa </br>
RF018 - Ativar/desativar a função que torna os retângulos invisíveis para que o usuário possa observar a imagem mesmo após a marcação </br>
RF019 - Ativar/desativar Single class mode. Modo que gera um novo retângulo automaticamente com o rótulo de uma classe específica definida pelo usuário </br>
RF020 - Poder escolher as cores utilizadas nos retângulos  </br>
RF021 - Poder restaurar as cores padrões utilizadas </br>
RF022 - Poder adicionar cores customizadas </br>
RF023 - Poder criar uma classe. O usuário digitará as classes presentes no universo das imagens a serem marcadas</br>
RF024 - Poder editar uma classe. Caso haja erro de digitação, o usuário terá opção de editar o texto</br>
RF025 - Poder deletar uma classe. Caso uma das classes não esteja presente no novo lote de imagens, o usuário poderá apagar</br>
RF026 - Permitir que o usuário possa escolher o diretório para salvar os arquivos de saída</br>
 
### Requisitos Não funcionais
RNF001 - Criar arquivos de saída dos tipos xml ou .txt  </br>
RNF002 - Salvar automaticamente os retângulos de uma imagem ao passar para próxima imagem do lote</br>
RNF003 - Mostrar os valores em RGB, Hsv e hexadecimal ao selecionar uma nova cor</br>
RNF004 - Escolher as cores: através de valores RGB, hsv, hexadecimal ou selecionar a partir de uma de uma tela com as cores disponíveis </br>
RNF005 - Desenvolver em python para atender as normas da linguagem python 2 ou 3 </br>
RNF006 - Deve utilizar a Biblioteca pyQt5 para contrução da interface gráfica </br>
RNF007 - Para desenhar um retângulo, o usuário deve clicar na posição inicial e manter o mesmo botão do mouse pressionado</br>
RNF008 - Ao finalizar o desenho de retângulo, deve ser mostrado um pop-up que permita que o usuário selecionar uma classe, ou adicionar, editar ou remover uma classe</br>
RNF009 - Cada classe(rótulo) deve ser único </br>
RNF010 - Quanto ao nome da classe, o sistema não deve diferenciar o texto entre caixa alta e baixa</br>
 


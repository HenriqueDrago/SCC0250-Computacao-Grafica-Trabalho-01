# SCC0250-Computacao-Grafica-Trabalho-01
Trabalho desenvolvido para a disciplina SCC0250 (Computação Gráfica), utilizando a biblioteca glfw para a renderização e transformação de objetos.

## Alunos
Henrique Drago, NUSP: 14675441

Henrique Yukio Sekido, NUSP: 14614564

## Projeto do grupo
**Cena**:
O projeto desenvolvido pelo grupo foi um cenário de praia. Nela, temos 8 objetos: areia, cadeira-de-sol, guarda-sol, peixe, mar, céu, nuvem e um sol. Como objetos 3D obrigatórios, fizemos a cadeira-de-sol e o guarda-sol.

**Controles**:
É possível controlar 3 objetos da nossa cena: Peixe, Nuvem e Sol.
- Peixe: Controle de Rotação, pressione a tecla 'a' para rodar o Peixe anti-horário e 'd' para rodar horário.
- Nuvem: Controle de Escala, pressione a tecla 'w' para aumentar a Nuvem e 's' para diminuir.
- Sol: Controle de Translação, pressione a tecla 'seta para esquerda' para o Sol ir para a esquerda, 'seta para direita' para ir para a direita, 'seta para baixo' para ir para baixo, 'seta para cima' para ir para cima, 'z' para trazer mais fora da tela e 'x' para trazer mais dentro da tela.

Para permitir a visualização da malha poligonal, basta apertar a tecla 'p'.

**Explicação das transformações**
A cena de praia, em conjunto com as transformações disponibilizadas, possuem um sentido bem definido. O sol pode ser transladado em qualquer eixo XYZ, representando figurativamente o comportamento do Sol na realidade. Já o peixe, pode ser rotacionado no mar, como um peixe normal. Por fim, a nuvem pode ser escalada, representando um dia ensolarado sem nuvens, quando a escala é mínima, ou representando um dia nublado, quando a escala é maior.

## Especificações do Trabalho
**Objetivo**:
Desenvolver um programa que apresente uma janela envolvendo diferentes objetos, cores e transformações geométricas, conforme abaixo.

**Requisitos**:
1. Devem ser exibidos 5 ou mais objetos de cores diferentes (pelo menos 2 deles devem ser 3D). Repetições de um mesmo objeto contarão apenas um, mesmo que tenham pequenas variações. Por exemplo, várias nuvens iguais ou modeladas a partir de números diferentes de círculos, contará apenas um objeto. Idem para várias estrelas, por exemplo.
2. Os objetos devem ser composições de primitivas simples diferentes das vistas em aula. Em outras palavras, um objeto não pode ser apenas um triângulo (pirâmide), quadrado (cubo) e círculo (esfera). Estrelas, cata-ventos, bonecos, etc. são exemplos de objetos válidos. Os objetos não podem ser importados de modelos prontos; eles devem ser criados por vocês.
3. Cada objeto deve ter sua própria matriz de transformação composta pelas transformações geométricas primárias.
4. As transformações escala, rotação e translação devem ser aplicadas, cada uma em um objeto diferente.
5. Usar teclado para aplicar translação em pelo menos um objeto.
6. Usar teclado para aplicar escala em pelo menos um objeto.
7. Usar teclado para aplicar rotação em pelo menos um objeto.
8. O programa deve ter um objetivo bem definido, ou seja, os objetos e transformações devem fazer sentido para a cena.
9. O usuário deve poder visualizar a malha poligonal quando quiser. Caso ele aperte ‘p’, as malhas dos objetos devem ser exibidas (caso estejam ocultas) ou ocultadas (caso estejam sendo exibidas).
10. Neste trabalho, NÃO devem ser utilizadas texturas, movimentação de câmera e efeitos de iluminação. Esses serão temas cobertos pelos próximos trabalhos.

**Critérios de Avaliação**:
1. Atendimento aos requisitos.
2. Qualidade do código (estruturação e comentários), que deverá ser submetido via e-disciplinas até o dia 06 de abril.
3. Qualidade e coerência da cena (complexidade dos objetos e das transformações, e o quanto o resultado final faz sentido / é coerente).
4. Apresentação em sala de aula, para todos, no dia 07 de abril. Quem não se sentir à vontade para apresentar para todos poderá apresentar apenas para o professor.
5. Apresentações fora da data apenas mediante comprovação (atestado
médico, declaração da empresa, etc.)

**Outras informações importantes**:
1. Pode utilizar qualquer código-base fornecido.
2. Pode-se utilizar, inclusive, outras linguagens de programação, desde que utilize apenas bibliotecas do OpenGL e do sistema de janelas. O uso de outras bibliotecas gráficas não será aceito.
3. Devem ser utilizadas apenas funções do pipeline moderno. No OpenGL, isso significa que as seguintes funções são obsoletas (deprecated) e não podem ser utilizadas: glRotate, glTranslate, glScale, glVertex, glColor, glLight, glMaterial, glBegin, glEnd, glMatrix, glMatrixMode, glLoadIdentity, glPushMatrix, glPopMatrix, glRect, glBitmap, glAphaFunc, glNewList, glDisplayList, glPushAttrib, glPopAttrib, glVertexPointer, glColorPointer, glTexCoordPointer, glNormalPointer, glMatrixMode, glCal.

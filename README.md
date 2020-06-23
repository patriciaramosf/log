Exercicio com CSS Flexbox & Grid

Para a estrutura principal da página usei CSS Grid. 
É verdade, que no enunciado do exercício eram pedidas 3 colunas. No entanto, devido ao tamanho das imagens, aparecia um scroll horizontal. A solução para contornar este problema e tornar a página responsive foi reduzir o das imagens em 20px nos aparelhos menores que 768px (telemóveis, tablets pequenos) e criar uma estrutura de coluna única, nos aparelhos maiores que 768px a estrutura é de duas colunas.
A estrutura de cada cartão está definida com flexbox, e fiz 6 cartões com descrições e textos de tamanhos diferentes para que se possa entender que as medidas establecidas foram cumpridas. No caso das descrições isto foi conseguido com um overflow: scroll. Também adicionei variáveis em CSS para facilitar o trabalho com as diferentes cores e tamanhos.

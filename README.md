# Uma experiência com
Comparator

Problema


• Suponha uma classe Product com os atributos name e price.

• Podemos implementar a comparação de produtos por meio da implementação da interface Comparable<Product>

• Entretanto, desta forma nossa classe não fica fechada para alteração: se o critério de comparação mudar, precisaremos alterar a classe Product.

• Podemos então usar o default method "sort" da interface List: default void sort(Comparator<? super E> c)

# Resumo da aula

* Comparator objeto de classe separada
  
* Comparator objeto de classe anônima
  
* Comparator objeto de expressão lambda com chaves
  
* Comparator objeto de expressão lambda sem chaves
  
* Comparator expressão lembda "direto no argumento"

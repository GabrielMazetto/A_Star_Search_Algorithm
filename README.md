# A_Star_Search_Algorithm

Implementação em linguagem C do algoritmo de busca A* (A Star) com o objetivo de otimizar o custo total na compra de produtos em diferentes supermercados.
Dada uma lista de produtos desejados e os supermercados que envolverão a busca, o algoritmo encontra de forma ótima quais produtos devem ser comprados em quais supermercados, levando também em consideração o frete a ser pago.


Estado: O estado é uma combinação do produto escolhido com o supermerdado aonde escelheu, junto com o custo atual da compra inteira (preço+frete+custo_atual_do_nó_pai) e o custo estimado dos produtos restantes pela heurística.
Heurística: A heurística é a soma dos valores mínimos que se pode pagar em cada produto desconsiderando o frete, devolvendo um custo estimado para os produtos ainda não escolhidos. A heurística é admissível pois o custo do produto nunca vai ser maior do que o custo+frete.

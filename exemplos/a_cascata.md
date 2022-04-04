# A Cascata (cascading)

A escolha do browser de qual regra aplicar, caso haja muitas regras para mesmo elemento.

* Seu estilo é lido de cima para baixo.

É levado em consideração 3 fatores

1. Origem do estilo
2. Especificidade
3. Importância

### Origem do Estilo

inline > tag style > tag link

### Especificidade

É um cáculo matématico , onde , cada tipo de seletor e origem do estilo, possuem valores a serem considerados.

0. Universal `*` selector, combinators e negation pseudo-class (:not())
1. Element type selector e pseudo-elements (::before,::after)
10. Classes e attributes selectors ([type="radio"])
100. ID selectors (#id)
1000. Inline

### A regra !important

* cuidado, evite o uso
* não é considerado uma boa prática
* quebra o fluxo natural da cascata
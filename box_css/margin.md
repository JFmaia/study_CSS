# Margem, é o espaço (margem) entre os elementos

* O Podemos divide a margem em 4 valores:
```css
/* margin-top | margin-right | margin-bottom | margin-left */
```

* valores: | | automático `<length>` `<percentage>`

Geralmente usamos uma forma abreviada para escrever a margem. Esse formato segue o sentido horário iniciado por , seguindo para , e .top,right,bottom,left

```css
margin: 12px 16px 10px 4px; /* TOP = 12px | RIGHT = 16px | BOTTOM = 10px | LEFT = 4px */
margin: 12px 16px 0; /* TOP = 12px | RIGHT = 16px | BOTTOM = 0px | LEFT = 16px */
margin: 8px 16px; /* TOP = 8px | RIGHT = 16px | BOTTOM = 8px | LEFT = 16px */
margin: 8px; /* TOP = 8px | RIGHT = 8px | BOTTOM = 8px | LEFT = 8px */
``` 
* A margem é aplicado em elementos com bloco de exibição
  
* Cuidado com a margem caindo que é quando o topo se junta ao fundo
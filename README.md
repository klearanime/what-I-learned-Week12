# what-I-learned-Week12

1. Inline and in HTML Styles = <element style="property: value;"> 
<style>
 selectors { property: value; }   
</style>

2. Selectors - The element on which the style should be applied.

3. Property and its value - This is the actual style to be applied to the elements.

4.  DOM (document object model) or Node - in relation to DOM. Node - 
  Every item in the DOM tree is called a node. There are two types of nodes - A text node, and an element node:
  Text Node - Node that has text. Element Node - Node that has
  an element.

5. Query/Get Elements - document.querySelector('css-selectors') & 
   document.querySelectorAll('css-selectors', ...)                                                   

7. Get and Modify Element Class -
node.classList 
node.classList.add('class-name', ...) 
node.classList.remove('class-name', ...) 
node.classList.toggle('class-name') 
node.classList.contains('class-name') 
node.classList.replace('old', 'new')

7. Remove Node -
parentNode.removeChild(nodeToRemove) or
nodeToRemove.parentNode.removeChild(nodeToRemove)

8. Modify Element -
node.style.color = 'red' 
node.style.padding = '10px' 
node.style.fontSize = '200%' or '200px'
node.setAttribute('attr-name', 'attr-value') 
node.removeAttribute('attr-name')

9. Events -
node.addEventListener('event-name', callback-function) node.removeEventListener('event-name', callback-function)

10. If you're not accustomed to coding - re-wire your brain.
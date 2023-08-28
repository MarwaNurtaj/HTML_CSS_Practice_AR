Cascading style sheet
--
--element
--selectors
-tag name{
    property;value;
    background_color: burlywood;

}
--grouping
-p,h1{

}
--nested selector
-ul li a{
    color: brown;
}
--universal selector 
*

last one will be prioritized

--color highlighter extension is useful

--id selector (#)
--class selectors (.)
class and id is something that is sharable with others
 
 --attribute selectors
 like 
 input[type]
 input[type="text"]
 
 --pseudo class
  pseudo class selector : 
  pseudo element selector ::

 hover/ visited
 --extension html to css autocompletion   

--descendent selector(div1 )
-child selector (#div1 > p)
-adjacent selector(+#div1 + p)
--combinator(#div1 ~ p)



<!-- ++++++++++++++++++++++++++++++++++++ -->
Specificity calculator
spacificity.keegan.st

id     ||  classes,attributes and pseudo-classes    ||    elements and pseudo-elements
0                   0                                               0


BEM is a methodology a stared for writing class name(BEM / OOCSS/ SMACSS)

Block =meaning full parent
{
    we can use letters, digits, dashes for naming block
    use dashes when more than one word
}
Element = 
{
    children of the block
        we can use letters, digits, dashes for naming and
    use underscore for naming element  when more than one word
    .syntax: block__element name
}

Modifier = 

{
    changes in appearance and states
    when we modify something like after hover button size or look change etc
    we can use letters, digits, dashes for naming and
    use underscore 
    block/element--modifier name
}
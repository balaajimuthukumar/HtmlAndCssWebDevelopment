<!-- 
    1) Never use inline css, internal css are used to decouple the inline css from the 
    html elements, always use external css
    2) never use fonts that are installed on the computer, If so then the users that access
    the website need to install it too in order to view them
    3)use default font system like sans-serif+
    4) h tags are not only used for their size selection but also the semantics
    5)When a parent element is assigned a style attribute for example font size, the 
    child elements also gets the same because of inheritance
    6)we always use classes instead of id's to prepare for future becuase it is semantically
    incorrect to use id for multiple items
    7)we mostly use hexadecimal and only for transparency we use rgba()
    8)when all three colours are in same channel then we get 256 types of grey
    9) : first-child psuedo class selects the first child of its parent of the same
    type(here it should be the 1s child that is present inside its parents and it is not 
    the 1st occurence)
    10)a: link will only target elements with href attribute
    11) The id has the highest priority during selector conflict,
     if multiple id selectors for it then last selector in the collection gets applied, 
     next of priority would be a class or psuedoclass followed by the element selector 
     then the universal selector. 
     12) !important keyword has the highest priority followed by the inline style then the ID
     and so on.
     13) Always create simple type of selectors
     14) child elements usually inherit styles from parent if there was no declaration, but
     some attributes like border does not get applied
     15) height of element is calculated by leftborder+leftpadding+content+rightborder+rightpadding
     16)Collapsing margin: when two margins cross paths the margin with the highest margin will be applied.
     if the H3 element and the p element were applied and margin top for h3 and margin bottom for p then
     the highest value from the either of the element gets applied.
     17) Use height auto only when the height is already specified, so that it can calculate to maintain the
     aspect ratio in case the width is changed. Else when only width is specified then the height
     is always auto.
     18)Inline elements - It only occupies space necessary, it does not cause line breaks before or after
     the element, height and width do not apply for the inline elements while margin and padding are 
     only applied horizontally
     19) inline- block is similar to block on the inside while inline on the outside.
     20) normal flow of the page means the elements are arranged according to their existence order.
     which is relative positioning.
     21) p:first-line -> selects the first line of the each para element and apply the style
     h3 + p:first-line -> here the + sign means selecting the adjacent element of the h3. Para's
     that are adjacent to the h3 or (immediately next) is selected.


-->
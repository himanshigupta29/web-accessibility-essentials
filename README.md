# web-accessibility-essentials
## Introduction 
* ✅ All \<input> and \<button> elements have in-built accessibility.
* ✅ For custom interactive elements to be accessible, use **tabindex** attribute to ensure they are keyboard accessible.*    
* ✅ Whenever possible use built-in HTML elements, instead of building your own cusstom version.
* ✅ Ude **tabindex=0** to add an element into natural tab order \<div tabindex="0"> I am accessible now \</div> . To focus this element either use Tab key on keyboard or use focus() method on the element
* ✅ Use **tabindex=-1** to remove an element from getting accessible \<buton tabindex="-1"> I am not accessible now \</button>. This element cannot be focussed by Tab key from keyboard but can be focussed using focus method on the element. Note using tabindex="-1" will not affect the accessibility of its childreen. The children will still be accessible either naturally or using tabindex
* ✅ If you are setting any tabindex with value > 0, 
  
## Make a non interactive element like **\<div>** interactive and accessible 
1 Add tabindex attribute which make it accessible via tab and focussibble
2 Add styles for :focus to the element

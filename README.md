Step 1
Begin with the basic HTML structure. Add a DOCTYPE declaration and html, head, body, and title elements.

Set the language of this page to English. Set the title to Piano.
Step 2
Add two meta tags, one to optimize your page for mobile devices, and one to specify an accepted charset for the page.
Step 3
Time to start working on the piano. Create a div element within your body element with the id set to piano.
Step 4
Nest a second div within your existing div, and set the class to be keys.
Step 5
Within your .keys element, add seven div elements. Give them all the class key.
Step 6
Remember that a class attribute can have multiple values. To separate your white keys from your black keys, you'll add a second class value of black--key. Add this to your second, third, fifth, sixth, and seventh .key elements.
Step 7
Now copy the set of seven .key elements, and paste two more sets into the .keys div.
Step 8
Add a link element within your head element. For that link element, set the rel attribute to stylesheet and the href to ./styles.css.
Step 9
Browsers can apply default margin and padding values to specific elements. To make sure your piano looks correct, you need to reset the box model.

Add an html rule selector to your CSS file, and set the box-sizing property to border-box.
Step 10
Now that you have reset the html box model, you need to pass that on to the elements within as well. To do this, you can set the box-sizing property to inherit, which will tell the targeted elements to use the same value as the parent element.

You will also need to target the pseudo-elements, which are special keywords that follow a selector. The two pseudo-elements you will be using are the ::before and ::after pseudo-elements.

The ::before selector creates a pseudo-element which is the first child of the selected element, while the ::after selector creates a pseudo-element which is the last child of the selected element. These pseudo-elements are often used to create cosmetic content, which you will see later in this project.

For now, create a CSS selector to target all elements with *, and include the pseudo-elements with ::before and ::after. Set the box-sizing property to inherit.
Step 11
Now target your #piano element with an id selector. Set background-color property to #00471b, the width property to 992px and the height property to 290px.
Step 12
Set the margin of the #piano to 80px auto.
Step 13
Time to style the keys. Below the #piano rule, target the .keys element with a class selector. Give the new rule a background-color property of #040404, a width property of 949px and a height property of 180px.
Step 14
Give the .keys a padding-left of 2px.
Step 15
Move the keys into position by adjusting the #piano selector. Set the padding property to 90px 20px 0 20px.
Step 16
Time to style the keys themselves. Create a class selector for the .key elements. Set the background-color set to the value #ffffff, the position property to relative, the width property to 41px, and the height property to 175px.
Step 17
Give the .key a margin of 2px and a float property set to left.
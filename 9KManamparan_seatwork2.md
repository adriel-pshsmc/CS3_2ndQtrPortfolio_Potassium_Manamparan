# Guide Questions

**Guided Question 1:** What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.
> The sidebar moved right and down based on the assigned value of change (e.g. 20px from top and 20px from left) from other elements declared before it. It is different from static positioning as static positioning places its position based on ____

**Guided Question 2:** What happens when you scroll the page? Why does the footer behave differently from position relative?
> The footer constantly stays at the bottom of the display page, regardless of scrolling. This is the key difference between fixed and relative as relative relies on the entire dimension of other element before it, while fixed relies on the display size of the browser.

**Guided Question 3:** What is the effect of position: absolute on an element? How is it different from fixed?
> The effect of position: absolute on an element would be that: it places the element on the declared distance away from the browser's dimensions, inclusive of scrolling. It is different from fixed, as fixed is based on the dimension of the website displayed, while absolute is based on the entire declared scope or size of the website.

**Guided Question 4:** Why does the notice appear on top of the content? What happens if you swap the z‑index values?
> The z-index allows for the content to be displayed above the other elements, as it describes how the elements are stacked above each other (from a imaginary z-axis, which is perpendicular of the x-y plane in our computer.) To note: the automatic z-value of all content is 0. Hence, if you swap the z-index values, it will display the content based on its z-value, where the element with lower z-value is shown behind the element with higher z-value



# Challenge Questions

**Challenge Question 1:** What changes that you have to do on the code that will position .notice box on the top right corner of the .content box? Please write the code on paper as well (both html and css on the part of .notice and .content).
> Define the size of the notice element and the header height sieand calculate for its position that will allow for it to be placed on the top-right corner of the box. (e.g. define notice's size as 50px height and 100px width and header's height as 50px then define notice as 380px from the left and 200px from top.)

**Challenge Question 2:** Try to change the position of .content to relative then to fixed. What do you observed each time?
> Changing it to relative pushes it down to the nearest available space that can fit its size, which includes how many pixels it is away from other elements. Meanwhile, fixed moves it based on the sized display and remains constant regardless of scrolling.

**Challenge Question 3:** What do you observe on about the effect of z-index on .notice and .content boxes?
> The element with the higher index gets placed on top of the other.



# Reflection Questions

**Reflection Question (a):** Could you summarize the differences between the CSS position values (static, relative, absolute, fixed)?
> Static: ; Relative: Position depends on other elements; Absolute: Position depends on Website Site; Fixed: Position depends on Display Site;

**Reflection Question (b):** How does absolute positioning depend on its parent element?

**Reflection Question (c):** How do you differentiate sticky from fixed (you can research on sticky)?

**Reflection Question (d):** If you were designing a webpage for a school event, how might you use positioning to highlight important information? Please give concrete examples.
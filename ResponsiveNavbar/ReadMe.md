LiveDemo: [Demo](https://naughty-hamilton-4cea88.netlify.app/)
# Things I Learned new in this project

**Learned from youtube video of Dev Ed**
[DevEd](https://www.youtube.com/watch?v=H4MkGzoACpQ)

## CSS Part

### ClipPath
    ```clip-path: circle(100px at 90% -10%);```
    size of circle: 100px
    position at x-axis: 90%
    position at y-axis: -10%

### transition **all** property
    ```transition: all 1s ease-out;```
    every property of the element will animate.
    It will get animated from the position it's generated.
    For example if an element postion is at 20% from left then when page loads then the same element will float from left to 20% from right.


## JS Part
### Toggle property
   
   ```element.classList``` it will return the list of class element has
  
   ```element.classList.toggle('className')``` 
   Toggles between a class name for an element.
   
   The first parameter removes the specified class from an element, and returns false.
   If the class does not exist, it is added to the element, and the return value is true.


### document.querySelector
    ```document.querySelector(".example");```
	Get the first element in the document with class="example"

### document.querySelectorAll
	```var x = document.querySelectorAll(".example"); ```
	Get all elements in the document with class="example"




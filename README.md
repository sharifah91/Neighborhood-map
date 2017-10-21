## Website Performance Optimization portfolio project

### Running the website

#### The live version of the website:

You can visit the live version of the website on the following link: https://sharifah91.github.io/

#### Project source code:

In this repository you will find the source code:
https://github.com/sharifah91/sharifah91.github.io


#### Note: 

I have used GitHub to host my website so the production code is derived from the source code.



### Optimizations Performed
#### Index.html
1- Eliminating render-blocking JavaScript and CSS in above-the-fold content
2- Optimizing images

#### Main.js
1- Replacing (querySelector) with (getElementById)
2- Replacing (querySelectorAll) with (getElementsByClassName)
3- Refactoring changePizzaSizes(size) function to minimize time to less than 5 ms
4- Refactoring updatePositions() function to raise the fps to 60
5- minimizing the number of moving pizzas from 200 to 30

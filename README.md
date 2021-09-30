# Reverse Engineering of Pudding Graph

I wanted to flex my D3.js a bit by recreating this graph from pudding.io.
It was the graph that inspired me to learn more about data visualization.

https://pudding.cool/projects/vocabulary/index.html

Ran into problems
- I had to scrape images from google automatically
  - Used Splinter Python package
- Some of the image names had empty spaces. I had to fill those spaces with a dash using a python script
-  https://docs.google.com/spreadsheets/d/1HIIfgDpNMM-j0hoQHN-yP5P1lNOfJuvym0u0sdWwD9g/edit#gid=737896402 


## Resource Articles

Resources that helped me learn more about D3 along the way

[Python os.listdir method](https://www.geeksforgeeks.org/python-os-listdir-method/#:~:text=listdir()%20method%20in%20python,working%20directory%20will%20be%20returned)

[Cutomizing D3 ticks](https://ghenshaw-work.medium.com/customizing-axes-in-d3-js-99d58863738b)
https://dzone.com/articles/d3-js-axes-ticks-and-gridlines

https://github.com/d3/d3-axis/issues/48

What does the call method do? why does this work with hiding the line?

d3 grid lines https://bl.ocks.org/cagrimmett/07f8c8daea00946b9e704e3efcbd5739
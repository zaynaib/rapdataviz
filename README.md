# Reverse Engineering of Pudding Graph

I wanted to flex my D3.js a bit by recreating a graph from pudding.io. It's a beeswarm plot that ranked American rappers
by the number of unique words used in their lyrics. Here is a link to [The Largest Vocabulary In Hip Hop Data Viz](https://pudding.cool/projects/vocabulary/index.html) by [Matt Daniels](https://twitter.com/matthew_daniels). It was the graph that inspired me to learn more about data visualizations. I used the data from this article to reverse engineer this graph.

## Technologies Used

- Excel
  - Used Excel to replace white spaces of names in the csv file with dashes, [spinal case](https://stackoverflow.com/questions/11273282/whats-the-name-for-hyphen-separated-case).
  
- Python
  - Splinter library for automating google searches for images of rappers displayed in this graph
  - Pillow library for automating the task of resizing the images that were download to 30 x 30 px. This was done for the web page to be loaded faster since I have more than 30 assets to load.

- JavaScript
  - D3.js to generate the graph

## Resources

Many thanks to online tech communities that helped me learn more about D3.js

Resources that helped me learn more about D3 along the way.

[Jonathan Soma](https://www.youtube.com/watch?v=NTS7uXOxQeM&t=10s) has one of the best D3.js channels free on Youtube.

[Python os.listdir method](https://www.geeksforgeeks.org/python-os-listdir-method/#:~:text=listdir()%20method%20in%20python,working%20directory%20will%20be%20returned)

[Customizing D3 ticks](https://bl.ocks.org/wadefagen/ce5d308d8080130de10f21254273e30c)

[Hiding axis line in D3](https://github.com/d3/d3-axis/issues/48)



# Reverse Engineering of Pudding Graph

I wanted to flex my D3.js a bit by recreating this graph from pudding.io.
It was the graph that inspired me to learn more about data visualization.

https://pudding.cool/projects/vocabulary/index.html

Ran into problems
- I had to scrape images from google automatically
  - Used Splinter Python package
- Some of the image names had empty spaces. I had to fill those spaces with a dash using a python script
-  
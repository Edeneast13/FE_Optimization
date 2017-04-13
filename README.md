## Website Performance Optimization portfolio project

### Getting started

First, close this repository then set up a local server using python and ngrok

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

1. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)

## index.html

PageSpeed Results
  ```bash 
  Mobile: 91
  Web: 93
  ```
 Optimizations
 
 -Inlined CSS
 
 -Minified CSS and JS
 
 -Moved scripts to the bottom
 
 -Reduced image sizes and added height/width to all images in html
 
 ## pizza.html
 
 Optimizations
 
 -moved math operations outside of for loop within the updatePositions() method
 
 -stored newwidth inside of a variable to ensure it is only called once within changePizzaSizes() method
 


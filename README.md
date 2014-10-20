#Backbone - A Guide 
###by - Nisheed Jagadish


__NOTE__:  Presentation created using `reveal.js` presentation framework created by [Hakim El Hattab](http://hakim.se/)

For more information about REVEAL.JS  please check out the repo [here](https://github.com/hakimel/reveal.js)

## Installation

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Basic setup

The core of reveal.js is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1. Download the latest version of bbg from <https://github.com/nisheed2440/bbg-revealjs>

2. Unzip and replace the example contents in index.html with your own

3. Open index.html in a browser to view it


### Full setup

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the bbg repository
   ```sh
   $ git clone https://github.com/nisheed2440/bbg-revealjs.git
   ```

5. Navigate to the bbg folder
   ```sh
   $ cd bbg
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.


## License

MIT licensed

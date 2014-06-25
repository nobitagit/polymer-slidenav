# Polymer SlideNav 

A Web-component for sliding navigation menus built on top of [Polymer](http://www.polymer-project.org/). 

Polymer SlideNav provides a flexible, easy to customise base for website and apps menus with sliding animation. Simply add it to the page and easily style it as needed.

## Demo

The web-component provides full functionality out of the box but no opinionated style allowing great flexibilty and ease of use. Check out some examples:
+ [Top drawer menu](http://nobitagit.github.io/polymer-slidenav/demos/demo-drawer.html)
+ [Fixed sliding menu](http://nobitagit.github.io/polymer-slidenav/demos/demo-fixed.html)

## Install

The best way to install the component is using [Bower](http://bower.io/):

```sh
$ bower install polymer-slidenav --save
```

Or [download as a ZIP](https://github.com/nobitagit/polymer-slidenav/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Polymer SlideNav:

    ```html
    <link rel="import" href="bower_components/polymer-slidenav/dist/polymer-slidenav.html">
    ```

3. Start using it.

    ```html
	  <polymer-slidenav>
			<slidenav-toggler>
				<-- insert burger icon here :) -->
			</slidenav-toggler>
			<slidenav-menu>
				<-- insert you list items or menu entries here -->
			</slidenav-menu>
	  </polymer-slidenav> 
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`speed`       | *string*    | `0.4s`       | The opening/closing animation speed.

Declare this option directly in the markup.

    ```html

    <polymer-slidenav speed=".2s">

    ```
    
## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. ( Submit a pull request )

## License

[MIT License](http://opensource.org/licenses/MIT)

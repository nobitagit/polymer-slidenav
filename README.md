# Polymer SlideNav 
## Web-component for sliding navigtion menus

This web-component is built on top of [Polymer](http://www.polymer-project.org/) and allows 
Check the demos [here](https://github.com/webcomponents/hello-world-polymer)

## Demo

[Check it live!](http://my-user.github.io/my-repo)

## Install

Install the component using [Bower](http://bower.io/):

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
    <link rel="import" href="bower_components/my-repo/dist/my-element.html">
    ```

3. Start using it.

    ```html
	  <polymer-slidenav>
			<slidenav-toggler></slidenav-toggler>
			<slidenav-menu></slidenav-menu>
	  </polymer-slidenav> 
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

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
5. Submit a pull request.

## License

[MIT License](http://opensource.org/licenses/MIT)

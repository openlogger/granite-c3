[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/LostInBrittany/granite-c3)

# granite-c3

> A lightweight element wrapping-up [C3.js](http://c3js.org/), D3-based chart library
>
> Polymer 1.5 ready

This is a fork on [https://lostinbrittany.github.io/granite-c3](https://lostinbrittany.github.io/granite-c3), adding some css variables for custom styling.

## Doc & demo

[https://lostinbrittany.github.io/granite-c3](https://lostinbrittany.github.io/granite-c3)


## Usage

```html
<granite-c3 data='{"x": "x", "columns": [["x", "2013-01-01", "2013-01-02", "2013-01-03", "2013-01-04", "2013-01-05", "2013-01-06"],["data1", 30, 200, 100, null, 150, 250],["data2",130, 340, 200, null, 200, 350]],"type": "step"}' axis='{ "x": {"type": "timeseries", "tick": { "format": "%Y-%m-%d"} } }'></granite-c3>
```

### Css variables
```css
--xy-region-opacity: /* global region opacity */
--xy-region-fill-clr-[1-5]: /* region colors 1-5. Add css class 'clr-1' to regions that will get color '--xy-region-fill-clr-1' */
```

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install openlogger/granite-c3 --save
```

Or [download as ZIP](https://github.com/openlogger/granite-c3/archive/gh-pages.zip).## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/granite-alert/granite-alert.html">
    ```

3. Start using it!

    ```html
    <granite-c3 data="{{data}}" axis="{{axis}}"></granite-c3>
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)

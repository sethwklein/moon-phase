# moon-phase

An element providing a moon phase calendar.


## Warning

Do not use this. I published it for demonstration purposes. I do not support
its use and portions don't meet my quality standards for things I release.
— @sethwklein


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With the Calendar

If you wish to work on the calendar in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep the bower
dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview the demo page at
`http://localhost:8080/components/moon-phase/`.


## Testing the Calendar

Simply navigate to the `/test` directory to run the tests. If you are using
Polyserve: `http://localhost:8080/components/seed-element/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.


## Yeoman support

If you'd like to use Yeoman to scaffold the calendar that's possible. The official [`generator-polymer`](https://github.com/yeoman/generator-polymer) generator has a [`seed`](https://github.com/yeoman/generator-polymer#seed) subgenerator.

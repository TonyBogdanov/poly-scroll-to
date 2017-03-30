# poly-scroll-to

[![Buy Me a Coffee](http://static.tonybogdanov.com/github/coffee.svg)](http://ko-fi.co/1236KUKJNC96B)

[Demo & Documentation](http://tonybogdanov.github.io/poly-scroll-to/bower_components/poly-scroll-to)

`<poly-scroll-to>` provides a quick and easy anchor scrolling (or "scroll to") behavior for
[Polymer](https://polymer-project.org) based projects.

To use the plugin just include it once in your page (preferably right after the opening `<body>` tag), then trigger
it by navigating the browser to any URL matching the `urlDelimiter` schema.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

And init your project with:

    bower init

## Installation

Install the component with:

    bower install --save poly-scroll-to

## Playing With Your Element

If you wish to work on your element in isolation, it's recommended that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at `http://localhost:8080/components/poly-scroll-to/`.
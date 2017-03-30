# poly-behavior-easing

[![Buy Me a Coffee](http://static.tonybogdanov.com/github/coffee.svg)](http://ko-fi.co/1236KUKJNC96B)

[Demo & Documentation](http://tonybogdanov.github.io/poly-behavior-easing/bower_components/poly-behavior-easing)

`Poly.EasingBehavior` provides a [Polymer](https://polymer-project.org) [behavior](https://www.polymer-project.org/1.0/docs/devguide/behaviors) for calculation interpolation using [bezier curves](https://en.wikipedia.org/wiki/B%C3%A9zier_curve).

Call `createEasing()` to generate your interpolator (a function) and then pass a value in the range [0; 1] to interpolate it and retrieve its corresponding projection value in the range [`minValue`; `maxValue`].

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

And init your project with:

    bower init

## Installation

Install the component with:

    bower install --save poly-behavior-easing

## Playing With Your Element

If you wish to work on your element in isolation, it's recommended that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at `http://localhost:8080/components/poly-behavior-easing/`.
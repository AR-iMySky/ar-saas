# [AR Saas](https://ar.imysky.com/) &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/master/LICENSE) [![npm version](https://img.shields.io/npm/v/react.svg?style=flat)](https://www.npmjs.com/package/react) [![Coverage Status](https://img.shields.io/coveralls/facebook/react/master.svg?style=flat)](https://coveralls.io/github/facebook/react?branch=master) [![CircleCI Status](https://circleci.com/gh/facebook/react.svg?style=shield&circle-token=:circle-token)](https://circleci.com/gh/facebook/react) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://reactjs.org/docs/how-to-contribute.html#your-first-pull-request)


## Installation

Texture is available via CocoaPods or Carthage. See our [Installation](http://texturegroup.org/docs/installation.html) guide for instructions.

## Performance Gains

Texture's basic unit is the `node`. An ASDisplayNode is an abstraction over `UIView`, which in turn is an abstraction over `CALayer`. Unlike views, which can only be used on the main thread, nodes are thread-safe: you can instantiate and configure entire hierarchies of them in parallel on background threads.

To keep its user interface smooth and responsive, your app should render at 60 frames per second — the gold standard on iOS. This means the main thread has one-sixtieth of a second to push each frame. That's 16 milliseconds to execute all layout and drawing code! And because of system overhead, your code usually has less than ten milliseconds to run before it causes a frame drop.

Texture lets you move image decoding, text sizing and rendering, layout, and other expensive UI operations off the main thread, to keep the main thread available to respond to user interaction.

## Advanced Developer Features

As the framework has grown, many features have been added that can save developers tons of time by eliminating common boilerplate style structures common in modern iOS apps. If you've ever dealt with cell reuse bugs, tried to performantly preload data for a page or scroll style interface or even just tried to keep your app from dropping too many frames you can benefit from integrating Texture.

## Learn More

* Read the our [Getting Started](http://texturegroup.org/docs/getting-started.html) guide
* Get the [sample projects](https://github.com/texturegroup/texture/tree/master/examples)
* Browse the [API reference](http://texturegroup.org/appledocs.html)

## Getting Help

We use Slack for real-time debugging, community updates, and general talk about Texture. [Signup](http://asdk-slack-auto-invite.herokuapp.com) yourself or email textureframework@gmail.com to get an invite.

## Release process

For the release process see the [RELEASE] (https://github.com/texturegroup/texture/blob/master/RELEASE.md) file.

## Contributing

We welcome any contributions. See the [CONTRIBUTING](https://github.com/texturegroup/texture/blob/master/CONTRIBUTING.md) file for how to get involved.

## License

The Texture project is available for free use, as described by the [LICENSE](https://github.com/texturegroup/texture/blob/master/LICENSE) (Apache 2.0).


# [AR SaaS](https://ar.imysky.com/) 

![AR SaaS](https://github.com/AR-iMySky/ar-saas/blob/master/docs/images/logo.png)

![version](https://img.shields.io/badge/version-1.5.3-blue.svg?maxAge=2592000) ![gem](https://img.shields.io/badge/gem-2.2.0-blue.svg?maxAge=2592000) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/master/LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://ar.imysky.com/)

## Installation

Texture is available via CocoaPods or Carthage. See our [Installation](http://texturegroup.org/docs/installation.html) guide for instructions.

## [Examples](https://itunes.apple.com/cn/app/id1105364011?mt=8) 

![image](docs/images/ar_example_01.png)  ![image](docs/images/ar_example_02.png)
![image](docs/images/ar_example_03.png)  ![image](docs/images/ar_example_04.png)

## Performance Gains

Texture's basic unit is the `node`. An ASDisplayNode is an abstraction over `UIView`, which in turn is an abstraction over `CALayer`. Unlike views, which can only be used on the main thread, nodes are thread-safe: you can instantiate and configure entire hierarchies of them in parallel on background threads.

To keep its user interface smooth and responsive, your app should render at 60 frames per second — the gold standard on iOS. This means the main thread has one-sixtieth of a second to push each frame. That's 16 milliseconds to execute all layout and drawing code! And because of system overhead, your code usually has less than ten milliseconds to run before it causes a frame drop.

Texture lets you move image decoding, text sizing and rendering, layout, and other expensive UI operations off the main thread, to keep the main thread available to respond to user interaction.

## Learn More

* Read the our [Getting Started](http://texturegroup.org/docs/getting-started.html) guide
* Get the [sample projects](https://github.com/texturegroup/texture/tree/master/examples)
* Browse the [API reference](http://texturegroup.org/appledocs.html)

## Release process

For the release process see the [RELEASE](https://ar.imysky.com).

## License

The Texture project is available for free use, as described by the LICENSE .


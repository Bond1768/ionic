# ion-img

Img is a tag that will lazyily load an image when ever the tag is in the viewport. This is extremely useful when generating a large list as images are only loaded when they're visible. The component uses [Intersection Observer](https://caniuse.com/#feat=intersectionobserver) internally, which is supported in most modern browser, but falls back to a `setTimeout` when it is not supported.


<!-- Auto Generated Below -->


## Properties

#### alt

string

This attribute defines the alternative text describing the image.
Users will see this text displayed if the image URL is wrong,
the image is not in one of the supported formats, or if the image is not yet downloaded.


#### src

string

The image URL. This attribute is mandatory for the <img> element.


## Attributes

#### alt

string

This attribute defines the alternative text describing the image.
Users will see this text displayed if the image URL is wrong,
the image is not in one of the supported formats, or if the image is not yet downloaded.


#### src

string

The image URL. This attribute is mandatory for the <img> element.


## Events

#### ionImgDidLoad



----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*

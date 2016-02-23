# photo-cropper

This is the minimal version of the [ReposDeHacks' `photo-cropper`][1] component.

`photo-cropper` is essentially a wrapper around [cropper.js][2]. This version is embeddable
in any UI (the original provided its own modal window).

## Usage

In the HTML:

```
<photo-cropper id="cropper" crop-width="300" aspect-ratio="1" style="width: 600px; height: 600px"></photo-cropper>
```

**Note:** Custom sizing is intentionally required.

In the JavaScript:

```
// to load an image into the cropper:
this.$.cropper.replaceImage(someDataURL);

// listening to crop changes:
this.$.cropper.addEventListener('cropped-image-changed', function(e) {
  var blob = e.detail.value; // Cropped image is a Blob.
});
```

## Authors

Original version:

* Sánchez Pineda Alan <sanchezpineda03@gmail.com>
* Sánchez Alamilla Edgar <sae.shikarta@gmail.com>
* Vargas Mejía Quetzalli <addmejia@gmail.com>

Minimal adaptation:

* Filip Wieland <hello@filipwieland.com>

[1]: https://github.com/ReposDeHacks/photo-cropper
[2]: https://github.com/fengyuanchen/cropperjs

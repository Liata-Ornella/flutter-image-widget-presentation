# Flutter Image Widget: Product Preview

A tiny shopping-product preview app demonstrating Flutter's `Image` widget with a local product image.

## Run the app

1. Install the Flutter SDK and set up an emulator or connect a device.
2. Open a terminal in this project folder.
3. Run:

   ```bash
   flutter pub get
   flutter run
   ```

The demo uses a local asset, so the product image does not require an internet connection.

## The three properties demonstrated

- **`width`** — starts at `260` logical pixels. Move the width slider to change the image's horizontal display size. Developers adjust it to fit different layouts and screen sizes.
- **`height`** — starts at `220` logical pixels. Move the height slider to change the image's vertical display size. Developers adjust it to keep a product preview within the intended space.
- **`fit`** — starts at `BoxFit.contain`. Choose `contain`, `cover`, or `fill` to see how the image is placed inside its box. Developers select a fit mode to balance showing the whole product with filling the available space.

The sliders and chips update the preview immediately. Press the reset button to return to the starting values.

## Screenshot

screenshot of the running app:

`![Image widget demo](screenshots/Screenshot widget.png)`  <img width="480" height="600" alt="my_product" src="https://github.com/user-attachments/assets/8be557dc-cfc3-4cc9-870e-da802896e3ed" />

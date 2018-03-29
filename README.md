# ⚡ AMP Spectre CSS Framework

This is an [AMP](https://www.ampproject.org) version of the lightweight [Spectre.css](https://picturepan2.github.io/spectre/) framework by Yan Zhu. It complies with the [AMP CSS spec](https://www.ampproject.org/docs/design/responsive/style_pages).

## Usage

Insert the contents of `spectre.min.css` and optionally `spectre-icons.min.css` file into the `<style amp-custom></style>` tag. Remember not to exceed 50KB of CSS and to use `<amp-img>` instead of `<img>` tags in AMP HTML.

## Demo

Check out the [demo page](https://niutech.github.io/amp-spectre/) as a valid AMP HTML document.

## Differences from Spectre.css

 - Removed `!important` and `style=""` attributes
 - Replaced `<img>` with `<amp-img>`
 - Replaced `.video-responsive` with `<amp-youtube layout="responsive">`
 - Replaced `style="width:10%;"` with `data-width="10%"` in `<div class="bar-item">`

## License

Licensed under MIT License.

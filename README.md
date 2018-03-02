# \<spine-avatar\>

`spine-avatar` displays the specified avatar image fit in a round area, or an initial from the
respective name string if no image was specified or image failed to load.

The image can be specified using the `image-src` attribute, and the name string can be specified
using the `name` attribute. The name is not displayed directly, and is only used to display a
one-letter avatar when image is not available. In this case, the avatar's background color is chosen
from a predefined list of colors, which can be customized using the `colors` property.

You should specify at least one of `image-src` and `name` attributes.

Example:
```
<spine-avatar image-url="https://avatars0.githubusercontent.com/u/28807796?s=200&v=4"
              name="John Doe">
</spine-avatar>
```

You can use the following CSS custom properties for customizing `spine-avatar`:

Custom property         | Description         | Default
------------------------|---------------------|----------
`--paper-avatar-width`  | Width of an avatar  | `40px`
`--paper-avatar-height` | Height of an avatar | `40px`

Similar to `--paper-avatar-width` and `--paper-avatar-height` CSS custom properties, you can specify
the avatar's size using the CSS `width` and `height` properties (with the difference being that
custom properties can be inherited throughout the document, if needed).

# License

Apache License

Version 2.0, January 2004

# MMSQ
Multiple media size query is a SASS mixin library for querying multiple media sizes in a single line. Instead of writing mltiple lines of code for each media size use `mmsq` to simplify your workflow.

# Examples

If you want to target `ipad` and `smartphone` media at once you can write rules for both media sizes in one mixin.

```scss
  @include is-media((ipad, smartphone)) {
		#branding {
			display: block;
			text-align: center;
			max-width: 100%;
		}
	}
```

This will generate media query CSS for both `ipad` and `smartphone`. You can use the following media devices as parameters:

- smartphone,
- smartphone-portrait
- smartphone-landscape
- ipad
- ipad-portrait
- ipad-landscape
- ipad-retina
- ipad-retina-portrait
- ipad-retina-landscape
- ipad-mini
- ipad-mini-portrait
- ipad-mini-landscape
- iphone4
- iphone4-portrait
- iphone4-landscape
- iphone5
- iphone5-portrait
- iphone5-landscape
- iphone6
- iphone6-portrait
- iphone6-landscape
- desktop
- gt-ipad-lt-desktop
- desktop-large
- desktop-xlarge
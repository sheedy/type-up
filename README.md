# Type Up

Generate baseline-respecting, readable typography based on font size and line length in Compass. Specify details as necessary. This project is a work in progress.

## Usage

1. Install extension (at the moment, copy the extensions directory to your project)
2. Import

	@import "typeup";

3. Write your settings

	$fontSize: 1.25em;
	$containerWidth: 35em;
	$xHeight: 1;

3. Use the mixin

	.main-wrapper {
		@include typeup()
	}

4. Enjoy your newly generated, vertically rhythmic and readable typography.

## License

MIT License.
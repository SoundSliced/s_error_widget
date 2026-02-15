 
## 2.1.0
- `s_packages` dependency upgraded to ^1.3.0
- Converted to `StatefulWidget` for expandable stack trace state
- Added `errorCode`, `stackTrace` (expandable monospace view), `showCopyButton`, and `actions`
- Copy button copies full error details to clipboard

## 2.0.0
- package no longer holds the source code for it, but exports/exposes the `s_packages` package instead, which will hold this package's latest source code.
- The only future changes to this package will be made via `s_packages` package dependency upgrades, in order to bring the new fixes or changes to this package
- dependent on `s_packages`: ^1.1.2


## 1.0.1
- internal wrap witgh Center widget, so to cover the whole of the constraint space the `SErrorWidget` is put in

## 1.0.0
- Initial release of s_error_widget.
- Customizable error widget with header and exception text.
- Support for custom icons and background colors.
- Added retry action with customizable button.
- Added `exceptionBuilder` for advanced error display customization.

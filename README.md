# Team Bauhaus Snippets

Hey, do you work on Team Bauhaus? Do you use VS Code? Here are some handy snippets for CSS (Styled Components), Javascript, and Javascript React.

## Features

### CSS

```
  !mq: Add a media query inside a Styled Component block
  !color: Use a color from the theme file
  !font-size: Use a font-size from the theme file
  !font-weight: Use a font-weight from the theme file
  !border-radius: Use a border-radius from the theme file
  !conline: A conditional line of CSS
  !conblock: A conditional block of CSS
  !switch: Call a switch from within a CSS block
```

### Javascript

```
  !scaffold: Scaffold out a new Spec file
  !scaffold: Scaffold out a new Styled Components stylesheet
  !block: Create a new Styled Component
  !th: Import the ThemeHelper function
  !switch: A switch statement to be used in a stylesheet
  !clog: Add a console log
  !clogged: Add a console log with `component.debug()`
  !buildcomp: Use buildComponent in your test file
```

### Javascript React

```
  !scaffold: Create a new JSX file
  !prop: Add a new proptype to the JSX
```

## Release Notes

### 0.0.7

#### Added

- Added `color:` prefix to CSS `!color` snippet
- Added ThemeHelper wrap around `!color` theme color

#### Fixed

- Fixed options for `!font-weight`
- Fixed `sm` option for `!font-size` and  `!border-radius`. It was `xm`
- Fixed scaffold examples for the Javascript snippets file in the README

### 0.0.6

#### Fixed

- Fixed `scaffold` examples for the Javascript snippets file in the README

### 0.0.5

#### Fixed

- Correct version number in README
- Renamed Javascript React snippet, it was wrong in the file

#### Changed

- Updating titles on CSS Snippets page
- Changed **New Styled Component** prefix `!nss` to `!scaffold`

#### Added

- Added `!block` to create a new Styled Component block
- Added `!scaffold` to create a new Spec file
- Added `vsc-extension-quickstart.md` to the `.gitignore`
- Added `!scaffold` to create a new JSX file

### 0.0.4

#### Added

- Added to the README and CHANGELOG

### 0.0.3

#### Added

- Adding an icon image

### 0.0.2

#### Added

- Adding more snipets

### 0.0.1

- Initial release
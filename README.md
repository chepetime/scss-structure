# 🎨 Basic SCSS Files

> SASS Directory Structure and Methodology.

In this repository you can find my personal SCSS approach for organizing CSS in any project. No building tool is providen, however the entry point is ```scss/app.scss```.

## 🔨 Tools and References

- [SASS](https://sass-lang.com/)
- [BEM](http://getbem.com/)
- [Using Sass to Control Scope With BEM Naming](https://css-tricks.com/using-sass-control-scope-bem-naming/)
- [CSScomb](http://csscomb.com)
- [Editor Config](http://editorconfig.org)
- [URL-encoder for SVG](https://yoksel.github.io/url-encoder/)
- [FlexBox Cheatsheet](http://vudav.github.io/flexbox-cheatsheet/)

## 📁 Structure

> This ASCII diagram represents the structure of the ```scss``` directory.

```
─── scss/
  ├── app.scss
  ├── base/
  │ ├── __base.scss               # SCSS Imports
  │ ├── _reset.scss               # Reset Styles
  │ ├── _mixins.scss              # Custom Mixins
  │ ├── _helpers.scss             # Custom Helpers
  │ ├── _colors.scss              # Colour Variables
  │ ├── _fonts.scss               # Colour Variables
  │ ├── _element-defaults.scss    # Global Styles
  │ └── _quick.scss               # Quick Adding Styles
  │
  ├── layout/
  │ ├── __layout.scss             # SCSS Imports
  │ ├── _offcanvas.scss           # Styles for Global Offcanvas
  │ ├── _wrapper.scss             # Styles for Global Wrapper
  │ ├── _section.scss             # Styles for Global Section
  │ ├── _content.scss             # Styles for Global Content
  │ ├── _header.scss              # Styles for Main Header
  │ ├── _navigation.scss          # Styles for Main Navigation
  │ └── _footer.scss              # Styles for Main Footer
  │
  ├── components/
  │ ├── __components.scss         # SCSS Imports
  │ │
  │ ├── example/
  │ │ └── __example.scss          # Example component
  │ │
  │ └── component_a/
  │   ├── __component_a.scss
  │   ├── __component_a__children.scss
  │   ├── __component_a__children.scss
  │   └── __component_a__children.scss
  │
  └── libs/
    └── __vendor.scss             # SCSS Imports for Thirdparty


```

--

Made with ❤️ in Mexico City

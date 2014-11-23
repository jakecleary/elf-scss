<img src="http://jakecleary.github.io/elf-scss/img/elf.svg" height="120px">

**Prefer [Stylus](https://github.com/corysimmons/elf)?**

### Features
- Unlimited nesting with consistently sized gutters.
- Nesting **without** parent contexts. For instance in Jeet you have to write `column(1/3 1/2)` where `1/2` is the size of the containing element. All ratio grid systems aside from Elf suffer from this in some form or fashion.
- Ratio based sizing (e.g. `column(1/3)`.
- Gutters can be any unit (e.g. `30px`, `2rem`, etc.). These are static so you can space elements vertically as well for a perfect grid.
- Tiny file size compared to other ratio grid systems.
- Flexbox makes short work of aligning elements vertically and horizontally.

#### CodePens
- [Forkable](http://codepen.io/clear-y/pen/pvvBqN)
- [Importable](http://codepen.io/clear-y/pen/oggOQP)
- [Collection of Examples](http://codepen.io/collection/nLKJkX/)

#### Installation
- Copy and paste [_elf.scss](_elf.scss) to your project
- `@import 'path/to/elf';`

#### API
View [_elf.scss](_elf.scss) for mixin and parameter descriptions.

- `debug($color: 'blue')`
- `column($ratio: 1, $gutter: $elf-gutter)`
- `cycle($item: 0, $uncycle: 0, $gutter: $elf-gutter)`
- `offset($ratio: 0, $column-or-span: 'column', $gutter: $elf-gutter)`
- `span($ratio: 1)`
- `shift($ratio: 1, $column-or-span: 'column', $gutter: $elf-gutter)`
- `unshift()`
- `align($direction: 'both')`
- `%cf`

#### Browser Support
- General http://caniuse.com/#search=calc
- `align()` http://caniuse.com/#search=flexbox

# Welcome

By default Vanilla Framework is authored in Sass (SCSS), so the following setup is needed:

1. Install Sass:
   `npm install -D sass`

2. Create `src/index.scss` with:
   ```scss
   @import 'vanilla-framework';
   @include vanilla;
   ```

3. In `src/main.jsx`, import the stylesheet:
   ```javascript
   import './index.scss';
   ```

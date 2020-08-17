## Molgenis themes 

Maintain and build molgenis bootstrap themes

- Uses bootstrap 4
- Each theme is maintained in a ```theme-name.scss``` file located in the ```themes``` dir

Usage:
```
yarn build
```

Build result is generated into the ```css``` dir

### Adding a new theme

- Create a new sass file ( .scss) the the themes dir
- Start the theme file with: ```@import "bootstrap-molgenis-pre-theme";```
- Write your theme styles
- End the theme file with: ```@import "bootstrap-molgenis-post-theme";```
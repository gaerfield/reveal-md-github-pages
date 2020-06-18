<!--s-->
## Customizations

* I changed a whee-bit the defaults

<!--s-->
## Customizations - CSS

* custom.css has some additional configs (who needs borders around pictures)
* just remove the content, if it not suits you
* but keep the file, or the build will fail

<!--s-->
## Customizations - includes

* the presentation is split up into multiple documents
* useful for large presentations
* an include is defined by

   `{{path/to/include.md}}`

<!--s-->
## Customizations - plantuml

* I really like diagrams
````
``` puml
A -> B
```
````

will become

```puml
A -> B
```

<!--s-->
## Customizations - plantuml

* check [plantuml](https://plantuml.com/) for more details
* or even better: [the hitchhikers guide to plantuml](https://crashedmind.github.io/PlantUMLHitchhikersGuide/)

<!--s-->
## Customizations

* included scripts are configured in includes.js
* clear the content, if customizations not needed (but keep the file!)
* never read the following files:
  * `scripts/fileInclude.js`
  * `scripts/pumlpreprocessor.js`
* I know, they are open-source, but they are also crappy
* Me not good is in javascript

<!--s-->

# The End

have fun ;)

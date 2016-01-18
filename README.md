It's static pages version of handlebars example

precompile ref:http://www.adamwadeharris.com/how-to-precompile-handlebars-templates/

hints:
1.If you are using precompile files,just change 
```
var template1 = Handlebars.compile($("#entry-template").html());
var html    = template1();
```
to
```
var template1 = Handlebars.templates['color-template']();  /////color-template <==It's the name of your handlebars file
```

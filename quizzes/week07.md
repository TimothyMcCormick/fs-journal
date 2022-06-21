# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
If we want to bind any variable, we can use the double curly braces or “Mustache” syntax to bind any variable from the relative component instance.

If we want to bind any variable inside an HTML attribute, we can use the v-bind directive. There is also a shorthand way of binding variables in an HTML attribute. Instead of writing v-bind:attribute-name, we can only use a colon “:” and attribute name.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
You don't have to redraw the entire webpage, you can just redraw elements or different 'views'.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
It says, when this page mounts or 'loads' run this code.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
It is for reactive data binding, we can use the v-model directive on an input form field.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
v-on click or submit/@submit or @click. When the action is performed it can run a particular function. 
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-else, v-else-if, v-show
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
It is how you can tell vue what unique property it can use to tell each for loop through elements which is which.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
It is a way to pass a template fragment to a child component, and let the child component render the fragment within its own template.
```
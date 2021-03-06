# html-email-workflow
A set of tools for producing HTML emails in a much less terrible way

### features

- [assemble](http://assemble.io/), for compiling HTML templates with reusable layouts, partials, pages, variables, etc.
- [juice](https://github.com/Automattic/juice), for inlining CSS into the compiled HTML files
- [livereload](http://livereload.com/), for, well, live reloading

### requirements

- [grunt](http://gruntjs.com/)
- livereload (optional, preferably by [browser extension](http://livereload.com/extensions/))

### how to use

1. Create your HTML email templates in the `src` directory, using assemble's layouts, partials, pages, variables, and so on to enhance code reuse and soothe your soul
2. Compile these templates using `grunt` or `grunt watch` - compiled templates will be placed in the `compiled` directory
3. Inline your CSS into the compiled templates using `grunt inline` - inlined templates will be placed in the `inlined` directory

### to-do

Please see the Issues on this repo to view forthcoming features and log your own feature suggestions!

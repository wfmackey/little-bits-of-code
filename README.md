# little-bits-of-code
A place to store handy little bits of (R, HTML, Rmarkdown, LaTeX, Stata) code


# HTML

1. Add tooltip (straight from @SteveLane)
```html
  <script>
  $(document).ready(function(){
      $('[data-toggle=\"tooltip\"]').tooltip(); 
  });
  </script>
```
Then use:
```html
<a href = "#" data-toggle="tooltip" title="Here is where the tooltip goes.">Here is the word/phrase you need a note on</a>
```

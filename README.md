# getBySelect

jQuery plugin: reloading page with GET parameters by Select change

Change page URL by Selects' changes with GET parameters according to name->value from current Select and chosen Option

Depends on jQuery event "onChange"

##Required

####URI.js - download from <a href="http://medialize.github.io/URI.js/build.html">here</a>

##Example

###HTML

    <select class="get" name="name1">
      <option value="1">1</option>
      <option value="2">2</option>
    </select>

    <select class="get" name="name2">
      <option value="3">3</option>
      <option value="4">4</option>
    </select>
    
###JS

    $('select.get').getBySelect();

###Result example

    "...some_url...?name1=&name2=4"

# getBySelect

jQuery plugin: reloading page with GET parameters by Select change

##Required

###URI.js - downlaod from <a href="http://medialize.github.io/URI.js/build.html">here</a>

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

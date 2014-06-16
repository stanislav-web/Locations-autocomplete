Locations-autocomplete
======================

List with a choice of settlements. Use AutoComplete Ajax
![Alt text](http://cdn.joxi.ru/uploads/prod/2014/06/16/7ff/c96/a8376f7c8a680c19e334cd16fb4d2b7d62563e21.jpg "See example")
```
<php
/**
 * Locations. Ajax autocomplete locations: country > region > city
 * @author Stanislav WEB | Lugansk <stanisov@gmail.com>
 * @extends jQuery, (jQuery Mobile)
 * @since Browsers Support:
 *  - Internet Explorer 8+
 *  - Mozilla Firefox 3.6+
 *  - Opera 10.5+
 *  - Safari 4+
 *  - iPhone Safari
 *  - Android Web Browser
 *  
 *  @see 
 *  $('select.autocomplete').on('change', function(e) {
 *      e.preventDefault();
 *      
 *      var query   =   {}; 
 *      
 *      // formed request params
 *      
 *      query['request']               =   $(this).data('request');
 *      query[$(this).attr('name')]    =   $(this).val();
 *      
 *      // send request
 *      Locations.request('/locations/json', query, 'POST');
 *   });   
 */
?>
```

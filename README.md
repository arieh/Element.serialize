Element.serialize
========
This method returns an object containing a key-value representation of all the inputs inside it. Should usually be useful when used on a form.

How to use
----------

    #JS
    var values = $('myForm').serialize(deep);
    
The deep argument specifies if you want the to enable deep parsing. This is useful if your form contains query arrays, and you want them to be parsed hierarchically.
For more examples look at the demo
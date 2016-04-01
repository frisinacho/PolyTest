# Use data binding
Of course, it’s not enough to have static local DOM. You usually want to have your element update its local DOM dynamically.

Data binding is a great way to quickly propagate changes in your element and reduce boilerplate code. You can bind properties in your component using the “double-mustache” syntax (`{{}}`). The `{{}}` is replaced by the value of the property referenced between the brackets.

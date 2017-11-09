# simplyTodo
A simple todo app for minimalists

Biggest lesson/struggle: dynamic generated elements - have to add handlers to previous/static elements, namely document, instead of themselves (not work). Which then event.stopPropagation dont work on the event if call since the event will not stop propagate until document!! Created an intermediate parent called "main" and main.on(dblclick) {e.stopPropagation} works!!!!

External library: autoresize a textarea library @http://www.jacklmoore.com/autosize/
    

# min_Todo (vanilla JS)
## The most minimal simplistic todo app that gets your TODO done!
## Run straight from on your browser
### USAGE:
Just launch it (click [here](https://ngnnah.github.io/js_min_todo/)) and:
- double click anywhere to create a new todo
- double click on any completed todo (Surprised? Yes, completed tasks turned green :!)
- double click a completed todo to undo it
- note: when typing, you can press Shift + Enter to jump to next line
### DEMO:
![image](https://user-images.githubusercontent.com/58123635/122483112-dd087200-cf9f-11eb-816a-6b9a7251cf0b.png)
### My own comments:
* As simple as a todo app can get
* Yet the UI is sublime, and responsive and auto-resizing todo tasks
* and the functionality works perfectly!
#### Biggest lesson or insight from this project: 
* Regarding working with dynamic generated elements: I have to add handlers to previous/static elements, namely document, instead of adding handlers to the dynamic elements themselves (**Note:** again, this will not work). 
* Because event.stopPropagation dont work on the event once called since the event will not stop propagate until it reaches the `document`!! Therefore, I created an intermediate parent called "main" and using `main.on(dblclick)` allowed `{e.stopPropagation}` to work!!!!
* Also, in this project, I use an external library: `autoresize` a textarea library @http://www.jacklmoore.com/autosize/
    

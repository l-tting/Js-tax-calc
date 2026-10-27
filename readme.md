*modularity* -> making a large program smaller and more manageable

2^32

*form input*

--> JS has 2 core purposes:
1. User interactivity -> ability of the user to interact with the application through events
2. Reactivity -> being able to render data automatically without a manual refresh


---> User interactivity enables a user perform any action when using the application
---> e.g. click, scroll, submit forms , hover , copy & paste

Goal : provide a user with a form to fill(basic salary & benefits)
       submit the form to JS for processing & computation
       output tax values in a table

*event* -> anything a user is able to do when using an application

link the form to the js program

*id attribute* -> the attribute that JS uses to uniquely identify and target a HTML element
*document.getElementById()* -> method / function that is used by JS to target an element its unique id attribute

*addEventListener()* -> a function that listens for an event as a user uses an application


*document.getElementByID().value*
  -> used to extract /target form elements specifically
  -> we will use it to extract values filled in the form
*document.getElementByID().innerHTML*
  -> used to target all other HTML elements except form elements
  -> we use to extract or output values in all html elements except form elements


*N/B* -> After an event occurs e.g submit , the default behaviour of the browser is to refresh
-> to prevent the default behaviour of the browser (refreshing) after an event occurs we use *event.preventDefault()*
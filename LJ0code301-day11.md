# Said Abdou Mattar code fellows 301 coding journey..  
Day 11:  
Today I have learned about Model View Controller(MVC):  
1.Model: Models represent knowledge. A model could be a single object, or some structure of objects. There should be a one-to-one correspondence between the model and its parts on the one hand, and the represented world as perceived by the owner of the model on the other hand.  

2.Views: A view is a (visual) representation of its model. It would ordinarily highlight certain attributes of the model and suppress others. Acting as a presentation filter.  
A view is attached to its model and gets the data necessary for the presentation from the model by asking questions. It may also update the model by sending appropriate messages.   All these questions and messages have to be in the terminology of the model, the view will therefore have to know the semantics of the attributes of the model it represents.  

3.Controllers: A controller is the link between a user and the system. It provides the user with input by arranging for relevant views to present themselves in appropriate places on the screen. It provides means for user output by presenting the user with menus or other means of giving commands and data. The controller receives such user output, translates it into the appropriate messages and pass these messages on to one or more of the views.  

Browsing pages:  
As we browse, the URL in the web browser's address bar updates. The page is also added to the top of what is called history stack. pressing back will take us down the stack, pressing forward will take us up the stack and if we request a new page it will replace anything above the current page  in the stack.  

ADDING INFORMATION TO THE BROWSER HISTORY OBJECT:  
pushState() method: Adds an entry to the history object.  
history.pushState(state, title, url);  
replaceState() method: Updates the current entry.  
history.replaceState(state, title, url);  

Note: we don't need to write window.history since the history object is a child of the window object, we write history.method() directly.  

The window.onpopstate EVENT: Used to handle the user moving backwards or forwards.  

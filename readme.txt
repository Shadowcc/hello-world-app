Scott Monroe
HellowWorldApp
IOS

This project is a simple interface that allows a user to input text into a field and have it displayed in the middle of the screen.  The text is displayed when the user hits done on the keyboard or pushes the Hello button.

The reason for the first responder is it dictates that the text field is active so that it knows that all input  goes to the text field.  When you send the resignFirstResponder message it tells the application that you are done editing the text field and it deselects the textfield and removes the cursor.  Since the textfield is no longer selected the keyboard disapears.


'Translate Page' Tab:

When the user starts up the app, they will be at the landing page, this page as a keyboard avoid view for when the user wants to enter text they want to translate but can
press on an empty space to hide the keyboard. Just below the text to be translated is the translate button that will go to another screen for the translation. 
Below this button there is a picker that will allow the user to pick which language they want to translate the text from and which language to translate it to. 

(unimplemented feature on the landing page: there are buttons at the top of the page 'Text' and 'Voice', when selected their color changes to white to show the user
which option is selected. we were going to try to implement speech to text but did not have time)

Once the user has typed in text to translate, selected languages from/to, and pressed the translate button they will be sent to a different screen which will
display the languages they selected, the text they want translated and initially a spinning circle while the request is made to the api to translate the text. Once the
text is translated the spinning circle is replaced with the translation. Just below the translation there is a + button which when pressed adds the currently
displayed translation to the saved translations list. This list is availible in the saved translations tab. But we also included the list to this current page just below
the + button.

'Saved Translations' Tab:

the purpose of this tab is to display the saved translations. so if the user does not have any then there is a message telling them they do not have any.
However if they do have translations then there is a list they can scroll through to see the translations. There is a trash can button they can press to delete
any of translations that they no longer want.

We implemented a presist store so it can remember the translations even when the app is terminated.

The end.

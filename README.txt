This is a very small module that makes default Zen sub-theme main menu be a bit more responsive. It does this by:

  Kicking in at 480px or less, then
  Hiding the menu items from display initially
  Removing the "element-invisible" class from the menu title so this can be used as the menu trigger
  Adding a class of "menu-trigger-unclicked", so you can use this to replace the text with a hamburger image or whatever you like (add a "+" before the word "Main Menu" perhaps)
  Adding a class of "menu-trigger-clicked" if the menu trigger is clicked, so you can use this to replace the text with a hamburger image or whatever you like (add a "-" before the word "Main Menu" perhaps)
  Slides the menu items into/out of view
  Sets each menu item at 100% width so they'll take up the full width of the phone (presuming it's a phone you are looking at the menu on), rather than displaying them lined-up beside each other
  Set the cursor to a pointer - we are using jQuery afterall!

There is not CSS included with this - styling of the menu is up to you - this just provides the functionality.

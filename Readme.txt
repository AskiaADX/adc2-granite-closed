Granite Radios

==============
CSS-only ADC 2.0 for single questions and multiple questions.


This is a combined implementation of the proposals for 
- demo-GraniteRadios (https://github.com/AskiaADX/demo-GraniteRadios)
- demo-GraniteCheckboxes (https://github.com/AskiaADX/demo-GraniteCheckboxes)

It will also include 
- demo-GrnaiteSwitches in a future version (https://github.com/AskiaADX/demo-GraniteSwitches)

==============

Preview

-------


[Preview of Granite radios](https://raw.githubusercontent.com/AskiaADX/demo-GraniteRadios/master/GraniteRadio-demo.gif)




Variables to be open to the end-users

----------------------------------------------


-	Radio and checkbox outer background gradient

-	Radio and checkbox inner background gradient

-	Radio tick color

-	Response item color for hover and active states






Known issues

------------


-	Does not handle exclusive answers in multiple questions

-	This demo was successfully tested in Chrome, Firefox, Safari, Opera and IE9+. Because it relies on CSS transforms for the check (tick) of the control, you will need to add a conditional tag for < IE9 that will display the default checkbox instead.

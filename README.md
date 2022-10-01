# SteelEye
Ans number 1 : Simple list component basically map the items value that is in array form and render it to the singleListItem that's wrapped in memo hook but as 
singleListItem called again and again by the memo hook does not work and singeleListItem render again and again and after first value all the values returned 
with the backgroundcolor red . If in case items array is empty then they value reflected on it is null because code uses default proptype as null.

Ans number 2 : The problem with the code is that on WrappedSingleListItem there is a onClick function but in the code that onClick function is not written.
And the secon problem with code is in WrappedListComponent function on return section where items array executed throw map is continously calling singleListItem
and pass the values to every props of in singleListItem like onClickHandler called with function , text is called with string , index called with number but isSelected
is also called with number but in propType the type of isSelected is boolean and the third problem with code is that the value passed in WrappedListComponent is passed
in random oreder not in organized manner.

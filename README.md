# SteelEye
Ans number 1 : Simple list component basically map the items value that is in array form and render it to the singleListItem that's wrapped in memo hook but as 
singleListItem called again and again by the memo hook does not work and singeleListItem render again and again and after first value all the values returned 
with the backgroundcolor red . If in case items array is empty then they value reflected on it is null because code uses default prototype as null.

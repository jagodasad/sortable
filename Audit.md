# Sortable Audit Tests

Fellowship → The JS Piscine (Raid → Sortable) !

# Sortable → Functional Tests
Does the data appear in a <table> element?

Does the table present just the required data (icon, name, full name, power stats, race, gender, height, weight, place of birth, alignment),<BR>
instead of all of it?

Has client-side pagination been implemented? Are there different pages that display different information?

Does the table initially displays 20 results?

Can you change the page size to one of 10, 20, 50, 100 or all results?

Are the results initially sorted by the name column in ascending order?

Are all columns of the table clickable in order to sort the results?

# Try to click once to sort the table by weight.
Was the table sorted numerically by weight in ascending order?<BR>
(be aware that cases like [75 kg, 100kg] should be in that order and not the other way around).

# Try to click twice to sort the table by place of birth.
Were the results sorted alphabetically by place of birth in descending order?

# Try to click several times on a column and observe its behavior.
Did the sort order toggle between ascending and descending order?<BR>
Are the missing values always shown last?

# Write only Cat on the search field.
As you type, do the results on the table change?<BR>
Does Catwoman appear in the results?<BR>
Does the project contains the use of fetch?

# Bonus.
Can you search for any fields apart from the name?<BR>
+Can you do a search with search these search operators: include/exclude for strings and equal/not equal/greater than/less than)?<BR>
+If you click on a hero, does the site display the details and a large image of it?<BR>
+Does the URL change when you make a search?<BR>
+After making a search and the URL changes, if you copy and paste it to a different tab, are the results displayed in the table the same as the ones from the previous tab?<BR>
+Does the project run quickly and effectively? (Favoring recursive, no unnecessary data requests, etc)?<BR>
+Does the code obey the good practices?<BR>

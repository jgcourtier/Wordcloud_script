The purpose of this script is to take natural language data that is in a single row of a table ie:

'The SERVICE was wonderful'

And format it in such a way where the end result is a removal of stop words, uniform it lowercase, and separate each token into a new row so that a word cloud in Tableau can be produced, counting each word as a separate row.

Result:

service

wonderful



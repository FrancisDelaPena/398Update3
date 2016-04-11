# 398Update3
Update 3 of Dr. Hayward's COMP 398 course

For COMP 398, Update 3 from 3/28/16-4/11/16.

For this version, I modified the "tcompare" section of the code to implement and experiment with James Tauber's implementation of the Unicode Collation Algorithm.

Unlike with Python's DIFF support, I could not find a way to compare exact changes.  However, this can be taken as an example of "scholarly collation", which the Diff algorithm separates itself from.
Scholarly collation should be able to find that there are differences, but not point out exactly what the differences are, so that students and researchers may find their own differences and comparisons.

In this case, using the same documents, the implementation prints out only identical lines to show how similar or different the texts are.

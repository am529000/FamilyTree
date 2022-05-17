# FamilyTreeProject
## TA family tree algorithm
1. Choose 2 People in the tree
2. Find Top Ancestor in the tree
3. Check for children or a partner to see if they are one of the chosen
4. once you find one of the children or a partner of the top ancestor go down to see if they have children or partners, if not choose another person on that same line. 
5. if you find that they hvae a child, start to go down to their children
6. go down the line of their children and dont stop until there is no more children
7. if only 1 was found or none were found go back to previous line and choose another person on the line
8. repeat steps 3-5 until you find both targets
9. once both are found, got to previous lines to the find the closest connection. 
10. go to a person that connects them.
11. if on same, possible siblings or cousin on nature of who is the ancestor.
12. find connection towards closest connecting ancestor.
13. if 1 away parent, if 2 away grandparent, if 3 away greatgrandparent, each add 1 = great on top of grandparent
14. next find seperate closest connection to each found person
15. (line 13), find seperate connection between next closest connection





A = generation in tree (ex. 5, 4, 3, 2...)
B = generation in tree (ex. 5, 4, 3, 2...)

parent of A (name)
parent of B (name)

same gen = sibling. 1st cousins
if parent A and B = same parent = siblings
if parent A and B = same gen but not same parent = uncle/aunt =  and/or a parent of A/B
same gen but not same parent = 1st cousins
each gen is a letter (ex. a, b, c, d, e...)
same letter = same gen
an equation for each possible combination to make it equal to an amount that determines connection

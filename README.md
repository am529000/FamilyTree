# FamilyTreeProject
## TA family tree algorithm
## NEW
A = generation in tree (ex. 5, 4, 3, 2...)
B = generation in tree (ex. 5, 4, 3, 2...)

parent of A (name code, ex. aa)
parent of B (name code, ex. aad)

List:
Name(a):
Name(ab):
Name(ab):
Name(abc):

List:
Elizabeth(a)
Marj(aa)
Rosanne(ab)
Ruthanne(ac)
Donnie(ad)
Patrica(ae)
Kim(aaa)
Monica(aab)
Martin(aac)
Gabe(aad)
John(aae)
Ben(aaf)
Jerome(aag)
John G(aaaa)
Jamie(aaab)
Julia(aaac)
Phil(aaba)
Alley(aabb)
Anna(aabc)
Steven(aabd)
Ellane(aada)
Jake(aadb)
Veera(aaga)
Precila(aagb)
Clarence(aagc)
Lincoln(aabaa)
Mo(aadaa)
Alex(aabaaa)

(each nextgeneration goes +1, and takes their old letters (aaa)
(each letter = a connection to the previous person above in the previous generation)
(each number = their generation number)


list of all people and their generation
asks if they are a chosen one, if not then continue
starts with the first person in the generation line, asks if they are a chosen one, if not continue through that generation
does through and asks everyone in that generation
goes down to next generation and continues till both are found
once both are found
find closest letter to find common ancestor, print(Ex. ComAnc: Marj)
count number of letters more than the common ancestor (Ex. Marj = aa, Jamie =aaab, so aaab - aa = ab or 2)



## OLD
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

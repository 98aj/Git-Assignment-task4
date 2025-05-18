Commands to complete this assignment are as follows.

task 4: 

1. mkdir task4
2. git init
3. touch master.txt
4. git add master.txt
5. git commit -m 'Commiting master file in master branch'
6. git remote add origin https://[secret-key-token]@github.com/98aj/Git-Assignment-task4.git
7. git push -u origin master
8. git branch private
9. git branch public1
10. git branch public2
11. git checkout public1
12. touch public1.txt
13. git add public1.txt
14. git commit -m 'Commiting public1 file in public1 branch'
15. git push -u origin public1
16. git chekcout master
17. git merge public1
18. git merge public2
19. git push -u origin master
20. git checkout private
21. echo 'Hello this is master file and changes done from private branch' > master.txt
22. cat master.txt (to verify changes are done)
23. git add master.txt
24. git commit -m 'Editing master file from private branch'
25. git push -u origin private
26. git checkout public1
27. git merge private
28. git push -u origin public1
29. git checkout public2
30. git merge private
31. git push -u origin public2
32. git checkout master
33. git merge private
34. git checkout private
35. git merge public1
36. git merge public2
37. git merge master
38. git push -u origin private

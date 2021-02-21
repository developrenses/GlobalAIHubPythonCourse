# GlobalAIHubPythonCourse
HW-1

import random
liste = set()
for num in range(1,100):
    if num >1:
        for i in range(2,num):  
            if (num % i) == 0:  
                break 
            
        else:
            liste.add(num)
            
lis1 = random.sample(liste,3)
liste.remove(lis1[0])
liste.remove(lis1[1])
liste.remove(lis1[2])
lis2 = random.sample(liste,3)
liste.remove(lis2[0])
liste.remove(lis2[1])
liste.remove(lis2[2])
lis3 = random.sample(liste,3)
matris = [lis1,
         lis2,
         lis3]
for i in range(3):
    print(matris[i])

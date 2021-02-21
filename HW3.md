# GlobalAIHubPythonCourse
HW-3

def prime_first():
    for a in range(0,500):
        for b in range(2,a):
            if (a%b==0):
                break
        else:
            if a!=0 and a!=1:
                print(a)
prime_first()

def prime_second():
    for c in range(500,1000):
        for d in range(2,c):
            if (c%d==0):
                break
        else:
            print(c)
prime_second()

#sadece fonksiyonları yazabildim :(

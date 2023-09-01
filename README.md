# Mario-Bullet
# cook your dish here
for i in range (int(input())):
    a,b,c = map(int,input().split())
    x = b//a
    if(c>x):
        print(c-x)
    else:
        print("0")

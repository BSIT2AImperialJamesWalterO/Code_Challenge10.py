# Code_Challenge10.py
for r in range(5, 0, -1):
    for s in range(1, r + 1):
        print(" ", end = " ")
    for t in range(6, r, -1):
        print("*" ,end=" ")
    for u in range(6, r, -1):
        print("*" ,end=" ")
    print()
    
for r in range(1,6):
    for s in range(1, r + 1):
        print(" ", end = " ")
    for t in range(6, r, -1):
        print("*" ,end=" ")
    for u in range(6, r, -1):
        print("*" ,end=" ")
    print()

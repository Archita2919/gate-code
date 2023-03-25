def AND (a, b):
 
    if a == 1 and b == 1:
        return True
    else:
        return False
    
# Driver code
if __name__=='__main__':
    print(AND(1, 1))

def NAND (a, b):
    if a == 1 and b == 1:
        return False
    else:
        return True
 
# Driver code
if __name__=='__main__':
    print(NAND(1, 0))

def OR(a, b):
    if a == 1 or b ==1:
        return True
    else:
        return False
 
# Driver code
if __name__=='__main__':
    print(OR(0, 0))

def XOR (a, b):
    if a != b:
        return 1
    else:
        return 0
 
# Driver code
if __name__=='__main__':
    print(XOR(5, 5))

def NOT(a):
    return not a
# Driver code
if __name__=='__main__':
    print(NOT(0))

def NOR(a, b):
    if(a == 0) and (b == 0):
        return 1
    elif(a == 0) and (b == 1):
        return 0
    elif(a == 1) and (b == 0):
        return 0
    elif(a == 1) and (b == 1):
        return 0
 
# Driver code
if __name__=='__main__':
    print(NOR(0, 0))

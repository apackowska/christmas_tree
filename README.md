# christmas_tree

def choinka (x):
    s = " "
    g = "*"
    for i in range (1, x+1):
        print ((x-i)*s + (2*i-1)*g)
    print ((x-1)*s + g)
    print ((x-2)*s + 3*g)

print (choinka(8))

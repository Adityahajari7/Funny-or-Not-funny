# Funny-or-Not-funny
# Enter your code here. Read input from STDIN. Print output to STDOUT
t = int(raw_input())
for a0 in range(t):
    a = str(raw_input())
    b = a[::-1]
    for i in range(len(a)):
        if i==len(a)-1:
            print "Funny"
        if abs(ord(a[i])-ord(a[i-1])) == abs(ord(b[i])-ord(b[i-1])):
            continue
        else:
            print "Not Funny"
            break
       
        
    

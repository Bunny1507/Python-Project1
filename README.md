# Python-Project1

f = open('bunny.txt','w')
f.write('India reacted to Kalams death with an outpouring of grief.'
        'numerous tributes were paid to the former president across'
        'the nation and on social media')
f.close()

f = open('bunny.txt',"r")
a = f.read()
sp = a.split(' ')
d = 0
for i in sp:
    d+=1
print(d)

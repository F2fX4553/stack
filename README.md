# stack

class stack: # ism lklas stack
    def __init__(self): # dalt lbina
        self.list=[] # hna ndiro arry wnsmiha asm li nhb items or list or arry or pos kima nhb
    def isempty(self): # hna nchof hade stack awe larry ida farar wida m3amer ida farare ydir true ida m3amer yktbli foalse
        return self.list == [] # hna kol torna yth9a9 ida fara wla m3amra

    def push(self,item): # hdi dala 3tinalha asm push wli hiya ndifo biha mtryrat da5le stak o lpush hdi n9dr nbdlha baye asm nhb mchi chart push
        self.list.append(item) # hna rana n9olo l append ya lappend ki y3tolk asmawat gardihom 3ndk

    def pop(self): # hdi dala sminaha pop bach n3rfo bli ade dala thdf
        return self.list.pop() # hna kolma nfasi haja ydor 3la lista yhwse 3la lasm li 9otlo souprimih ki yl9ah yfasih

    def size(self): # hdi dala sminaha size bach t3tili lhjm ta3 list
        return len(self.list) # hna yhsbli list ch7al mn object fiha


    def printstack(self): # hdi dala bach tatba3 wch kayn da5le  list
        for item in reversed(self.list): # hdi mfhmthach apipri wch haba t9sd mi fhmt bli
            print(item) # hdi bach ytba3li l3nasir


s = stack() # hdi bach n3yt lclass w ywrili wch fih
print(s.isempty()) # hna ntba3 true or foals bach ychof fara wla m3amra
print('==================================')
'''
hdo items li rah ndirhom da5le list'''
s.push('oussama')
s.push('roch')
s.push('nariman')
s.push('yasmin')
s.push(10)

s.printstack()

print('=================================')
print(s.pop()) # hna 3titlo amre bach yhdfli l itime 0 and 1
print(s.pop())


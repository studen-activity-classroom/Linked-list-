class Names:
    def __init__(self, data):
        self.data = data
        self.next = None
    
N1 = Names('ana')
N2 = Names('isa')
N3 = Names('jaha')
N4 = Names('friya')

N1.next = N2
N2.next = N3
N3.next = N4

currentNames = N1
while currentNames:
    print(currentNames.data, end=" -> ")
    currentNames = currentNames.next
print("null")null")

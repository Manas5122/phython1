#list
man = ["repp", "ramesh", 123, "uday"]
gayt= ["manoj", "santhu", 878, 465]
print(man)
print(gayt)

#empty list
manas = []
print(manas)

#nested list
manas = ["python", [8, 4, 6], ['a']]
print(manas)

manas = ('s','o','f','t','w','a','r','e')
print(manas[0])
print(manas[5])
print(manas[-6])
print(manas[1:4])
print(manas[:10])

manas = ["dhoni", "raina", 63, 87, "koihli", "jadeda"]
man = ["smith", "warner", 12, 65, "cricket"]
print(manas)
#update....
manas[3] = 66
print(manas)
#append...
manas.append(82)
print(manas)
#insert..
man.insert(123, "ram")
print(man)
#delete.._doc_
del manas[5]
print(manas)
#remove
man.remove("smith")
print(man)
#indexing
gayatri = [7556, 2776, "data", "name", 7646, 978464]
print(gayatri[2])
print(gayatri[1:3])

#sets
jeev = {"r", "y", "b", 7586, "s"}
print(jeev)
print(len(jeev))
jeev.add(5.6)
print(jeev)

set1 = {"false", "true", 97909}
set2 = {"problem", "solution", 664}
set3 = set1 & set2
print(set3)
set1 = 800
set2 = 300
print(set1 != set2)
print(set1 == set2)
print((set1) >= (set2))
print((set1) <= (set2))


#dictionaries
gopi = {"name": "manas", "age": 21, "year": 2000, "section": "k"}
print(gopi)
print(gopi["name"])
print(gopi.pop('age'))
print(gopi.popitem())
#update
gopi["name"] = "virat"
print(gopi)
#delete
del gopi["year"]
print(gopi)
#add item
gopi['address'] = 'mumbai'
print(gopi)
#clear
gopi.clear()
print(gopi)

#tuple
jeevan = ("hello", 21, 65, 8.9)
print(jeevan)
jeevan = ("mobile", "laptop", [54, 87, 12], (
    76,
    43,
))
print(jeevan)
jeevan = (54, 63, 76), ("hello", "world")
print(jeevan[0])
print(jeevan[1])
print(jeevan[0][1])


name = "aabbbccde"
all=[]
dict={}

for i in range(len(name)):         #Converts the string to a list
    all.append(name[i])


for lett in all:
     dict.update({lett:all.count(lett)})       #Creates a dictionary with key as alphabets and value as frequency of letter also the duplicate letters are ignored.
print(dict)


all_item = dict.items()
sorted_items = sorted(all_item)    # Takes the key-value of dictionary and SORTS by KEY in form of tuples inside a list [('a', 2), ('b', 3), ('c', 2), ('d', 1), ('e', 1)]
print(sorted_items)

sorted_items.sort(key=lambda x: x[1],reverse=True)     # SORTS the tuples according to second value inside tuple. [('b', 3), ('a', 2), ('c', 2), ('d', 1), ('e', 1)]
print(sorted_items)

for i in range(3):
    print(sorted_items[i][0], sorted_items[i][1])   # 




#======================1======================
str_1 = "The worlds fastest plane"
print(str_1.find("plane")) # Word plane startet with 19 index
print(str_1.find("car")) # str_1 haven't word car, and the function gave us -1 index
#======================2======================
start_number = 1 
while start_number<=10: # While will print the each number between 1 and 10
    print(start_number)
    start_number+=1
print(*list(range(1,11)),sep = "\n") # Range+list+* will print the each number between 1 and 10
print(*list(filter(lambda x: x%2 == 0,list(range(1,11)))),sep = "\n") # Range+list+filter+* will print the each even number between 1 and 10
#======================3======================
max_int = int(input("Enter the max number: "))
print("Sum all the number = ",sum(range(1,max_int+1))) # Enter the sum all the number
#======================Bonus======================
#======================1======================
print("a" + str(1))
#======================2======================
var = 2 # Any integer number
if isinstance(var, int):
    print("Я целое число!")
else: 
    print("Я не целое число!")
#======================3======================
are_fresh = True
are_big = True 
if are_fresh and are_big:
    print("Эти яблоки большие и свежие")
elif are_big and not are_fresh: 
    print("Эти яблоки большие, но не свежие")
elif are_fresh and not are_big:
    print("Эти яблоки свежие, но маленькие")
else: 
    print("Эти яблоки маленькие и не свежие")
#======================4======================
source_list = [1,2,3,4,5,6,7,8]
odd_numbers = list()
even_numbers = list()
for element in source_list: 
    print(element)
    if element % 2 == 0:
        even_numbers.append(element)
    else:
        odd_numbers.append(element)
print(odd_numbers,even_numbers,sep = "\n")
#======================5======================
def find_nth_occurence(phrase: str, letter_to_search: str, occurence) -> int:
    if phrase.count(letter_to_search)<occurence:
        return -1
    else:
        e = 0
        for i in range(len(phrase)):
            if phrase[i] == letter_to_search:
                e+=1
            if e == occurence:
                return i
assert find_nth_occurence("Dobry vecher, everybody", "y", 3) == 22
assert find_nth_occurence("Hello world", "o", 2) == 7

# * list in python *
 - Store multiple items in a single variables. 
 - lites are created using Square bracket [].

#### Create a list:
```
fruits=["apple","banana","mango"]
print(fruits)
```
#### List items are :
- ordered
- changable
- allow duplicate values 

## List length : 
len() function is used for count how many items a list has.
```
fruits=["apple","banana","mango"]
print(len(fruits)) 

// 3
```
Use list() constructer when we creating a new list.
```
fruits=list(("apple","banana","mango")) 
print(fruits)

# note the double round brackets 
```
## Acess list items :-
#### - Acess items
- In python , list items acess by referring to the index number.
```
fruits=["apple","banana","mango"]
print(fruits[1])  // banana
```
#### - Negative Items
- Negative indexing means start from the end. 
- -1 ---> Last items
- -2 ---> Second last items 
#### - Range of indexes
- range of indexes by specify where to start and where to end the range.
```
fruits=["apple","banana","mango"]
print(fruits[1:2])  // ['banana','mango']
```
#### - Check item exists or not 
- if you want to check either items exists or not , We use **IN** keyword.
```
fruits=["apple","banana","mango"]
if "apple" in fruits:
print("yes , it exists")  // Yes, it exists
```
## Change items value :-
- If you want to change item in list, So you refer to the index number.
```
fruits=["apple","banana","mango"]
fruits[2]="pineapple"
print(fruits)  // ['apple','banana','pineapple']
```
#### - Insert items
- without replacing any value , we can use the **insert()** method.
```
fruits=["apple","banana","mango"]
fruits.insert(1,"pineapple")
print(fruits)  // ['apple','pineapple','banana','mango']
```
### - Append items:-
- add an items to the end of the list use **append()** method.
```
fruits=["apple","banana","mango"]
fruits.append("pineapple")
print(fruits)  // ['apple','banana','mango','pineapple']
```
### - Extend items:-
- append element from another list to the current list.
```
fruits=["apple","banana","mango"]
fruits_new= ["milkshakes","pineapple"]
fruits.extend(fruits_new)
print(fruits)  

// ['apple','banana','mango','milkshakes','pineapple']

```
### - Remove Specified item:-
- **remove()** method use to remove specified item.
```
fruits=["apple","banana","mango"]
fruits.remove("mango")
print(fruits)  // ['apple','banana']
```
### - Remove Specific Index:-
- **pop()** method to use remove the specified index items.
```
fruits=["apple","banana","mango"]
fruits.pop(1)
print(fruits)  // ['apple','mango']
```
### - Clear the list:-
- **clear()** use to empaties the list.
```
fruits=["apple","banana","mango"]
fruits.clear()
print(fruits)  // []
```
## Loops in list
### - Loop through a list:-
- for is used to loop through the list items.
```
fruits=["apple","banana","mango"]
for x in fruits:
print(fruits)  

// apple
   banana
   mango
```
### - Loop through the index number:-   
- loop through the list items by refering to their index number.
- use the **range()** and **len()** functions to creat a suitable iterable.
```
fruits=["apple","banana","mango"]
for i in range(len(fruits))
print(fruits)  

// apple
   banana
   mango 
```








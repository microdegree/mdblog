---
title: 'ಪೈಥಾನ್-ಕಲಿಕೆ-zeroದಿಂದ-heroತನಕ'
author: [Ghost]
tags: []
image: img/marvin-meyer-794521-unsplash.jpg
date: '2020-11-05T10:00:00.000Z'
draft: false
---



# **ಪೈಥಾನ್ ಕಲಿಕೆ: Zeroದಿಂದ Heroತನಕ**

[![Hemalatharao](https://miro.medium.com/fit/c/96/96/0*_LxkLpCb93uoJDAA)](https://medium.com/@hemalatharao936?source=post_page-----107b751b1edf--------------------------------)

[Hemalatharao](https://medium.com/@hemalatharao936?source=post_page-----107b751b1edf--------------------------------)

Follow

[Nov 4](https://medium.com/microdegree/%E0%B2%AA%E0%B3%88%E0%B2%A5%E0%B2%BE%E0%B2%A8%E0%B3%8D-%E0%B2%95%E0%B2%B2%E0%B2%BF%E0%B2%95%E0%B3%86-zero%E0%B2%A6%E0%B2%BF%E0%B2%82%E0%B2%A6-hero%E0%B2%A4%E0%B2%A8%E0%B2%95-107b751b1edf?source=post_page-----107b751b1edf--------------------------------)  ·  10  min read

ಮೊದಲನೆಯದಾಗಿ, ಪೈಥಾನ್ ಎಂದರೇನು?

ಅದರ creator  _Guido van Rossum_  ಪ್ರಕಾರ, ಪೈಥಾನ್ ಒಂದು:

“ಉನ್ನತ-ಮಟ್ಟದ ಪ್ರೋಗ್ರಾಮಿಂಗ್ ಭಾಷೆ, ಮತ್ತು ಅದರ core design philosophyವು ಕೋಡ್ ಓದುವಿಕೆ ಮತ್ತು ಸಿಂಟ್ಯಾಕ್ಸ್ ಬಗ್ಗೆ ಆಗಿದೆ, ಇದು ಪ್ರೋಗ್ರಾಮರ್ಗಳಿಗೆ ಕೆಲವು conceptಗಳನ್ನು ವ್ಯಕ್ತಪಡಿಸಲು ಅನುವು ಮಾಡಿಕೊಡುತ್ತದೆ.”

ನನ್ನ ಮಟ್ಟಿಗೆ, ಪೈಥಾನ್ ಕಲಿಯಲು ಮೊದಲ ಕಾರಣವೆಂದರೆ ಅದು ಸುಂದರವಾದ ಪ್ರೋಗ್ರಾಮಿಂಗ್ ಭಾಷೆ. ಅದರಲ್ಲಿ ಕೋಡ್ ಮಾಡುವುದು ಮತ್ತು ನನ್ನ ಆಲೋಚನೆಗಳನ್ನು ವ್ಯಕ್ತಪಡಿಸುವುದು ನಿಜವಾಗಿಯೂ ಸಹಜ.

ಇನ್ನೊಂದು ಕಾರಣವೆಂದರೆ ನಾವು ಪೈಥಾನ್‌ನಲ್ಲಿ ಕೋಡಿಂಗ್ ಅನ್ನು ಅನೇಕ ವಿಧಗಳಲ್ಲಿ ಬಳಸಬಹುದು like : ಡೇಟಾ ಸೈನ್ಸ್, ವೆಬ್ ಡೆವಲಪ್‌ಮೆಂಟ್ ಮತ್ತು ಮೆಷಿನ್ ಲರ್ನಿಂಗ್. Quora, Pinterest ಮತ್ತು Spotify ಎಲ್ಲರೂ ತಮ್ಮ ಬ್ಯಾಕೆಂಡ್ ವೆಬ್ developmentಗೆ ಪೈಥಾನ್ ಅನ್ನು ಬಳಸುತ್ತಾರೆ.

**The Basics**

**1. Variables**

valueವನ್ನು ಸಂಗ್ರಹಿಸುವ ಪದಗಳಾಗಿ ನೀವು variableಗಳ ಬಗ್ಗೆ ಯೋಚಿಸಬಹುದು.

ಪೈಥಾನ್‌ನಲ್ಲಿ, ವೇರಿಯೇಬಲ್ ಅನ್ನುdefine ಮಾಡುವುದು ಮತ್ತು ಅದಕ್ಕೆ valueವನ್ನು ಹೊಂದಿಸುವುದು ನಿಜವಾಗಿಯೂ ಸುಲಭ. ನೀವು “ten” ಎಂಬ ವೇರಿಯೇಬಲ್ನಲ್ಲಿ ಸಂಖ್ಯೆ 10 ಅನ್ನು ಸಂಗ್ರಹಿಸಲು ಬಯಸುತ್ತೀರಿ ಎಂದು ಕಲ್ಪಿಸಿಕೊಳ್ಳಿ. ಇದನ್ನುಈ ರೀತಿಯಾಗಿ ಬರೆಯಬಹುದು:

ten = 10

ಇಲ್ಲಿ value 10 ಅನ್ನು ವೇರಿಯಬಲ್(variable) “ten” ಗೆ ನಿಗದಿಪಡಿಸಿದ್ದೀರಿ.

Twenty =20

Some_number =1000;

ನೀವು ಬಯಸುವ ಯಾವುದೇ **variables**ಗಳಿಗೆ ನೀವು ಬೇರೆ ಯಾವುದೇ  **value** ನಿಯೋಜಿಸಬಹುದು. ಮೇಲಿನ ಉದಾಹರಣೆಯಲ್ಲಿ ನೀವು ನೋಡುವಂತೆ, ವೇರಿಯೇಬಲ್ “Twenty” ಎಂಬ ವೇರಿಯೇಬಲ್ integer 20 ಅನ್ನು ಸಂಗ್ರಹಿಸುತ್ತದೆ, ಮತ್ತು “some_number” 1,000 valueವನ್ನು ಸಂಗ್ರಹಿಸುತ್ತದೆ.

Integerಗಳಲ್ಲದೆ, ನಾವು boolean (true/false), Strings, float ಮತ್ತು ಇತರ ಹಲವು data typesಗಳನ್ನು ಸಹ ಬಳಸಬಹುದು.

#boolean

True_bool = true

False_bool = false

#string

My_name = ”XYZ”

#float

Price = 25.50

**2. Control Flow: conditional statements​**

ಹೇಳಿಕೆ ನಿಜವೋ, ಸುಳ್ಳೋ ಎಂದು evaluate ಮಾಡಲು  **“if”**  expression ನ್ನು ಬಳಸಲಾಗುತ್ತದೆ. Expression ನಿಜವಾಗಿದ್ದರೆ, ಅದು “if” staementಲ್ಲಿರುವದನ್ನು ಕಾರ್ಯಗತಗೊಳಿಸುತ್ತದೆ. ಉದಾಹರಣೆಗೆ:

if True  **:**

print(“Hello Python”)

if 2 > 1:

print(“2 is greater than 1”)

2, 1 ಕ್ಕಿಂತ ಹೆಚ್ಚಾಗಿದೆ, ಆದ್ದರಿಂದ  **“print”**  ಕೋಡ್ ಅನ್ನು ಕಾರ್ಯಗತಗೊಳಿಸಲಾಗುತ್ತದೆ.

**“If”**  expression ತಪ್ಪಾಗಿದ್ದರೆ “else” ಹೇಳಿಕೆಯನ್ನು ಕಾರ್ಯಗತಗೊಳಿಸಲಾಗುತ್ತದೆ.

if 1 > 2  **:**

print(“Hello Python”)

else:

print(“1 is not greater than 2”)

1, 2 ಕ್ಕಿಂತ ಹೆಚ್ಚಿಲ್ಲ, ಆದ್ದರಿಂದ “else” ಹೇಳಿಕೆಯೊಳಗಿನ ಕೋಡ್ ಅನ್ನು ಕಾರ್ಯಗತಗೊಳಿಸಲಾಗುತ್ತದೆ.

ನೀವು  **“elif”**  ಹೇಳಿಕೆಯನ್ನು ಸಹ ಬಳಸಬಹುದು:

if 1 > 2  **:**

print(“1 is greater than 2”)

elif 2 > 1  **:**

print(“2 is greater than 1”)

else:

print(“both equal”)

**3. ಲೂಪಿಂಗ್ / ಇಟರೇಟರ್(Looping/Iterator):​**

ಪೈಥಾನ್‌ನಲ್ಲಿ, ನಾವು ವಿಭಿನ್ನ ರೂಪಗಳಲ್ಲಿ iterate ಮಾಡಬಹುದು.

**While Looping:**  ಹೇಳಿಕೆ ನಿಜವಾಗಿದ್ದರೆ, ಬ್ಲಾಕ್‌ನೊಳಗಿನ ಕೋಡ್ ಅನ್ನು ಕಾರ್ಯಗತಗೊಳಿಸಲಾಗುತ್ತದೆ. ಆದ್ದರಿಂದ, ಈ ಕೋಡ್ 1 ರಿಂದ 10 ರ ಸಂಖ್ಯೆಯನ್ನು print ಮಾಡುತ್ತದೆ..

i = 1

while i < 10:

print(i)

i += 1

ಅದೇ ಸಮಯದಲ್ಲಿ  **ಲೂಪ್‌(loop)**ಗೆ  **“loop condition”**  ಅಗತ್ಯವಿದೆ.  **Loop condition** ನಿಜವಾಗಿದ್ದರೆ, ಅದು iterate ಮಾಡುವುದನ್ನು ಮುಂದುವರಿಸುತ್ತದೆ. ಈ ಉದಾಹರಣೆಯಲ್ಲಿ, ಸಂಖ್ಯೆ 11 ಆಗಿದ್ದಾಗ  **loop condition** equals  _false_  ಆಗುತ್ತದೆ.

ಅದನ್ನು ಚೆನ್ನಾಗಿ ಅರ್ಥಮಾಡಿಕೊಳ್ಳಲು ಕೋಡ್‌ನ ಮತ್ತೊಂದು basic bit:

loop_condition = True

while loop_condition:

print(“Loop Condition keeps: %s” %(loop_condition))

loop_condition = False

loop condition\ trueವಾಗಿದೆ ಆದ್ದರಿಂದ ನಾವು ಅದನ್ನು false ಎಂದು ಹೊಂದಿಸುವವರೆಗೆ ಪುನರಾವರ್ತನೆಯಾಗುತ್ತದೆ(iterate).

**for Looping:**

ನೀವು ಬ್ಲಾಕ್‌ಗೆ “num” ಎಂಬ ವೇರಿಯೇಬಲ್ ಅನ್ನು ಅನ್ವಯಿಸುತ್ತೀರಿ, ಮತ್ತು  **“for”**  statement ಅದನ್ನು ನಿಮಗಾಗಿ iterate ಮಾಡುತ್ತದೆ. ಈ ಕೋಡ್ while ಕೋಡ್‌ನಂತೆಯೇ 1 ರಿಂದ 10 ರವರೆಗೆ print ಮಾಡುತ್ತದೆ.

for i in range(1, 11):

print(i)

range 1 ರಿಂದ ಪ್ರಾರಂಭವಾಗುತ್ತದೆ ಮತ್ತು 11 ನೇ elementವರೆಗೆ print ಮಾಡುತ್ತದೆ. (10 ಎಂಬುದು 10 ನೇ element ಆಗಿದೆ).

**List : Collection| Array | Data Structure**

ನೀವು integer 1 ಅನ್ನು ವೇರಿಯೇಬಲ್ನಲ್ಲಿ ಸಂಗ್ರಹಿಸಲು ಬಯಸುತ್ತೀರಿ ಎಂದು ಕಲ್ಪಿಸಿಕೊಳ್ಳಿ. ಆದರೆ ಈಗ ನೀವು 2 ಅನ್ನು ಸಂಗ್ರಹಿಸಲು ಬಯಸುತ್ತೀರಿ. ಮತ್ತು 3, 4, 5…

ನನಗೆ ಬೇಕಾದ ಎಲ್ಲಾ integerಗಳನ್ನು ಸಂಗ್ರಹಿಸಲು ನನಗೆ ಇನ್ನೊಂದು ಮಾರ್ಗವಿದೆ.

**_List_** ಎನ್ನುವುದು valueಗಳ ಪಟ್ಟಿಯನ್ನು ಸಂಗ್ರಹಿಸಲು ಬಳಸಬಹುದಾದ ಸಂಗ್ರಹವಾಗಿದೆ (ನಿಮಗೆ ಬೇಕಾದ ಈ integerಗಳಂತೆ).

my_int=[1,2,3,4,5,6]

ನಾವು ಒಂದು rangeನ್ನು ರಚಿಸಿದ್ದೇವೆ ಮತ್ತು ಅದನ್ನು my_int ನಲ್ಲಿ ಸಂಗ್ರಹಿಸಿದ್ದೇವೆ.

“ಈ ಶ್ರೇಣಿಯಿಂದ ನಾನು ಹೇಗೆ valueವನ್ನು ಪಡೆಯಬಹುದು?”

**_List_** ನಲ್ಲಿ  **_Index_**  ಅನ್ನುವ concept ಇದೆ. ಮೊದಲ element, index 0 ಪಡೆಯುತ್ತದೆ. ಎರಡನೆಯದು 1 ಪಡೆಯುತ್ತದೆ, ಮತ್ತು so on.

ಅದನ್ನು ಸ್ಪಷ್ಟಪಡಿಸಲು, ನಾವು ರಚನೆಯನ್ನು ಮತ್ತು ಪ್ರತಿಯೊಂದು elementನ್ನು ಅದರ indexದೊಂದಿಗೆ ಪ್ರತಿನಿಧಿಸಬಹುದು.

![Image for post](https://miro.medium.com/max/60/0*IkQrmybL_k8Y80It?q=20)

![Image for post](https://miro.medium.com/max/419/0*IkQrmybL_k8Y80It)

ಪೈಥಾನ್ ಸಿಂಟ್ಯಾಕ್ಸ್ ಬಳಸಿ, ಅರ್ಥಮಾಡಿಕೊಳ್ಳುವುದು ಸಹ ಸರಳವಾಗಿದೆ:

my_int = [10,20,30,40]

print(my_int[0]) # 10

print(my_int[1]) # 20

print(my_int[3]) # 40

ನೀವು integersಗಳನ್ನು ಸಂಗ್ರಹಿಸಲು ಬಯಸುವುದಿಲ್ಲ ಎಂದು ಕಲ್ಪಿಸಿಕೊಳ್ಳಿ. ನೀವು stringಗಳನ್ನು ಸಂಗ್ರಹಿಸಲು ಬಯಸುತ್ತೀರಿ. ಇಲ್ಲಿ ನಾವು ಪ್ರಾಣಿಗಳ ಹೆಸರುಗಳನ್ನೂ list ಮಾಡುವ.

Animals_name=[“Cat”,” Dog”,” Rabbit”,” Lion”,” Tiger”]

print(Animals_name(4)) #Tiger

ಇದು integerಗಳಂತೆಯೇ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆ.

listಗಳ indexಗಳು ಹೇಗೆ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತವೆ ಎಂಬುದನ್ನು ನಾವು ಈಗ ಕಲಿತಿದ್ದೇವೆ. ಆದರೆ list data structure (an item to a list) ನಾವು ಒಂದು elementನ್ನು ಹೇಗೆ ಸೇರಿಸಬಹುದು ಎಂಬುದನ್ನು ನಾನು ಇನ್ನೂ ನಿಮಗೆ ತೋರಿಸಬೇಕಾಗಿದೆ.

Listಗೆ ಹೊಸ valueವನ್ನು ಸೇರಿಸುವ ಸಾಮಾನ್ಯ ವಿಧಾನವೆಂದರೆ  **append**. ಅದು ಹೇಗೆ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆ ಎಂಬುದನ್ನು ನೋಡೋಣ:

# animals list

animals = [‘cat’, ‘dog’, ‘rabbit’]

# ‘guinea pig’ is appended to the animal’s list

animals.append(‘guinea pig’)

# Updated animals list

print(‘Updated animals list: ‘, animals)

Output:

Updated animals list: [‘cat’, ‘dog’, ‘rabbit’, ‘guinea pig’]

**Dictionary: Key-Value Data Structure**

Listಗಳನ್ನು integer ಸಂಖ್ಯೆಗಳೊಂದಿಗೆ ಸೂಚಿಸಲಾಗುತ್ತದೆ ಎಂದು ಈಗ ನಮಗೆ ತಿಳಿದಿದೆ.ನಾವು ಬಳಸಬಹುದಾದ ಕೆಲವು data structureಗಳು numeric, string ಅಥವಾ ಇತರ ರೀತಿಯ indicesಗಳಾಗಿವೆ.

**Dictionary data structure**  ಬಗ್ಗೆ ಕಲಿಯೋಣ. Dictionary ಇದು Key-Value pair ಸಂಗ್ರಹವಾಗಿದೆ. ಇದು ಹೇಗೆ ಕಾಣುತ್ತದೆ ಎಂಬುದು ಇಲ್ಲಿದೆ:

dictionary_example = {

“key1”: “value1”,

“key2”: “value2”

}

keyಯು valueವನ್ನು ಸೂಚಿಸುವ index ಆಗಿದೆ. dictionary valueವನ್ನು ನಾವು keyಯನ್ನು ಬಳಸಿ ಪ್ರವೇಶಿಸುತ್ತೇವೆ.

dictionary = {

“name”: “Arun”,

“lastname”: “K”,

“nationality”: “Indian”

}

print(“My name is %s” %(dictionary_[“name”])) # My name is Arun

print(“Last name is %s” %(dictionary[“lastname”])) # last name is K

print(“And by the way I’m %s” %(dictionary[“nationality”])) # And by the way I’m Indian

Dictionary ರಚನೆಯಾಗಿದೆ. name, last name ಮತ್ತು nationality. ಆ attributeಗಳು dictionary valueಗಳಾಗಿವೆ.

indexನ್ನು ಬಳಸಿಕೊಂಡು listನ್ನು ಹೇಗೆ ಪ್ರವೇಶಿಸುವುದು ಎಂದು ನಾವು ಕಲಿತಂತೆ, dictionaryಯಲ್ಲಿ ಸಂಗ್ರಹವಾಗಿರುವ valueವನ್ನು ಪ್ರವೇಶಿಸಲು ನಾವು indexಗಳನ್ನು (dictionary ಸಂದರ್ಭದ keyಗಳನ್ನು) ಸಹ ಬಳಸುತ್ತೇವೆ.

ಉದಾಹರಣೆಯಲ್ಲಿ, dictionaryಯಲ್ಲಿ, ಸಂಗ್ರಹವಾಗಿರುವ ಎಲ್ಲಾ valueಗಳನ್ನು ಬಳಸಿಕೊಂಡು name, last name ಮತ್ತು nationalityನ್ನುprint ಮಾಡಲಾಗಿದೆ.

dictionary ಮತ್ತೊಂದು ವಿಷಯವೆಂದರೆ ನಾವು ಯಾವುದನ್ನೂvalueವಾಗಿ ಬಳಸಬಹುದು. dictionaryನಲ್ಲಿ, “age” ಮತ್ತು integer valueನ್ನು ಸೇರಿಸಲು ನಾನು ಬಯಸುತ್ತೇನೆ:

dictionary = {

“name”: “Arun”,

“lastname”: “K”,

“Age”: 24,

“nationality”: “Indian”

}

print(“My name is %s” %(dictionary_[“name”])) # My name is Arun

print(“Last name is %s” %(dictionary[“lastname”])) # last name is K

print(“And by the way I’m %s” %(dictionary[“age”])) # And by the way I’m 24

print(“And by the way I’m %s” %(dictionary[“nationality”])) # And by the way I’m Indian

ಇಲ್ಲಿ ನಾವು ಕೀ (age) value (24) pairನ್ನು, ಸ್ಟ್ರಿಂಗ್(string) ಅನ್ನು ಕೀಯಾಗಿ ಮತ್ತು integerವನ್ನು valueವಾಗಿ ಬಳಸುತ್ತೇವೆ.

Listನಲ್ಲಿ ಮಾಡಿದಂತೆ, dictionaryಯಲ್ಲಿ ಎಲಿಮೆಂಟ್ಸ್ ಅನ್ನು ಹೇಗೆ add ಮಾಡಬಹುದು ಎಂಬುದನ್ನು ಕಲಿಯುವ.

dictionary = {

“name”: “Arun”,

“lastname”: “K”,

“nationality”: “Indian”

}

dictionary[‘age’] = 24

print(dictionary) # {‘nationality’: ‘Indian’, ‘age’: 24, ‘lastname’: ‘K’, ‘name’: ‘Arun’}

ನಾವು dictionary,  **ಕೀ**ಗೆ  **value**ವನ್ನು ನಿಗದಿಪಡಿಸಬೇಕಾಗಿದೆ.

**Iteration: Looping Through Data Structures**

ನಾವು  **ಪೈಥಾನ್ ಬೇಸಿಕ್ಸ್ನಲ್ಲಿ(basic)**  ಕಲಿತಂತೆ, list iteration ತುಂಬಾ ಸರಳವಾಗಿದೆ. ನಾವು ಪೈಥಾನ್ ಡೆವಲಪರ್‌ಗಳು ಸಾಮಾನ್ಯವಾಗಿ ಲೂಪಿಂಗ್‌ಗಾಗಿ ಬಳಸುತ್ತೇವೆ.

# Python3 code to iterate over a list

list = [1, 3, 5, 7, 9]

# Using for loop

for i in list:

print(i)

ಆದ್ದರಿಂದ listನಲ್ಲಿರುವ ಪ್ರತಿಯೊಂದು integerನ್ನು print ಮಾಡುತ್ತೇವೆ.

Hash data structureಗಾಗಿ, ನಾವು for loop ಅನ್ನು ಸಹ ಬಳಸಬಹುದು, ಆದರೆ ನಾವು ಕೀಯನ್ನು ಅನ್ವಯಿಸುತ್ತೇವೆ:

a_dict = {‘color’: ‘blue’}

for key in a_dict:

print(“%s → %s” %(key, a_dict[key]))

# color → blue

ಇದನ್ನು ಹೇಗೆ ಬಳಸುವುದು ಎಂಬುದಕ್ಕೆ ಇದು ಒಂದು ಉದಾಹರಣೆಯಾಗಿದೆ. dictionaryಯ ಪ್ರತಿಯೊಂದು ಕೀಗಾಗಿ, ನಾವು ಕೀ ಮತ್ತು ಅದರ ಅನುಗುಣವಾದ valueವನ್ನು print ಮಾಡುತ್ತೇವೆ.

ಇದನ್ನು ಮಾಡಲು ಇನ್ನೊಂದು ಮಾರ್ಗವೆಂದರೆ  **iteritems**  ವಿಧಾನವನ್ನು ಬಳಸುವುದು

a_dict = {‘color’: ‘blue’}

for key,value in a_dict.items():

print(“%s → %s” %(key, value))

# color → blue

ನಾವು ಎರಡು parameterಗಳನ್ನು ಕೀ ಮತ್ತು value ಎಂದು ಹೆಸರಿಸಿದ್ದೇವೆ, ಆದರೆ ಇದು ಅಗತ್ಯವಿಲ್ಲ. ಯಾವ ಹೆಸರು ಬೇಕಾದರೂ ಕೊಡಬಹುದು.

dictionary = {

“name”: “Arun”,

“lastname”: “K”,

“nationality”: “Indian”

}

for attribute, value in dictionary.items():

print(“My %s is %s” %(attribute, value))

# My name isArun

# My nickname is K

# My nationality is Indian

# My age is 24

ನಾವು dictionaryಯ ಕೀಗಾಗಿ attributeನ್ನು parameter ಆಗಿ ಬಳಸಿದ್ದೇವೆ ಎಂದು ನಾವು ನೋಡಬಹುದು ಮತ್ತು ಅದು ಸರಿಯಾಗಿ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆ.

**Classes & Objects**

Theory:

Objects ಅಂದರೆ ಕಾರುಗಳು, ನಾಯಿಗಳು ಅಥವಾ ಬೈಕ್‌ಗಳಂತಹ ನೈಜ ಜಗತ್ತಿನ ವಸ್ತುಗಳ ಪ್ರಾತಿನಿಧ್ಯವಾಗಿದೆ. ವಸ್ತುಗಳು ಎರಡು ಮುಖ್ಯ ಗುಣಲಕ್ಷಣಗಳನ್ನು ಹಂಚಿಕೊಳ್ಳುತ್ತವೆ:  **data**  and  **behavior**.

ಕಾರುಗಳು ಚಕ್ರಗಳ ಸಂಖ್ಯೆ, ಬಾಗಿಲುಗಳ ಸಂಖ್ಯೆ ಮತ್ತು ಆಸನ ಸಾಮರ್ಥ್ಯ(seating capacity)ದಂತಹ  **ಡೇಟಾ**ವನ್ನು ಹೊಂದಿವೆ, ಅವುಗಳು  **behaviour**ಯನ್ನು ಸಹ ಪ್ರದರ್ಶಿಸುತ್ತವೆ: ಅವು ವೇಗವನ್ನು ಹೆಚ್ಚಿಸಬಹುದು, ನಿಲ್ಲಿಸಬಹುದು, ಎಷ್ಟು ಇಂಧನ ಉಳಿದಿದೆ ಎಂಬುದನ್ನು ತೋರಿಸಬಹುದು.

ಆಬ್ಜೆಕ್ಟ್-ಓರಿಯೆಂಟೆಡ್ ಪ್ರೋಗ್ರಾಮಿಂಗ್‌ನಲ್ಲಿ(Object-oriented programming) ನಾವು ಡೇಟಾ(data)ವನ್ನು attributeಗಳಾಗಿ ಮತ್ತು behaviourಯನ್ನು method ಆಗಿ ಗುರುತಿಸುತ್ತೇವೆ.

data->attribute

behaviour->methods

ಒಂದು  **class**  ಪ್ರತ್ಯೇಕ ವಸ್ತುಗಳನ್ನು ರಚಿಸುವ ನೀಲನಕ್ಷೆ(blueprint). ನೈಜ ಜಗತ್ತಿನಲ್ಲಿ, ಒಂದೇ ರೀತಿಯ ಅನೇಕ ವಸ್ತುಗಳನ್ನು ನಾವು ಹೆಚ್ಚಾಗಿ ಕಾಣುತ್ತೇವೆ. ಕಾರುಗಳಂತೆ. ಒಂದೇ ರೀತಿಯ ತಯಾರಿಕೆ ಮತ್ತು ಮಾದರಿ (ಮತ್ತು ಎಲ್ಲವು ಎಂಜಿನ್, ಚಕ್ರಗಳು, ಬಾಗಿಲುಗಳು ಮತ್ತು ಮುಂತಾದವುಗಳನ್ನು ಹೊಂದಿವೆ). ಪ್ರತಿಯೊಂದು ಕಾರನ್ನು ಒಂದೇ ರೀತಿಯ blueprintಗಳಿಂದ ನಿರ್ಮಿಸಲಾಗಿದೆ ಮತ್ತು ಒಂದೇ componentಗಳನ್ನು ಹೊಂದಿದೆ.

**Python Object-Oriented Programming mode: ON**

ಪೈಥಾನ್, ಆಬ್ಜೆಕ್ಟ್-ಓರಿಯೆಂಟೆಡ್ ಪ್ರೋಗ್ರಾಮಿಂಗ್ ಭಾಷೆಯಾಗಿ, ಈ ಪರಿಕಲ್ಪನೆಗಳನ್ನು ಹೊಂದಿದೆ: class ಮತ್ತು object.

ಒಂದು class blueprint, ಅದರ objectಗಳಿಗೆ ಒಂದು ಮಾದರಿ(model).

ಆದ್ದರಿಂದ ಮತ್ತೆ, ಒಂದು class ಇದು ಕೇವಲ ಒಂದು ಮಾದರಿ, ಅಥವಾ attribute ಮತ್ತು behaviourನ್ನು ವ್ಯಾಖ್ಯಾನಿಸುವ ಒಂದು ಮಾರ್ಗವಾಗಿದೆ. ಉದಾಹರಣೆಯಾಗಿ, vehicle class ತನ್ನದೇ ಆದ attributeಗಳನ್ನು ಹೊಂದಿದ್ದು ಅದು ಯಾವ objectಗಳು vehicleಗಳು ಎಂಬುದನ್ನು ವ್ಯಾಖ್ಯಾನಿಸುತ್ತದೆ. ಚಕ್ರಗಳ ಸಂಖ್ಯೆ, ಟ್ಯಾಂಕ್ ಪ್ರಕಾರ, ಆಸನ ಸಾಮರ್ಥ್ಯ ಮತ್ತು ಗರಿಷ್ಠ ವೇಗ ಎಲ್ಲವೂ vehicleನ ಲಕ್ಷಣಗಳಾಗಿವೆ.

ಇದನ್ನು ಗಮನದಲ್ಲಿಟ್ಟುಕೊಂಡು, classesಗಾಗಿ ಪೈಥಾನ್ ಸಿಂಟ್ಯಾಕ್ಸ್ ಅನ್ನು ನೋಡೋಣ:

**syntax:**

**class Vehicle:**

**pass**

ನಾವು class statementಯೊಂದಿಗೆ classesಗಳನ್ನು ವ್ಯಾಖ್ಯಾನಿಸುತ್ತೇವೆ.

Objects ಒಂದು classನ ನಿದರ್ಶನಗಳಾಗಿವೆ. classನ್ನು ಹೆಸರಿಸುವ ಮೂಲಕ ನಾವು ಒಂದು ಉದಾಹರಣೆಯನ್ನು ರಚಿಸುತ್ತೇವೆ.

car = Vehicle()

print(car)

ಇಲ್ಲಿ  _car_**, class**  _vehicle_ನ  **object**ಗಿದೆ.

ನಮ್ಮ vehicle class ನಾಲ್ಕು attributeಗಳನ್ನು ಹೊಂದಿದೆ ಎಂಬುದನ್ನು ನೆನಪಿಡಿ: ಚಕ್ರಗಳ ಸಂಖ್ಯೆ, ಟ್ಯಾಂಕ್ ಪ್ರಕಾರ, ಆಸನ ಸಾಮರ್ಥ್ಯ ಮತ್ತು ಗರಿಷ್ಠ ವೇಗ. Vehicle objectನ್ನು ರಚಿಸುವಾಗ ನಾವು ಈ ಎಲ್ಲಾ attributeಗಳನ್ನು ಹೊಂದಿಸುತ್ತೇವೆ. ಆದ್ದರಿಂದ ಇಲ್ಲಿ, ಡೇಟಾವನ್ನು ಪ್ರಾರಂಭಿಸಿದಾಗ ಅದನ್ನು ಸ್ವೀಕರಿಸಲು ನಾವು ನಮ್ಮ classನ್ನು ವ್ಯಾಖ್ಯಾನಿಸುತ್ತೇವೆ:

class Vehicle:

def __init__(self, no_wheels, type_tank, seat_capacity, max_velocity):

self.no_wheels =no_wheels

self.type_tank = type_tank

self.seat_capacity = seat_capacity

self.max_velocity = max_velocity

ನಾವು  **init**  ವಿಧಾನ(method)ವನ್ನು ಬಳಸುತ್ತೇವೆ. ನಾವು ಇದನ್ನು ಕನ್‌ಸ್ಟ್ರಕ್ಟರ್ ವಿಧಾನ ಎಂದು ಕರೆಯುತ್ತೇವೆ. ಆದ್ದರಿಂದ ನಾವು vehicle objectನ್ನು ರಚಿಸಿದಾಗ, ನಾವು ಈ attributeಗಳನ್ನು ವ್ಯಾಖ್ಯಾನಿಸಬಹುದು. ನಾವು BMW model ಅನ್ನು ಪ್ರೀತಿಸುತ್ತೇವೆ ಎಂದು ಊಹಿಸಿ, ಮತ್ತು ನಾವು ಈ ರೀತಿಯ  **objec**tನ್ನು ರಚಿಸಲು ಬಯಸುತ್ತೇವೆ. ಇದು ನಾಲ್ಕು ಚಕ್ರಗಳನ್ನು ಹೊಂದಿದೆ, ವಿದ್ಯುತ್ ಶಕ್ತಿಯ ಮೇಲೆ ಚಲಿಸುತ್ತದೆ, 4 ಆಸನಗಳಿಗೆ ಸ್ಥಳಾವಕಾಶವನ್ನು ಹೊಂದಿದೆ, ಮತ್ತು ಗರಿಷ್ಠ ವೇಗವು 310 km/h (193 mph) . ಈ object ನ್ನು ರಚಿಸೋಣ:

class Vehicle:

def __init__(self, no_wheels, type_tank, seat_capacity, max_velocity):

self.no_wheels =no_wheels

self.type_tank = type_tank

self.seat_capacity = seat_capacity

self.max_velocity = max_velocity

def no_wheels(self):

return self.no_wheels

def set_no_wheels(self, number):

self.no_wheels = number

ಇದು ಎರಡು ವಿಧಾನಗಳ ಅನುಷ್ಠಾನವಾಗಿದೆ:

no_wheels ಮತ್ತು set_no_wheels. ನಾವು ಅದನ್ನು Getter ಮತ್ತು Setter ಎಂದು ಕರೆಯುತ್ತೇವೆ. ಏಕೆಂದರೆ ಮೊದಲನೆಯದು attribute valueವನ್ನು ಪಡೆಯುತ್ತದೆ, ಮತ್ತು ಎರಡನೆಯದು attributeಗೆ new valueವನ್ನು ಹೊಂದಿಸುತ್ತದೆ.

ಪೈಥಾನ್‌ನಲ್ಲಿ, getterಗಳು ಮತ್ತು setterಗಳನ್ನು ವ್ಯಾಖ್ಯಾನಿಸಲು @property (ಡೆಕೋರೇಟರ್‌ಗಳು) ಬಳಸಿ ನಾವು ಅದನ್ನು ಮಾಡಬಹುದು. ಇದನ್ನು ಕೋಡ್‌ನೊಂದಿಗೆ ನೋಡೋಣ:

class Vehicle:

def __init__(self, no_wheels, type_tank, seat_capacity, max_velocity):

self.no_wheels =no_wheels

self.type_tank = type_tank

self.seat_capacity = seat_capacity

self.max_velocity = max_velocity

@property

def no_wheels(self):

return self.no_wheels

@no_wheels.setter

def set_no_wheels(self, number):

self.no_wheels = number

ನಾವು ಈ ವಿಧಾನಗಳನ್ನು attributeಗಳಾಗಿ ಬಳಸಬಹುದು:

BMW = Vehicle(4, ‘electric’, 4, 310)

print(BMW.no_wheels) # 4

BMW.no_wheels = 2 # setting number of wheels to 2

print(BMW.no_wheels) # 2

ವಿಧಾನಗಳನ್ನು ವ್ಯಾಖ್ಯಾನಿಸುವುದಕ್ಕಿಂತ ಇದು ಸ್ವಲ್ಪ ಭಿನ್ನವಾಗಿದೆ. ವಿಧಾನಗಳು attributeಗಳಾಗಿ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತವೆ. ಉದಾಹರಣೆಗೆ, ನಾವು ಹೊಸ ಸಂಖ್ಯೆಯ ಚಕ್ರಗಳನ್ನು ಹೊಂದಿಸಿದಾಗ, ನಾವು ಎರಡನ್ನುparameterಗಿ ಅನ್ವಯಿಸುವುದಿಲ್ಲ, ಆದರೆ value 2 ಅನ್ನು no_wheelsಗಳಿಗೆ ಹೊಂದಿಸುತ್ತೇವೆ. ಪೈಥೋನಿಕ್ getter ಮತ್ತು setter ಕೋಡ್ ಬರೆಯಲು ಇದು ಒಂದು ಮಾರ್ಗವಾಗಿದೆ.

ಆದರೆ “make_noise” ವಿಧಾನದಂತಹ ಇತರ ವಿಷಯಗಳಿಗೆ ನಾವು ವಿಧಾನಗಳನ್ನು ಸಹ ಬಳಸಬಹುದು. ಇದನ್ನು ನೋಡೋಣ:

class Vehicle:

def __init__(self, no_wheels, type_tank, seat_capacity, max_velocity):

self.no_wheels =no_wheels

self.type_tank = type_tank

self.seat_capacity = seat_capacity

self.max_velocity = max_velocity

def make_noise(self):

print(‘VRUUUUUUUM’)

ನಾವು ಈ ವಿಧಾನವನ್ನು ಕರೆದಾಗ, ಅದು “VRRRRUUUUM” string ಅನ್ನು ಹಿಂದಿರುಗಿಸುತ್ತದೆ.

BMW = Vehicle(4, ‘electric’, 4, 310)

BMW.make_noise() # VRUUUUUUUM

**ಎನ್ಕ್ಯಾಪ್ಸುಲೇಷನ್(Encapsulation):Hiding Information**

ಎನ್ಕ್ಯಾಪ್ಸುಲೇಷನ್(Encapsulation) ಎನ್ನುವುದು objectಗಳ ಡೇಟಾ ಮತ್ತು methodಗಳಿಗೆ ನೇರ ಪ್ರವೇಶವನ್ನು ನಿರ್ಬಂಧಿಸುವ ಒಂದು ಕಾರ್ಯವಿಧಾನವಾಗಿದೆ. ಆದರೆ ಅದೇ ಸಮಯದಲ್ಲಿ, ಅದು ಆ ಡೇಟಾದ (ಆಬ್ಜೆಕ್ಟ್‌ಗಳ methodಗಳು) ಕಾರ್ಯಾಚರಣೆಯನ್ನು ಸುಗಮಗೊಳಿಸುತ್ತದೆ.

“ಡೇಟಾ members ಮತ್ತು member function ನ್ನು ಮರೆಮಾಡಲು ಎನ್ಕ್ಯಾಪ್ಸುಲೇಷನ್ ಅನ್ನು ಬಳಸಬಹುದು. ಈ ವ್ಯಾಖ್ಯಾನದಡಿಯಲ್ಲಿ, ಎನ್‌ಕ್ಯಾಪ್ಸುಲೇಷನ್ ಎಂದರೆ objectನ ಆಂತರಿಕ ಪ್ರಾತಿನಿಧ್ಯವನ್ನು(internal reperesentation) ಸಾಮಾನ್ಯವಾಗಿ objectನ ವ್ಯಾಖ್ಯಾನದ ಹೊರಗಿನ ನೋಟದಿಂದ ಮರೆಮಾಡಲಾಗಿದೆ. ” — ವಿಕಿಪೀಡಿಯಾ

objectನ ಎಲ್ಲಾ ಆಂತರಿಕ ಪ್ರಾತಿನಿಧ್ಯವನ್ನು ಹೊರಗಿನಿಂದ ಮರೆಮಾಡಲಾಗಿದೆ. object ಮಾತ್ರ ಅದರ ಆಂತರಿಕ ಡೇಟಾದೊಂದಿಗೆ ಸಂವಹನ ನಡೆಸಬಲ್ಲದು.

ಮೊದಲಿಗೆ, public ಮತ್ತು non-public ನಿದರ್ಶನ ಅಸ್ಥಿರಗಳು(instance variables) ಮತ್ತು methodಗಳು ಹೇಗೆ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತವೆ ಎಂಬುದನ್ನು ನಾವು ಅರ್ಥಮಾಡಿಕೊಳ್ಳಬೇಕು.

**Public instance variable:**

ಪೈಥಾನ್ classಗಾಗಿ, ನಮ್ಮ ಕನ್‌ಸ್ಟ್ರಕ್ಟರ್(constructor) methodಲ್ಲಿ ನಾವು  **Public instance variable**  ಅನ್ನು ಪ್ರಾರಂಭಿಸಬಹುದು. ಇದನ್ನು ನೋಡೋಣ:

ಕನ್ಸ್ಟ್ರಕ್ಟರ್ ವಿಧಾನದೊಳಗೆ:

class Animal:

def __init__(self, animal_name):

self.animal_name = animal_name

ಇಲ್ಲಿ ನಾವು animal_name ಮೌಲ್ಯ(value)ವನ್ನು public instance variableಗೆ ವಾದವಾಗಿ ಅನ್ವಯಿಸುತ್ತೇವೆ.

cat = Animal(‘Cat’)

print(cat.animal_name) # => Cat

Class ಒಳಗೆ:

class Animal:

animal_name = ‘Cat’

ಇಲ್ಲಿ, ನಾವು animal_nameನ್ನು ಆರ್ಗ್ಯುಮೆಂಟ್‌(argument)ನಂತೆ ಅನ್ವಯಿಸುವ ಅಗತ್ಯವಿಲ್ಲ, ಮತ್ತು ಎಲ್ಲಾ ನಿದರ್ಶನ objectಗಳು cat ಯೊಂದಿಗೆ ಪ್ರಾರಂಭಿಸಲಾದ class attributeನ್ನು ಹೊಂದಿರುತ್ತವೆ.

cat = Animal()

print(cat.animal_name) # => Cat

ನಾವು  _public instance variable_  ಮತ್ತು _class_  attributeಗಳನ್ನು ಬಳಸಬಹುದು ಎಂದು ನಾವು ಈಗ ಕಲಿತಿದ್ದೇವೆ. _public_ ಭಾಗದ ಮತ್ತೊಂದು ಕುತೂಹಲಕಾರಿ ವಿಷಯವೆಂದರೆ ನಾವು ವೇರಿಯಬಲ್ ಮೌಲ್ಯ(value)ವನ್ನು ನಿರ್ವಹಿಸಬಹುದು. ಅದರಿಂದ ನಮ್ಮ objectವು ಅದರ ವೇರಿಯಬಲ್ ಮೌಲ್ಯವನ್ನು ನಿರ್ವಹಿಸಬಹುದು:  _get ಮತ್ತು set_ ವೇರಿಯಬಲ್ value.

Animal classನ್ನು ಗಮನದಲ್ಲಿಟ್ಟುಕೊಂಡು, ನಾವು ಅದರ breed ವೇರಿಯೇಬಲ್‌ಗೆ ಮತ್ತೊಂದು valueವನ್ನು ಹೊಂದಿಸಲು ಬಯಸುತ್ತೇವೆ:

cat = Animal(‘Cat’)

cat.breed = ‘Persian’

print(cat.breed) ` # => Persian

ನಾವು ಮತ್ತೊಂದು valueವನ್ನು (Persian) breed instance ವೇರಿಯೇಬಲ್‌ಗೆ ಹೊಂದಿಸಿದ್ದೇವೆ ಮತ್ತು ಅದು valueವನ್ನು ನವೀಕರಿಸಿದೆ. ಇದು public ವೇರಿಯಬಲ್ ಆಗಿರುವುದರಿಂದ, ನಾವು ಅದನ್ನು ಮಾಡಬಹುದು.

**Non-public instance variable:**

**ನಾವು ಇಲ್ಲಿ “private” ಎಂಬ ಪದವನ್ನು ಬಳಸುವುದಿಲ್ಲ, ಏಕೆಂದರೆ ಪೈಥಾನ್‌ನಲ್ಲಿ ಯಾವುದೇ attribute ನಿಜವಾಗಿಯೂ privateಗಿಲ್ಲ (ಸಾಮಾನ್ಯವಾಗಿ ಅನಗತ್ಯವಾದ ಕೆಲಸವಿಲ್ಲದೆ). — ಪಿಇಪಿ 8**

Public instance variable ಆಗಿ, ನಾವು non-public instance variable ಅನ್ನು ಕನ್‌ಸ್ಟ್ರಕ್ಟರ್ method ಒಳಗೆ ಅಥವಾ class ಒಳಗೆ ವ್ಯಾಖ್ಯಾನಿಸಬಹುದು. ಸಿಂಟ್ಯಾಕ್ಸ್ ವ್ಯತ್ಯಾಸವೆಂದರೆ: public instance variableಗಳಿಗಾಗಿ, ವೇರಿಯಬಲ್ ಹೆಸರಿನ ಮೊದಲು ಅಂಡರ್ಸ್ಕೋರ್ (_)(underscore) ಬಳಸಿ.

**“‘ Private’ instance variableಗಳು ಪೈಥಾನ್‌ನಲ್ಲಿ ಅಸ್ತಿತ್ವದಲ್ಲಿಲ್ಲದ ವಸ್ತುವಿನ ಒಳಗಿನಿಂದ ಹೊರತುಪಡಿಸಿ ಪ್ರವೇಶಿಸಲಾಗುವುದಿಲ್ಲ. ಆದಾಗ್ಯೂ, ಹೆಚ್ಚಿನ ಪೈಥಾನ್ ಕೋಡ್ ಅನ್ನು ಅನುಸರಿಸುವ ಒಂದು ಸಮಾವೇಶವಿದೆ: ಅಂಡರ್ಸ್ಕೋರ್ (e.g.. _spam) ನೊಂದಿಗೆ prefixed ಹೆಸರನ್ನು API ಯ non-public ಭಾಗವಾಗಿ ಪರಿಗಣಿಸಬೇಕು (ಅದು function, method ಅಥವಾ data member ಆಗಿರಲಿ) ”- ಪೈಥಾನ್ ಸಾಫ್ಟ್‌ವೇರ್ ಫೌಂಡೇಶನ್**

ಒಂದು ಉದಾಹರಣೆ ಇಲ್ಲಿದೆ:

class Company:

def __init__(self, name, email):

self._name = name

self._email = email

ನೀವು ಇಮೇಲ್ ವೇರಿಯಬಲ್ ನೋಡಿದ್ದೀರಾ? non-public variable ಅನ್ನು ನಾವು ಹೀಗೆ ವ್ಯಾಖ್ಯಾನಿಸುತ್ತೇವೆ:

google = Person(‘Google’, ‘google@gmail.com’)

print(google._email) # google[@gmail.com](mailto:tk@mail.com)

ನಾವು ಅದನ್ನು ಪ್ರವೇಶಿಸಬಹುದು(access) ಮತ್ತು ನವೀಕರಿಸಬಹುದು(update).non-public variableಗಳು ಕೇವಲ ಒಂದು ಸಮಾವೇಶವಾಗಿದೆ(convention) ಮತ್ತು ಇದನ್ನು API ಯ non-public ಭಾಗವಾಗಿ ಪರಿಗಣಿಸಬೇಕು.

ಆದ್ದರಿಂದ ನಾವು ನಮ್ಮ class ವ್ಯಾಖ್ಯಾನ(definition)ದೊಳಗೆ ಅದನ್ನು ಮಾಡಲು ಅನುಮತಿಸುವ ವಿಧಾನವನ್ನು(method) ಬಳಸುತ್ತೇವೆ. ಅದನ್ನು ಅರ್ಥಮಾಡಿಕೊಳ್ಳಲು ಎರಡು ವಿಧಾನಗಳನ್ನು(methods) (email ಮತ್ತು update_mail) ಕಾರ್ಯಗತಗೊಳಿಸೋಣ:

class Company:

def __init__(self, name, email):

self._name = name

self._email = email

def update_email(self, new_email):

self._email = new_email

def email(self):

return self._email

ಈಗ ನಾವು ಆ ವಿಧಾನಗಳನ್ನು(methods) ಬಳಸಿಕೊಂಡು non-public variableನ್ನು ನವೀಕರಿಸಬಹುದು(update) ಮತ್ತು ಪ್ರವೇಶಿಸಬಹುದು(access). ನೋಡೋಣ:

google =Company(‘Google’, ‘google@gmail.com’)

print(google.email()) # => google@gmail.com

# google._email = ‘new_google@gmail.com’ — treat as a non-public part of the class API

print(google.email()) # => google@gmail.com

google.update_email(‘new_google@gmail.com’)

print(google.email()) # => new_google@gmail.com

1.  ಹೆಸರು google ಮತ್ತು ಇಮೇಲ್ google@gmail.com ನೊಂದಿಗೆ ನಾವು ಹೊಸ objectನ್ನು ಪ್ರಾರಂಭಿಸಿದ್ದೇವೆ
2.  non-public ವೇರಿಯೇಬಲ್ ಅನ್ನು methodದೊಂದಿಗೆ ಪ್ರವೇಶಿಸುವ ಮೂಲಕ ಇಮೇಲ್ ಅನ್ನು ಮುದ್ರಿಸಲಾಗಿದೆ
3.  ನಮ್ಮ classದಿಂದ ಹೊಸ ಇಮೇಲ್ ಅನ್ನು ಹೊಂದಿಸಲು ಪ್ರಯತ್ನಿಸಿದೆ
4.  ನಾವು non-public ವೇರಿಯೇಬಲ್ ಅನ್ನು API ಯ ಸಾರ್ವಜನಿಕೇತರ ಭಾಗವಾಗಿ ಪರಿಗಣಿಸಬೇಕಾಗಿದೆ
5.  ನಮ್ಮ instance method ದೊಂದಿಗೆ non-public ವೇರಿಯೇಬಲ್ ಅನ್ನು ನವೀಕರಿಸಲಾಗಿದೆ
6.  ಸಹಾಯಕ ವಿಧಾನದೊಂದಿಗೆ ನಾವು ಅದನ್ನು ನಮ್ಮ classದೊಳಗೆ ನವೀಕರಿಸಬಹುದು.

**ಪಬ್ಲಿಕ್ ವಿಧಾನ(Public Method):**

Public Methodಗಳೊಂದಿಗೆ, ನಾವು ಅವುಗಳನ್ನು ನಮ್ಮ classದಿಂದಲೂ ಬಳಸಬಹುದು:

class Person:

def __init__(self,f_name, age):

self.f_name = name

self._age = age

def show_age(self):

return self._age

ಪರೀಕ್ಷೆ ಮಾಡುವ

person = Person(‘Ram’, 25)

print(person.show_age()) # => 25

**Non-Public ವಿಧಾನ(Non-public method):**

ಆದರೆ  **Non-public method**ಗಳೊಂದಿಗೆ ನಾವು ಅದನ್ನು ಮಾಡಲು ಸಾಧ್ಯವಿಲ್ಲ. ಅದೇ person classನ್ನು ಕಾರ್ಯಗತಗೊಳಿಸೋಣ, ಆದರೆ ಈಗ ಅಂಡರ್ಸ್ಕೋರ್ (_) ಅನ್ನು ಬಳಸಿಕೊಂಡು show_age  **Non-public method**ದೊಂದಿಗೆ ಕಾರ್ಯಗತಗೊಳಿಸೋಣ.

class Person:

def __init__(self, name, age):

self._name = name

self._age = age

def _show_age(self):

return self._age

ಈಗ non-public method ನ್ನು ಆಬ್ಜೆಕ್ಟ್(object) ಒಟ್ಟಿಗೆ ಕರೆಯುವ

person = Person(‘Ram’, 25)

print(person._show_age()) # => 25

ನಾವು ಅದನ್ನು ಪ್ರವೇಶಿಸಬಹುದು(access) ಮತ್ತು ನವೀಕರಿಸಬಹುದು(update). non-public methodಗಳು ಕೇವಲ ಒಂದು ಸಮಾವೇಶವಾಗಿದೆ(convention) ಮತ್ತು ಇದನ್ನು API ಯ non-public ಭಾಗವಾಗಿ ಪರಿಗಣಿಸಬೇಕು.

ನಾವು ಅದನ್ನು ಹೇಗೆ ಬಳಸಬಹುದು ಎಂಬುದಕ್ಕೆ ಉದಾಹರಣೆ ಇಲ್ಲಿದೆ:

class Person:

def __init__(self, f_name, salary):

self.f_name = f_name

self._salary = salary

def show_salary(self):

return self._get_salary()

def _get_salary(self):

return self._salary

person = Person(‘Ram’, 20000)

print(person.show_salary()) # => 20000

ಇಲ್ಲಿ ನಾವು _get_salary ಸಾರ್ವಜನಿಕೇತರ ವಿಧಾನ(non-public method) ಮತ್ತು show_salary public methodನ್ನು ಹೊಂದಿದ್ದೇವೆ. Show_salary ಅನ್ನು ನಮ್ಮ objectನಿಂದ (ನಮ್ಮ classದಿಂದ ಹೊರಗೆ) ಬಳಸಬಹುದು ಮತ್ತು _get_salary ಅನ್ನು ನಮ್ಮ class ವ್ಯಾಖ್ಯಾನದೊಳಗೆ(definition) ಮಾತ್ರ ಬಳಸಲಾಗುತ್ತದೆ (show_salary ವಿಧಾನದ ಒಳಗೆ). ಆದರೆ ಮತ್ತೆ: ಸಮಾವೇಶದ (convention) ವಿಷಯವಾಗಿ.

**ಎನ್ಕ್ಯಾಪ್ಸುಲೇಷನ್ ಸಾರಾಂಶ(Encapsulation Summary):**

ಎನ್ಕ್ಯಾಪ್ಸುಲೇಷನ್ ಮೂಲಕ ನಾವು ವಸ್ತುವಿನ ಆಂತರಿಕ ಪ್ರಾತಿನಿಧ್ಯವನ್ನು(internal representation) ಹೊರಗಿನಿಂದ ಮರೆಮಾಡಲಾಗಿದೆ ಎಂದು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಬಹುದು.

**Inheritance(ಇನ್ಹೆರಿಟನ್ಸ್)(ಅನುವಂಶಿಕ): behaviors and characteristics**

ಕೆಲವು objects ಕೆಲವು ವಿಷಯಗಳನ್ನು ಸಾಮಾನ್ಯವಾಗಿ ಹೊಂದಿವೆ: ಅವು  **behaviors and characteristics**.

ಉದಾಹರಣೆಗೆ, ನನ್ನ ತಂದೆಯಿಂದ ಕೆಲವು ಗುಣಲಕ್ಷಣಗಳು ಮತ್ತು ನಡವಳಿಕೆಗಳನ್ನು ನಾನು ಪಡೆದಿದ್ದೇನೆ. ನಾನು ಅವರ ಕಣ್ಣು ಮತ್ತು ಕೂದಲನ್ನು ಗುಣಲಕ್ಷಣಗಳಾಗಿ ಅನುವಂಶಿಕವಾಗಿ ಪಡೆದಿದ್ದೇನೆ.

ಆಬ್ಜೆಕ್ಟ್-ಓರಿಯೆಂಟೆಡ್ ಪ್ರೋಗ್ರಾಮಿಂಗ್‌ನಲ್ಲಿ, classes ಸಾಮಾನ್ಯ ಗುಣಲಕ್ಷಣಗಳನ್ನು (data) ಮತ್ತು ನಡವಳಿಕೆಯನ್ನು (methodಗಳನ್ನು) ಮತ್ತೊಂದು class ದಿಂದ ಪಡೆದುಕೊಳ್ಳಬಹುದು.

ನಾವು ಇನ್ನೊಂದು ಉದಾಹರಣೆಯನ್ನು ನೋಡೋಣ ಮತ್ತು ಅದನ್ನು ಪೈಥಾನ್‌ನಲ್ಲಿ ಕಾರ್ಯಗತಗೊಳಿಸೋಣ.

Animal ಅನ್ನು ಕಲ್ಪಿಸಿಕೊಳ್ಳಿ. ಇಲ್ಲಿ sleep ಹಾಗು eat, animal ನ ಲಕ್ಷಣಗಳಾಗಿವೆ. Dog class Animal classದಿಂದ ಇದೇ ಗುಣಲಕ್ಷಣಗಳನ್ನು ಪಡೆದುಕೊಳ್ಳುತ್ತದೆ ಎಂದು ನಾವು ಹೇಳಬಹುದು.

class Animal:

def sleep(self):

print(“Animal is Sleeping”)

def eat(self):

print(“Animal is eating”)

#child class Dog inherits the base class Animal

class Dog(Animal):

def bark(self):

print(“dog barking”)

d = Dog()

d.bark()

d.sleep()

d.eat()

**Article By: Hemalatha**

Credits:  [https://medium.com/the-renaissance-developer/learning-python-from-zero-to-hero-8ceed48486d5](https://medium.com/the-renaissance-developer/learning-python-from-zero-to-hero-8ceed48486d5)

MicroDegree is an edtech platform for learning Emerging Technologies such as Full-Stack Development, Data Science, Machine Learning using vernacular at an affordable price. For more details reach out to hello@microdegree.work

🚀 For Course Certification : [https://bit.ly/3gt2nY7](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqblAzcGQxZlRtSmdYZlppbDNUd2t0MFNSanV1QXxBQ3Jtc0tuS2VjaXpMd1hFS1I5NEFuMkxkYThlZE9MZkVzNGFmTXYxTTRtZjBsX0lkSTU3MEpEdnpCTnI3MUp2QVpNdWc0LXBjNEpVWEVhMTBuajBEeXRiMnZSWnpFVDJHMTlCRk91bkNpR24ySGxUSzJUblNfUQ%3D%3D&q=https%3A%2F%2Fbit.ly%2F3gt2nY7)

👍 Youtube:: [https://bit.ly/3ajK4Cz](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbDlUVFVtUVN1Wnl0Z3lpZ19aUVV5ZVU1SWQyQXxBQ3Jtc0tuamNVOWJCVkdsNmwzcEF2VG1XS0cwYmZWekJVbFp2enBldkg1WUEzUm1iSkZuV0ZzbGduSG8tSXlRM1N1bzRtR1BCMGN2cTJMekJSS0xzVE9pdFBrd2hpNUV5SDQ5dl9sSFFYbERzQ1NNdU5CWWU4WQ%3D%3D&q=https%3A%2F%2Fbit.ly%2F3ajK4Cz)

Website : [https://microdegree.work](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbjR2M3JJekdSZTZlTVFCNkt5RFBTc1JNMlhpUXxBQ3Jtc0tuZHhRdjZtQW9ubmliWXAxSVNfMm5UemNrS2RMd1hDMmtIdEdGcmlFZmpkTDRkV1JFbkl3Wng1b2NRSXZJeWVlMjFGWmRpWmJSUU5jTGZmMFA0NTMxRUJtTnBlVlNESUdDYlA1QU4tcUdzZ1gwZHFUWQ%3D%3D&q=https%3A%2F%2Fmicrodegree.work)

LinkedIn : [https://www.linkedin.com/company/micr](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa1Z1SEw5M182a2I3ZC1BN25WeFdYYVNaRWkzQXxBQ3Jtc0tsTmlGQkN5RExFekhvWWFjVHJEZUZadVZVNW5NTURjYkxaSWlVTzFJaVU0aUJ3Q1Y1QXZaRU5sbEJFaVpiOUp6a3V4a3dZczVlSVA4SzVvYU1Jc3A3SEVUMkROUEpNeFFSNkxrbldZOVhTQTBUQWdFbw%3D%3D&q=https%3A%2F%2Fwww.linkedin.com%2Fcompany%2Fmicr)...

Facebook : [https://www.facebook.com/microdegree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa3BNeV9oRnNsVmdiMW1malJ4M3M2REVXUVItUXxBQ3Jtc0tsN0V6MXIxOXRCSU9DMDVBQm0wemEyMnFWMWRNQVRNNlNxX2ZwOHdQLWRUWVQ1SnBSR3JFLUFnLV9VS2FYdk9QQ0x5MjZZOEMyV2JkV2o2emNVMHhZVEZUbDRKdTBoVnBXS3FGNERiZkN3aFNXOF9Xbw%3D%3D&q=https%3A%2F%2Fwww.facebook.com%2Fmicrodegree)

Instagram : [https://www.instagram.com/micro.degree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbU82YjFKOFBrMXZ4QkRrWWtlbTlzV1VvU1g1QXxBQ3Jtc0trYndfRGt1cUtVS3ZUaFRkVEJtSUd4M1VJTndfR2s1WDQ0Y3Axd0dXdzN1eVRNZHF2VEo5MFhyZkkxRmVXcXJZMUN0X1dXYTZsY1RyNS11OVJWWG0zd0ZKX1EzcXJMSFU4Tnd2QzF6dUJYLTdrZW0zaw%3D%3D&q=https%3A%2F%2Fwww.instagram.com%2Fmicro.degree)
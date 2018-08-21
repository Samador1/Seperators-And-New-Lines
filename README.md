# Seperators-And-New-Lines
Python 3.7.0 (v3.7.0:1bf9cc5093, Jun 26 2018, 23:26:24) 
[Clang 6.0 (clang-600.0.57)] on darwin
Type "copyright", "credits" or "license()" for more information.
>>> print  "Sierra"
SyntaxError: Missing parentheses in call to 'print'. Did you mean print("Sierra")?
>>> print("Sierra")
Sierra
>>> print("Sierra Amador")
Sierra Amador
>>> print("Sierra Amador", "student")
Sierra Amador student
>>> course = "Pyhton for Beginners (2018)"
>>> print(course)
Pyhton for Beginners (2018)
>>> print(course, "Sierra Amador")
Pyhton for Beginners (2018) Sierra Amador
>>> print(17)
17
>>> print(85490450.0)
85490450.0
>>> print(255/76*2+9-18)
-2.2894736842105274
>>> 
============= RESTART: /Users/sierraamador/Desktop/Seperators.py =============
print("Sierra","Eric","Ryann","Toni","Eric")

Sierra Eric Ryann Toni Eric
>>> 
============= RESTART: /Users/sierraamador/Desktop/Seperators.py =============
print("Sierra","Eric","Ryann","Toni","Eric", sep = "|")


Sierra|Eric|Ryann|Toni|Eric
>>> 
============= RESTART: /Users/sierraamador/Desktop/Seperators.py =============
print("Sierra","Eric","Ryann","Toni","Eric", sep = "****")

Sierra****Eric****Ryann****Toni****Eric
>>> 
============= RESTART: /Users/sierraamador/Desktop/Seperators.py =============
print("Sierra","Eric","Ryann","Toni","Eric", sep = "****")
print(10,15,20,25,sep="****")

Sierra****Eric****Ryann****Toni****Eric
10****15****20****25
>>> 
============= RESTART: /Users/sierraamador/Desktop/Seperators.py =============
print("Sierra","Eric","Ryann","Toni","Eric", sep = "")
print(10,15,20,25,sep="****")


SierraEricRyannToniEric
10****15****20****25
>>> 
============= RESTART: /Users/sierraamador/Desktop/Seperators.py =============
print("Sierra","Eric","Ryann","Toni","Eric", sep = "")
print(10,15,20,25,sep="****")
print("Blink 182","AVA","Systems of a Down", “\n”, "Wezzer")

SierraEricRyannToniEric
10****15****20****25
Blink 182 AVA Systems of a Down 
 Wezzer
>>> 
============= RESTART: /Users/sierraamador/Desktop/Seperators.py =============
print("Sierra","Eric","Ryann","Toni","Eric", sep = "")
print(10,15,20,25,sep="****")
print("Blink 182","AVA","Systems of a Down", "Wezzer", sep = "\n")

SierraEricRyannToniEric
10****15****20****25
Blink 182
AVA
Systems of a Down
Wezzer
>>> 

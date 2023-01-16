#Things I learnt today

1. A > \* - It is a type of combinator for Group selectors that selects all the children of A.
2. A::first-child - This pseudo element selects the first child of given parent.
3. A::last-child - This pseudo element selects the last child of given parent.
4. .class > tag:nth-child(number) : This selects the all n numbered children of the given tag whose parent is given class.
5. .class1.class2 - This selects the element having both the classes.
6. shorthand for flex - flex: <'flex-grow'> <'flex-shrink'> <'flex-basis'>.
7. flex:1 - It means flex-grow : 1; ➜ The div will grow in same proportion as the window-size.  
   flex-shrink : 1; ➜ The div will shrink in same proportion as the window-size
   flex-basis : 0; ➜ The div does not have a starting value as such and will
   take up screen as per the screen size available.
8. toggle method: classList.toggle("className") let's you toggle a class. It means it will add the class if not present in classList and vice versa.
9. .contains - You can use this method to check if a substring is present in the string. Here I have used this to check if a class is present in classList or not.

<img src="./day5.png" alt="day5"/>

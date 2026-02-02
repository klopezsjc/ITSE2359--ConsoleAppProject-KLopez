# ITSE2359--ConsoleAppProject-KLopez

Console App Character Create Screen 
-How to Run the Program-

Open the file in VS Code, press Ctrl+Shift+P, then click the "Run and Debug" button. Or you can also just compile it in the terminal with g++ main.cpp -o main and then run with ./main 

-What I Got Working-

I finished all the main requirements for the project. The program has a menu that keeps looping until you pick Exit. You can create a character with a name and pick one of 4 classes (Warrior, Mage, Rogue, or Cleric). Each class gets a bonus to one of their stats. You can view all your character's stats and there's a combat ratings calculator that shows you HP, MP, attack, and defense. You can also level up your character up to level 10. Everything has input validation so it won't crash if you type letters or wrong numbers.

-Known Bugs or Limitations-

When I view character stats the spacing between the stat names and values looks uneven because some stat names are longer than others. I know it has something to do with the different word lengths but I'm not sure how to fix the alignment yet. I tried to add multiple characters but quickly got stuck on how to store more than one at a time so I decided to scrap it because of time constraints.

-Testing I Did-

I tested all 5 menu options to make sure they work. I created characters with all 4 different classes. I typed letters when it wants numbers and it doesn't crash anymore. I typed numbers that are too big or too small and it asks again. I tried to view stats before making a character and it gives an error message like it should. I also leveled up from level 1 all the way to level 10 to make sure the max level part works.

-Reflection-
The hardest part was getting all the control flow structures working together especially the loops and switch statements. I had some issues with input validation where the program would crash or loop forever when users entered the wrong type of input. I ended up watching some tutorial videos and looking at examples online which helped a lot.

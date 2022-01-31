# Unit 0 - warmup 6 - string practice

#### 1. Complete the following table of string methods.
| Method Name | Parameters ? | Description__________________________________________________________ |
|-------------|--------------|-----------------------------------------------------------------------|
| upper       |              |                                                                       |
| lower       |              |                                                                       |
| capitalize  |              |                                                                       |
| strip       |              |                                                                       |
| lstrip      |              |                                                                       |
| rstrip      |              |                                                                       |
| count       |              |                                                                       |
| replace     |              |                                                                       |
| center      |              |                                                                       |
| ljust       |              |                                                                       |
| rjust       |              |                                                                       |
| find        |              |                                                                       |
| rfind       |              |                                                                       |
| index       |              |                                                                       |

#### 2. From last class... be prepared to share your solution. Following the accumulator pattern we looked at, write a function that takes a string, creates a new string with the following:

1. Double each vowel
2. triple each consonant, except g and k
3. g & k should be removed because they are kind of useless

Do one at a time!

&nbsp;  
&nbsp;  
&nbsp;  

### Practice during this class:

#### A. Write a program that similuates a character fighting a monster, RPG style. The character should start with health points and so should the monster. They should take turns "attacking" each other until one of them dies. Be creative!

Some important considerations:

1. Start simple. Manually assign HP to each. 
2. Then get a loop that simulates "attacks". the random module will be helpful here: `import random` and to get a random integer: `num = random.randint(0, 100)` Subtract that from the health of the user or monster!
3. The attack simluation must be a function! This way you can repeatbattles over and over. 

#### B. Combine this battle with the choose-your-own-adventrure story you started (you started this, right!?) a couple weeks ago.

1. Let's say you have a character wondering through the forrest... give the user some story based on what they choose. Do they want to go south? What happens then? Maybe west? Or through a door? Be creative! This will be the next problem set...

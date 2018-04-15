# INFO6205-523-GA-BuyEquipment
Final Project for INFO 6205, Implantation of Genetic Algorithm for specific problem
## Group member: 
Yiru Cang 001814283   Jiaming Duan  001814402
## Project Topic
Each player has 3,000 gold coins in the starting state. In the game, each player has 100 kinds of equipment to choose, each of the equipment has different level of price (In our project, the price always flows between 1-100). Players can choose to purchase any number of equipment. Each kind of equipment will make effect of attacking other players with the corresponding damage value (In our project, the damage value of all the equipment is between 1-1000) after purchase.   
However, more equipment for one player won’t lead to a better effect. In the actual game, too much game equipment will cause the player to walk slower, which directly affects the probability of winning or losing the game.
## Basic Information
Genotype: 100 Equipment 2^100 possible = 1.268E30  
Phenotype : One of the the player finishes buying the equipment, how many damage value it has and how much money it cost matches the phenotype.  
Expression : One kind of combination can match several kinds of genotype.  
Environment: The overall property the player has (3000 coins) is a limitation and we are trying to reach higher damage value.  
Fitness: The higher damage value the player can reach within the limit of the money, the better result it will be.
## Output
It will generally gives the best match after 200 generation testing.
## Adjustable values
In main function, the number of chidren each generation can give and the initail gene length is changeble.

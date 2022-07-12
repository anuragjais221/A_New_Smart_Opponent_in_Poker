**************************************README**********************************
We have implemented Texas Hold'em Poker in our term project. Here we have used 
different code file for different operation and uses. The have mentioned the
file name along with its description below.

File_Name      Description

constant.py    This file contains different constants that we have used in our
	       different poker code file. This includes constant number array 
               related to flushes, prime number constants, non-flush hand constant 
               values, product value array for different combination number, values
               for different card rank values and another five table card combination array.

poker_constant.py
               This file contains defination of different winning file card 
               combination and their rank value, also defination for different 
               suit type etc.

utility.py     This file conatins defination for deck, card_rank, print_hand function,
               hand_rank function, five card evaluation function, five card evaluation
               function, seven crd evaluation function, seven hand evaluation function,
               deck index find function, hand strength function, Ppot, Npot function and
               effective hand strength function.

poker_game_main.py
               This file contains the main code and it required function to run the poker 
               game with 5 computer player and one human player with human input externaly.
               Here all the player will try to play effectively to increase their chance for 
               winning. Although this code has some bug that is why have added a modified code
               that is discussed below. Although it can run for several round but can exit 
               for some corner case condition.

poker_game_human.py
               This code file almost contain same code like the previous one only this is 
               different is that we have commented some of corner case logic, expect this it
               will work same as like the previous one without any bug.

poker_game_random.py
               This code also works same as the previous code and only the diffrence is that 
               we have made the human player as a random player who can player aggresively 
               with other computer player. Here only at the starting of the code you to put 
               a name to the random player. Everything else will work of its own.

file1, file2.csv 
                This two file, the one named file1.csv will have varioius card suit value and
                file2.csv will have winning percentage of each card suit.

pokershell_Monte_Carlo_simulator
                 Texas hold 'em command line calculator and simulator. it provides handful 
                 information about possible game outcomes:

                 1. win/tie/lose probability for the player
                 2. statistics of winning hands - provides statistics of possible winning hands
                 3. statistics of beating hands - provides statistics of possible opponent's hands
                 4. covers all betting rounds/streets
                 
                 Steps to run this simulator:
		 1. go to root directory of downloaded repository
                 2. launch setup script python setup.py install
                 3. launch pokershell pokershell (use -h to display help)
                 4. While running the any of the poker_game_human or poker_game_random file
                    after each round note down the table cards at round and at the end also note 
                    down winning hand and put that data like data example: 
                    (pokershell) jdqs 5 0.08;  5h6c5s 3 0.62; 7h 1.02
                 (Note: This code file is download from github.)

win_rate_simulator 
                This file contains win_rate_simulator in which poker_strategy file will run the 
                simulator for 1000 times for 2 to 6 player suit and generates the win rate plot 
                which is also added in that file.



*******************************************THANK YOU******************************************

 
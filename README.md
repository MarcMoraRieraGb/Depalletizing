# Depalletizing

In this program you select how many pieces you want for the 3 different machines and the priority. The convoyer belt send 4 diferent pallets, each one has 3 rows and different pieces.

For the robot to know which pallet is coming we generate a random number between 0 and 1. After selecting how many pieces we want and their priority and the random number is generated the first pallet enters and if, for example, you said that the machine 1 has a priority of 1 he will see if the pallet that enters has it he despalletizes the pieces he needs, if not he will discard it and wait for a pallet that has pieces for the machine 1.

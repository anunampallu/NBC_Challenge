List of Classes:

Debug,
Cours,
CutLine,
Debug2,
PlayerBio,
Round,
Rankings,
Player,
Leaderboard,
RootObject,
Form1,
Solution,
BestWorstRounds

Member functions of each class:

Class Name              	Member function

Fom1				              Form1_Load---Responsible for attaching data to data grid view.

Solution			            Solution constructor---Here we are checking, who are under par players based on par_total and their stokes in each round.
				                  Stores them in a list named ListOfUnderParPlayers.

Solution			            GetPlayersAsDictionary---Responsible for returning dictionary of all players. 
				                  Return type is Dictionary<string, Player> 

Solution			            GetUnderParPlayers---Resposible for returning all players who are under par.
				                  Return type is List<string> 				

Solution			            GetBestWorstRounds---Reponsible for returning all players who are under par along with that palyers best and worst rounds
				                  Return type is Dictionary<string, BestWorstRounds> 
				                  Here we are looping through the ListOfUnderParPlayers and checking 4 rounds of each player and determine the best and worst round.


Problem Statement -
The objective of this project is to build and compare multiple machine learning algorithms
for the classification of round winners in the game CS:GO.

Dataset Description -
CS:GO is a tactical shooter, where two teams (CT and Terrorist) play for a best of 30 rounds,
with each round being 1 minute and 55 seconds. There are 5 players on each team (10 in
total) and the first team to reach 16 rounds wins the game. At the start, one team plays as
CT and the other as Terrorist. After 15 rounds played, the teams swap side. There are 7
different maps a game can be played on. You win a round as a Terrorist by either planting
the bomb and making sure it explodes, or by eliminating the other team. You win a round as
CT by either eliminating the other team, or by disarming the bomb, should it have been
planted.

CSGO round winner dataset contains 122410 records with 97 attributes.Some of the main attributes are as follows:

Attributes Description

time_left - The time left in the current round

ct_score -The current score of the Counter-Terrorist team

t_score- The current score of the Terrorist team

map- The map the round is being played on

bomb_planted-If the bomb has been planted or not

ct_health- The total health of all Counter-Terrorist players

t_health- The total health of all Terrorist players

ct_armor- The total armor of all Counter-Terrorist players

t_armor- The total armor of all Terrorist players

ct_money- The total bankroll of all Counter-Terrorist players

t_money- The total bankroll of all Terrorist players

ct_helmets- Number of helmets on the Counter-terrorist team

t_helmets- Number of helmets on the terrorist team

ct_defuse_kits- Number of defuse kits on the Counter-Terrorist team

ct_players_alive- Number of alive players on the Counter-Terrorist team

t_players_alive- Number of alive players on the Terrorist team

ct_weapon_X Weapon X- count on Counter-Terrorist team

t_weapon_X Weapon X- count on Terrorist team

ct_grenade_X- Grenade X count on Counter-Terrorist team

t_grenade_X Grenade- X count on Terrorist team

round_winner Winner

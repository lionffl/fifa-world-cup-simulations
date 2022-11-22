# README
A simple program in Python that runs simulations of the FIFA World Cup.

# Instructions
* The program reads .csv file that contains 2 colums: team name and rating
* The rating are provided by FIFA (https://www.fifa.com/fifa-world-ranking/men?dateId=id13792)
* This information is used to calculate which team has more chance to win a match in a tournament simulation
* To run:
`python tournament.py [filename]`
* You can find two .csv examples with 2018 data, so you can run to obtain an approximate result(since the result of each match have some randomness) as shown below

```
$ python tournament.py 2018m.csv
Belgium: 20.9% chance of winning
Brazil: 20.3% chance of winning
Portugal: 14.5% chance of winning
Spain: 13.6% chance of winning
Switzerland: 10.5% chance of winning
Argentina: 6.5% chance of winning
England: 3.7% chance of winning
France: 3.3% chance of winning
Denmark: 2.2% chance of winning
Croatia: 2.0% chance of winning
Colombia: 1.8% chance of winning
Sweden: 0.5% chance of winning
Uruguay: 0.1% chance of winning
Mexico: 0.1% chance of winning
```

# Credits
* Functions below were developed by CS50 Staff:
* print_result, simulate_game, simulate_round

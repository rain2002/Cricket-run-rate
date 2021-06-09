# Cricket-run-rate
Introduction: 
The project is based on the C++ language. In this project, we will be using C++ code to find out the way to calculate the current run rate and projected score in cricket. The code is for the first innings as we need not calculate the projected score for the second innings since the team has to chase. 

Problem statement:
Writing a C++ code to find out the current run rate and projected score of the team having run rate: current run rate, 6 runs per over, 8 runs per over, 10 runs per over, 12 runs per over in the first innings of a limited-overs match.  


Methodology: 
First, we use float to store the score, overs, extras and the overs present in the innings.
Float is used as overs taken not as a number of balls bowled.
First, we take the number of overs is present in the innings.
Then we ask the present score of the team which is batting first.
Take the number overs taken by the batting team managed to get this score. We store value using float.
The code asks the user to enter the extra balls bowled by the bowling team.
Hereafter the extras will be added to the total number of balls and then converted back into overs.
The run rate is calculated by dividing the score by the number of balls bowled and then multiplied with 6.
Then the projected score is calculated by multiplying the current run rate with the remaining overs.
Then projected score at 6, 8, 10, 12 runs are calculated by multiplying those numbers with the current run rate and dividing with 6.  

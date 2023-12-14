# Computer Science Project Investigation
## Secondary Research
1. According to MedicalNewsToday, the average person should walk 8 kilometers, 5 miles or 10,000 steps per day to remain healthy.
[ref](https://www.medicalnewstoday.com/articles/how-many-steps-should-you-take-a-day#:~:text=How%20many%20steps%20to%20take%20for%20general%20health&text=Walking%20is%20a%20form%20of,8%20kilometers%2C%20or%205%20miles)

2. More steps = lower risk of dying from any cause during follow-up, not dying = wellbeing!
[ref](https://www.nih.gov/news-events/nih-research-matters/number-steps-day-more-important-step-intensity#:~:text=Compared%20with%20people%20who%20took,those%20who%20took%20only%204%2C000.)

3. In regards to battery life, the microbit draws approx. 6-9mA when in use.
[ref](https://www.instructables.com/BBC-Microbit-Power-Usage-Mu-an-Off-line-MicroPytho/)


## Summary
- The microbit's accelerometer will detect movement and store it as analog input. This data is then used to get total distance travelled. This is what is used to give the feedback described in my objectives.

- The microbit optionally takes the user's height as an input via the webpage, this can be used to find the user's appoximate step count in the distance they travelled using the formula from my
[objectives](./).

- Considering the microbit won't be able to send data while active outside, it will have to be synced to the server manually.

- Most of the work such, as the formulas, can be done on the microbit and stored until synced.

- The server is only needed to store and graph the data, as well as manage user inputted variables, such as height.

## Key Factors and Abstractions
- The microbit should be turned on only when in use, to maximise battery power.
- The microbit would have to be synced with the server after being used, it cannot send data when outside.

## Objectives
- To make a program that tracks the users steps taken and comments on the amount taken, for example:
    - If too little steps are taken, it will advise you to walk more
    - If an average amount of steps is taken, it will have a neutral response
    - If a lot of steps are taken, it will congratulate you
- Average steps 
- Maybe implement calorie counter to tell the user if they're gaining or losing weight?
- Bmi calculator?
- Get the user's height as an input to find how many steps they take per km with [this](https://lowellrunning.com/stepspermile/) formula 


## Primary Research
- im not doing all that
# Timer

The program is a countdown program. Basically, takes a time with a special format and starts countdown with seconds.

I used chrono, ctime, iomanip and thread libraries for this program.

### Installation

Program compile just with that;

```
g++ -Wall -pthread -std=c++2a main.cpp src/countdown.cpp -o Timer
```

You can run with that command;

```
./Timer
```


### Usage

Program running just in command line right now. I will set a graphical interface with QT5. Command line input like that;

```
1s => 1 second
5s => 5 second
1m => 1 minute
5m => 5 minute
1h => 1 hours
5h => 5 hours
```


### Issues

+ Add command line parser for takes verbose output limit and on that way, I can add description and usage.
+ Set QT5 
# ⏱️ Java Countdown Timer

A simple Java console application that counts down from a user-specified number of seconds. The program displays the countdown every second and prints a message when the countdown reaches zero.

## Features

* Allows the user to choose the countdown duration in seconds
* Displays the remaining time every second
* Automatically stops when the countdown reaches zero
* Displays a completion message
* Uses a scheduled timer to control the countdown

## Technologies Used

* Java
* IntelliJ IDEA

## How It Works

1. The program asks the user to enter the number of seconds to count down from.
2. A `Timer` and `TimerTask` are created.
3. The remaining seconds are displayed every second.
4. The countdown continues until the timer reaches zero.
5. The timer is cancelled and the completion message is displayed.

## Example

```text
Enter the number of seconds to countdown from: 5

5
4
3
2
1
0
HAPPY NEW YEAR!
```

## Concepts Practiced

* Variables and data types
* User input with `Scanner`
* `Timer`
* `TimerTask`
* Anonymous classes
* Method overriding
* Scheduling tasks at fixed intervals
* Conditional statements
* Basic countdown logic

## Author

**Albert123-blip**

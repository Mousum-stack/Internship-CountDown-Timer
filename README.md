# Countdown Timer

A simple and aesthetically pleasing countdown timer. This timer displays the remaining time in days, hours, minutes, and seconds. It's built using HTML, CSS, and JavaScript.

Countdown Timer Screenshot
<img width="1440" alt="Screenshot 2023-08-28 at 12 35 43 AM" src="https://github.com/Mousum-stack/Internship-CountDown-Timer/assets/109821242/3b4f6e19-334d-44c8-9bea-11188352a025">

## Features

- Beautiful gradient design.
- Responsive: Scales perfectly on mobile and desktop.
- Uses Google's Roboto font for a sleek look.
- Displays time remaining in days, hours, minutes, and seconds.

## Setup

1. Clone this repository to your local machine.
   \```
   git clone https://github.com/Mousum-stack/Internship-CountDown-Timer.git   
   \```
2. Navigate to the directory.
   \```
   cd Internship-CountDown-Timer
   \```
3. Open `index.html` in your preferred browser.

## Customization

To set the timer to a different duration:

1. Open `index.html`.
2. In the JavaScript section, find the line:
   \```javascript
   var countDownDate = new Date().getTime() + 1 * 24 * 60 * 60 * 1000; // 1 day from now
   \```
3. Adjust the multiplier (in this case `1`) to the desired number of days.

## Contribute

Feel free to fork, open pull requests or submit issues. Contributions are welcome!

## License

Internsavy Internship.

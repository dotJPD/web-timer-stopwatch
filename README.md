# Web timer and stopwatch
A basic, minimalistic one-hour timer and stopwatch that tracks how long you've taken between each instance of setting the timer. May change in the future to make the amount of time for the timer customizable.

Vanilla JavaScript was all that was needed to get this done.

Alarm sound is customizable. Just use any `.mp3` file you want and rename it to `timeout.mp3`, and replace what is here with that.

Initially used `setInterval` to change time, but because that turned out to be unreliable, so now the `setInterval` calls just check with the time given by `Date.now()` in quick intervals and updates accordingly.

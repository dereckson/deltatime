# deltatime

Compute the number of seconds between two dates.

This is mainly intended to compute dates generated in logs by the `date` UNIX utility.

## Usage

```
$ deltatime
Start date:
Wed Sep 12 17:21:44 UTC 2018
End date:
Wed Sep 12 17:23:32 UTC 2018

108 seconds
```

## Tips

If you omit a date, the current date and time are used.

The absolute value will be used.

The tool recognizes a lot of formats, see [this reference](https://www.tcl.tk/man/tcl8.6/TclCmd/clock.htm#M25) for more information.

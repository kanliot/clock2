# clock2
Shows a 12 or 24 hour digital clock that updates each second.  Runs in a foreground process in your terminal.

### Installation:
Download the clock2 script, then run it with `perl ./clock2` or by making the script executable and running it directly.    
Most *nix systems have perl already installed.

    clock2 
     
     Options:
       -h, -help            brief help message
       -m, -military 	24 hour clock
    
     `clock2` shows the current time, until you break out of the program.
     Like 1:23:45 PM
     
 ![looks like](https://raw.githubusercontent.com/kanliot/clock2/main/clock2.png)
 ##### `clock2` doesn't actually clear the terminal screen.  It uses vt100 control characters to clear the current line. 
 

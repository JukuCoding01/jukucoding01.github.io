

### Can't See the Effects Clearly?

Maybe the program is in Queen loop block, and after the program is uploaded, the light board or light strip is blinking really fast or not lighting up at all. Here's somehting you could do.

1. Check connection. See [how to connect the blocks correctly? ](./code.3.md)

2. Make sure that the "set LIGHTBAR show" block is placed somewhere in the program. Otherwise the light strip will not light up.

3. Make sure you set the length of the light strip at the beginnin gof your program.

4. Make sure the position index of the light bulb of you want to light up is smaller than or equal to the length of the light strip you set minus 1. [Position index <= (length of light strip - 1)]
    
5. Maybe the light is flashing too fast to see any changes with your bare eyes. Try insert a "wait n milliseconds" block somewhere in the middle of your program and adjust the number. This allows the program to wait for a certain time before moving on to the next command. Increase the number and/or add more of the same blocks until you can ssee the effects.

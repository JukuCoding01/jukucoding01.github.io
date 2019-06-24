

### Can't See the Effects Clearly? 

Maybe the program is in Queen loop block, and after the program is uploaded, the light board or light strip is blinking really fast or not lighting up at all. Here's somehting you could do.

1. Check connection. See [how to connect the blocks correctly? ](./code.3.md)

2. Make sure the coordinates of the character you created is in the board. The board is an 8 by 8 matrix, and the coordinates for x and y are between (0,0) and (7,7).
    
3. Use the Queen loop block to execute your program. If your program is put inside the Queen setup block, it will only execute once and flashes on the light board so fast that you can't see it. 

4. Maybe the light is flashing too fast to see any changes with your bare eyes. Try insert a "wait n milliseconds" block somewhere in the middle of your program and adjust the number. This allows the program to wait for a certain time before moving on to the next command. Increase the number and/or add more of the same blocks until you can ssee the effects.
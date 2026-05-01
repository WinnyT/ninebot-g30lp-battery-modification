# Designing new battery pack for Ninebot G30LP Scooter
The new battery pack I have designed will provide more range to the scooter with a lower cost, and can be adjust based on personal preferences. This design can potentially increase the speed of the scooter through some modification.

# How To Build
To use the new Design Ninebot scooter pack, you just have to follow these few step:
1. Unscrew/remove the old battery pack
   1. Open up the old battery pack, it mights be hard at first because there is glue between the cap.
   2. Take out the BMS and be carefull with the wire. 
2. 3D print the new design and buy the battery cells (18650) based on your desire range.
   1. Check the Voltage of each cell to make sure there are no dead cells.
   2. Put the battery in with the right side up ( blue is negative, red is positive)
3. Spot welding all the battery by following the chart (see bellow)
4. Connect the BMS to the pack
   1. Replace the BMS pin
   2. Put the temperature control wire into the dedicated spot
   3. Solder it on the nickel strip between 2 cells. **NOT** on top of the cells
   4. Solder the total negative wire first ( black line)
   5. Follow the number from 1 - 10.
6. Secure the pack
   1. Cut the Epoxy Resin Board according to the battery pack size.
   2. Put double tape on the battery pack ( space it out)
   3. If the board is not in one piece, you can tape it with Kapton Tape
   4. Stick the board on the pack, then put the whole pack into heat shrink
   5. Carefully shrink it
   6. Secure the wire (chargind and data cable) with silicone
7. Put the pack back into the battery compartment by using the bolt, washer and **thread locker**

# Why Did I Make This
My scooter is my best friend when it come to commuting. When I don't have a lisence, I use scooter; when I do have a permit, I use scooter; when I will have a class D lisence, I will still use scooter. First of all because it's environmental friendly and compact. Second is because driving a car is costly for me. The insurance and gas might drain all my pay check, but it does buy time, and time is all I have. 
But after a while of driving it (3000+ miles), my scooter has become weaker and unable to go farther. When I checked the price of the new battery pack, it cost ~$300. 
I don't think it worth the price so I decided to make it my own, and the cost indeed come out lower! I can now go farther (library AND back), and the speed is more stable. 

# CAD
<img width="911" height="575" alt="image" src="https://github.com/user-attachments/assets/effba524-ebfd-44e4-b13b-286a1897dd77" />

# Welding Layout
There are 3 layers. The step to weld is matching letters to letters, number to number. Letters starts from A then B, C, D,etc. Numbers starts from 1 then 2, 3, 4, etc. E.g: A1 - A1 then A2 - A2,..., A6 - A6. Then, go to B1 - B1. <br>
First Layer:
<img width="1035" height="173" alt="image" src="https://github.com/user-attachments/assets/6f07a1c6-f2bd-4c27-8bbb-fb1588edd9b6" />
_flip across the X-axis_ <br>
Second Layers: 
<img width="1028" height="171" alt="image" src="https://github.com/user-attachments/assets/4a839a42-2dce-4f66-af6c-628ed9b5b273" />
Third Layers:
<img width="1029" height="171" alt="image" src="https://github.com/user-attachments/assets/5f58f86a-7a4e-4a2d-ab82-d2e1dbac7ba7" />

# BMS
<img width="1044" height="168" alt="image" src="https://github.com/user-attachments/assets/9d101348-22f9-426b-9d7e-a5a2b6cfde4d" />


# BOM
Check out BOM-Fall Out.csv

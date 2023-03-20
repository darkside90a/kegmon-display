# kegmon-display
A variant of mp-se's Kegmon display case

You find a complete description of his great Kegmon project here:

https://github.com/mp-se/kegmon

I used a Kemo G081N (120x70x35mm). 
If you are situated in Sweden/Norway, you can get it from Kjell&Co (#89026):
![P1010688](https://user-images.githubusercontent.com/52971840/226316950-78174870-2e15-4780-90fd-5162a2dc6276.JPG)

Lid off. All modules are on the top side:
![P1010693](https://user-images.githubusercontent.com/52971840/226317607-6bb30ef3-486b-4451-8b40-8b5fb9a5b51a.JPG)

A hole in the lid is filled with a CNC machined piece of 4mm acrylic as a window (km-display.stl):
![P1010697](https://user-images.githubusercontent.com/52971840/226319622-d6f17871-f715-4f94-9da5-609149cc0fca.JPG)
![kegmon-display](https://user-images.githubusercontent.com/52971840/226325878-38225038-0885-4782-9e4d-fa57c766afb2.png)


Two spacers (km-spacer.stl) lifts the PCB up from the bottom of the case so that the displays are as close to the acrylic window as possible. Both spacers are printed the same way. I just flipped one of them during assembly.
The frame (km-frame1.stl) keeps the displays as horizontal as possible.
![P1010694](https://user-images.githubusercontent.com/52971840/226321673-55faf3a0-c673-496d-a64e-6ce4f3cc4076.JPG)
![km-spacer](https://user-images.githubusercontent.com/52971840/226326004-935ba087-94a2-467e-b088-cae5a91dd63a.png)
![km-frame](https://user-images.githubusercontent.com/52971840/226326047-b6d381f0-f619-4dc8-b592-113ce38bfa82.png)



All modules are mounted on sockets - "plug-in", easy if I need to replace any of them. Displays are mounted on double height sockets. They have some distance, allowing 1.3" display replacement. RJ45's are placed upside-down to keep the assembly as low as possible. They have extra mechanical support by help of cable strips.
![P1010696](https://user-images.githubusercontent.com/52971840/226324180-2664fd24-5f86-4c69-826f-6e283174efda.JPG)


Bottom. Took me only 2-3hrs to do all wiring on the 60x80mm experiment PCB:

![P1010695](https://user-images.githubusercontent.com/52971840/226325716-0f040b5c-cabe-4f0b-be30-0b83391f6fa9.JPG)

Brackets for mounting the frame were made by "killing" two of these car cable interconnectors and soldered on to the PCB: 
![P1010692](https://user-images.githubusercontent.com/52971840/226327062-fa8ed11f-c0d7-4e75-8930-8c3d8bb91426.JPG)


Before soldering, I made a design in KiCad with 3D models to see how it would look like. Also did a rough layout to have something to check against:
![DSC_1682](https://user-images.githubusercontent.com/52971840/226330165-a557e49a-15c2-4069-85d1-8e0ca784e866.JPG)



Regrets:

If I was asked to make this again, I would have moved the ESP one more step (2.5mm) away from the edge of the PCB 
( = A much smaller cutout in the case).

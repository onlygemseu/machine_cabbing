# OnlyGems opensource Cabbing machine
<img width="1052" height="694" alt="image" src="https://github.com/user-attachments/assets/8678793c-4613-4348-ae43-7e0eaab6cb45" />

## How to use this repo
1. Install windows powertools if you want to see the preview of the printable STL files in your windows folder.
   <img width="733" height="364" alt="image" src="https://github.com/user-attachments/assets/9ddebb8e-0e7a-415e-a73f-e5e5ff886ae4" />
2. Install FreeCad in case you want to adjust plexi holders or see the parts assembly in the FCStd files. C4d files are Cinema 4D models made with trial version. 
3. BOM is just as an example. You can switch different wheels, or material vendors. The ones mentioned in BOM are for convenience (available online or via eshops in EU).

## Build instructions (prerequisites)

### DISCLAIMER AND WARNINGS
I am providing this information as my own experience. I hold no responsibility for any possible injuries or financial losses due to any reasons. Electrical wiring, motor connection, lighting should be done by a skilled person or a professional to ensure all wires are properly set up and grounded. IF THE MOTOR IS NOT PROPERLY GROUNDED AND CONNECTED YOU MAY GET ELECTROCUTED EVEN BY TOUCHING A WET WHEEL!!! Be aware that the rotating wheels, shaft, bearings and pulleys have a lot of momentum and can grab your clothing or hair. Always cover the moving parts with proper covers or avoid getting near them or leaning towards them. Especially watch out for the moving belt and pullies!!! Always make sure all parts are tight and wheels, motor, pulley or any other parts are NOT loose. Make sure the tension on the belt is sufficient and it will not slip easily nor be too stiff.
The machine is NOT a toy and if you want your kids to use it, its your own responsibility to look after them and make sure they dont get harmed. 
!!! MACHINE CONSTRUCTION AND USE ARE AT YOUR OWN RISK !!!
1. Ordering the parts 
  
   1.1 When ordering aluminum extrusion profiles, make sure they are of good quality as they hold the structural integrity of your machine. I recommend using T-nuts, because they have a strong grip, once they settle in.

   1.2 The shaft should be made of inox non corrosive steel. This will prevent excesive wear, corosion and sticking of wheel hubs onto the shaft.

   1.3 Make sure the shaft you buy is straight as possible (ideally if available at your local vendor, choose precise inox steel rod). Bent shaft will cause serious vibrations at full speed.

   1.4 Electric motor should be about 0.75kW on 220V with about 1400 rpm. The motor should have a staring and running capacitor (if singlephase) or connected in start/delta setting (3phase motor). In case of 3phase motors you might need a frequency inverter (VFD) to tune your startup power. Star/delta is still not weak enough not to yank your wheels on the startup. Most of the lapidary wheels are designed for upto around 2000 rpm. Overshooting RPM may cause wheel failure and damage the machine or hurt you.

   1.5 In order to prevent excesively fast start and wheel slipage on the shaft, the motor should start progressively. I use a singlephase motor and have changed the startup capacitor to 25 uF (microfarads). These can be bought in any radio/electro shop.

   1.6 You can order pullies with tapper bush. They are really easy to set up on the shafts. I also recommend to choose your pulleys to match the RPM of the motor and desired RPM. [https://www.blocklayer.com/pulley-belt](https://www.blocklayer.com/pulley-belt) (site can be also switched to inches).
   You can buy a single or dual beltpulleys for SPZ belt size.

   1.7 When buying Dome bearings, make sure they come with a lubrication cap as they will accumulate grinding dust and need to be lubricated from time to time. Dome bearings are self-aligning and will have some tolerance when inserting the shaft. Make sure the bearings in the dome do not move freely but significant pressure is needed to roll them out of the dome. Also make sure the shaft goes smootly into the bearing hole. Small rough imperfections on inner bearing hole or shaft can be sanded out, but if the surface is too uneven try a different bearing. (I matched the shaft and the bearing directly in the store)

   1.8 For parts that are exposted to water directly I recommend using inox steel components (bolts and nuts, grub screws). Although not necessary, iit will be easier to disassemble the machine parts when needed.

   1.9 For convenience you can use butterfly nuts in places that you would later frequently disassemble, e.g. front shield hinges.

   1.10 Main water supply hose should be about 1/2" diameter. There are tons of connectivity components to assemble the main line. I used standard gardening hose and connectors with a shutter valve on both sides. The nozzle supply hose is about 4mm in diameter and runs from the splitter to the nozzle. Nozzle sets and splitters are "Gardena microdrip"

   1.11 Nozzles should have either direct or 360° spray area to distribute the water evenly on the wheel surface.

   1.12 Depending on your water source, the best and most flexible is direct connection to water tap using a click-in hose connector. It will allow you to get much higher water pressures on each of your microdrip nozzles. If you have no direct water source at hand, you can use an aquarium pump with a 1/2 hose attachment. I use 1000 l per hour pump. Its okay for work but nozzles tend to clog a bit after accumulating limescale and change the direction of spraying.

   1.13 For 3D printed parts, I used PETG. I dont recommend using PLA. Close to the motor vents, the temperatures might soften the plastic components.   
   
2. Assembly
   
2.1 Frame
   <img width="1585" height="710" alt="image" src="https://github.com/user-attachments/assets/2dc2afed-eca8-44e8-b620-bef2183460ac" />

     2.1.1 Assemble two side frame sections (A,B) by connecting (1) 40160 profile with (2) 20cm 4040 profile with a (11) conneting T8 strip. Secure the connections with (17)grub/setting screws M6x8.

     2.1.2 Connect 2.1.1 to (4) backframe. Slide in M8 T-nuts (12) to secure the (7) 4040 corner brackets on both sides of each 2.1.1 piece. Secure with (15) M8x16 screws. Do not tighten yet, we will adjust the length once we insert the shaft.

     2.1.3 Connect the (3) motor support frame sections to 2.1.2. For the inner angle connection use the (13) inner bracket T8. For the outer connection use a (7) corner bracket. Slide two M8 T nuts onto each of the frame supports. Tack with (15) M8x16 screws. Do not tighten the screws yet.

     2.1.4 Slide in two (12) M8 T nuts into each (1) 40160 profile.

     2.1.5 Place rubber washers over every T nut as in the picture (motor placement, bearings placement).

2.2 Bearings, motor and alignment

     2.2.1 Place A to the far most edge of the (4) backframe and tighten all screws.

     2.2.2 Place B about 90cm far from A.

     2.2.3 Place dome bearings on the top of 40160 profiles and align the T nuts and rubber washers to match the mounting holes of the dome bearing. Do not tighten the bearings yet.

     2.2.4 Loose the setting screws on the bearings and make sure the shaft slides into the mounting hole easily without getting stuck. If it gets stuck at any point, use WD-40 to lubricate the mounting hole and pull out the shaft by wiggling it out. Sand out roughness that made the shaft stuck and repeat trying until the shaft gets into the mounting hole without catching on the mounting hole.

     2.2.5 Roughly align the bearings and insert the shaft across the bearings from A to B. Make sure the bearings are "somewhere in the middle" of the 40160 profile and handtighten them. Place the pulley of your choice on the driving end of your shaft and secure it against movement.

     2.2.6 adjust the B so that you would get enough space for your wheels. Max with this sizing is 8 wheels with 50mm width and 200mm diameter. The spacing in between the wheels is roughly 3-4cm. The far end of the shaft on the A side in the bearing should not exceed the bearing mounting hole length.

     2.2.7 If you are Ok with your A-B alignment secure all the (7) corner brackets by tightning the screws.

     2.2.8 Install the drive pulley on your electric motor shaft and align the (3) motor mounting supports to match the mounting holes on the motor. Place the drive belt on both pulleys and adjust the motor assembly placement util the belt is driven straight with no sideways deviation.

     2.2.9 Remove the motor and the shaft from the bearings and tighten all inner and outer corner brackets on the (3) motor supports.

  2.3 Assembling wheels on the shaft

     2.3.1 Based on your wheel hubs and you wheel setup, print the respective hub brackets or design your own based on the wheels used.

     2.3.2 Tighten the pulley on the shaft. You will be inserting the wheels from the other end (side A). Insert the shaft into the bearing and leave 10-15cm on the pulley side (B). Tighten the bearing on side B and firmy rotate the bearing out of its dome by pulling the shaft on side A outwards. This will allow you to insert wheels on the shaft.

     2.3.3 Split the shaft with a marker for placement of your wheels. They should be roughly 4cm from each other. Slide in your printed hub brackets accordingly on both sides of the wheels and secure them with settings screws. Push the shaft back so that the dome bearing on side B will get back to its original position and slide the shaft into the bearing on side A.

     2.3.4 Make sure the bearings are roughly in the same position on both (1) 40160 profiles. Tighten the screws on both bearings and try to rotate the whole shaft assembly by hand. The shaft should move smoothly, and based on your wheel setup, should have some momentum when slowing down. Check if the wheels are not wobbling or moving sideways on the shaft. If your plastic hub brackets are not gripping to the wheel hubs enough, you can spray them with rubber spray and let dry out for a few hours. This will enhance the hub bracket grip and will better distribute the momentum on start.

2.4 Motor and drivetrain

     2.4.1 Place the motor on the motor support profiles. Install the drive belt on the pulleys and tighten it by pushing the motor farther from the wheel shaft. The drive belt should not be slipping easily but also should not be too tight. Align the angle of your motor with the wheel shaft so that the belt will be running smoothly without grabbing the pulley edges. This might cause heat buildup and excesive wear and/or the belt might snap more easily. Make sure to cover the belt and pulleys when the machine is operational to prevent any injury.

     2.4.2 Based on the motor you are using, the start of the motor should be slower and smooth. If the motor yanks the wheel shaft, your wheels will likely slip or can grind into the shaft and you wont be able to slide them out later. In my case im using 0.75kW single phase motor. I changed the starting capacitor to 25uF (microfarads), which is still a bit to strong for the start but definitely better than the original 250uF. Make sure the motor rotation is correct. If not switch it based on the motor installation diagram of your motor. The wheels should be rotating downwards/to you when you are in front of them. Do not change the running capacitor - this might cause excesive heat buildup, motor failure or capacitor can sweal and blow up. If you are using 3 phase motor, use the star/delta setting for startup and running. In 3phase your startup will most likely be still too powerful so you will need a frequency inverter (VFD) to tune your motor startup. VFD is an expensive component, so thats why Im sticking with single phase motor and a smaller capacitor.
   IF YOU ARE NOT FAMILIAR AND CONFIDENT WITH SETTING UP YOUR ELECTRICAL WIRING, MAKE SURE TO CONTACT A PROFESSIONAL TO SET IT UP FOR YOU. MISTAKES IN THIS STEP CAN CAUSE YOU INJURIES, DESTROY YOUR MOTOR OR IN EXTREME CASES CAUSE FIRE.   

     2.4.3 Secure all bolts and screws on bearings, frame, motor and bearing settings screws holding the shaft. Tighten the tapper bush screws.

     2.4.4 When testing the motor, DOUBLE CHECK THAT ALL THE SCREWS ARE TIGHT on the frame and motor and bearing mounts. First, step aside from the wheel assembly and only then start the motor. Do a really short run first (split of a second) to see if nothing starts resonating or if the wheels are not getting yanked with too much power (squeeking noises). If they do, either adjust the motor power on startup or tighten the lose hub brackets on your wheels. If you observe vibrations, try to wiggle the wheels sideways. If they move tighten them to hold their place on the shaft.

     2.4.5 Do a second test run now reaching the full speed. Observe any heavy resonation, wheel wobbling, belt slippage and other noises. In case the soft wheels are wobbling or resonating, you will not be able to do anything with them unless you return these wheels to your reseller. In case your aluminum hub wheels are vibrating, its possible that they werent correctly aligned when manufactured. It is also possible that your shaft is bent or bearings are not correctly adjusted. Before returning your wheels to the reseller, make sure the problem is not on your side. First try to run the shaft without wheels to see if it is vibrating. If it is, let a professional straighten shaft and align the bearings again.

 2.5 Wheel covers and plexi (TBD)

 2.6 Lighting (TBD)

 2.7 Water lines (TBD)


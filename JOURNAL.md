Made by: @1Mon

Repository link: https://github.com/2Mon/tim

Total hours: 12

# Feb 15 2026 | Research

ive been wanting to make a silly printer for a while. I came across some cool motion systems from OYO, the person who made POYON. I was inspired by his design for a CoreXZYZ, which he called MOT. I was talking with some friends and they showed me MIR, which is another printer made by Apsu. It uses the same motion system. Neither design had much progress outside of the motion system, so I want to flesh it out a bit and make a working machine. Also, OYO's design has some weird mounts for the idlers. Its kinda impossible to use as is, so I will be expanding the frame a bit to make it easier to fit everything in. 

This is OyO's design with the impossible idlers. He seems to design motion systems without caring if they are usable lol.
<img height="450" alt="Screenshot 2026-02-27 at 5 25 16 PM" src="https://github.com/user-attachments/assets/18169bb7-1bf3-405f-8f28-beb0c8c0dce6" /> <img height="450" alt="Screenshot 2026-02-27 at 5 26 08 PM" src="https://github.com/user-attachments/assets/a0e23e30-e03b-4da0-94a1-900485af7521" />

This one is MIR, and while it is more fleshed out it still needs a toolhead. 
<img width="600" alt="image" src="https://github.com/user-attachments/assets/ee94fbd4-fc64-4340-86b1-e14044969b20" />

I want to keep the compact size of OyO's design while using the better XYZ (if we want to call it that) joints from MIR. I call it TIM. in theory because its MIR and MOT combined and reversed, but also tim is a cool name.

Time Spent: 2h


# Feb 20 2026 | Motor Mount

I really like the way that OyO laid out the motors in his design. Since I am trying to bring this to RMRRF, I need to keep this small enough to fit in a suitcase. I set up the motors so that the bodies are on the inside, right below where the build plate will go. I think that I will end up doing an external electronics bay on this, so this will help keep everything super compact. I am using two bearings to make the belt go to the edge of the motor, maximizing the xy travel while keeping the footprint very small. I can probably fit this as a carry on. 

<img width="644" height="484" alt="Screenshot 2026-03-01 at 12 24 00 PM" src="https://github.com/user-attachments/assets/6f057836-9704-4737-aafb-274700c4edde" />

This part also includes mounting for the four Z rods, which currently just slot into the holes. I should probably add a way to constrain them better. I dont plan to have an actual extrusion frame around this machine, so those rods need to be super rigid in the printer part.

And here you can see it with the motors, z rods, and bearings. 

<img width="642" height="439" alt="Screenshot 2026-03-01 at 12 27 45 PM" src="https://github.com/user-attachments/assets/c3349bf4-d860-414a-a0ad-f390e702669d" />

Time Spent: 4h

# Feb 25 2026 | Gantry Stuff

Making the gantry for this is going to be VERY difficult. I am trying to keep it compact, and the belt path is not exactly easy to make compact. My first iteration turned out to be impossible to make IRL. there were sections that were WAYY too thin to be able to print well and stay stable during prints and under belt tension. Heres that first design: 

<img width="229" height="260" alt="Screenshot 2026-03-01 at 6 39 12 PM" src="https://github.com/user-attachments/assets/859b9020-4565-43bc-8e4a-8d54dc865435" />

I ended up changing up the belt path a tiny bit from this version, as the innitial setup didnt really allow a lot of space for the belt to be able to pass over the bearings. I changed it to have the single side of the bearing (wow i need a better name for this) be further out on the rod, which restricts my travel a bit but ends up making the belt path MUCH easier. 

Here is my current design. It uses 125mm long 8mm linear rods and F693ZZ bearings for the belts to ride on. 

<img width="522" height="394" alt="Screenshot 2026-03-01 at 6 45 04 PM" src="https://github.com/user-attachments/assets/3388542c-d7cb-471f-bd92-a020d7e2485f" />

And here it is with the bearings and rods. Its a little difficult to see how it will go together.

<img width="634" height="296" alt="Screenshot 2026-03-01 at 6 45 33 PM" src="https://github.com/user-attachments/assets/144ac54c-452f-4766-976d-7d5e57152660" />

And here it is in the context of the rest of the machine. You can kinda see how the belts will go up from the motors to the gantry and back down. 

<img width="595" height="386" alt="Screenshot 2026-03-01 at 6 46 22 PM" src="https://github.com/user-attachments/assets/f1e5e52f-7b3b-418b-9ba0-3eeb92c75535" />

Time Spent: 6h 


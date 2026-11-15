Made by: @1Mon

Repository link: https://github.com/2Mon/awd-splitter

Total hours: 11

# Feb 19 2026 | V1 Schematic

I started off by doing a schematic for my PCB. Im not super happy with it yet, its a bit messy and hard to read. I think I did the wrong symbol for the 1x8 connector. Its also not very readable atm. The goal of this project was to create a PCB that can take 4 motor connectors, as well as 4 thermistor and 4 fan connectors and combine them to make a couple big wires that would be easier to connect. In theory, this should be used on both sides of the connector to break it out again to the mainboard.

![Screenshot 2026-02-19 at 10.44.57 AM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3MzE2LCJwdXIiOiJibG9iX2lkIn19--2fe7ffb8b227ee5266c9c75cde6f96c544ed3598/Screenshot%202026-02-19%20at%2010.44.57%E2%80%AFAM.png)

My Schematic ^^


 ![Screenshot 2026-02-19 at 10.48.09 AM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3MzIzLCJwdXIiOiJibG9iX2lkIn19--51d7f631da06fdeb14d2c01501a4dc7731202254/Screenshot%202026-02-19%20at%2010.48.09%E2%80%AFAM.png)
What i want to be able to do with a couple wires

Time Spent: 1h

# Feb 19 2026 | V1 PCB

I began to route the PCB during this session. Overall its alright, but I think it could be made more compact. The Clik-Mate connectors I decided to use turn out to be really difficult to crimp manually, and since the connectors are surface mount, I dont feel super comfortable soldering it myself. I think I will end up changing to Molex Nano-Fit. I cant use JST connectors on this as it needs to survive chamber temps, and JST is only rated to 80c. These are rated for 105c!!. 

![Screenshot 2026-02-19 at 10.48.55 AM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3MzI1LCJwdXIiOiJibG9iX2lkIn19--0c0aaa7b52859ec3f2b99eee9fd830a0a92f46e7/Screenshot%202026-02-19%20at%2010.48.55%E2%80%AFAM.png)

Time Spent: 3h

# Feb 19 2026 | Change of plans!! V2 Schematic

Okay yeah my v1 kinda sucked. I redid the schematic with a different symbol which should work better for readability and use. I also redid my labels and added some text to show what each connection is for as it was unclear before. Its basically just two 2x8 connectors broken out into 4 1x4s and 8 1x2s. Overall very simple. 

![Screenshot 2026-02-19 at 10.52.53 AM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3MzM1LCJwdXIiOiJibG9iX2lkIn19--be16cecbec9cf13316e1f6eeb88a60a95173b268/Screenshot%202026-02-19%20at%2010.52.53%E2%80%AFAM.png)

I also added some mounting holes that are grounded, which will be connected to the frame of the printer so the whole thing is grounded together.

Time Spent: 1.5h

# Feb 19 2026 | V2 PCB

Im getting better at PCB design!! there are a couple little warnings, but those are because of the footprint im using. Its ok!! I need to double check all the labels and stuff to make sure that its accurate, as im planning to make this fully open source for anyone to use. I tried to keep it fairly compact, as I want to be able to mount this easily to a 2020 extrusion. This shouldnt be an issue as currently its only 28mm wide at the widest and 16 at the thinnest point. I want to add some more decoration and stuff, maybe a silkscreen pattern for the back?

![Screenshot 2026-02-19 at 10.58.25 AM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3MzM5LCJwdXIiOiJibG9iX2lkIn19--801cf824183276b8dd23901e84ffee422cf424f6/Screenshot%202026-02-19%20at%2010.58.25%E2%80%AFAM.png)

Time Spent: 3h

# Feb 19 2026 | Silkscreen Art

I added some silkscreen art to make it clear what each pin of the big connectors goes where. since this is being open sourced and given to some cool people for their machines, i need to make sure its really clear which motor is which. I also added some cool squiggly lines to the back of the pcb to give it some more character, i think it looks really cool!!

![Screenshot 2026-02-19 at 7.20.45 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3NjEzLCJwdXIiOiJibG9iX2lkIn19--5dd03d963cbb26da914be72b145ebcffb73c5bc0/Screenshot%202026-02-19%20at%207.20.45%E2%80%AFPM.png)

![Screenshot 2026-02-19 at 7.27.15 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3NjE4LCJwdXIiOiJibG9iX2lkIn19--f3a3d589aa3ccffc95325bb1a1c7aabd2be532cc/Screenshot%202026-02-19%20at%207.27.15%E2%80%AFPM.png)

![Screenshot 2026-02-19 at 7.28.09 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3NjIwLCJwdXIiOiJibG9iX2lkIn19--17d591757c002002da9fd06e963fd78934550d86/Screenshot%202026-02-19%20at%207.28.09%E2%80%AFPM.png)

I think i managed to make the routing pretty clean, im especially happy with this part!

![Screenshot 2026-02-19 at 7.28.34 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3NjIyLCJwdXIiOiJibG9iX2lkIn19--92456dbae206d7f60fda4f257a1b026613c04a23/Screenshot%202026-02-19%20at%207.28.34%E2%80%AFPM.png)

Time Spent: 2h

# Feb 19 2026 | Made Repo

I made the repo for this project! Basically just making a nice readme and a BOM, and uploading the PCB files. overall really chill!! Now i can submit my project!
![Screenshot 2026-02-19 at 8.19.38 PM](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTA3NjI5LCJwdXIiOiJibG9iX2lkIn19--a4f39c0617d5f52c9f1c364f81a06d89fd4f7757/Screenshot%202026-02-19%20at%208.19.38%E2%80%AFPM.png)

Time Spent: 0.5h

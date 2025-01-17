# Watch Escapement Mechanism
As [**Wikipedia**](https://en.wikipedia.org/wiki/Escapement) says: 
>An escapement is a mechanical linkage in mechanical watches and clocks 🕒 that gives impulses to the timekeeping element and *periodically*  releases the **gear train** ⚙️ to move forward, advancing the clock's hands. The impulse action transfers energy to the clock's timekeeping element (usually a pendulum or **balance wheel**) to replace the energy lost to friction during its cycle 🔄 and keep the timekeeper oscillating.

![](Canvases/watch%20mechanism%20front%20view%201.jpg)
# Why designing this mechanism?
It's quite amazing to understand how a watch works. But you know what's even better? To model it.
I chose this mechanism because it seemed interesting, I wanted to make something practical and I've been curious to find out how a watch works.

# How does it work in Fusion 360?
Bassically it's all about the joints.  I made 6 revolute joints, 1 contact set and 3 motion links. I strongly don't recommend you to use contact sets. To make the motion study I used the escape wheel joint.

## Components
I divided the project into 3 main components, each of them having their own subcomponents:
1. **Main Spring**
   - Spring Frame Back
   - Spring Barrel
   - Ratchet
   - Main Spring
   - Winding Stem
   - Spring Frame Front
   - Winding Key
   - Bracket
   - Barrel Ratchet
   - Ratchet Spring
2. **Gear Train**
   - Train Frame Back
   - Gear Train
   - Escape Wheel
   - Train Frame Front
   - Bracket x2
3. **Balance**
   - Balance Frame Back
   - Hairspring
   - Balance
   - Impact Pin Housing
   - Pallet Fork
   - Balance Frame Front
   - Bracket
   
## Steps for 3D modeling the mechanism:

- 🟣 Make the holder parts (frames and brackets) using the canvases.
- 🟣 Make the gears using **Add-ins Tools**. 
- 🟣 Make the spirals using **Coil** and **Project to Surface**.
- 🟣 Make the other subcomponents using the canvases.
- 🟣 Assemble the mechanism using **Align**.
- 🟣 Add the screws, nuts and washers using **McMaster-Carr Component**.
- 🟣 **Ground** the holder. 
- 🟣 Make the mechanism work using **joints**, **contact sets** and **motion links**. 

## Tasks

- [x] ✏️ Make the canvases.  
- [x] ➗ Divide the project into components.  
- [x] ➰ Start sketching using the canvases.  
- [x] 🔛 Make sure you have Capture History turned on.  
- [x] 💾 Save multiple versions and suggestively name them.
- [x] 🔠 Properly use names for bodies, components, joints, construction
planes.
- [x] 🟡 Render the object applying appearance and scene.
- [x] 🖼️ Save the renderings as photos and as a video.
- [x] ↪️ Add joints, motion links and joints limits.
- [x] ▶️ Create motion studies.

## What will you find here?
Canvases for each and one component and for the whole mechanism, stl files for each subcomponent and some f3d files showing my progress.

## Resources

- [LarkysPrints on Thingiverse](https://www.thingiverse.com/thing:3364860)
- [Prusa 3D by Joseph Prusa on Youtube](https://www.youtube.com/watch?v=u4dbpJuXrzg&feature=youtu.be)
- [domjubgwefer on Youtube](https://www.youtube.com/watch?v=AWud6KU8Z4s&t=6s)
- [alaskanlimoguy on Youtube](https://www.youtube.com/watch?v=4-xS49tFSjo)

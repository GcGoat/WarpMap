Setup:
- Programable Board
- Warp Drive (optional)
- Databank (optional but strongly recommended)
- Screen unit (M sized recomended)

Connection:
Folow basic order when connecting to have least posible adjustments later on
1. From PB (programable board) connect to ships core unit
2. From PB connect to warp drive
3. From PB connect to databank
4. From PB connect to screen(s)
By folowing these steps you will have screen connected to slot4 which will automatically recognize it and you can use it straight away without aditional adjustments

When everything connected copy code from https://raw.githubusercontent.com/GcGoat/WarpMap/main/JSON and then right click PB go into Advanced and then "Paste lua configuration from clipboard" after which you should get confirmation and you are done. Enable Pb and turn on screen

In case you skipped some steps and you dont have databank or wapr drive, screen will not work until you properly set it up. For that you will need to add 2 filters (mouseDown(* *) and mouseUp(* *)) for each screen. Appropriate code needs to be added for each screen. keep in mind that last variable needs to match actual slot name, otherwise it will not work.

Sine Notes. Due to bug relating to ships weight, you might not see its accurate weight until you sit into pilots chair.

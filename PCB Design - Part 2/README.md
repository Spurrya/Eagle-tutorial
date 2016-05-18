# PCB Design Workshop

After you have created your schematic, open it

On the top, click on board. You will get a popup asking you "Create from schematic?". Click "yes".

EAGLE has limitations on the board size for the free version, however, our board is small enough and can be created with the free version.

It is important to understand that PCB board is made of layers.
Our board has TWO layers of ground plate present (top and bottom).
The top and the bottom layers are connected to each other using 'vias'.

Below is are the descriptions to some of the PCB layers:

* **Top**- Top copper layer, connections and pads to solder on components.

* **Bottom** - Copper layer on the bottom

* **Vias** - Connection b/w the top and bottom layers

* **Unrouted** - Unrouted connections from your schematic diagram

* **Dimension** - Size of the board

* **T-place** - Silkscreen on the top of the board which will tell you where to place the components

* **T-origin** - Cross-section of the component so we know the center

* **T-name and value** - Corresponding names and values of each components


**Rasnet** helps us find the closest connection between the parts automatically.

**Ground Plate** - We will be adding a ground plate in this workshop as it Assist with heat dissipation,Lower the resistance of the path and Electromagnetic shielding.

However, we need to also be aware that there are several disadvantages of a ground plates as it can cause your circuit to be less responsive.

Exceptionally quick circuits? Might want to remove the ground plate


To draw the ground plate, use the polygon function and name is 'GND' (or the same name you gave your ground pins).

EAGLE has an option to automatically map your connection and optimize it (to some extend on the free version).

Click on 'Autorouter' - It will automatically create the connections for you

Click on 'Via' to add via points

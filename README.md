## Ksoloti Core Shield Kicad Template

Shield Template Project for Ksoloti Core v0.5+ and Kicad 6+. You can use this as a starting point to design your own shield.

# Installation Instructions

Clone this repo to your User Templates directory. It will then show up under the `User Templates` tab when you create a `New Project from Template`. You can find the default User Templates directory by checking the `KICAD_USER_TEMPLATE_DIR` variable in `Preferences > Configure Paths...` or by navigating to the `User Templates` tab in the Project Template Selector window after you've selected `New Project from Template` in the file menu.

Example Locations (might differ depending on your Kicad version):
 * Windows: `C:\Users\<user name>\Documents\kicad\<version>\template\`
 * Mac: `/Users/<user name>/Documents/kicad/<version>/template/`
 * Linux: `/home/<username>/.local/share/kicad/<version>/template/`

Alternatively, clone the project any location you wish and then browse to it in the `Project Template Selector` window on the `User Templates` tab. 

## About
The Ksoloti Core plugs into the bottom of the template and all its relevant pins are brought out to the sockets of the template.

All pins in this template have been realized as single-pin footprints so you can delete whichever pins you don't need and claim back some space for your design.

The included mounting holes are also optional. You can delete them if they conflict with your part placement (the headers make a solid enough connection), although it is recommended you keep the two top (north) holes to maintain a solid connection when plugging your USB cables. M3 standoffs with 12mm length fit well here.

##  Top view

![ksoloti_shield_template_top.png](/meta/ksoloti_shield_template_top.png)

# Bottom view

![ksoloti_shield_template_bottom.png](/meta/ksoloti_shield_template_bottom.png)

# Bottom view with Core plugged in

![ksoloti_shield_template_bottom_3d.png](/meta/ksoloti_shield_template_bottom_3d.png)

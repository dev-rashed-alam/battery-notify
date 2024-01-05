# battery-notify
A simple script to notify you when your battery charging reaches 80% or above and discharging reaches 20% or below in Linux to elongate battery lifespan.

This program will continue to notify you every 2 minutes after your battery reaches 80% or above until you disconect the charger or it reaches 20% or below until you connect the charger.

![preview](https://imgur.com/eISIRBB.png)

## Installation :

### 1. Install dependencies: `acpi`, `libnotify`, `mpg123`, `git`

#### Ubuntu
`sudo apt install acpi libnotify-bin mpg123 git`


### 3. Add the `battery-notify.sh` script as a startup application
(Open settings then search startup then add new program and select the script)

### 4. Logout and relogin your current session and enjoy elongated battery lifespan by turning of charging at 80% 👍


# Rack-mount server platform for Raspberry Pi

3D printed, 2U rack mount platform for clustering Raspberry Pi or similar form factor single board computers. 

The STL files contained at the root level of this repository are directly from [Uptime Lab's official website](https://uplab.pro).

Within folders in this repository, there are folders named ```extra```.  Each ```extra``` folder contains derivative models based on Uptime Lab's models, as well as models that were inspired by the original models.

Using the models in this repository, a 3D printer, a few other parts and a bunch of time, you can create a platform of dense, single board computers.  

Using [Uptime Lab's](https://uplab.pro/) [original](https://uplab.pro/2020/12/raspberry-pi-server-mark-iii/) accomodates 18 Raspberry Pi computers, with enough space for each RPi to have a PoE module.  A similar density of Pine64's [Rock64](https://www.pine64.org/devices/single-board-computers/rock64/) can also be achieved with the same models.  Using the ```Narrow``` and ```Wide``` body models in ```extra``` can be used when accomodate wider boards; namely allowing for the use the PCIe on the RockPro64.

----

![Uptime Platform for Raspberry Pi Mark III n18](images/mark-iii-x18.jpg?raw=true)

## Printer Settings

A Creality Ender 3 pro and Creality 6 SE printers were used textrao print all the parts.

* Filament: [eSUN PLA PRO (PLA+)](https://www.amazon.com/gp/product/B01EKEMDA6/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
* Filament temperature: 210 C
* Bed temperature: 80 C
* Z-Hop: Yes
* Cura Profile: Dynamic Quality

These settings were arrived upon after many, many prototypes.  These settings might not be ideal when using your own 3D printer.  Experiment by printing a couple different models.

I would recommend test printing ```extra/Nameplate Long-Wide.stl``` or ```Nameplate.stl``` and ```Body x17.stl```.  Things to watch for:

1. The prongs on ```Nameplate``` will crack off easily if printed with too low a density.
2. ```Body``` model is printed vertically.  Doing so leaves a minimal amount of surface area touching the build plate.  Without good adhesion, the model will easily become detached.

----

## Build Notes

* Many of the Raspberry Pi computers and Power over Ethernet (PoE) modules were sourced from [Adafruit](https://www.adafruit.com).  Others were sourced from eBay, [SparkFun](https://www.sparkfun.com), Pishop (both [Canada](https://pishop.ca) and [US](https://pishop.us)).
* Gigabit switch: HP ProCurve JG237A A5120 PoE+ EI Switch 48 Port 
* Multi-port USB: [TRIPP-LITE U280-016-RM USB Charging Station 16 ports](https://www.tripplite.com/16-port-usb-charging-station-syncing-function-5v-40a-200w-usb-charger-output~u280016rm)
* [Threaded rod](https://www.mcmaster.com/catalog/128/3479) and M5 Fan [bolts](https://www.mcmaster.com/catalog/128/3447)
* [M5 nuts](https://www.mcmaster.com/catalog/128/3500)
* Torx round head, [thread forming screws](https://www.mcmaster.com/catalog/128/3287) for plastic; these are only needed if you chose not to use PoE modules *or* you are using Pine64's Rock64, A64, or RockPro64, as well as Orange Pi PC and other similar form factor boards.
* [ARCTIC P8 - 80 mm Case Fan](https://www.amazon.com/gp/product/B00NTUJZ36/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
* [USB to 3-pin adapter cable](https://www.amazon.com/gp/product/B07JW73KVR/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) (five individual adapters are needed; one for each fan)

----

![Uptime Platform for Raspberry Pi Mark III n18](images/IMG_9233.jpg?raw=true)

----
[Official website uplab.pro](https://uplab.pro/2020/12/raspberry-pi-server-mark-iii/)


<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a> <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

</br>

Original Models - Copyright &copy; Uptime Lab/Ivan Kuleshov 2020-2022</br>
*Extra* Models - Copyright &copy; A.C. Jokela 2022

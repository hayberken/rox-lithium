#Lithium#

Lithium just sits in your Panel and glows different colors to let you know the charge status of your laptop battery. A tooltip gives you additional details.

For each battery charge level from 100% to 0%, Lithium displays a different icon. A different indicated (e.g. a lightning bolt) indicates On AC power. These icons can easily be replaced by changing the contents of the images directory. In fact, 5 different styles are provided.

* Color (svg)
* Horiz (svg)
* Mono
* Mono+ (a little color)
* Tango (from GNOME PowerManager)

#Options#
Lithium has options to select the Theme, control notification of low battery status and how often to update its status.

#Requirements#
* ROX-Lib2
* python
* a battery
* APM, ACPI or PMU support in your kernel

(note: the code will automatically try acpi and pmu before apm. If you have problems with acpi or pmu you can simply delete the acpi.py or pmu.py files and only apm.py will be used.)

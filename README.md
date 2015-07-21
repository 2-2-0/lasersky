# lasersky
system for handling a laser system using python over a raspberry pi

hw: jpv + mm
sw & audio: 220

designed, built and coded by WKH for Timberland / Ache Producciones
presented at carnaval Bahidora, 2015

needs pygame library

This system controls a number of lasers under different patterns that trigger both lasers and audio.

Lasers are triggered using an 818 relay board from electronicaestudio.com, but may be used with any system, as we only send on/offs using the GPIO pins on the Raspberry Pi. Code is set NOT to use GPIO pins, so please enable directly on the code by setting line 31 gpio=False to gpio=True.

# esphome_configs

Pool Controller ESPHome config file

Using Kamoer Peristaltic pumps with stepper motor for dosing chemicals.

ESP32<br>
2x Kamoer KCM-B166<br>
2x a4988 Stepper drivers<br>
Atlas Scientific EZO for pH and ORP probes<br>
Atlas Scientific ORP and pH Mini Probes<br>
UniPi 1.1 (connected using I2C)<br>
Tentacle T3 board (Connected using I2C)<br>
Dallas temp sensor<br>
SR-04T for water level in a water tank<br>

Switching low voltage only with UniPi relays, controls big 230V 16A power relays. This HW was left over from previous unfinished project which I converted to ESPHome. The same for Tentacle T3. You can replace these with EZO boards and use different relay board<br>

All automations happen on the ESP itself, the only thing you need is input helpers to be able to control pH and ORP. Then just add all sensors and switches from the ESP to your dashboard as you wish.<br>



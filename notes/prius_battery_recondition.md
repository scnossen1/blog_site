# Prius Hybrid Battery Reconditioning

## Project Specific Terms and Definitions as I Understand Them

There are what I came to understand as I undertook this project. All definitions will be as it applies to a 2nd Gen Prius' hybrid battery, but a lot of this information could also be used for NiMH batteries in general. Additionally, it's my understanding these high level concepts also apply to all battery types.

- Volts: Electrical potential or difference. Voltage is to electricity, as pressure is to water.
- Amps: Electrical current or the rate at which electrons flow. Amps is to electricity, as flow rate is to water.
- Amp Hours: The capacity of a battery. A 2nd gen prius battery module has 6.5Ah or 6500mAh when new.
- Cell: These are the individual parts of a module. A 2nd gen Prius module has 6 cells.
- Module: These are the individual parts of a hybrid battery pack. A 2nd gen Prius battery pack has 28 modules.
- NiMH Battery: This the particular battery chemistry that makes up a 2nd gen Prius hybrid battery.
    - [Charging NiMH](https://www.batteryuniversity.com/article/bu-408-charging-nickel-metal-hydride/)
    - [Nickle Based Battery Information](https://www.batteryuniversity.com/article/bu-203-nickel-based-batteries/)
- Delta Peak: This is a behavior of NiMH batteries where, when the battery is full, the voltage will actually nose down. Detecting the decrease is how its determined to be full.
- Nominal Voltage: 1.2V per NiMH cell or 7.2V per module
- Reconditioning NiMH Modules: 
- Balancing a Battery: 
- Battery Charger: I went with the EV-Peak CQ3. It can do 4 modules at a time. It also has lots of features that make the reconditioning processes easier.

## Specific Information I Gathered to (hopefully) Recondition My Battery
- Capacity: Consensus ranges from 4,000mAh to 5,000mAh between Reddit and Prius Chat. I am aiming for 4,500mAh as a cutoff.
- Internal Resistance: https://www.batteryuniversity.com/article/bu-902-how-to-measure-internal-resistance/
- Delta Peak (mV): I have decided to go with 5mV/C (30 mV/Module in my case). My research points to lower more accurate but harder to determine when full. Higher easier to detect but less accurate. There is also the issue of overcharging/venting with a high value as the battery is pushed further before its determined to be full. Based on the "quality" of my charger and looking for a safe middle, I think 5mV/C is safe.  
    - [Battery University](https://www.batteryuniversity.com/article/bu-408-charging-nickel-metal-hydride/): 5mV/C
    - [RC Forums](https://www.rcgroups.com/forums/showthread.php?647530-Delta-Peak-voltage-when-charging-NiMh-batteries): 3-4mV/C
    - [Prius Chat Forum](https://priuschat.com/threads/nimh-sensitivity-d-peak.139907/): 3.33mV/C
    - EV-Peak CQ3 Default: 7mV/C
- Charge Rate:
- Discharge Rate:
- Reconditioning Loops:
- ADD ALL OTHER SETTINGS IN THE EV-PEAK CQ3
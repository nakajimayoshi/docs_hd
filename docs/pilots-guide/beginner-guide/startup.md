# Starting the Aircraft

>Several acronyms are used in this guide to refer to specific components of the aircraft. Check the [Boeing abbreviations dictionary](docs_hd/docs/pilots-guide/abbreviations.md) for terms that seem unfamiliar. 

>Some flight deck model behaviors have not been implemented yet. We will update this guide as more functionality is added, but for now the scope of this guide is to cover the capabilities of our aircraft.

## Cockpit Preparation
Begin by scanning the [bottom pedestal]().<br>
* Check that the [parking brake]() is engaged (UP position)
* Ensure the [Speed Brakes]() are disarmed and retracted
* [Flaps]() are retracted
* [Engine Master Switches 1 and 2]() are both off. 
* [Engine Ignition]() knobs are in the `OFF` position. 
* [Thrust Levers]() are set to idle.

Next, move to the **center panel** and ensure the [gear lever]() is set to `DOWN`. 

Finally, move to the overhead panel and check that both the Captain's and First Officer's wipers are in the `OFF` position.

## Overhead Panel

## Electrical
It's necessary to supply electrical power to the aircraft in order to use any of the flight systems.
First, open the battery switch to supply power from the aircraft's main battery. Then turn on any one of the three external power switches.
If flying at night, this is a good time to familiarize yourself with the [flight deck and panel brightness lights]() and adjust as needed for visibility. 

> Some gates or stands are not equipped with ground power. This is regular at smaller airports in Microsoft Flight Simulator. You can either call a Ground Power Unit (GPU) if available or 
use the APU described in the upcoming steps.

## IRS 
Prior to aligning the [IRS](), your PFD and MFD will look like ![this](). **This is normal behavior**, and indicates you have not aligned 
the IRS, a system used to geolocate the aircraft's position. Align the IRS by rotating the RIGHT and LEFT knobs to `ON` position. It takes several minutes to 
align [depending on your latitude](). 

>To align the IRS instantly (not realistic) open the HEAVY menu in the FMC, select the IRS configuration option, and select the `FORCE ALIGN` option. 


![]() <!-- GIF HERE -->
## APU 
To supply enough power for engine start we need to start the APU. Turn the APU knob to the "START" position. 

On the glareshield panel, ensure the APU is supplying power to the aircraft by selecting SYS, then on the MFD select the ELEC tab. 
If the EGT and voltage are rising, the APU is powering on and beginning to supply additional power to the aircraft. If the APU is not turning on, please refer to our support guide for troubleshooting.
>Note that the 787 Dreamliner features a 'no bleed' architecture. There is no need to supply the engines with bleed air from the APU or any external air power units, as the start sequence is handled entirely by electricity.

## Exterior Lighting 
Set NAV and LOGO light switches to the `ON` position. 

## Passenger Signs
Set the passenger seatbelt signs knob to the `ON` position. 

> In the experimental version, `AUTO` is also supported. 

> In real life, the seatbelt sign is not turned on until fueling is complete. 

## Hydraulics 
Ensure the C1, C2, L and R ELEC Hydraulic knobs are set to the `AUTO` position. 

## Fuel
Ensure only the L PUMPS FWD switch is set to `ON`.

>The default 787 by Asobo includes a bug where engaging the left center fuel pump disables the APU. This is behavior is corrected in the experimental version only.

## Radio Panel 
Select the VHF menu and set the active frequency to **ATIS**, and the standby frequency to the **Ground** frequency. 
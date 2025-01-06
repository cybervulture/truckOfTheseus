### see also
[toyotaRSeriesNotes](toyotaRSeriesNotes.md)
[toyotaVFTransferCaseNotes](toyotaVFTransferCaseNotes.md)
## engine
2011 Volkswagen 2.0L TDI (engine code CJAA), sourced from totaled Jetta Sportwagen

Status
- 112k miles
- wholly stock
- needs removed from the VW
Plans
- BiTDI turbo setup from VW Amarok, engine code CSHA (maybe also CNEA)
- DPF delete and tune for compounds
- injectors or whatever else the engine needs to make the compounds work
[notes from darkside dev on tuning the BiTDI](https://www.darksidedevelopments.co.uk/Blog/20-bitdi-engines-what-to-know/)
## transmission - R155F (2nd gen 2TR manual taco) or R156F (3nd gen 2TR manual taco)
|         | **R150F** XVZ | **R151F** 22RET | **R155F** 2TR Taco | **R156F** 2TR Taco | RA60F (Aisin AY6) 1GR | RA61F 1GR FJC | RC60 (Aisin AC6) Hilux | RC62F (Aisin AC6) 2GR Taco | Amarok BiTDI |
| ------- | ------------- | --------------- | ------------------ | ------------------ | --------------------- | ------------- | ---------------------- | -------------------------- | ------------ |
| **1st** | 3.83          | 4.32            | 3.95               | 4.31               | 4.17                  | 4.17          | 4.78                   | 3.98                       | 4.82         |
| **2nd** | 2.06          | 2.33            | 2.06               | 2.33               | 2.19                  | 2.19          | 2.42                   | 2.02                       | 2.54         |
| **3rd** | 1.44          | 1.44            | 1.44               | 1.44               | 1.49                  | 1.49          | 1.44                   | 1.32                       | 1.49         |
| **4th** | 1.00          | 1.00            | 1.00               | 1.00               | 1.19                  | 1.19          | 1.00                   | 1.00                       | 1.00         |
| **5th** | 0.84          | 0.84            | 0.81               | 0.79               | 1.00                  | 1.00          | 0.77                   | 0.85                       | 0.76         |
| **6th** | --            | --              | --                 | --                 | 0.85                  | 0.80          | 0.64                   | 0.71                       | 0.64         |
| **rev** | 4.22          | 4.220           | 4.22               | 4.22               | 3.61                  | 3.61          | 4.07                   | 3.39                       | 4.37         |
Notes
- the R155F is compatible with the aftermarket UZ V8 swap bellhousing as evidenced by [Big Tire Garage's V8 taco swap](https://youtu.be/AR05MSszc_M?si=6s42Iqa_TK3y4ZgA)
- presumably the R156F has the same mounting pattern on both sides of the bellhousing so it should be compatible anywhere a R150F (1995+), R151F, or R155F would work
- the RA60F/RC62F 6MT from the GR family V6 engines was considered but is not viable due to sizing, allegedly all the diameters are overall larger than the R15X series and doesn't fit well in the trans tunnel (I can't find my original source for this)
- ratios from [wikipedia](https://en.wikipedia.org/wiki/Toyota_R_transmission) support R156F is the best on account of deepest first gear and tallest 5th gear 
Status
- currently has the earliest R150F possible from the first year of the 3VZ
- needs rebuild so it's time to replace
Plans
- replace with R156F from 3nd gen taco and eventually mate to eco-crawler doubler
- the R156F should have the same tailhousing as all the modern Toyota transmissions, allowing for any modern VF transfer case to be installed
- looking specifically at the RC62 the gearing is essentially a R150 with an extra overdrive gear and a reasonable match to the Amarok transmission
## doubler
Status
- none, I have the marlin 10* clocked adapter that I can sell since I wanna do things differently and be weird
Plans
- [Northwest Fab eco-crawler](https://northwestfab.com/collections/eco-crawler-underdrives) to use the guts from the case thats in the truck currently, use VF4 transmission side pattern with VF4 case side pattern for 3rd gen tacoma 2TR to VF4AM [see fitment chart](https://cdn.shopify.com/s/files/1/0509/2261/9043/files/EcoCrawler_Fitment_Guide_R00.pdf?v=1660254556)
- pretty sure the adapter can be custom ordered for the R155F tailhousing and 
## transfer case
|       | **2WD** | **AWD** | **4WD** | Application                                                                                                                                                                                   |
| ----- | ------- | ------- | ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| VF1   | x       |         | x       | 3VZ equipped trucks/T4Rs                                                                                                                                                                      |
| VF2   | x       |         | x       | Basically everything that's 2WD/4WD only (lots of variants but that's irrelevant)                                                                                                             |
| VF3AM | x       | x       | x       | [3rd gen T4Rs with mulitmode](https://www.toyota-4runner.org/3rd-gen-t4rs/78448-t-case-differences-all-years-3rd-gens-transfer-case-awd-multi-mode.html)(1999-2000 limited and all 2001-2002) |
| VF4AM | x       | x       | x       | 4th gen T4R V6 models and late 1st gen sequoia                                                                                                                                                |
| VF4B  |         | x       | x       | FJ Cruiser                                                                                                                                                                                    |
| VF4BM |         | x       | x       | 4th gen T4R V8, 5th gen T4R limited, GX470, GX460, 1st gen Sequoia                                                                                                                            |
Status
- VF1A, in good condition as far as I remember
Plans
- steal the guts from the VF1A that's in the truck right now for an eco-crawler doubler box
- replace with a VF4AM series awd case from 4th gen T4R with [Northwest Fab Topshift](https://northwestfab.com/products/toyota-vf2-vf4-transfer-case-top-shift-conversion-kit) and [NWF Trident Triple Shifters](https://northwestfab.com/products/trident-triple-shifters-for-toyota?pr_prod_strat=e5_desc&pr_rec_id=03ec9ee62&pr_rec_pid=7808032211107&pr_ref_pid=7824492691619&pr_seq=uniform)
- the result is a driver drop "multimode" case providing 2WD, AWD, 4WD-H, and 4WD-L
- install a transfer case parking brake
## adapters
Engine to Transmission
- [TD Conversions adapter](https://tdconversions.com/collections/toyota), they make one for the TDI to any of the Toyota transmissions
Transmission to Transfer case
- the ecocrawler box will bolt to any combination of manual transmission and VF series case
- a R156F or a RC62F should bolt directly to a VF4AM if the doubler is omitted, both come factory with the same (newest) version of the VF2 which uses the same mounting patters as the VF4B from the FJC, which has been demonstrated to fit the RA60F/RC62F
## axles
### front
Status
- 1983 solid front axle with 1988 IFS hubs and 2006 Tundra disks
- current width as measured is 59.53" between the wheel mounting surfaces (including the thickness of the rotors)
	- this is different than the 58.25" that is reported by [roundforge](https://www.roundforge.com/articles/toyota-axle-widths/), dunno why
Plans
- flip a 60 series axle to accomadate the driver drop VF4AM transfer case and run 5th gen 4Runner slip on rotors and their respective calipers
- per [roundforge](https://www.roundforge.com/articles/toyota-axle-widths/)this is 58.9" wide (has rotors that mount inside the hubs)
- per [this forum post on IH8MUD](https://forum.ih8mud.com/threads/tech-debate-wms-width-of-fj6x-front-axle.917869/post-10288002) and [this post on marlins forum](https://board.marlincrawler.com/index.php?topic=50008.0) the axle is 58.5", which is within reasonable tolerance to the roundforge measurement
- assuming a slip on rotor thickness of 0.25" the total width of the axle will increase by approximately 0.50", putting the modified axle width somewhere in the ballpark between 59.0" and 59.5"
- add a locker of some sort, currently thinking a harrop elocker
### rear
Status
- currently running an IFS housing with custom full float with 2015 4runner rear disc brakes (slip on rotors)
- measured at 58.75" between mounting surfaces (this would be plenty compatible with a worst case scenario front axle at 59.5" wide)
Plans
- build new v2 full float adapters using the mill and lathe to address some small shortcomings in the original design
	- fix sealing surface
	- fully weld bracket then machine off extra weld to make it look nicer
- add a locker of some sort, currently thinking a harrop elocker
- if I feel really ambitious and can source a 9.5" rear end convert my axle to a 9.5" housing, see [post 354 on zuk's thread on yotatech](https://www.yotatech.com/forums/f152/sas-fj60-axle-housing-flip-front-shackle-my-2001-tacoma-283930/index18.html#post52379664)
## general notes
- front axle conversion to spring under and shackle forward, the plan is in my head but its not written down or drawn out anywhere
	- see [zuk's argument here for why shackle forward](https://www.yotatech.com/forums/f152/sas-fj60-axle-housing-flip-front-shackle-my-2001-tacoma-283930/)
	- spring under should net me at least 5 inches of extra axle travel at the current ride height, if I lower it some I'll still have more travel than I do currently
	- spring under also lets me ditch the z-link steering and go to a more traditional crossover steering with the tie rod roughly inline with the axle tube
- brake lines need rerun since they're all old and very crusty
	- eventually would like to [add ABS (FJ40)](https://youtu.be/dFsnpSypG9U?si=Bk-GkY7Bf3PFQkB8) using a [MK60 ABS control unit](https://grassrootsmotorsports.com/forum/grm/standalone-abs-installs-mk60-and-more/248099/page1/) and custom tone rings so probably run brake lines with that in mind and cap off the spare lines
		- [OEM applications of the MK60 ABS system](https://www.ate-brakes.com/products/hydraulic-parts/mk60-abs-control-unit/)
		- [An install in a Miata using BMW parts](https://www.miataturbo.net/suspension-brakes-drivetrain-49/mk60-abs-installation-guide-100731/)
		- [VW coding for the MK60](http://wiki.ross-tech.com/wiki/index.php/VW_Golf_(1K)_Brake_Electronics_(MK60))
- [carpart for parts](https://www.car-part.com)

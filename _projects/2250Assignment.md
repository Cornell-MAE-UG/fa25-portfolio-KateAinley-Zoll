---
layout: project
title: MAE 2250 Spotted Lantern Fly Project
description: This is the client pitch on our SPL system idea. 
technologies: [Autodesk Fusion]
image: /assets/images/SPL.png
---


## HertzTrap: Frequency-Based Spotted Lanternfly Deterrent


**Team:** Newton's Nightmares

**Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape


## Problem statement


Farmers in vineyards are trying to continue growth and production of their vineyards. However, the growing population of Spotted Lanternflies (SLFs) puts significant pressure on farmers as these insects feed off grapevines, lowering yield and significantly damaging or killing the plants. The SLF is an exceptionally harmful pest because there are no natural predators and regular pest control does not work effectively. When harvesting, if more than 2 SLFs are found in a 1 kg sample of harvest, the entire section must be discarded per health code—a devastating loss for farmers already running on thin margins. Our team is aiming to take advantage of the SLF's documented attraction to 60 Hz frequencies and create a product that draws SLFs away from grapevines.


## Impact


SLF infestations prevent farms from passing health code inspections, forcing the discard of otherwise viable harvests. This directly threatens farm profitability and viability. A product that removes SLFs from grapevines before harvest can prevent yield loss, help farms meet health codes, and significantly increase both productivity and profit margins.


## Proposed direction(s)


### Concept A: HertzTrap


**What it is:** A modified electric insect trap designed to attract adult SLFs using a 60 Hz vibrational stimulus, based on published observations of SLF responsiveness to specific frequency cues.


**How it would be used:**
- Traps are installed along vineyard perimeters or near vine canopies before harvest
- Device emits 60 Hz stimulus to attract SLFs away from grape vines
- SLFs fly into an electrified grid and are neutralized before entering vineyard
- Device operates continuously during migration window


**Why it's better than the status quo:**
- Targets SLFs before they enter vineyards and have access to grapes
- Avoids pesticide application and associated labor
- Uses simple electrical components instead of a high-precision sorting system


**End-of-semester proof-of-concept:** We will develop a full CAD model with real-world dimensions and a scaled-down HertzTrap shell built to accurate proportions. The shell will include an internal slot and 60 Hz speaker, plus a PLA or ABS mesh outer layer to represent the electrically charged shock layer.


## Key risks / unknowns


- **Attraction Strength:** SLFs may not respond strongly enough to 60 Hz cues in open vineyard environments. We will test this through outdoor trials to validate effectiveness.
- **Nontarget Effects:** The trap may attract or harm beneficial insects. We will evaluate trap selectivity through observational testing.
- **Environmental Durability:** Outdoor weather and dust may reduce performance. We will evaluate possible materials, durability, and placement strategies.


## Questions


1. **What size trap would be most practical for your operations?** *Decision affected:* Sizing and the number of traps we recommend installing per acre.

2. **Will disposing of dead flies be an issue for your farms?** *Decision affected:* Whether we need to design the trap to minimize aftereffects or provide disposal guidance.

3. **Is harming non-SLF animals and pests of similar size/behavior a major environmental concern?** *Decision affected:* Whether we need to refine trap selectivity or if the current design approach is acceptable.



## References


- Wine Market Value - https://www.grandviewresearch.com/industry-analysis/us-wine-market

- Spotted Lanternfly Information - https://cals.cornell.edu/integrated-pest-management/outreach-education/whats-bugging-you/spotted-lanternfly/spotted-lanternfly-damage

- 60 Hz Research - https://www.usda.gov/about-usda/news/blog/spotted-lanternfly-reveals-potential-weakness


ODP 5 
ODP 5 - Functional Prototype
Team - Newton’s Nightmares
Design Documentation:


Component Name
Source
McMaster Code
Upper Electrical Box
RPL
N/A
Upper Lid
RPL
N/A
Copper Mesh
McMaster
9224T55






Legs
Amazon: link
N/A
Arduino Nano
McMaster
1387N33
Shocker PCB
Amazon: link
N/A
Battery Box
McMaster
7712K317
Speaker
Amazon: link
N/A
Amplifier
Amazon: link
N/A
Power Switch
Amazon: link
N/A


Full Prototype CAD:

![]({{ "/assets/images/ODP51.png" | relative_url }})

1. Start with an empty upper electrical box.
![]({{ "/assets/images/ODP52.png" | relative_url }})
2. Attach all electrical components, taped in with the materials we had, for the final, it will be glued.
![]({{ "/assets/images/ODP53.png" | relative_url }})
3. Mount top cover with screws
![]({{ "/assets/images/ODP54.png" | relative_url }})
4. Apply mesh to middle mesh structure. Weave it through and hot glued it. For the final we will make it more secure.
![]({{ "/assets/images/ODP55.png" | relative_url }})
5. Attach legs with superglue to the electrical box. 
![]({{ "/assets/images/ODP56.png" | relative_url }})
Design Tests
1. Drop Test

This test evaluates the durability of the upper body of the HertzTrap when dropped, focusing on the strength of the material and geometry of the electronics hub. Since the major components are housed in this box, failure to protect the electronics would compromise the entire prototype.

Method:
The trap will drop legs facing up onto a grass surface. Three heights will be tested: 1 ft, 2 ft, and 4 ft. The legs are replaceable and not the final version, so the test focuses on the stability and integrity of the upper box.

Results:

Height 1: 1 foot: No damage done to the box or devices. Staying in the same orientation as what we dropped it at, we saw no change. (The first photo is in the wrong orientation; we just had it sideways to show the height difference, but dropped it upside down like seen in the after photo).
![]({{ "/assets/images/ODP57.png" | relative_url }})
Height 2: 2 feet. Again, no deformation to the device, but this time it fell over when hitting the ground. Still no visible damage, and all the devices were safe within the electrical box. 
![]({{ "/assets/images/ODP58.png" | relative_url }})
Height 3: 4 feet: The box fell over, and the legs we have (not our final legs, as they have not come in yet) were a bit unstable. They moved quite a bit but didn’t break off. The electrical components were all still attached on the inside. 
![]({{ "/assets/images/ODP59.png" | relative_url }})
Conclusion:
The upper box shows excellent durability at lower heights. At 4 ft, temporary legs exhibited instability, suggesting that final legs should be reinforced to prevent potential breakage from higher drops or repeated impacts. This informs the next prototype by emphasizing stronger leg joints or additional corner reinforcement, which we plan to do.


2. Box Capacity and Electrical Component Fit

The purpose of this test is to determine if there is adequate space within the upper electrical box to house all the electronics we plan to install. Since we do not know the exact electrical output/wiring needed to power our mesh correctly, we will use estimates based on existing bug zappers and our planned sketches. This tests our upgrade capabilities for the electrical components of our zapper, in case we need a bigger battery or another circuit board. Additional room and good estimation can aid in the main function of our zapper, neutralizing SLFs.

We will measure the approximate volume and dimensions of our current and planned components to visualize the available/needed space.

Results: 96 inches is the volume of our box, but most of the components will be sitting in the area of 16 inches, with a 1.5-inch height. Our components of speaker, Arduino Nano, Zapper PCB board, and battery case take up 10 inches area wise and at various heights, all under 1.5 inches. Therefore, we have more than enough room for everything in our upper electrical box. 

Conclusion: There is ample room for all current and planned electrical components. The extra space allows for potential upgrades without redesigning the box, ensuring the next prototype can accommodate larger batteries, additional circuitry, or airflow improvements for heat management.

3. Strength/Sturdiness Tests
The purpose of this test is to determine the vertical loads that our zapper can withstand without breaking and/or buckling. This is by far the most important test that we can perform, as the legs and upper box’s strength are both tested. These components need to remain static under large loads to simulate the weight imposed by farmers, machinery, and weather conditions. This tests the geometry and materials chosen for our legs and upper electrical box, allowing us to decide on further upgrades needed to either component.
We will test this by adding weights to the upper lid of the electrical box incrementally, till we either a) buckle at the legs, b) the lid for the electrical box breaks, or c) the box tips over.
Results:
Since we do not have our main legs (ordered on Amazon), we can still simulate what this would look like with our temporary legs. We expect these to fail much more easily than our final legs.

Weight 1: 544g- stable
![]({{ "/assets/images/ODP500.png" | relative_url }})
Weight 2: 1095g- stable
![]({{ "/assets/images/ODP5000.png" | relative_url }})
Weight 3: 1654g- stable
![]({{ "/assets/images/ODP50000.png" | relative_url }})
Weight 4: 2195g- The box started to tip over, with visible stress on the legs
![]({{ "/assets/images/ODP500000.png" | relative_url }})
Conclusion: The prototype can support the weight of grapevine debris and small animals (typically 200–500 g) with a significant safety margin. Temporary legs are weaker than the final design, suggesting that the next prototype should include robust leg material and reinforced joints to handle higher loads and ensure long-term durability, which again we plan on doing.

Success Criteria
Context: Our HertzTrap device is designed to eliminate Spotted Lanternflies before they gain access to grapevines by attracting them away from entering grapevines through 60Hz audio, and zapping them.
It should be able to:
The HertzTrap device should be able to change height using its extendable legs from up to 3 ft in 6-inch increments to match the height of most grapevines. Each height position should lock securely and remain stable without tipping or collapsing. The device should be easy for a single user to adjust, and all increments should be reachable without tools or excessive effort. A higher number of stable increments and smooth adjustability are high priorities for ensuring the trap can be positioned optimally for different vineyard setups.

The electrically charged mesh at the center of the trap should be able to deliver the intended voltage consistently when the upper box is powered on. This can be demonstrated safely by poking the mesh with a conductive material, such as a metal rod, to confirm that the circuit is active and continuous. The mesh should maintain full voltage without interruptions during testing, and any exposed parts should be secured to prevent accidental contact. Maintaining reliable electrical function is a high priority because it directly affects the device’s ability to neutralize targets effectively.

The trap should be lightweight and easily movable, allowing a single user to lift and reposition the device within 15 seconds without excessive effort. The total mass and dimensions of the device should allow for easy transport across uneven vineyard terrain, and the design should minimize awkward handling. Lower total mass, compact design, and quick repositioning are high priorities, as these features make it practical for repeated use in different locations to maximize the trap’s effectiveness.



ODP 6

ODP 6: Exhibit and Client Report
Team: T5 - Newton's Nightmares 
(James King, Junayed Ridwan, Kate Ainley-Zoll, Anya Besana, Sanithu Kethaka Parattu Mohottige)

Problem Overview
During the pre-harvest grape season, vineyards across the Northeast face devastating losses from the Spotted Lanternfly (SLF). With no natural predators and ineffective conventional pest control, SLF populations continue to surge unchecked. These insects feed directly on grapevines, reducing yield and threatening plant health. The challenge is to intercept SLFs before they ever reach the vines, preserving crop quality and keeping farmers profitable.

Sub-problem and Prototype Application 
	Our concept was to prevent SLFs from reaching the vines in the first place - rather than removing them after harvest, offering a more effective and scalable solution to protecting vineyard yield. To do this, we wanted to create a product that could passively kill the SLFs and draw them away from the vines before doing harm to the plant. We identified a critical weak point in the spotted lanternfly and exploited it by adapting the proven lure-and-kill method of UV bug traps to the USDA's discovery that these insects are uniquely drawn to 60 Hz frequencies. We called this product the Hertz Trap. 
	The HertzTrap is a self-contained electric insect trap that lures and eliminates SLFs before they reach the grapevines. By luring them toward this specific frequency, the trap brings them into contact with an electrified mesh that completes the circuit and neutralizes them instantly. Because it is compact and pesticide-free, it serves as a low-maintenance tool that can be easily deployed across large-scale vineyards without the need for manual insect removal.

Prototype
The final HertzTrap prototype was built to validate the core concept at a functional scale. The enclosure houses a 60 Hz speaker at its center, surrounded by a dual-layer electrified mesh powered by a bug zapper circuit board. When SLFs are drawn toward the frequency stimulus, they make contact with the charged mesh, complete the circuit, and are eliminated. The four independently adjustable legs allow the trap to be staked and leveled at grapevine canopy height across uneven terrain. The enclosure was designed to be weatherproof and structurally rigid, withstanding up to 30 lbs of force without deformation. At just 8 lbs total, the final assembly is lightweight enough for rapid single-user deployment across large farm areas. Overall, the final prototype successfully integrates the electrical, acoustic, and structural subsystems into a compact, field-ready package.
![]({{ "/assets/images/ODP61.png" | relative_url }})
Testing and Results
Three key performance criteria were evaluated through physical testing of the prototype to ensure a successful product.

1. Structural durability, this was confirmed by applying incremental loads to the top of the enclosure; the trap withstood up to 40 lbs without deformation or failure,
 meeting the demands of outdoor farm use. We also dropped 5-10 lb weights from a foot high to replicate branches and falling situations.
![]({{ "/assets/images/ODP62.png" | relative_url }})
2. Adjustability, this was verified by extending and locking each leg independently, confirming a maximum stable height of 3 feet suitable for placement near vine canopies. Individual legs were tested to support the trap at angles and rough areas.
![]({{ "/assets/images/ODP63.png" | relative_url }})
3. Portability, this was tested by timing a single user relocating the trap across a 
simulated farm layout; the trap was consistently moved and reset in under 15 seconds, 
and at 6 lbs total weight, a single user could feasibly deploy over 100 units within a 
standard workday.
![]({{ "/assets/images/ODP64.png" | relative_url }})
While these criteria confirmed the trap's physical viability, they did not address some more critical unknowns surrounding the trap's core function. In retrospect, more decision-relevant success criteria would have focused on biological performance: specifically, whether the mesh density and voltage are sufficient to reliably neutralize a Spotted Lanternfly upon contact, and whether the 60 Hz acoustic stimulus attracts SLFs at a meaningful range under field conditions. In order to simulate a branch falling onto the box, or a drop from a high height, we should have documented weights falling from a height rather than placing them directly on the box. Bench testing confirmed arc discharge across the mesh layers, providing a preliminary indication that the electrical system is functional, but controlled experiments with live insects at measured distances were not conducted. These tests -verifying kill reliability at the chosen mesh geometry and quantifying attraction range and capture rate in a vineyard environment - represent the most important next steps before the HertzTrap can be evaluated as an effective pest control solution.


Prototype and Testing Details 
The HertzTrap enclosure measures approximately 8 × 8 × 2 inches and was fabricated using 3D printing, chosen for its ability to produce a rigid, weatherproof housing at low cost with rapid iteration. The electrical system consists of a repurposed handheld bug zapper circuit board powered by two AA batteries, which steps up the input voltage to a level sufficient to arc across the mesh gap. In parallel with the trapping system, an acoustic subsystem was developed, consisting of a 57 mm diameter speaker driven by an amplifier and controlled by an Arduino Nano to generate a 60 Hz signal. The trap uses a dual-layer mesh configuration: a higher-density inner copper mesh and a lower-density outer metal mesh, with the two layers held at opposite polarities. When an insect bridges the gap between layers, it completes the circuit and is eliminated. The outer mesh has larger gaps so that the SLF can effectively bridge the two meshes. Successful arc discharge between the mesh layers was confirmed during bench testing, validating that the electrical system functions as intended at the chosen mesh spacing and density. 
	![]({{ "/assets/images/ODP65.png" | relative_url }})
Conclusion and Recommendations
	The Hertz Trap offers significant scalability. Future iterations will integrate solar arrays atop the enclosure for continuous field operation, eliminating the need for manual recharging. Furthermore, optimizing mesh density specifically for Spotted Lanternfly geometry will ensure a more reliable circuit completion. These advancements aim to maximize capture rates and long-term durability in agricultural environments. The Hertz Trap is a promising solution to the continuous strain the SLFs put on the vineyard industry. 
According to our clients, E&J Gallo Winery, they stated that another company they have been working with has provided a similar product, a form of “Bug Zapper” that can be placed around the vineyard and passively kills all of the SLFs. The Hertz Trap’s next step in development would be to verify its efficiency, discovering its ideal frequency range and volume to attract the largest number of SLFs. Once that field experiment is concluded and the data drawn, the Hertz Trap will need to be optimized. The electrical components can be compacted into a custom circuit board, fueled by one rechargeable battery by the solar panels. Additionally, there would be a benefit for an additional low-density mesh on the outermost legs to ensure only the SLFs get in without debris accidentally activating the zap. Future iterations should also investigate selectivity, ensuring the trap does not harm beneficial insects,  as well as long-term weatherproofing for extended outdoor operation.



















Bill of Materials

![]({{ "/assets/images/ODP66.png" | relative_url }})
References: 
Wine Market Value
https://www.grandviewresearch.com/industry-analysis/us-wine-market  
Spotted Lanternfly Information
https://cals.cornell.edu/integrated-pest-management/outreach-education/whats-bugging-you/spotted-lanternfly/spotted-lanternfly-damage 
60 Hz Research https://www.usda.gov/about-usda/news/blog/spotted-lanternfly-reveals-potential-weakness 



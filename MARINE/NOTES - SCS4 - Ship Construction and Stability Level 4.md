
###### Precursor and Background
Ship Construction and Stability 4, referred to as SCS4, is the middle level of ship stability courses offered within Canada for masters and mates. The content between SCS3 and SCS4 is largely the same, though at the SCS4 level the formulas and work touched upon in SCS3 are expanded and more calculations are done (ie. calculating free surface effect and correction, as opposed to just taking the FSE/FSC values from the ship's stability booklet.). As to the other levels of stability; SCS3 is used only for domestically limited tickets; and SCS5 is a higher level of the course which is only applicable to candidates at the master mariner or master near coastal level. 
SCS4 is definitely one of the more difficult watchkeeping courses due to the focus on mathematics, which can also make it out to be much more intimidating than it needs to be.

###### Tips for Success
To succeed in SCS4 I would highly recommend completing a math refresher course focused on algebra and touching up on multiplication/division, trigonometry, and interpolation (I would highly recommend excluding excel tutorials from search results if looking for a tutorial on interpolation). Interpolation is used frequently when interpreting data given in the ship's stability booklet. The BEDMAS order of operations is used for formulas, so if you've ever used different order of operations through your scholastic career, forget what you know and adhere to BEDMAS because it's just non-negotiable. 
Using others' standard stability formula sheets can be helpful to gauge which formulas from the material are noteworthy and used frequently; but ultimately it will be the most helpful to create your own formula sheet and take care noting what each value within the formula actually represents (ie. whether the value 'D' refers to draft, depth, or distance to a particular point.). There are between 30-40 formulas which are used repeatedly for calculation. This is a very intimidating course, so any work which can be done to split it into bite-sized chunks will really aid the learning process. 

### Resources
[Khan Academy](https://www.khanacademy.org/) for math refreshers and help.
[Derret's Ship Stability for Masters and Mates](https://files.catbox.moe/uyhgii.pdf) most widely used stability textbook. because it's oriented towards both masters and mates, this is quite a dense textbook. there are plenty of example problems and answers, but there is a lack of questions using hydrostatic data from the stability book itself, which presents a challenge.
[Eyre's Ship Construction](https://file.garden/aIK7T2ngWhc8oB6b/textbooks/ShipConstruction.pdf) helpful aid to the construction portion of the course, but be aware it is more oriented towards the naval architect than the average watchkeeper.
[Dokkum's Ship Stability](https://file.garden/aIK7T2ngWhc8oB6b/textbooks/dokkum_stability.pdf) and [Encylopedia of Ship Knowledge](https://file.garden/aIK7T2ngWhc8oB6b/textbooks/dokkum_ShipKnowledge.pdf) are a fantastic pair of textbooks for both the stability and construction portions of the course, respectively. The diagrams in the stability textbook are fairly easy to understand as opposed to the Derret's textbook; and I personally find the ship knowledge textbook to be a fantastic resource as it is full of photos of different types of vessels, perspectives from simulations, and shipyard photos of actual construction.
[Kemp and Young Ship Stability](https://file.garden/aIK7T2ngWhc8oB6b/textbooks/kemp%20and%20young%20stability%20notes.pdf) another fantastic and concise textbook from the more dated Kemp and Young series. The stability textbook has a rather straightforward and concise formula sheet at the start which may be useful for some. There is also a construction textbook "Ship Construction Sketches and Notes" in the kemp and young series which I was not able to find as a pdf... but it always seems to be available at a very modest price and from what I have seen in person, the sketches and diagrams pertain exactly to the curriculum.

### Syllabus
*+see section 5.11 of TP2293e for the up to date syllabus..* #syllabus
![page 1](https://safe.voyage/assets/marine/syllabus/scs4%20p1.png)
![page 2](https://safe.voyage/assets/marine/syllabus/scs4%20p2.png)
![page 3](https://safe.voyage/assets/marine/syllabus/scs4%20p3.png)
![page 4](https://safe.voyage/assets/marine/syllabus/scs4%20p4.png)
![page 5](https://safe.voyage/assets/marine/syllabus/scs4%20p5.png)
![page 6](https://safe.voyage/assets/marine/syllabus/scs4%20p6.png)
![page 7](https://safe.voyage/assets/marine/syllabus/scs4%20p7.png)
![page 8](https://safe.voyage/assets/marine/syllabus/scs4%20p8.png)

### Formulas
when i get back home as part of scanning my actual notes I need to scan my formula sheets to add here. consider using the pre class for formulas because it seems like that might solve the issue I had with our classroom formula sheet at times being confusing using BEDMAS.

### Values for Formulas and Unit Conversion
#conversion #values
*+all units are in metric. I will not be bothering with the imperial system.*

A - area. area of what is specified after the value. 2d measure of a space
V - volume. 3d measure of a space
△ - displacement. sometimes the capital W is used to represent this value, but to avoid confusion I prefer this symbol.
L - length
B - breadth, or the width of the ship.
D - draft. sometimes depth is used in questions, but to avoid confusion 'depth' is used in the formula rather than 'd', since draft is way more common.
d - distance. it is always noteworthy where the distance is measured from.
w - weight, typically of an object. only the lowercase w is used.
ρ - relative density, or specific gravity. usually just referred to as density. (in my handwritten notes this symbol appears a bit differently, more like a musical note, but I will include my handwritten values table alongside my formulas and notes to clear up any confusion)
θ - variable used to represent an angle of heel or list
*** 
1 meter / 10 decimetres / 100 centimetres / 1000 millimetres
0.1 meter / 1 decimetre /  10 centimetres / 100 millimetres
0.01 meter / 0.1 decimetres / 1 centimetre / 10 millimetres
0.001 meter / 0.01 decimetres / 0.1 centimetres / 1 millimetre
*+decimetres are never used as a value, but are included to make the conversion table more transparent*
***
1 tonne / 1000 kilograms
1 kilogram / 0.001 tonnes
***
#### Definitions
- list - an internal inclining force attributed to the application of cargo (shift, removal, or addition) from the centerline of the vessel. corrective action must be taken to account for and correct the effects of list ^list
- heel - an external inclining force attributed to waves and wind or other dynamic inclining forces. because heel is a condition caused by forces outside of the ship, it is not considered static in the same way that list is and will eventually resolve, allowing the ship to return to the upright position (in stable equilibrium) ^heel
- watertight - withstands high-pressure water force (such as complete submersion) and all weather conditions. frequently used underdeck to maintain critical buoyancy below the waterline. ^wt
- weathertight - withstands spray/rain and all otherwise normal weather conditions.  
- TPC - tonnes per centimetre immersion. this is a representation of how much a vessel will sink or rise by 1cm depending on how many tonnes of cargo is loaded or discharged. ^tpc
***
## Foundations of Ship Stability
#force #moments #buoyancy #floatation
We are all aware that ships are buoyant, and that is why they are able to float despite their immense weight. Buoyancy is proven by [Archimedes' principle](https://en.wikipedia.org/wiki/Archimedes%27_principle), which states in layman's terms  that the upward force of buoyancy is equal to the weight of displacement of an object either fully or partially submerged in fluid. Therefore, the displacement of a ship (which we touch upon later as the force of gravity opposing buoyancy) is equal to the upward force of buoyancy. The forces of gravity (the tonnes of water being displaced) and buoyancy (upward thrust equal to displacement) and their alignment to a ship are integral to stability. When a ship becomes too heavy it will exceed buoyancy and sink; but inversely when it is too light and therefore top heavy it risks tipping over. If gravity and buoyancy were perfectly aligned and no forces could push them out of line, the ship would remain upright; but obviously this is not the case and the forces of wind, waves, vessel movement and internal cargo movement will exert horizontal force and tilt the ship out of vertical alignment one way or another. These are where transverse (port/starboard) and longitudinal (fore/aft) stability come into play.
Transverse stability is more critical than longitudinal stability, simply because the vessel will never be as wide (broad) as it is long. Because a minimum force of buoyancy (draft and reserve buoyancy) must be kept to keep the ship from tipping over, it is also very important to ensure that as the ship tilts ([[#^heel]] and [[#^list]]) it will also have enough reserve righting force (touched upon later as the righting lever, or GZ moment in [[#Transverse Stability (MGBK)]]) to ensure that it will return back to the upright position. Because gravity and buoyancy are forces which always work vertically, even when the ship itself is tilted over, their desire to become aligned will always goad the ship back into the upright position. Transverse stability can be thought of like balancing scales, or a board which is suspended at the midpoint (the ships centreline). As weight is added to one side of the board, it will tilt to that one side; and the act of the board tipping due to weight added is what is called a 'moment of force'. The degree to which the board, or ship, will tilt is dependant on the weight of the object being loaded or removed, and the length of the lever upon which the force acts (the distance from the middle point of equilibrium). This is why on large ships, the weight of one person moving from one side to the other has no effect on the transverse stability; but adding a shipping container to one side may cause it to list. In order for balance to be achieved, the weight on one side must equal the weight on the other side; or in other terms, the sum of *moments* on one side must be equal to the sum of moments on the other side. 

>moments of force = weight x distance

## Density (ρ), Mass and Volume
#density #mass #volume
We know that two objects can have the same mass but take up different volumes (1 tonne of feathers vs 1 tonne of bricks); this is due to their densities being different. Thus, it can be said that mass, volume and density all have a relationship to one another. [Density](https://en.wikipedia.org/wiki/Density) is a representation of mass per unit volume, which comes more into play when discussing sinkage/rise and draft, or how much cargo may be loaded within a specific space (like oil which is less dense than water, or iron ore which is a very dense cargo). 

>mass = density x volume
>volume = mass / density
>density = mass / volume

## Displacement △
#displacement #density #volume
displacement is defined as the number of tonnes of water it displaces, and is sometimes referred to as the *volume of displacement*. The volume of the ship's underwater space could be found by multiplying the length by the breadth and draft; however this will not give a true representation of the volume of displacement because the *density of the water* has not been accounted for. Because the *relative density* of fresh water is 1.000 t/m3, the volume of displacement is as straightforward as L x B x D, because these values would be multiplied by 1 and nothing would change about the equation. When the *relative density* or [*specific gravity*](https://en.wikipedia.org/wiki/Relative_density) (sometimes referred to as SG) is not equal to 1, the volume of the ship must be multiplied by that number in order to find the volume of displacement. The *relative density* of seawater is 1.025 t/m3, so the **seawater displacement** of a vessel is equal to the L x B x D x 1.025. If the displacement in an area not purely sea or fresh (such as a harbour or estuary), then the formula for displacement is L x B x D x ρ, which is usually referred to as *dock water density*.

>△sw = L x B x D x 1.025
>△fw = L x B x D x 1.000
>△dw = L x B x D x ρ

## Loadlines and Draft
#draft #loadlines #plimsoll #class
Draft and loadlines are hopefully not new concepts by this time. The [plimsoll line](https://en.wikipedia.org/wiki/Load_line_(watercraft)), which is the foundation of all loading lines, came into practice in 1870 to regulate the amount of cargo which can be safely loaded onboard ships to maintain stability. In the modern era, the plimsoll line is representative of a vessel's verifiable safety, as in order to receive the welded mark on the side of the vessel from a classification society (such as Lloyds Register, or the American Bureau) she must first pass a number of criteria set out by them. 

Safety is increased by ensuring;
- hull integrity in inclement sea conditions
- watertight/weathertight integrity of openings 
- minimum freeboard to retain reserve buoyancy
- water sheds off the deck
- vessel will not be unknowingly overloaded
- adequate stability and strength for all loading conditions
- crew are safe and protected when working on deck
- that modifications to the ship do not compromise the vessel

![plimsoll and loadline example with distances labelled]()

The loadlines give a representation of acceptable draft for the vessel on an even-keel. It is important to remember that the greater the draft is; the more of the ship is submerged underwater. The implications of this are that when a vessel rises, draft is subtracted; and inversely when it sinks, draft is added. Because saltwater is more dense than fresh water, a ship will float higher in saltwater than it would in fresh water, which means that the draft will decrease when entering salt water from fresh, or increase when moving from fresh to salt water.
Because changes in water density allow the ship to rise or sink more than it would normally, there are multiple lines to indicate how much of the ship may be submerged at one time, depending on the part of the world where it is operating. The plimsoll line acts as the established baseline, where the S loadline, 'summer loadline' or 'saltwater loadline' is marked. If the ship was submerged perfectly to her summer loadline, as she travels to different areas of the world she would either rise or sink to the other markings appropriately. At a height of 1/48th *above* the summer draft is the **T loadline** or 'tropical loadline', which is where the ship would *sink up to* in tropical waters. At a height of △/4TPC ([[#^tpc]]) *above* the summer draft is the **F loadline** or 'freshwater loadline', which is where the ship *sinks up to* in fresh water. at 1/48th of the summer draft *above* the F loadline is the **TF loadline** or 'tropical fresh loadline'. The TF loadline is the deepest the vessel may sink to (excluding timber loadlines, which I will not be elaborating on). Moving back down to the S line, at 1/48th the summer draft *below* the summer loadline is the **W loadline** or 'winter loadline', representing where a ship would *rise to* in winter waters. Further below the winter loadline, but only on vessels which are *under 100 meters in length*, is the WNA loadline or 'winter north atlantic line', located 50mm *below* the W lines

To touch back upon draft, we also will sometimes see the term 'statutory freeboard' used; this term is the opposite of draft and represents the amount of the ship from the draft to the upper deck which is not submerged. Freeboard is the opposite of draft, and generally represents the amount of reserve buoyancy that a vessel has. Loadlines are measured from midships, but there are times where only the forward and aft drafts are given; in these cases it is necessary to take the mean average between the drafts by adding both together and dividing by 2. The mean draft is different from the midship draft, which will be elaborated on at a later time, but ultimately the difference between the mean and actual midship drafts will determine whether the vessel is hogged or sagged. 

>[!info] the inverse relationship between the rise/sinkage of the vessel and decrease/increase of draft should always be kept in mind
>vessel rises = draft decreases
>vessel sinks = draft increases
>FW to SW = vessel rises
>SW to FW = vessel sinks
## Ship Shapes
#boxshape #WPA 
As ideal as it would be, mathematically, for ships to be rectangular shaped objects- we know that this is very rarely the case. Barges are the quintessential 'box-shaped vessel', but there are also other cases where this is true. Box-shaped vessels are easy to deal with as their water-plane area is as simple as length times breadth (WPA is a measure of the area of the ship for 1cm of immersion at the waterline). WPA for normal ship shapes is discussed later, alongside [[#Simpson's Rules]]. For now, we will use the given WPA value, as opposed to calculating it ourselves outside of for box-shaped vessels.

![new draft/old draft = old density/new density formula]()
## Tonnes Per Centimetre Immersion (TPC)
#sinkage #rise #TPC 
The measure of how much a vessel will sink when weight has been added or removed is referred to as *tonnes per centimetre immersion* or TPC. TPC is a measure of how much the draft will change by 1cm per tonnes of cargo loaded or discharged *in a specific density of water*. If the TPC was 30, then that would mean that it would take 30 tonnes of cargo to change the vessel's draft by 1cm. Because TPC uses the WPA to calculate sinkage or rise, box-shaped vessels will have a constant WPA, whereas standard-shaped vessels will have different TPC values depending on the WPA being measured. To describe the increase or decrease of draft, we use the words sinkage or rise in accordance. When TPC is given without specifying the density, we always assume it is the TPC for seawater (TPCsw). Because the density of water in the harbour is rarely pure sea or pure fresh water, for the highest degree of accuracy we want to convert it to TPCdw using the differences in the density. The formulas for TPC are below the following example.

*A vessel with a draft of 8.00m loads 375 tonnes of cargo. If the TPC is 21.0 and cargo is being loaded (therefore sinking the ship), we would take the weight of the cargo and divide it by the TPC to determine sinkage in centimetres. In this example, the vessel's sinkage is 17.85cm, or approximately 0.18m, increasing the draft to 8.18m.
If a vessel with a draft of 6.50 discharged 456.3 tonnes of cargo and had a TPC of 20.8, what would happen to the draft? Because we know that discharging weight will cause the ship to rise, we would divide the weight of the cargo by the TPC to discover that the rise is 21.93cm, or approximately 0.22m. The draft after discharge would then be 6.28m*

With TPC, we normally divide the cargo weight by the TPC to find the sinkage/rise factor; but in cases where there is already a desired sinkage or rise (a specific draft which we want to achieve), you would multiply that allowance by the TPC value to find the required tonnage.

>TPC = (density of water x WPA) / 100
>TPCdw = (TPCsw x dock density) / 1025 <- we remove the decimal completely from the density value when using this formula to convert from TPCsw to TPCdw.

## Fresh Water Allowance / Dock Water Allowance
#FWA #DWA 
Because the density of fresh water and dock water causes the ship to sink deeper in these waters, we can account for this sinkage using *fresh or dock water allowance*, allowing the ship to achieve a desired draft when in salt water. DWA/FWA tend to work together with TPC when a vessel is dealing with cargo, because the DWA/FWA value will change the sinkage/rise possible and will allow more cargo to be loaded or discharged from the ship! DWA/FWA can also be used to determine the change of draft when moving between densities of water.

>FWAmm = △/4TPC <- you can obtain a FWA in centimetres by dividing by 40TPC if desired.
>DWA = (FWA x (1025 - density)) / 25 <- whether the DWA is in millimetres or centimetres will depend on which value the FWA uses. For this formula, we remove the decimal from the density values used.
***
## Transverse Stability (MGBK)
#stiffness #tenderness #GM #GZ #heeling #hamburgerstyle 
[Stability](https://en.wikipedia.org/wiki/Ship_stability) can be defined as the ability of a vessel to return to the upright position after being disturbed my some external force, such as wind or waves. A good and stable vessel is able to withstand not only the effect of wind and waves heeling her over, but will also return to the upright position after tilting during a steep turn. We are not as concerned with longitudinal stability as we are with transverse stability, because as stated earlier the width of the vessel is never as great as the length of the vessel; ships are also designed to handle fore/aft movement and the pounding of waves head-on, so it can be said that taking force on the side is not what the ship is specifically designed to do. Transverse stability is of the utmost importance onboard.

![diagram showing MGBK in a stable state and heeled state]()

We know that the force of buoyancy acts vertically upward through the geometric center of the ship (also known as the *centroid* of the underwater volume). The center of buoyancy 'B' changes with the amount of the ship submerged (draft), and is typically about half of the ships draft. 'B' is an upward force working towards the ship's *metacenter* 'M', which is initially on the centerline of the vessel. BM is referred to as the *metacentric radius*.
The measure from the keel 'K' which is always known and does not change, to the center of buoyancy is referred to as the 'KB'. The movement of the keel is always relative to the vessel, while gravity and buoyancy are larger forces which do not adhere to the limitations of the vessel.

For a ship to float, the force of buoyancy must be equal and opposite to the force of gravity, 'G'. Gravity works vertically downwards, and when a vessel is in the upright position it can be said that GB are in alignment. When tilted over, G and B will form parallel coupled lines, which in turn forms the *righting lever*, 'GZ', where 'Z' is the horizontal arm formed from G to a point on the vertical BM line. If you were to draw lines connecting GZM, they would form a right angled triangle, angled 90 degrees at the point of Z. The tendency of the righting lever to return the vessel to the upright position is known as the *righting moment* or **moment of statical stability**. Because the metacenter M forms the pivot point for the GZ lever, then the GM or [*metacentric height*](https://en.wikipedia.org/wiki/Metacentric_height) dictates the strength of the righting lever GZ; a large GM distance will create a large GZ lever, and a small GM distance will create a proportionately smaller GZ lever.

![diagram showing the GZ lever]()

>righting moment = △ x GZ
>
>(for small angles of heel 12 degrees or less) GZ = GM x Sinθ
>(for angles of heel larger than 12 degrees) GZ = KN - KGSinθ 
>*+we will discuss the KN and KG values used for larger angles of heel at a later time

The ability of the righting lever is entirely dependant on how the forces of MG are aligned. If **M is above G**, then the vessel is said to be in **stable equilibrium** and will create a righting lever as G and B attempt to achieve realignment. If **M and G** coincide (are beside one another), then the vessel is said to be in **neutral equilibrium**. When in a state of neutral equilibrium, there will be no GZ lever because GZM is 0, and thus when inclined over the vessel will remain in that inclined state because there are no forces (GZ) forcing it to an upright state. Last and worst of all, is if **G is above M**, which is the state of **unstable equilibrium**. If forced to incline in an unstable state, the vessel will continue to move away from the inclining force even after it has been removed. Rather than having a GZ lever, it can be thought of as having a ZG lever which works counterintuitively as the G and M vertical arms seek realignment with each other (which is ultimately the state of neutral equilibrium). When the vessel achieves neutral equilibrium from a state of unstable equilibrium, the angle at which the vessel settles is known as the [*angle of loll*](https://en.wikipedia.org/wiki/Angle_of_loll). If the vessel heels to an angle greater than 40 degrees it will capsize.

![diagram showing states of equilibrium as totems]()
![diagram demonstrating the righting action for each state of equilibrium]()

>        states of equilibrium
    M                                            G
    G                   MG                    M
    B                      B                     B
    K                      K                     K
>  stable             neutral            unstable

>Tanθ (θ = angle of loll) = √(2GM / BM)
>GM at angle of loll = 2 x GM*initial* x (1/Cosθ) (θ = angle of heel)

The forces of gravity and buoyancy work vertically regardless of the ship's position; whereas the keel may shift out of alignment and thus will always be a reference point relative to the vessel itself (see [[#About 'K']]). Because the ship is a 3D body, there are 3 measures by which 'G' can act; vertically (VCG, which is equivalent to 'KG', discussed in [[#Vertical Movement of 'G']]), transversely (TCG, for a port/starboard shift of G, discussed in [[#Listing]]), or longitudinally (LCG, for a fore/aft shift of G attributed to trim, which is discussed at a later time in [[#Longitudinal Stability / Trim]]). 

In terms of transverse movement, we have both [[#^heel]] (describing external and temporary inclining forces like wind) and [[#^list]] (describing internal inclining force where corrective action must be taken, like shifting cargo). When the vessel heels, as long as it is in stable equilibrium the righting lever will create a righting moment and return the vessel upright.
## About 'K'
#KG #KB #KM #GM #BM
If we were to observe the vertically aligned forces of MGBK, we would see that because K is the lowest point if we were to measure various values from K, we are able to use those values to isolate other distances between points. One of the most common uses is using KM and KG (VCG) to isolate and determine the GM.

>KM - KG = GM
>KM - KB = BM
>KB + BM = KM

>KB = 1/2 D (box shaped vessels)
>KB = (total moments taken about the keel) / (total volume of △) 
>*+KB for ship-shapes is discussed much later after learning [[#Simpson's Rules]]*

![diagram demonstrating MGBK totem with KB/KG/KM]()

Because KB and BM are relatively easy values to obtain, we can use those to find the KM, which in turn can be used with the VCG (found by accounting for the [[#Vertical Movement of 'G']] after shifting, loading, or discharging cargo) to isolate the GM.

>BM = B^2 / (12 x D) (*used for box shaped vessels*)
>BM = (L x B^3) / (12 x △)
>BM = I / V  *or* BM = (inertia of the waterplane) / (volume of displacement)
>*+for BM = I/V typically the value I is given in the question and hints towards using this BM formula over the others. the BM formula used depends on the information given in a particular question and whether the vessel is box-shaped or ship-shaped.

As mentioned briefly in [[#Transverse Stability (MGBK)]], the value KN is used to determine GZ with large angles of heel. KN is the horizontal line drawn between K and the vertical arm of B, joining into a right-angled triangle of KNB. KN is a value that is pulled from the ship's stability booklet using the angle of heel/list and is then used to determine GZ.

![diagram demonstrating KNB angle]()
## Vertical Movement of 'G'
#GM #GZ  #GG1
When weight is added, discharged, or shifted, then G will move in the same direction as the cargo. The shift of G from it's initial position to a new position is referred to as the G-G1. If cargo was added to the vessel, the GG1 would increase and thus the KG would *decrease*, *increasing* the GM. If cargo was discharged, then GG1 would decrease and thus KG would *increase*, *shrinking* the GM. With the shifting of cargo, it could go either way depending on the direction that cargo is shifted, but the key takeaway for the shift of cargo is that the displacement *will not change*.

>[!info] used for the shifting of cargo only
>GG1 = (w x d) / △ or... *GG1 = weight of cargo x distance of cargo (VCG) / displacement*
>GG1 is either added to or subtracted from the KG depending on where the cargo was shifted, keeping in mind that G1 *always shifts towards the direction cargo was moved*

![diagram and examples showing the shift of G]()

>[!info] used for the loss or gain of cargo only
>
>force (*weight*) x distance = moments
>Final KG = total moments / total weight (*also called total △*)
>KM - KG*final* = GM*final*

![diagram and example showing adding of cargo using moments table]()
![diagram and example showing loss of cargo using moments table]()

We use a different formula for the addition and loss of cargo than for the shift due to the fact that displacement changes. Using these formulas to create a moments table is much more straightforward than using other formulas which exist, and the force x distance = moments formula is a reoccurring formula used with various different values for many different stability calculations. We are also able to work backwards using these known formulas to achieve a specified GM, for example, using algebra to find an amount of weight to be loaded to achieve a set GM.

![example of solving for weight when given a desired GM]()

When a weight is suspended or lifted on the deck, rather than regarding the movement of G as being relative to the cargo suspended, it instead is regarded as having shifted to the *end of the lifting arm*. If a davit on deck was used to lift a shipping container, we would regard the KG as being measured from the keel to the end of the davit arm. 

The changes to VCG (KG) will impact the GZ lever by changing GM. As the KG *increases*, the GZ lever *shrinks* because GM has decreased; and when KG *decreases*, the GZ lever *increases* because GM has increased. The loss of increase of GZ can be found using the formula;

>Gx = GG1 x Sinθ
>*+Gx is ultimately accounting for the vertical shift of Z
>*+*this formula is not as important or reoccurring as the other formulas given in this section*
## Listing
#GZ #GM #GGh
Until now, we have only considered the vertical movement of G and how it affects KG and thus GM; now we will consider the *horizontal movement*, referred to as G-Gh, and how the offcentering of cargo creates inclination through [[#^list]]. Using the same principles as vertical shift of G, we also reuse the formula for the shift of cargo; GGh = (w x d) / △. This is because when accounting for the effects of list, we still calculate the vertical shift of cargo, and *then* account for the horizontal shift. Using the values found (GGh from horizontal movement, and new GM from vertical movement) we can then solve for the angle of list using the formula GGh / GM = Tanθ (θ= angle of list)

>[!info] formulas for list
>GGh = (w x d) / △ or... *GGh = weight of cargo x distance (TCG) / displacement*
>GGh / GM = Tanθ
>Tanθ = inverse Tanθ (to receive an angular value)

The work order for list problems is...
1. calculate GGv (where the value of 'd' for distance is the VCG) (I like to write GG1 as GGv to specify the vertical component here)
2. apply GGv to the GM*initial* to find GM*new* (this can also be done using final KG = total moments/total weight and then using KM - KG*final* = GM*new*)
3. calculate GGh (where the value of 'd' for distance is the TCG) (for total moments, since port and starboard are opposite motions, we take the sum of the opposing movement and whatever is left over dictates the direction that the list will occur)
4. calculate the resultant list using GGh / GM*final* = Tanθ

![example of list problem using shift of cargo]()
![example of list problem with added cargo]()
![example of list problem with lost cargo]()

Like with vertical movement of G, we can also solve for the addition or loss of cargo using the force x distance = moments table. Rather than finding the final FG this way, we are instead finding the overall GGh using port/starboard moments, which can be a useful way of working with multiple instances of cargo loss and gain.

![example of list problem with loss and addition of cargo using moments table]()

We are also able to reverse this process and work backwards, and using a given angle of list we are able to use algebra in order to find the appropriate amount of weight (for example, ballast to take on) in order to correct the effects of list.

![example of solving for weight given an angle of list]()

Due to the nature of list, there are times where draft on one side of the vessel will increase as a result of the angle of list. Because the keel is often not completely flat, we must use the value *rise of floor* to account for the distance between the actual keel and the base of one side of the vessel. When there is no rise of floor (the keel is flat), just the old draft is used.

![example of list increase due to draft and how the formula works]()

>new draft due to list = 0.5Breadth x Sinθ + (old draft - rise of floor) x Cosθ (θ = angle of list)
## Free Surface Effect and Correction
#FSC #FSM #GG1
Free surface effect is the pendulum-like force of a liquid left to freely move back and forth across a deck or compartment. Free surface effect causes a *virtual* loss of GM and thus impacts stability; therefore it is one of the most worrisome and detrimental effects to account for onboard because it is a dynamic condition and can be difficult to deal with suddenly. Free surface effect can occur for many reasons, such as...
- tanks that are not empty or full to the top (partially filled tanks are referred to as slack tanks)
- ingress of water on deck due to heavy weather 
- internal water piping such as a fire main bursting within a compartment, flooding it
- flooding as a result of damage
Vessels with large open compartments, such as ro-ro ferries and bulk cargo carriers can experience an extreme free surface effect if their large cargo compartments experience water ingress. Vessels or cargo tanks built specially for the purpose of carrying liquids are subdivided in order to reduce the free surface effect; just adding 1 subdivision is capable of reducing free surface effect by 1/4. During the construction process, free surface effects and corrections are accounted for by the architect; however it is still necessary to understand how to determine and apply free surface effect (FSE) and correction (FSC) from a watchkeeping standpoint.

>FSC = ((L x B^3) / (12 x △*new*)) x ρ (density of the liquid)
>FSC = Free Surface Moments / △*new* (after weight of liquid has been accounted for)
>GM - FSC (always subtracted from GM) = GM*fluid* 

As with listing, the work order for free surface problems can also be broken down into steps. The following steps are the work order for a problem in which, for example, a fire main has broken in a compartment and added weight, causing a list on one side of the vessel...
1. calculate the weight of the added liquid (using density x volume = mass)
2. calculate the GGv due to the added weight (ultimately finding the new GM or *GMsolid*)
3. calculate the FSC (taking care to use △*final* including liquid weight)
4. subtract FSC from GM*solid* to find GM*fluid*
5. calculate horizontal movement, GGh
6. solve the angle of list using GGh / GM*fluid* = Tanθ
A key takeaway is that FSE only effects vertical GM and is accounted for when solving the vertical 'portion' of listing questions. If given in the form of moments, the free surface moments can be incorporated into the force x distance = moments table for both transverse and vertical movement, condensing the calculation workspace. 

![example of FSE questions]()
![example of FSM calculations solved using values given via stability booklet]()

Free surface moments (FSM) are given in the stability booklets and are sometimes referred to as *intertia moment*. The Gypsum Centennial stability booklet used in SCS4 has a section on free surface calculations and *includes an example of how to calculate free surface corrections* as is legally required. 
## Hydrostatic Tables and Stability Books
#GZ
When a vessel is first constructed, the naval architect will consider the nature of work the vessel will be conducting and the states that it will be operating in. Using these considerations, hydrostatic data will be calculated in various states and is published in the vessel's specific stability booklet in the *hydrostatic tables*. In SCS4, the 'M/V Gypsum Centennial' and 'M/V Sept-iles' stability books are used for examinations and practice reading hydrostatic data. 

One of the most significant pieces of information found in the hydrostatic tables is the *curve of statical stability*. This curved diagram gives key information such as...
- initial GM
- maximum GZ and where it occurs
- angle of *DEI* deck edge immersion/angle of downflooding, which is the point at which the vessel is so severely inclined that the deck's edge touches the water and flooding into the vessel occurs
- the [angle of vanishing stability](https://en.wikipedia.org/wiki/Limit_of_positive_stability), beyond which the vessel will capsize and flip over keel-up
- entire range of stability for the vessel
- area under the curve, or *area of dynamical stability*

![diagram showing the curve of statical stability labelled to show information which can be derived]()

>[!info] Regulatory Minimums for Ship Stability as per International Loadline Convention
>Minimum Initial GM: 0.15 meters
>Minimum Area under Curve up to 30 degrees of heel: 0.055 meter-radians
>Minimum Area under Curve up to 40 degrees of heel: 0.09 meter-radians
>*this information will appear in the stability booklet as it is legally required to

***
## Summary of Transverse Stability
#summary
Transverse stability is the most important plane of stability relevant to the ship's safety because the ship is never as broad as it is long. The metacentric height (GM) determines the safety (and therefore seaworthiness) of a vessel by determining the uprighting potential of the vessel against heeling factors (such as wind, waves, or heel that occurs as the vessel turns). The GM and righting potential of the ship is regulated and vessels must comply with minimum standards across the industry (often varying depending on the type of vessel), ensuring that loading operations never compromise the GM to endanger the vessel and crew.

***
## Longitudinal Stability / Trim
#trim #hotdogstyle
Longitudinal stability focuses on trim, the difference between the fore and aft drafts. Most vessels are often trimmed by the stern as opposed to by the head in order to increase their propellor immersion and thus their propulsion/manoeuvrability. Ships will have a forward and after draft marking, as well as a marking at amidships. The importance of the midship marking is determining a vessel's hog or sag (also called *distortion*) by comparing the actual midship draft reading to the mean draft obtained by taking the average between the fore and aft drafts. Of note as well is that drafts are not at the extreme far ends of the vessel due to the nature of construction (coming into play with conversion tables given in the hydrostatic tables). When looking at a vessel longitudinally, the extreme length of the ship (LOA or *length overall*) is rarely used for calculations, and instead the length between perpendiculars (LBP) is used. The perpendiculars of the ship measure from an invisible vertical line passing through the rudder post on the aft end, to the curve of the stem on the forward end. Midships is considered to be the point exactly in the middle of the perpendiculars (half of the LBP); but the ship also does not necessarily pivot at the midships and actually pivots at the *longitudinal centre of floatation* or LCF, which can be forward (sometimes referred to as *FOAM*S), aft (sometimes referred to as *AOAMS*) or directly on the midship line. The LCF changes position depending on the cargo load and is obtained from the hydrostatic tables. Because the ship pivots at the LCF, which is not always on the midship line, then this also means that the most accurate measure of draft (TMD or true mean draft) is the draft obtained at the LCF. The TMD is obtained by applying a correction to the mean draft. The *layer correction* is the difference between drafts (trim) multiplied with the distance of the LCF from midships, and this value is divided by the length between perpendiculars. These formulas are expressed below;

>True Mean Draft = mean draft + layer correction
>Layer correction = ((aft draft - fwd draft) x LCF)/length between perpendiculars
>*+if the LCF is foams, we express that distance with a negative value. if the LCF is aoams, we express that distance as a positive value. This ensures that we obtain a positive or negative layer correction, which can always be added directly to the mean draft in order to obtain the appropriate TMD relative to the LCF position.*

![diagram demonstrating how to obtain TMD]()
The draft readings taken from the hydrostatic tables are always the true mean draft at the LCF.

Just like with transverse stability, there is also a longitudinal centre of gravity (LCG) and longitudinal centre of buoyancy (LCB). The relationship between the LCB and LCG forms, similarly to the GZ righting arm, the *GB trimming lever*, which is used at a later point to calculate the shift of the LCG or LCB after weight has changed onboard. We know that gravity always moves vertically downwards and buoyancy vertically upwards; so when the LCG is aft of the LCB this indicates that the vessel is trimmed by the stern (the stern is under downwards force). If the LCG was forward of the LCB then the vessel would be trimmed by the head, and if the LCG and LCB were in the same spot then the *ship would be on an even keel*. 
The amount of weight which would have to be added, removed, or shifted onboard in order to change the overall trim of the vessel is expressed as *moment to change trim* or MCTC (moment to change trim by 1 centimetre) in a way similar to TPC. The MCTC is taken from the hydrostatic tables at a certain draft or displacement, but can also be obtained with the formula;

>MCTC = (weight x GM*longitudinal*) / 100 x Length

The big takeaway of longitudinal stability is that there is a lot more stability leeway in the shifting of weights onboard due to the construction of the vessel and nature of cargo shipping. It is necessary to balance the overall weight between the forward and aft ends of the vessel to reduce stresses on the ship (which can lead to distortion and breaking), and because of these reasons the vessel has a number of ballasting and cargo tanks over the length which allow weight to be loaded in different locations. For example, the gypsum centennial has 4 main cargo tanks (2 foams and 2 aoams) and a large number of tanks (such as the aft peak tank on the far stern and the forepeak tank on the far bow), which all have their own individual longitudinal centres of gravity and thus allow many different adjustments to trim and draft. Longitudinal stability is the same as transverse stability in the sense that it ultimately revolves around the balancing of forces on both ends of a scale.
## Change of Draft / Change of Trim
#hogging #sagging #CoD #CoT #trim
We know now that the vessel pivots at the LCF as weight is added or moved (expressed through the MCTC value). If the draft was to change at one end due to the overall change of trim, then it would naturally follow that if the aft draft was to increase, *then the forward draft would decrease proportionately* on the opposite end. Change of draft can be determined through multiple means. From a practical standpoint, the hydrostatic tables will contain a trimming table for a value of weight (such as 100 tonnes), and using the trim tables in accordance with small values of weight added or removed (typically around or under 1000 tonnes for a large ship like the Gypsum Centennial), we can easily obtain the changes to the forward and aft draft by following the steps given in the stability tables. 
With larger weights added or removed to a single tank onboard, we can determine the change of trim by factoring the weight and LCG of the tank over the MCTC, yielding a net change of trim which can then be broken down into a change of draft forward and aft using the LCF. Using this method, we must also factor in the sinkage or rise using the TPC, which we add or subtract from the overall change of draft to the original forward and aft drafts.

>[!info] change of draft when weight is added or removed from one tank
>Change of Trim (COT) in cms = ( weight x (distance of the tank's LCG to the LCF) ) / MCTC
>Change of Draft aft (CoDa) in cms = ( COT x (distance from the aft perpendicular to the LCF) ) / LBP
>Change of Draft forward (CoDf) in cms = COT - CoDa

The working order for this type of question is as follows;
1. note the vessel's LBP, initial forward and aft drafts, the location of the LCF, the MCTC, the TPC, and the LCG of the tank where cargo is being loaded/unloaded
2. determine the change of trim using; w x distance of the tank to the LCF / MCTC
3. determine the overall sinkage or rise by dividing the cargo weight by the TPC
4. determine the change of draft aft by multiplying the weight by the half of the LBP plus or minus the LCF (the distance from the aft perpendicular to the LCF), and then dividing this value by the entire LBP
5. find the change of draft forward by subtracting the change of draft aft from the total change of trim
6. now that we have the changes of draft forward and aft and the sinkage, we change these values from centimetres into meters, and then add or subtract these values accordingly to the initial drafts (if a tank forward is loaded, the forward end would sink deeper while the aft end rises, so the CoDf would be added while the CoDa would be subtracted)

![example question using the COT+sinkage method]()

In the case where multiple weights are loaded and discharged all at once, we can solve by taking a measure of trimming moments (exactly the same as how we used moments to solve multiple weight problems for transverse stability). The formula total moments / total weight can be used to give us a final LCG and final △. Because multiple tanks are being loaded, we can factor in their LCG by multiplying the weight added or lost by the LCG to get a longitudinal moment, the total sum of which is used to determine the final LCG. The change of trim can found in this case by multiplying the trimming lever GB by the final △ to obtain a *trimming moment*, which is then divided by the MCTC to find the COT. Using this method (trimming moments), we do not have to factor in the sinkage or rise because the new displacement is found and then used to find the new mean draft, MCTC, LCF and LCB. 

>[!info] solving COD using trimming moments
>LCG - LCB = GB
>*the GB is just the difference between the LCG and LCB, so the value should always be absolute. To determine whether the LCG is aft or forward of the LCB to find the overall trim after weight is added, the final LCF, LCG and LCB should be plotted on a basic diagram for reference.*
>GB x △*final* = trimming moment
>COT (cm) = trimming moment / MCTC
>CoDa (cm) = COT x distance from the AP to the LCF / LBP
>CODf = COT - CoDa

The work order for a problem like this is as follows;
1. determine the initial: draft forward, draft aft, mean draft, original △ and LCG
2. note the weights lost or added and their individual LCGs
3. using w x d (LCG) = moments, make a graph of the total weight and total longitudinal moments
4. take the sum longitudinal moments and divide by the sum weight (△*final*) to find the final LCG
5. now that the △*final* is known, use the hydrostatic tables to find the new mean draft, MCTC, LCF and LCB (interpolating between values where necessary)
6. plot a basic diagram where the LCF is noted and the position of the LCB and LCG are noted to determine whether the vessel is trimmed by the head or stern (or at all)
7. use the difference between the LCG and LCB to find the GB trimming lever
8. the GB is then multiplied by △*final* to find the trimming moments
9. take the trimming moments and divide by the MCTC to find the COT
10. determine the change of draft aft by multiplying the COT by the distance from the AP to the LCF, then dividing by the LBP
11. find the change of draft forward by subtracting the CoDa from the COT
12. now that the COD aft and forward are known, they can be converted into meters and then added or subtracted accordingly from the new mean draft (this is why the trim must be determined so that logic can be used to know on which end the COD is added and which is subtracted)

![example of trimming moments problem]()

Because trimming moments uses the same total moments / total weight equation that is used to determine VCG, FSC and GGh; we can actually combine all these degrees of motion into one huge table to solve for all these values at once (using FSM, vertical moments, transverse moments, and longitudinal moments). This is a lot of work and can be really tedious! But ultimately this is as complex as the calculations tend to get. Because these sort of problems take so much work, it is really important to label calculations and tables clearly. When learning how to work through these large moments problems, it can be beneficial at the start to break it down into steps, note which information has to be taken from the hydrostatic tables (draft, displacement, MCTC, LCF, LCB and KMt), and note which formulas will be used for calculation.

![example of large trimming moments problem]()
## Simpson's Rules
#LCF #KB #WPA
[Simpson's rules](https://en.wikipedia.org/wiki/Simpson%27s_rules_(ship_stability)) are a set of mathematical rules used in ship stability and naval architecture to find the area of an irregular shape represented as a curved area subdivided by ordinates (number of partitions within the curve). Simpson's rules for ship stability differ slightly from the standard Simpson's rules by adding a third rule used to find a specific area when given three consecutive ordinates. Simpson's rules are used to determine the waterplane area or volume of irregularly shaped hulls, the area under the righting arm curve (for application in dynamic stability). They can also be applied to find the KB and the LCF depending on the perspective of the ship.

>Simpson's First Rule (1-4-1 rule) is used to find an area when there is an odd number of ordinates (such as 3, 5, 7, etc..).
>h = the equal spacing between ordinates
>x y z = represent different ordinate values
>area = h/3 x (1x + 4y + 1z)
>*in the case where more than 3 ordinates are present, the formula loops in a pattern of 1-4-2-4-2-4-1, always starting and ending with 1. The reason for this is represented more easily through a drawn diagram.

![simpsons first rule diagram]()

>Simpson's Second Rule (1-3-3-1 rule) used to find an area when the number or ordinates - 1 is divisible by 3 (such as 4, 7, 10, etc)
>h = the equal spacing between ordinates
>w x y z = represent different ordinate values
>area = 3h/8 x (1w + 3x + 3y + 1z)
>*this rule loops in a pattern of 1-3-3-2-3-3-1, always starting and ending with 1. The reason it loops this way is the same as with the first rule.

![simpson's second rule diagram]()

>Simpson's Third Rule (5-8-1 rule) is used to find one area between ordinates when given 3 consecutive ordinates
>h = the equal spacing between ordinates
>x y z = represent different ordinate values
>area between y and z = h/12 x (5x + 8y - 1z)
>area between x and y = h/12 x (5z + 8y - 1x)\

![simpson's third rule diagram]()
## Bilging and Permeability
#bilging #permeability #draft #stowage
Permeability as a percentage is a measure of the amount of water that is able to fill a compartment with other equipment occupying the space of that compartment. An example of this is that the engine room typically has anywhere from 85% to 95% permeability, due to the engine and machinery taking up *volume within that space*. Therefore, it can be said that;

>permeability % (the decimal answer being multiplied by 100 to obtain a percentage) = (compartment total volume - cargo volume) / total compartment volume

Permeability is a factor into bilging, which is when an underwater space is flooded due to puncturing of the hull. With bilging, the centre of buoyancy (centroid of the underwater volume) moves *but the centre of gravity does not* because weight has not necessarily been added on. In this case, the volume of lost buoyancy is equal to the volume of compensating buoyancy.

>new draft due to bilging = compartment volume "the flooded space" / (ship WPA - compartment WPA) "intact waterplane area"

## Pressure and Thrust
#pressure #thrust #maxheight
Water pressure increase uniformly with depth, because hydrostatic pressure at any depth is due to the weight of the water above the point in question. Therefore, pressure depends on water density and depth. The force of thrust on an area is equal to pressure multiplied by that area. A typical example of thrust and pressure applied to shipping work would be using a maximum pressure with a density of cargo to determine a maximum allowable height that the cargo in question can be loaded.

>pressure = ρ (density) x depth
>thrust = pressure x area
>allowable height (when density is known) = maximum pressure / ρ
>allowable height (when stowage factor is known) = maximum pressure x stowage factor
>*+stowage factor and density have an inverse relationship*

## Shearing Force and Bending Moments
#shearing #bending #stresses
Ships are designed and built to withstand the many forces to which they may be subjected over the course of their service. Of particular note is [[#^shearing]] force, which is caused when one compartment is loaded differently than the adjacent compartment, which creates an uneven distribution of both *weight and buoyancy* putting opposite forces onto such compartments. Stresses can be divided into static force (constant and unchanging force) which constitutes loaded weight (G) and hydrostatic pressure (B), and dynamic force (changing all the time) which constitutes motion like waves and wind and other mostly meteorological applied force.

In the ship's stability booklet, *shearing force* and *bending moments* are calculated for the many standardized conditions expected during operation. Shearing force is the sum of the loads acting to the left or right of the position in question, while bending moments are a measure of the total moments tending to alter its shape, and is equal to the algebraic sum of the moments of all loads acting between the concerning sections. In simpler terms, shearing force is the sum of weight times buoyancy over the length of a vessel; while bending moments are the product of shearing force multiplied by distance over the length of the vessel. Shear force tends to be a sharp and angular graph, while bending moments are more curved. A peak and then dip in shearing force tends to indicate hogging, while a dip and then peak will indicate sag; but this varies case-by case.

[diagrams of shearing force from notes]()

***

## Ship Construction
#construction #diagrams 
By now, we would hope to have a good general idea of how a ship is constructed and the terminology used to express certain parts of the ship. The ship is subject to all manner of forces, so it must naturally be constructed in such a way as to minimize the damages that these forces can inflict, thus preserving the watertight integrity of the vessel. Different ships are constructed in different ways; a fishing vessel looks different than a container ship because it is built in a different way to accommodate the nature of its work.

## Ship Stresses
#stresses
The ship as a body in water is able to move in 3 planes with 6 general degrees of motion; yawing and heaving, surging and rolling, and pitching and swaying. These degrees of motion combined with the construction of the vessel and force of the loads the vessel are subject to will produce a number of structural stresses in all conditions. When a load is applied, *stress* is created on the area where the load is distributed. Prolonged stresses to an area will eventually cause *deformation* or *strain*, which is the permanent warping of an area due to stress and which if left unchecked will eventually lead to breakage of the area (such as 'back breaking' when hogging stress eventually leads the keel to snap in half). Compressive stress is the result of forces pressing an area tightly together (in a squeezing manner); while tension is the result of forces pulling an area in opposite directions (in a stretching manner). Due to the nature of vessel construction, various forces will compress the upper deck while tensing the keel or vice versa. Some of the stresses that uneven loading will produce are;

- Sagging - a vessel that is heavier at the midship than the fore and aft end is subject to sagging, which will produce *compression* on the upper deck and *tension* on the keel. This is a type of longitudinal stress. Despite even loading, a long vessel will still be subject to temporary dynamic sagging stress as waves pass and the crests of waves support each end, while the midship lay in the trough unsupported.
- Hogging - a vessel that is lighter at the midship than at the fore or aft end is said to be hogging, which produces *compression* on the keel and *tension* on the upper deck. Hogging is a stress like a "cat arching its back". This is a type of longitudinal stress. Despite even loading, a long vessel will be subject to dynamic hogging stress as the midship section becomes supported by the crest of a wave, leaving the perpendiculars unsupported over the trough.
- Shearing - due to the uneven force of buoyancy and gravity working in opposite directions on adjacent compartments loaded unequally, shearing force will put tension on the partition between compartments or point at which they join. This is a type of longitudinal stress. Shearing force is measured in the stability booklet. ^shearing
- Racking - a transverse force occurring as a ship rolls. The deck has a tendency to move laterally relevant to the bottom structure as the entire ship rolls. Transverse bulkheads primarily resist this kind of deformation. 
- Torsion - a twisting force that mostly occurs in very long or wide ships, like container ships (which have 'torsion boxes' added to help resist this nature of structural stress). As a wave hits the ship at about 45 degrees, the righting moment will create a twisting force about the entire length as the bow rights at a different time than the stern. 
- Panting - a local stress which occurs on the bow. Panting occurs as the hull moves up and down due to varied water pressure in forward momentum. Panting is to be expected from the stem up to about 15% of the length of the ship and extra reinforcement is made in the bow to resist panting stress.
- Pounding - a local stress occurring on the stern as the vessel moves forward and varied water pressure applies force to the bottom shell. Most severe in conditions of light weight, which is another reason why vessels tend to be trimmed by the stern. The pounding region occurs from about 5% of the stern to about 25-30% of the vessel's length, and there is special reinforcement of this region to resist this type of stress.

[diagram of compression]()
[diagrams of hog and sag]()

## Structural Components
#construction 
The primary structural reinforcements of the ship can be broken into the degree (longitudinal, transverse or vertical) by which they are built to provide strength. 

Longitudinal reinforcements
- girders, such as the continuous centre girder which runs the entire length of the ship above the keel, or the other side girders which tend to support the bottom framing.
- shell plating, composing the hull along the length of the ship
- stringers, a kind of girder that provides reinforcement to the hull
- longitudinals, fore/aft reinforcement between bulkheads that give strength and rigidity to the framework and shell.
- strakes, such as the garboard strake which run immediately on either side of the keel along the hull, or the rubbing strake which prevents damage to the hull from docking

Transverse reinforcements
- transverse bulkheads, vertical partitions dividing the hull into compartments. There are also longitudinal bulkheads, since every "wall" within a ship is technically also a bulkhead, but when discussing bulkheads they are primarily referred to in the transverse sense. Some transverse bulkheads are completely watertight. One particular bulkhead of note is the collision bulkhead on the bow, which is especially reinforced and is designed to take the force of a head-on impact; this is why it is more beneficial in a collision or grounding scenario to take a force head on, as the collision bulkhead is designed to protect the watertight integrity of the vessel in this exact scenario. The collision bulkhead separates the bow from the cargo compartments, which are especially vulnerable to flooding. On the aft end, there is also the aft peak bulkhead, which sometimes is not in one continuous section and separates the stern from the machinery spaces (like the engine room). There are specially reinforced bulkheads called 'corrugated bulkheads' which are riveted to give them enhanced strength. 
- frames, a reinforcement that runs in the transverse direction. Frames are numbered and evenly spaced over the vessel at intervals of no less than 1 metre; except in the bow where they are spaced at 700mm and 610mm depending on the region. 
- floors, which run parallel to the keel and transversely connect to frames at the turn of the keel. Longitudinals, frames, girders and the margin plate all intersect with the floors to strengthen the bottom of the vessel and support the weight of decks and tanks. Floors are discussed more with the double bottom ([[#^db]]) tank/hull.
- beams, which join frames via the beam knee and support decks transversely.

Vertical reinforcements
- stantions, vertical pillars which support decks

These components will reappear under many specific names and variations, but as long as you have a good understanding of the general naming principles, you should be able to have a good enough understanding of structural terminology.

## Composition of the Bow
#construction 
The panting region is found in the bow, where special reinforcement is made to reduce the effects of this stress on the bow. The plated stem composes the hull structure, and is supported by a combination of decks and frames. Decks are supported by both panting beams and panting stringers, and frames are spaced closer together in the panting region. Brackets provide additional support to the decks. The collision bulkhead is watertight and keeps the bow separate from the rest of the ship. The forepeak tank is enclosed in the bow and is used mostly as a ballasting region, typically to change the trim of the vessel. The forepeak tank has washplates and bulkhead subdivisions that reduce the free surface effects within the tank. Above the bow, on the top deck is the forecastle, where the mooring winches and anchor windlasses are. The anchor cable runs from the chain locker, where the bitter end is secured to the bulkhead, out through the spurling pipe and through the anchor windlass. The rest of the anchor chain runs out through the hawse pipe to the anchor itself. 

[diagram of the bow]()

## Composition of the Stern
#construction 
The pounding region lies on the stern, and the stern region is especially reinforced to withstand the effects of pounding as well as the vibration and force of the rudder shaft. The afterpeak bulkhead separates the aft end from the machinery spaces (typically from the engine room at the stern of the ship). The stern tube is watertight (secured with a retaining ring) and is lined with bearings which lubricate the shaft. The stern tube is joined to the propellor by the propellor boss (secured via the stern nuts) and the propellor boss runs through a watertight opening in the stern frame. At the bottom of the stern frame is the cast sole piece, where in certain configurations of the rudder is where the stern pintle connects to the rudder blade. The top of the rudder blade is joined by the heel pintle, which connects to the rudder trunk where an inspection manhole is available for maintenance of the rudder. Above the rudder trunk lies the steering flat or steering gear, where the rudder emergency steering is accessed. The entire stern frame is reinforced with horizontal webbing (longitudinally) and floors (transversely). The aft peak tank is at the stern and, like the forepeak tank, is used primarily for ballasting and altering the trim of the vessel. It is quite common that the vessel is trimmed by the stern, and due to the nature of the ballasting tank the aft peak tank is subdivided to reduce free surface effect.

[diagram of the stern]()

## Transverse Sections and the Double Bottom
#construction 
The transverse configuration of a compartment will vary greatly depending on the type of ship. Large cargo bulkers may have hopper tanks at the top and bottom sides of the hold, allowing ballast or additional cargo to be loaded. On the sides, composing the hull itself, transverse side frames support the side shell. Certain configurations of tanks allow decks to run transversely, which are supported by beams. On the top of a hatch, it will be surrounded by a coaming which provides a layer of protection against water running into the tank.

The double bottom is both a tank and means of structural reinforcement between the keel and the enclosed compartments and cargo spaces of the ship. Historically, the double bottom could be used as a ballast tank; but now regulation prohibits the storage of water within this space and it instead acts as an additional layer of protection between tanks and the hull. The double bottom is either constructed in *solid floor* or *bracket floor* style, where the solid floor construction tends to provide greater reinforcement and structural strength at the cost of increased weight, while the bracket style construction still gives structural reinforcement to the compartment while being much less heavy and expensive to manufacture. The double bottom is reinforced longitudinally with girders and longitudinals, and transversely with frames and floors. Solid floors are constructed with a lightening hole to decrease overall weight, allow liquid to flow between frames, and to allow inspection of the space. The upper deck of the double bottom is sometimes referred to as either the 'inner bottom' or 'tank top' (as the double bottom is technically a tank). ^db

[diagram of a transverse section of the ship]()
[diagram of the double bottom]()

## Miscellaneous Structural Components
#construction 
The 'railings' around the decks are referred to as bulwarks. Bulwarks are no less than 1 metre high, except in cases where the height would interfere with the work being done in that area. The bulwarks are supported by stantions or stays, which are spaced 1.2 metres apart, but on class B ships are spaced closer together. The bulwark does not extend all the way to the deck, leaving a gap called the 'freeing port' which allows water to shed off the deck, reducing on-deck free surface effects.

[diagram of the bulwark]()
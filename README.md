# microFermenT

## This project is the result of two problems in a student laboratory at the Technical University of Munich.

A guided laboratory course for third year bioprocess engineering students was designed by lecturer Markus Gütlich. One experiment was the cultivation of Lactobacillus lactis in its wild-type strain and the recording of basic growth parameters such as pH, cell density or carbon source concentration. Due to a tight schedule and the slow growth of *Lactobacillus lactis*, the main problem was the limited time available of only 6 hours.
The second problem was the cost of laboratory equipment required for controlled environment growth of micro-organisms. Bioreactors or fermenters are typically used for this purpose. With its equipment, a Sartorius Stedim Biostat A benchtop fermenter, the Chair of Biopolymer Chemistry at TUM was able to help. But with only one piece of equipment, which was too complicated to learn in just 6 hours, it was not possible to provide hands-on experience for 30 students.

To solve both problems, a 3D printable miniature bioreactor was developed by Martin Ortner, a PhD student at the Department of Biopolymer Chemistry. He worked closely with Markus Gütlich, who contributed the pedagogical aspects. Together with the switch from *Lactobacillus lactis* to the fast-growing *Vibrio natriegens*, the 6 hour deadline was reachable.

With autoclavability in mind, the hardware is based on a 1 liter, 80 mm wide mouth laboratory bottle. Using HighTemp resin, custom inserts were 3D printed on a FormLabs Form3. In order to counteract the corrosion of the highly saline growth media, all metal parts were either made of A2 stainless steel or were replaced with ceramics.


![image of fermenter_schematic](https://github.com/MOrtner/microFermenT/blob/main/images/render_schematic.png)

Here, a set of two finished **microFermenT**ers are shown doing their duty in growing *V. natriegens*:

![image of fermenter_in action](https://github.com/MOrtner/microFermenT/blob/main/images/example_fermenter.png)

The following graph shows the difference between a Batch (solid lines) and Fed-Batch (dashed lines) fermentation in both, cell density and carbon source (glucose) utilization:
![example kinetics](https://github.com/MOrtner/microFermenT/blob/main/images/example_growth.png)


# Cultivation of Vibrio natrigens in a bioreactor


Objective: To record growth curves, determine the doubling time and the maximum cell density in minimal medium.


Background:

In the laboratory, the gram-negative bacterium Escherichia coli is usually used in genetic engineering work. Various serotypes of this bacterium exist. Serotype K is usually used in the laboratory, and in particular strain K12. E. coli K12 was specially developed as a safety strain that has genetic properties designed to ensure that the bacterium cannot survive outside the laboratory. Under optimal conditions, E. coli has a doubling rate of 1/20 min.
Vibrio natriegens [ATCC 14048/ DSM 759] is also a gram-negative bacterium that originally occurs in West African mudflats. It therefore requires higher salt concentrations, which are also typical in seawater (approx. 3.5 % NaCl). Furthermore, Vibrio natriegens is not very demanding, so that it can be cultivated in the same media as E. coli K12, as long as enough salt is added to these media. Vibrio natriegens has only recently been used in the laboratory. The main advantage of this organism is its outstandingly high growth rate, which is only 1/10 min under optimal conditions. In addition, all promoters, antibiotics and plasmids that are also used in E. coli function in this bacterium. This makes Vibrio natriegens the optimal bacterium for processes in which a large amount of biomass is to be produced in a short time. Several research groups around the world are currently using the CRISPR/CAS9 method to further improve the Vibrio natriegens strain. For example, the strain lacks the enzyme catalase, which is why it cannot break down the resulting H2O2 when stored in the refrigerator. Vibrio natriegens can therefore only be stored in the refrigerator to a limited extent. Other undesirable genes are also deleted. For example, work is underway to destroy the recombinase that enables the bacterium to integrate plasmid DNA into the chromosome. This could lead to the spread of antibiotic-resistant strains. In addition, the genes for endonucleases that can cut plasmid DNA are also being deleted. Finally, attempts are being made to switch off the genes for some proteases that can break down proteins produced in excess in the wild-type strain. However, the latter is not possible with protein production strains and strains with deleted protease promise a higher yield of recombinant protein.
There are different feeding strategies for the fermentation of microorganisms. In the batch process, a saturating concentration of the C source is initially introduced. The microorganisms then grow at the maximum doubling rate until one component of the medium finally becomes limiting. In the fed-batch process, you start with a sufficient amount of feed to ensure initial growth of the culture. After a few doubling steps, the C source is used up and the bacteria stop multiplying. At the same time, the oxygen saturation in the medium usually also increases, as the microorganisms can no longer run a citric acid cycle. If this state is maintained for a longer period of time, the bacteria enter the stationary phase. This changes the expression of numerous genes, which can have a negative effect on the yield of the desired fermentation products. If, on the other hand, the starvation phase is only short, the bacteria can be brought back into the growth phase through further targeted addition of feed. By constantly alternating between short starvation phases and growth phases, the bacteria are kept in an optimal state for producing the desired substances. In addition, the growth of the culture can be controlled so that induction and harvest times are at the desired times. In technology, many fermentation processes are therefore carried out using the fed-batch method. However, this requires permanent monitoring of the culture in terms of substrate concentration, pH value, biomass quantity and oxygen content in the medium. These values must therefore be constantly monitored using probes or by taking samples.
In the practical course, you will record growth curves of V. natriegens in minimal medium and determine the maximum doubling rates from these values. You will also investigate the influence of batch and fed-batch fermentation on growth behavior and determine the duration of the lag phase, which is the time it takes for V. natriegens to return to its maximum growth rate from a state of substrate limitation.
For this purpose, two cultures of V. natriegens are inoculated in minimal medium in mini fermenters developed in-house. These fermenters make it possible to regulate the temperature, the stirrer speed and the air supply. In one fermenter, the bacteria are cultivated under a saturating glucose concentration. In the second vessel, on the other hand, a limited amount of glucose is specified. Initially, both cultures will grow in the same way. After a certain time, however, the growth rate in the fed-batch culture will slow down and eventually come to a complete standstill. In this situation, the bacteria have completely used up the available glucose. This can be measured by a stagnation in the cell density curve over time. If glucose is added again, the bacteria begin to multiply again after a short lag phase. In order to document the transition to substrate limitation and the renewed transition to the growth phase, the measurement intervals should be particularly short at these times.


Required solutions:


VN base medium
MOPS	
21g/l	
NaCl (NH4)2SO4 K2HPO4 KH2PO4	15g/l 5g/l 1g/l 1g/l	
Potassium chloride solution mM		
Magnesium sulphate solution: MgSO4 7H2O (1000 x)	

250	

g/l
Calcium chloride solution: CaCl2 (1000 x)	

10g/l	
Thiamine solution Thiamine (1000 x)	

1mg/ml	
Trace elemet solution (1000x) FeSO4 x 7H20	

16,4	

g/l
MnSO4 x H2O CuSO4 x 5H2O ZnSO4 x 7 H2O
NiCl2 x 6 H20	10g/l 0.313
1g/l
0,02	g/l g/l
 
Glucose feed solution:
	Glucose20 %	(w/v)




Experiment execution:
1.	Heat the water bath to 37°C

2.	Assemble two fermenters in cooperation with your neighboring groups. Connect the vessels to the air supply and install the pH electrode.
3.	Place the two fermenter vessels in the water bath

4.	As soon as the water bath has reached a temperature of 37°, fill in the medium. You will find the main component of the minimum medium in the 37° incubator.
5.	Fill each fermenter vessel with 870 ml of the base medium (weigh out, ρ=1) and mix the finished medium from its components in the fermenter vessel.
Add the following components while stirring:

Trace element solution	900	µl
Magnesium sulphate solution	900	µl
Calcium chloride solution	900	µl
Thiamine solution	900	µl
Potassium chloride	900	µl


6.	Add glucose to one of the vessels to a final concentration of 2 g/l. Add glucose to the other vessel to a concentration of 0.1 g/l.
7.	Inoculate both fermenters with the starting culture provided at a dilution of 1:50.
8.	Samples of 1 ml per group are taken regularly during fermentation. At these times, cut off the air supply and switch off the stirrer. Try not to carry any air bubbles with you when taking the samples. It makes sense for one person to take 4 ml of culture and distribute it to four waiting Eppis.
9.	Whenever you take samples, make a note of the pH value.
 
10.	Calibrate the photometer against air and measure the output OD600 in each vessel. (Measuring program on the GeneQuant 1300 photometer: Applications\Single Wavelength)
11.	Then centrifuge the contents of the vial (tabletop centrifuge; 13000 rpm) and keep the supernatant on ice for the subsequent glucose test.
12.	After one hour, take the next samples from both tubes. From now on, the glucose determination is only carried out in the fed-batch tube. (However, the OD is measured in both vessels at all times).
13.	Repeat the OD measurement in both vessels every 20 minutes until you have recorded the entire kinetics (or until the end of the practical day).
14.	As soon as you notice that the fed-batch culture is clearly lagging behind the batch culture in terms of growth, measure the fed-batch culture every 10 minutes.
15.	As soon as the fed-batch culture has been stationary for 30 minutes, add more glucose so that the concentration in the fed-batch vessel rises to 2 g/l.
16.	Draw the growth curve and determine the maximum growth rate for each vessel and the duration of the lag phase after the feed pulse (the * in the table) until the culture returns to the exponential phase.
17.	Typical times for sampling for the glucose test could be: (Your values may vary!)


Time	0	60	90	120	140	160	180	190	200*	210	220	240
batch	X	X		X			X					X
fed-batch	X	X	X	X	X	X	X	X	X	X	X	X




18.	During the experiment, enter the growth curve and the pH value on the enclosed graph paper. (Later also the glucose concentration) Scaling of the Y-axis: ODmax=1.5, pH= 6.5-7.5; scaling of the X-axis: 1 mm/min)
19.	Indicate for the protocol what the components in the minimal medium are used for (a table with 2 columns and one (enzyme) function per substance is sufficient)
 



Remark:

•	You can create the diagram by hand and on graph paper.

•	However, if you are working with EXCEL for the evaluation, you should bear in mind that Excel can only display two Y-axes in a diagram (move the second Y-axis to the right). The third Y-axis is obtained by overlaying the first diagram with a transparent second diagram. In this case, however, make sure that the two X-axes match correctly and move the Y-axis to the left in the overlay diagram.
•	If you instead work with a science-oriented plotting program such as Origin (available via TUMonline / Software), you can position all three axes separately in a single graph.


Determination of the glucose concentration during fermentation: Required solutions:
Glucose reagent:

Na2H P04 x 12 H20	17,6	g/l
NaH2 P04 x 2 H20	7,6	g/l
Set pH to 7.0		
ABTS	0,5	g/l
Glucose oxidase	3,3	mg/l
Horseradish peroxidase	6,7	mg/l
This solution is provided to you, keep it on ice at all times. It must be prepared fresh every day.


Glucose solution:

Glucose monohydrate		200mg/l (1 mM)


Stop solution:

Sulphuric acid	2,5	M
 
Carrying out the measurement:



1.	During fermentation, you took samples from the fermenter vessels. You determined the OD600 in these samples, then centrifuged the cells and stored the supernatants on ice.
2.	During fermentation, create a calibration curve for the glucose test. Mix the following samples for this. Please note that you must use the glucose measuring solution and not the glucose feed solution. You can also determine the glucose concentration in the first fermenter samples while the fermentation is still running. At the end of fermentation, you then only have a few samples to measure. This saves time.


Calibration line:

Sample no.	
1	
2	
3	
4	
5	
6
Glucose measuring solution (µl)	0	10	20	30	40	50
dist. water (µl)	50	40	30	20	10	0
Glucose reagent (µl)	750	750	750	750	750	750



3.	Incubate the tests for 30 min in the heating block at 37°C.

4.	Stop the reaction by adding 100 µl of stop solution.

5.	Determine the OD at 405 nm.

6.	When measuring the fermenter samples, you must differentiate between those samples that contain a high glucose concentration and those that contain a low concentration. Otherwise your measured values will lie outside the calibration line. The samples with a high concentration are those from the batch approach and the late samples from the fed-batch approach (after feeding). The early fed-batch samples, on the other hand, have a low glucose concentration. Use 50 µl of the samples with a low concentration for measurement and only 2.5 µl of the samples with a high concentration. However, pipetting 2.5 µl naturally results in higher pipetting errors. These samples are therefore pre-diluted.
 
To determine glucose in the low-concentration samples, mix 750 µl of glucose reagent in 1.5 ml Eppis with 50 µl of their supernatants and proceed as described above.
For samples with a high concentration, first mix 50 µl of your sample with 950 µl of water and add 50 µl of this mixture to a second Eppi and mix 750 µl of glucose reagent there for the test.
7.	Determine the glucose concentration in your batch and fed-batch preparations for the protocol using the calibration series and enter these values in the growth curve diagram. As the values for batch and fed-batch differ significantly, they are difficult to represent using a single scale. A logarithmic Y-axis would be possible here, but would be confusing. It is therefore best to use two separate Y-axes for the glucose values, or split the axes. Excel cannot display split axes by default. Professional XY plot programs such as Origin, however, can. A campus license for Origin is available from the Faculty of Physics. If you want to use Excel, you can, as mentioned above, create the representation with the help of overlay graphics. Or you can draw the curves by hand. Also consider the spread of the pH axis. Otherwise you can hardly see the small changes. The diagram should therefore show the following curves: OD, glucose concentration and pH value, each for batch and fed-batch. This means that you need at least three Y-axes, but probably more.

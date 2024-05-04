# microFermenT

## This project is the result of two problems in a student laboratory at the Technical University of Munich.

A guided laboratory course for third year bioprocess engineering students was designed by lecturer Markus Gütlich. One experiment was the cultivation of Lactobacillus lactis in its wild-type strain and the recording of basic growth parameters such as pH and cell density. Due to a tight schedule and the slow growth of *Lactobacillus lactis*, the main problem was the limited time available of only 6 hours.
The second problem was the cost of laboratory equipment required for controlled environment growth of micro-organisms. Bioreactors or fermenters are typically used for this purpose. With its equipment, a Sartorius Stedim Biostat A benchtop fermenter, the Chair of Biopolymer Chemistry at TUM was able to help. But with only one piece of equipment, which was too complicated to learn in just 6 hours, it was not possible to provide hands-on experience for 30 students.

To solve both problems, a 3D printable miniature bioreactor was developed by Martin Ortner, a PhD student at the Department of Biopolymer Chemistry. He worked closely with Markus Gütlich, who contributed the pedagogical aspects. Together with the switch from *Lactobacillus lactis* to the fast-growing *Vibrio natriegens*, the 6 hour deadline was reachable.

With autoclavability in mind, the hardware is based on a 1 liter, 80 mm wide mouth laboratory bottle. Using HighTemp resin, custom inserts were 3D printed on a FormLabs Form3. In order to counteract the corrosion of the highly saline growth media, all metal parts were either made of A2 stainless steel or were replaced with ceramics.


![image of fermenter_schematic](https://github.com/MOrtner/microFermenT/blob/main/images/render_schematic.png)

Here, a set of two finished **microFermenT**ers are shown doing their duty in growing *V. natriegens*:

![image of fermenter_in action](https://github.com/MOrtner/microFermenT/blob/main/images/example_fermenter.png)

# Cultivation of Vibrio natrigens in a bioreactor


Objective: To record growth curves, determine the doubling time and the maximum cell density in minimal medium.


Background:

In the laboratory, the gram-negative bacterium Escherichia coli is usually used in genetic engineering work. Various serotypes of this bacterium exist. Serotype K is usually used in the laboratory, and in particular strain K12. E. coli K12 was specially developed as a safety strain that has genetic properties designed to ensure that the bacterium cannot survive outside the laboratory. Under optimal conditions, E. coli has a doubling rate of 1/20 min.
Vibrio natriegens [ATCC 14048/ DSM 759] is also a gram-negative bacterium that originally occurs in West African mudflats. It therefore requires higher salt concentrations, which are also typical in seawater (approx. 3.5 % NaCl). Furthermore, Vibrio natriegens is not very demanding, so that it can be cultivated in the same media as E. coli K12, as long as enough salt is added to these media. Vibrio natriegens has only recently been used in the laboratory. The main advantage of this organism is its outstandingly high growth rate, which is only 1/10 min under optimal conditions. In addition, all promoters, antibiotics and plasmids that are also used in E. coli function in this bacterium. This makes Vibrio natriegens the optimal bacterium for processes in which a large amount of biomass is to be produced in a short time. Several research groups around the world are currently using the CRISPR/CAS9 method to further improve the Vibrio natriegens strain. For example, the strain lacks the enzyme catalase, which is why it cannot break down the resulting H2O2 when stored in the refrigerator. Vibrio natriegens can therefore only be stored in the refrigerator to a limited extent. Other undesirable genes are also deleted. For example, work is underway to destroy the recombinase that enables the bacterium to integrate plasmid DNA into the chromosome. This could lead to the spread of antibiotic-resistant strains. In addition, the genes for endonucleases that can cut plasmid DNA are also being deleted. Finally, attempts are being made to switch off the genes for some proteases that can break down proteins produced in excess in the wild-type strain. However, the latter is not possible with protein production strains and strains with deleted protease promise a higher yield of recombinant protein.
There are different feeding strategies for the fermentation of microorganisms. In the batch process, a saturating concentration of the C source is initially introduced. The microorganisms then grow at the maximum doubling rate until one component of the medium finally becomes limiting. In the fed-batch process, you start with a sufficient amount of feed to ensure initial growth of the culture. After a few doubling steps, the C source is used up and the bacteria stop multiplying. At the same time, the oxygen saturation in the medium usually also increases, as the microorganisms can no longer run a citric acid cycle. If this state is maintained for a longer period of time, the bacteria enter the stationary phase. This changes the expression of numerous genes, which can have a negative effect on the yield of the desired fermentation products. If, on the other hand, the starvation phase is only short, the bacteria can be brought back into the growth phase through further targeted addition of feed. By constantly alternating between short starvation phases and growth phases, the bacteria are kept in an optimal state for producing the desired substances. In addition, the growth of the culture can be controlled so that induction and harvest times are at the desired times. In technology, many fermentation processes are therefore carried out using the fed-batch method. However, this requires permanent monitoring of the culture in terms of substrate concentration, pH value, biomass quantity and oxygen content in the medium. These values must therefore be constantly monitored using probes or by taking samples.
In the practical course, you will record growth curves of V. natriegens in minimal medium and determine the maximum doubling rates from these values. You will also investigate the influence of batch and fed-batch fermentation on growth behavior and determine the duration of the lag phase, which is the time it takes for V. natriegens to return to its maximum growth rate from a state of substrate limitation.
For this purpose, two cultures of V. natriegens are inoculated in minimal medium in mini fermenters developed in-house. These fermenters make it possible to regulate the temperature, the stirrer speed and the air supply. In one fermenter, the bacteria are cultivated under a saturating glucose concentration. In the second vessel, on the other hand, a limited amount of glucose is specified. Initially, both cultures will grow in the same way. After a certain time, however, the growth rate in the fed-batch culture will slow down and eventually come to a complete standstill. In this situation, the bacteria have completely used up the available glucose. This can be measured by a stagnation in the cell density curve over time. If glucose is added again, the bacteria begin to multiply again after a short lag phase. In order to document the transition to substrate limitation and the renewed transition to the growth phase, the measurement intervals should be particularly short at these times.

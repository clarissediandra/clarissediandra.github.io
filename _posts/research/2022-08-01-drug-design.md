---
title: "Screening of Inhibitors Targeting GSK3𝛽 kinase in Drug Design"
layout: post
categories: Research
---

![DrugDesignProjectCover](/assets/img/research/drug-design/4i.png){: width="80%" }

This project aims to evaluate compound libraries of inhibitors as drug candidates by analysing their binding thermodynamics and kinetic parameters with their target protein, GSK3𝛽. Specifically, this project utilised in silico docking to identify compounds with the lowest binding energies and in vitro screening to assess GSK3𝛽 kinase activity and inhibitor effects through biochemical assays. Key data, including binding energy, IC50 values, and inhibitor concentration effects, were obtained and validated using 3D structural analysis. Promising inhibitors are selected for further development, with the ultimate goal of advancing treatments for cell signaling diseases such as cancer.


Protein phosphorylation by serine/threonine and tyrosine kinases is crucial for cellular signaling, protein synthesis, and growth. GSK3 kinase, a serine/threonine kinase, regulates blood glucose levels and cell proliferation through the PKB/AKT and WNT pathways. Dysregulation of GSK3 activity, including GSK3 overexpression or malfunction, is linked to diseases like Alzheimer’s and cancer, making it a significant target for drug development.

Targeting protein kinases, including GSK3, has become a cornerstone of drug development. Kinase-directed drugs inhibit kinase activity and prevent aberrant binding to natural substrates like ATP or amino acids while preserving essential cellular functions.

This experiment aims to identify and develop potent GSK3B kinase inhibitors. Initially, in silico docking methods will screen a library of compounds to select candidates with the lowest binding energies. Selected compounds will then undergo in vitro biochemical assays to validate their inhibitory effects on GSK3 activity and their potential as therapeutic agents. The combined use of computational and experimental approaches aims to ensure the identification of effective inhibitors, contributing to the development of treatments for diseases linked to kinase dysregulation.

## In Silico Docking

This project aims to identify the best GSK3β drug candidates using in silico docking and in vitro biochemical assays. Figure 1 highlights seven top structures that were selected from inhibitor libraries based on their highly negative ligand binding energies, indicating strong predicted interactions with GSK3's active site.

![Figure1](/assets/img/research/drug-design/1.png){: width="80%" }
*Figure 1. In silico inhibitor compounds selection results.*
<div style="margin-top:-10px;"></div>
<div style="margin: 0 auto; width: 80%; font: italic; font-style: italic; text-align: justify;">
The 3D structure between 7 possible inhibitor compounds interactions within 3.5 Å distance from the GSK3ꞵ's residues (panels A-G). Panel A (Inhibitor 9), B (Inhibitor 10), C (Inhibitor 16), D (Inhibitor 22), E (Inhibitor 33), F (Inhibitor 47), and G (Inhibitor 49). The inhibitor compounds in each panel A-G are illustrated with color based on their residual element (C with grey, N with blue, O with red, S with yellow). Interactions are illustrated in each panel (hydrogen bond with straight gray lines, hydrophobic interactions with dotted gray lines, and water bond with straight lines and a sphere in the middle).These protein:inhibitor interactions are generated by PyMol Software. GSK3ꞵ's structure was taken from Protein Data Bank (pdb code: 1UV5. Inhibitor structures were taken from the ZINC database. Lysine (light burgundy), Leucine (light pink), Valine (green), Tyrosine (turquoise), Isoleucine (gold), Arginine (neon green), Aspartic acid (dark purple), Alanine (dark blue), Glutamine (orange), Threonine (light green), Aspargine (nude). The bottom right panel shows the calculated binding energies tested in ArgusLab Software.
</div>

## In Vitro Screening using Biochemical Assays

Experimental validation of the in silico predictions involved biochemical assays to evaluate GSK3β activity using two coupled reactions. In the first reaction, GSK3β phosphorylated a substrate using ATP, producing phosphorylated substrate and ADP. In the second reaction, the remaining ATP was dephosphorylated during oxyluciferin formation by luciferase, generating luminescence proportional to ATP concentration (figure. 2). As expected, luminescence increased with higher ATP levels and decreased with higher GSK3β concentrations, as more ATP was consumed in the first reaction. An outlier at the lowest GSK3β concentration (0.0006 µM) was removed due to inaccuracies, which could skew the dose-response analysis (figure. 2b). This finding highlights potential measurement limitations at very low enzyme concentrations.

![Figure2](/assets/img/research/drug-design/2.png){: width="80%" }
*Figure 2. GSK3β Kinase Assay Quality Results.*
<div style="margin-top:-10px;"></div>
<div style="margin: 0 auto; width: 80%; font: italic; font-style: italic; text-align: justify;">
Luminescence vs. ATP concentration graph (A). Luminescence vs. GSK3ꞵ concentration (B). Dotted plots show the measured luminescence in different ATP or GSK3ꞵ concentrations. Dotted lines show best-fit lines. Line equation of both graphs is shown in the bottom right of each graph (y = mx + c). Omitted value from analysis (red cross).
</div>

After validating GSK3β activity, a biochemical assay was conducted to test GSK3β against the seven selected inhibitor compounds from in silico docking. The supplier's data indicated GSK3β should have a specific activity of 245 Units/mg. However, initial assays using 2.5 ng/µL of GSK3β in a 40 µL reaction yielded 1108 Units/mg (figure. 3). To achieve the target 245 Units/mg specific activity in the same reaction volume, the enzyme concentration needed to be reduced to 0.5 ng/µL. Since the enzyme contributes only 10 µL of the total reaction volume, the stock concentration must be adjusted to 2.0 ng/µL (a fourfold increase) to ensure proper dilution and experimental accuracy.

![Figure3](/assets/img/research/drug-design/3.png){: width="80%" }
*Figure 3. GSK3ꞵ kinase's experimental data used in biochemical assays.*
<div style="margin-top:-10px;"></div>
<div style="margin: 0 auto; width: 80%; font: italic; font-style: italic; text-align: justify;">
In vitro GSK3ꞵ kinase activity assay (A). In vitro GSK3ꞵ kinase in inhibitor presence. Conditions of the assay (light blue), Calculated values (purple), Given values (brown), Formulas (dark blue). Formulas were used to deduce the calculated values from both given values and condition of the assay.
</div>

During the inhibitor activity and efficacy assay, the most effective inhibitors were expected to reduce GSK3β's substrate turnover, leaving more ATP available for luciferase catalysis, resulting in increased luminescence. The IC50 values, which measure the potency of each inhibitor, were calculated to assess their ability to inhibit GSK3β activity. A low IC50 indicates a promising drug candidate, while a high IC50 suggests potential toxicity. In this screening, inhibitor 10 (I10) and inhibitor 9 (I9) were selected as the top candidates, showing significant inhibition of GSK3β with minimal outlier data. Both inhibitors exhibited a sigmoidal curve, indicating that increasing inhibitor concentration led to greater inhibition of GSK3β activity and higher luminescence. I10 was favored over I9 due to its lower IC50, making it a more potent candidate. Other inhibitors, such as I22 and I49, showed downward sigmoidal curves, indicating poor efficacy, while compounds like I16 and I47 had small differences in luminescence, suggesting minimal inhibition, with I16's data failing to produce a valid IC50.

![Figure4i](/assets/img/research/drug-design/4i.png){: width="80%" }
![Figure4ii](/assets/img/research/drug-design/4ii.png){: width="80%" }
![Figure4iii](/assets/img/research/drug-design/4iii.png){: width="80%" }
![Figure4iv](/assets/img/research/drug-design/4iv.png){: width="80%" }
*Figure 4. Assay on Inhibitor's activity on GSK3ꞵ kinase & its efficacy as drug candidates.*
<div style="margin-top:-10px;"></div>
<div style="margin: 0 auto; width: 80%; font: italic; font-style: italic; text-align: justify;">
Luminescence vs. Log of inhibitor concentration. Panel A (Inhibitor 9), B (Inhibitor 10), C (Inhibitor 16), D (Inhibitor 22), E (Inhibitor 33), F (Inhibitor 47), and G (Inhibitor 49). Square plots show average luminescence values for every log [inhibitor]. Standard deviation was used to plot the error bars. These data were plotted in a non-linear curve with a dose-response fit curve (red line). Omitted data from analysis (red square & error bars). Log [inhibitor] = 0 shows positive (bottom plot) & negative (top plot) GSK3ꞵ control. IC50 values for each protein:inhibitor interaction is shown on the bottom right. (-) shows no IC50 value was able to be recorded.
</div>

### Conclusion

This experiment successfully identified two potential GSK3 inhibitors, I10 and I9, as strong drug candidates based on their comprehensive evaluation through in silico docking and in vitro biochemical assays. Both compounds exhibited favorable properties, including highly negative ligand binding energies and low IC50 values, indicating their strong affinity and effectiveness in inhibiting GSK3 activity. I10, identified as 6-bromoindirubin-3’-oxime, emerged as the most potent candidate due to its additional hydrogen bond within GSK3’s active site, enhancing the stability of the protein-inhibitor complex. In contrast, I9, while slightly less effective, demonstrated stable hydrophobic interactions with key residues, including Lys85, contributing to its inhibitory activity. Both inhibitors showed significantly better binding and efficacy compared to other tested compounds, which were limited by structural incompatibilities or insufficient impacts on GSK3 activity.

The findings highlight the value of combining in silico methods to efficiently screen for candidates with high binding affinity and in vitro assays for validating biochemical efficacy. However, additional validation using advanced techniques like Isothermal Titration Calorimetry (ITC) is suggested to provide direct catalytic rate measurements and confirm the inhibitors' biophysical properties. The identified compounds, especially I10, hold promise for further development in preclinical and clinical trials, where their therapeutic potential against diseases like cancer, involving dysregulated GSK3 activity, can be explored. These results underscore the importance of understanding enzyme biochemistry and leveraging modern technologies for targeted drug discovery and development.
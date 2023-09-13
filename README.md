<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

#myInput {
  background-image: url('/css/searchicon.png');
  background-position: 10px 12px;
  background-repeat: no-repeat;
  width: 100%;
  font-size: 16px;
  padding: 12px 20px 12px 40px;
  border: 1px solid #ddd;
  margin-bottom: 12px;
}

#myUL {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

#myUL li a {
  border: 1px solid #ddd;
  margin-top: -1px; /* Prevent double borders */
  background-color: #f6f6f6;
  padding: 12px;
  text-decoration: none;
  font-size: 18px;
  color: black;
  display: block
}

#myUL li a:hover:not(.header) {
  background-color: #eee;
}
</style>
</head>
<body>

<h2>PRACOWNIA RUTYNOWA</h2>

<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Czego szukasz?" title="Type in a name">

<ul id="myUL">
  <li><a href="#">Multichem U - 8P8910 <font color="red">[R1 - P1]</font></a></li>
  <li><a href="#">Nucleic Acid - 132131001HC <font color="red">[R1 - P1]</font></a></li>
  <li><a href="#">ALKP 2 - Alkaline Phosphatase 2 - 4T8320 <font color="red">[R1 - P1]</font></a></li>	
  <li><a href="#">AMY 2 - Amylase 2 - 4T8520 <font color="red">[R1 - P1]</font></a></li>
  <li><a href="#">AST 2 - Asparate Aminotransferase 2 - 4T8620 <font color="red">[R1 - P1]</font></a></li>

  <li><a href="#">ALT 2 - Alaine Aminotransferase 2 - 4T8430 <font color="red">[R1 - P2]</font></a></li>
  <li><a href="#">BILE ACIDS - Total Bile Acids Reagent kit - 8P5722 <font color="red">[R1 - P2]</font></a></li>
  <li><a href="#">BILI D - Direct Bilirubin Reagent kit - 7P9720 <font color="red">[R1 - P2]</font></a></li>
  <li><a href="#">BILI TOTAL - Total Bilirubin Reagent kit - 4V5131 <font color="red">[R1 - P2]</font></a></li>
  <li><a href="#">CARB - Carbamazepine Reagent kit - 8P5820 <font color="red">[R1 - P2]</font></a></li>

  <li><a href="#">C3 - Complement C3 - 9P5624 <font color="red">[R1 - P3]</font></a></li>
  <li><a href="#">C4 - Complement C4 - 9P5724 <font color="red">[R1 - P3]</font></a></li>
  <li><a href="#">CK - Creatine Kinase Reagent kit - 8P4220 <font color="red">[R1 - P3]</font></a></li>
  <li><a href="#">CHOL 2 - Cholesterol 2 - 4T8830 <font color="red">[R1 - P3]</font></a></li>
  <li><a href="#">CHE - Cholinesterase Reagent kit - 9P9422 <font color="red">[R1 - P3]</font></a></li>
  <li><a href="#">CERULO - Ceruloplasmin Reagent kit - 9P9320 <font color="red">[R1 - P3]</font></a></li>
  <li><a href="#">DIRECT LDL - Direct LDL Reagent kit - 7P7120 <font color="red">[R1 - P3]</font></a></li>

  <li><a href="#">UIBC - UIBC Reagent kit - 8P4420 <font color="red">[R1 - P4]</font></a></li>
  <li><a href="#">LITHIUM - Lithium Reagent kit - 8P5320 <font color="red">[R1 - P4]</font></a></li>
  <li><a href="#">LP(A) - Lp(a) Reagent kit - 1R1420 <font color="red">[R1 - P4]</font></a></li>
  <li><a href="#">IGA - Immunoglobulin A - 9P6124 <font color="red">[R1 - P4]</font></a></li>
  <li><a href="#">IGM - Immunoglobulin M - 9P6324 <font color="red">[R1 - P4]</font></a></li>
  <li><a href="#">IGG - Immunoglobulin G - 9P6224 <font color="red">[R1 - P4]</font></a></li>
  <li><a href="#">IGE - IgE Reagent kit - 1R1322 <font color="red">[R1 - P4]</font></a></li>
  <li><a href="#">LDH 2 - Lactate Dehydrogenase 2 - 4T9920 <font color="red">[R1 - P4]</font></a></li>

  <li><a href="#">UALB - Microalbumin - 8P0424 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">UREA - Urea Nitrogen Reagent kit - 8P1620 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">B2-M STD - B2-Microglobulin Standard - 1R0901 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">UIBC CAL - UIBC Calibrator kit - 8P4401 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">CRP WR CAL - CRP Vario Wide Range Cal. kit - 7P5601 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">ASO-RF CTRL 1 - ASO-RF Control 1 kit - 4S0910 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">SPEC PROT CAL - Specific Proteins Multiconstituent Cal. kit - 8P6201 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">BILI CALS - Bilirubin Cal. kit - 8P6101 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">CRP HS CALS - CRP Vario High Sensitivity Cal. kit - 7P5602 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">ASO-RF CTRL 2 - ASO-RF Control 2 kit - 4S0911 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">U/CSF PROT CALS - Urine/CSF Protein Cal. kit - 8P7101 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">PLASMAPROT CAL - Plasmaproteins Cal. 3x kit - 8P6601 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">RF STANDARD - RF Standard - 1R1601 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">MICROALB CALS - Microalbumin Calibrators - 8P0404 <font color="red">[R1 - P5]</font></a></li>
  <li><a href="#">ASO STD - ASO Standard - 1R0601 <font color="red">[R1 - P5]</font></a></li>

  <li><a href="#">GLUCOSE - Glucose Reagent kit - 7P5530 <font color="red">[R1 - P6]</font></a></li>
  <li><a href="#">CRP - CRP Vario Reagent kit - 7P5620 <font color="red">[R1 - P6]</font></a></li>

  <li><a href="#">ULTRA HDL - Ultra HDL Reagent kit - 7P7530 <font color="red">[R2 - P1]</font></a></li>
  <li><a href="#">TESTO -2nd Gen. Testosterone Reagent kit - 7P6832 <font color="green">[R2 - P1]</font></a></li>
  <li><a href="#">ESTRADIOL - Estradiol Reagent kit - 7P5030 <font color="green">[R2 - P1]</font></a></li>
  <li><a href="#">HIV AG/AB- HIV Ag/Ab Combo Reagent kit - 8P0732 <font color="green">[R2 - P1]</font></a></li>
  <li><a href="#">ANTI HCV - Anti HCV Reagent kit - 8P0633 <font color="green">[R2 - P1]</font></a></li>

  <li><a href="#">URIC 2 - Uric Acid 2 - 4U0930 <font color="red">[R2 - P2]</font></a></li>
  <li><a href="#">ANTI TG - Anti TG Reagent kit - 9P3420 <font color="green">[R2 - P2]</font></a></li>
  <li><a href="#">ANTI TPO - Anti TPO Reagent kit - 9P3522 <font color="green">[R2 - P2]</font></a></li>

  <li><a href="#">ASO - ASO Reagent kit - 1R0620 <font color="red">[R2 - P3]</font></a></li>
  <li><a href="#">B2-M - B2-Microglobulin Reagent kit - 1R0920 <font color="red">[R2 - P3]</font></a></li>
  <li><a href="#">MAG - Magnesium - 8P1925 <font color="red">[R2 - P3]</font></a></li>
  <li><a href="#">RF - RF Reagent kit - 1R1632 <font color="red">[R2 - P3]</font></a></li>

  <li><a href="#">PHOSPHORUS - Phosphorus Reagent kit - 8P4020 <font color="red">[R2 - P4]</font></a></li>
  <li><a href="#">VALPORIC - Valporic Acid Reagent kit - 9P9220 <font color="red">[R2 - P4]</font></a></li>
  <li><a href="#">TRIG 2 - Triglyceride 2 - 4U0620 <font color="red">[R2 - P4]</font></a></li>
  <li><a href="#">PROLACTIN - Prolactin Reagent kit - 7P6630 <font color="green">[R2 - P4]</font></a></li>
  <li><a href="#">ANTI HBC M - Anti HBC IgM Reagent kit - 7P8622 <font color="green">[R2 - P4]</font></a></li>
  <li><a href="#">FSH - FSH Reagent kit - 7P4930 <font color="green">[R2 - P4]</font></a></li>
  <li><a href="#">CK-MB STAT - Stat CK-MB Reagent kit - 4V3820 <font color="green">[R2 - P4]</font></a></li>

  <li><a href="#">TDM MC CAL - TDM Multiconstituent Cal. kit - 8P7404 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">IGE STD - IgE Standard - 1R1301 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">MC CALS - Multiconstituent Cal. kit - 8P6001 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">CONCC - Cnosolidated Chemistry cal. - 4V6201 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">FE/MYO/IGE CTRL - Ferritin / Myoglobin / IgE Control kit - 4R4616 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">LIPID MC CAL - Lipid Multiconstituent cal. kit - 9P1403 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">IMMUNO CTRLS - Immuno control set - 8P7517 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">CLIN CHEM CAL - Clinical Chemistry cal. kit - 8P6503 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">LP(A) CALS - Lp(a) control kit - 1R1401 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">PROTEINS CTRL - Proteins control kit - 8p6710 <font color="red">[R2 - P5]</font></a></li>
  <li><a href="#">BILE ACIDS CAL - Total Bile Acids cal. kit - 8P5701 <font color="red">[R2 - P5]</font></a></li>

  <li><a href="#">IRON 2 - Iron 2 - 4T9820 <font color="red">[R2 - P6]</font></a></li>
  <li><a href="#">GGT 2 - Gamma Glutamyl Transferase 2 - 4T9630 <font color="red">[R2 - P6]</font></a></li>
  <li><a href="#">ACID PHOSPHOTASE - 9D8721 <font color="green">[R2 - P6]</font></a></li>

  <li><a href="#">FERRITIN - Ferritin Reagent kit - 7P6530 <font color="green">[R3 - P1]</font></a></li>
  <li><a href="#">B12 - B12 Reagent kit - 7P6732 <font color="green">[R3 - P1]</font></a></li>
  <li><a href="#">FOLATE - Folate Reagent kit - 7P1432 <font color="green">[R3 - P1]</font></a></li>
  <li><a href="#">VIT D 25-OH - 25-OH Vitamin D Reagent kit - 8P4532 <font color="green">[R3 - P1]</font></a></li>
  <li><a href="#">LH - LH Reagent kit - 7P9130 <font color="green">[R3 - P1]</font></a></li>
  <li><a href="#">DHEA-S - DHEA-S Reagent kit - 9P3720 <font color="green">[R3 - P1]</font></a></li>
  <li><a href="#">B-HCG - Total B-hCG Reagent kit - 7P5130 <font color="green">[R3 - P1]</font></a></li>
  <li><a href="#">CA 15-3 - CA 15-3 Reagent kit - 8P5120 <font color="green">[R3 - P1]</font></a></li>

  <li><a href="#">INSULIN - Insulin Reagent kit - 4T7520 <font color="green">[R3 - P2]</font></a></li>
  <li><a href="#">TRAB - Trab Reagent kit - 4V1822 <font color="green">[R3 - P2]</font></a></li>
  <li><a href="#">PROGEST - Progesteron Reagent kit - 8P3620 <font color="green">[R3 - P2]</font></a></li>

  <li><a href="#">CORTISOL - Cortisol Reagent kit - 8P3330 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">TOXO IGG CALS - Toxo IgG cal. - 7P4501 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">TOXO IGM CALS - Toxo IgM cal. - 7P4701 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">SYPHILIS CAL - ST cal. - 7P6001 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">ANTI-HBC CAL - Anti-HBC 2 cal. - 7P8701 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">ANTI-HBC M CALS - Anti-HBC M cal. - 7P8601 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">HE4 CALS - HE4 cal. - 8P5001 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">EBV VCA G CAL - EBC VCA IgG cal. - 9P2101 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">ANTI-HBS CALS - Anti-HBs cal. - 7P8901 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">CMV  IGG CAL - CMV IgG cal. - 7P4201 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">HBSAG QUAL CALS - HBsAg Qualitative 2 cal. - 8P1001 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">HBsAg QualC Manual Diluent - 8P1140 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">PROGEST MANUAL DILUENT - Progesteron Manual Diluent - 8P3640 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">EBV VCA M CAL - EBV VCA IgM cal. - 9P2201 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">CMV IGM CAL - CMV IgM cal. - 7P4401 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">ANTI-CCP CALS - Anti-CCP cal. - 9P2701 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">INSULIN CALS - Insulin cal. - 4T7501 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">ANTI-HCV CAL - Anti-HCV cal. - 8P0602 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">AFP CALS - AFP cal. - 7P9001 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">TSH CALS - TSH cal. - 7P4801 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">TOTAL PSA CALS - Total PSA cal. - 7P9201 <font color="green">[R3 - P4]</font></a></li>
  <li><a href="#">TRAB CALS - TRAb cal. - 4V1801 <font color="green">[R3 - P4]</font></a></li>

  <li><a href="#">CA 19-9 XR CALS - 8P3201 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">CEA CALS - 7P6201 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">ESTRADIOL CALS - 7P5001 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">LH CALS - 7P9101 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">B12 CALS - 7P6701 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">HAVAB IGG CAL - 8P2601 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">HAVAB IGM CAL - 2R2801 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">FSH CALS - 7P4901 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">CA 125 2 CALS - 8P4901 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">DHEA-S CALS - 9P3701 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">CA 15-3 CALS - 8P5101 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">FREE T4 CALS - 7P7001 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">FREE T3 CALS - 7P6901 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">C-PEPTIDE CALS - 9P3601 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">VIT D 25OH CALS - 25-OH Vitamin D cal. - 8P4501 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">RUBELLA IGG CALS - 8P4601 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">FERRITIN CALS - 7P6501 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">TOTAL T3 CALS - 7P9401 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">TOTAL T4 CALS - 7P9501 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">RUBELLA IGM CAL - 8P4701 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">HOMOCYSTEINE CALS - 9P2801 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">FREE PSA CALS - 7P9301 <font color="green">[R3 - P5]</font></a></li>
  <li><a href="#">HIV AG/AB CAL - HIV Ag/Ab Combo cal. - 8P0701 <font color="green">[R3 - P5]</font></a></li>

  <li><a href="#">HE4 - HE4 Reagent kit - 8P5022 <font color="green">[R4 - P1]</font></a></li>
  <li><a href="#">ANTI-CCP - Anti CCP Reagent kit - 9P2720 <font color="green">[R4 - P1]</font></a></li>
  <li><a href="#">AFP - AFP Reagent kit - 7P9030 <font color="green">[R4 - P1]</font></a></li>
  <li><a href="#">ALERE NT-PROBNP - Alere NT-proBNP Reagent kit - 4S7920 <font color="green">[R4 - P1]</font></a></li>
  <li><a href="#">TOXO IGM - Toxo IgM Reagent kit - 7P4732 <font color="green">[R4 - P1]</font></a></li>
  <li><a href="#">TOXO IGG - Toxo IgG Reagent kit - 7P4532 <font color="green">[R4 - P1]</font></a></li>
  <li><a href="#">CMV IGG - CMV IgG Reagent kit - 7P4232 <font color="green">[R4 - P1]</font></a></li>
  <li><a href="#">CMV IGM - CMV IgM Reagent kit - 7P4432 <font color="green">[R4 - P1]</font></a></li>
  <li><a href="#">CA 125 2 - CA 125 2 Reagent kit - 8P4930 <font color="green">[R4 - P1]</font></a></li>
  <li><a href="#">CMV ADIVIDITY - CMV IgG Adividity Reagent kit - 7P4322 <font color="green">[R4 - P1]</font></a></li>

  <li><a href="#">TSH - TSH Reagent kit - 7P4830 <font color="green">[R4 - P2]</font></a></li>
  <li><a href="#">FREE PSA - Free PSA Reagent kit - 7P9330 <font color="green">[R4 - P2]</font></a></li>
  <li><a href="#">TOTAL PSA - Total PSA Reagent kit - 7P9230 <font color="green">[R4 - P2]</font></a></li>
  <li><a href="#">CA 19-9 XR - CA 19-9 XR Reagent kit - 8P3230 <font color="green">[R4 - P2]</font></a></li>
  <li><a href="#">CEA - CEA Reagent kit - 7P6230 <font color="green">[R4 - P2]</font></a></li>

  <li><a href="#">HOMOCYSTEINE - Homocysteine Reagent kit - 9P2820 <font color="green">[R4 - P3]</font></a></li>
  <li><a href="#">SYPHILIS - Syphilis TP Reagent kit - 7P6032 <font color="green">[R4 - P3]</font></a></li>
  <li><a href="#">HBSAG QUALC - HBsAg Qualitative 2 Confirmatory Reagent kit - 8P1122 <font color="green">[R4 - P3]</font></a></li>
  <li><a href="#">HBSAG QUAL - HBsAg Qualitative 2 Reagent kit - 8P1032 <font color="green">[R4 - P3]</font></a></li>
  <li><a href="#">RUBELLA IGG - Rubella IgG Reagent kit - 8P4632 <font color="green">[R4 - P3]</font></a></li>
  <li><a href="#">RUBELLA IGM - Rubella IgM Reagent kit - 8P4732 <font color="green">[R4 - P3]</font></a></li>
  <li><a href="#">TOX AVIDITY - Toxo IgG Avidity Reagent kit - 7P4622 <font color="green">[R4 - P3]</font></a></li>

  <li><a href="#">HAVAB IGG CTRLS - 8P2610 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">ANTI-HBC CTRLS - Anti HBc 2 ctrls - 7P8710 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">ANTI-HBC M CTRLS - Anti-HBc IgM ctrls - 7P8610 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">HBSAG QUAL CTRLS - HBsAg Qualitative 2 ctrls - 8P1010 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">HOMOCYSTEINE CTRLS - 9P2810 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">ANTI-HBS CTRLS - 7P8910 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">CMV IGG CTRLS - 7P4210 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">TOXO IGM CTRLS - Toxo IgM ctrls - 7P4710 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">TRAB CTRLS - 4V1810 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">TOXO IGG CTRLS - 7P4510 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">HE4 CTRLS - 8P5010 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">TOX AVIDITY CTRL - Toxo IgG Avidity ctrls - 7P4610 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">CMV AVIDITY CTRLS - CMV IgG Avidity ctrls - 7P4310 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">C-PEPTIDE CTRLS - 9P3610 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">CMV IGM CTRLS - CMV IgM ctrls - 7P4410 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">FOLATE CTRLS - 8P1410 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">COV-2 IGG 2 CTRLS - SARS-CoV-2 IgG 2 Quant control kit - 6S6112 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">HIV AG/AB CTRLS - HIV Ag/Ab Combo cotrols - 8P0710 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">EBV VCA G CTRLS - EBV VCA IgG ctrls - 9P2110 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">RUBELLA IGM CTRLS - 8P4713 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">RUBELLA IGG CTRLS - 8P4610 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">EBV VCA M CTRLS - EBV VCA IgM ctrls - 9P2210 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">ANTI-CCP CTRLS - 9P2710 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">SYPHILIS CTRLS - Syphilis TP ctrls - 7P6010 <font color="green">[R4 - P4]</font></a></li>
  <li><a href="#">ANTI-HCV CTRLS - 8P0611 <font color="green">[R4 - P4]</font></a></li>

  <li><a href="#">FREE T4 - Free T4 Reagent kit - 7P7030 <font color="green">[R4 - P5]</font></a></li>
  <li><a href="#">FREE T3 - Free T3 Reagent kit - 7P6930 <font color="green">[R4 - P5]</font></a></li>
  <li><a href="#">TOTAL T4 - Total T4 Reagent kit - 7P9520 <font color="green">[R4 - P5]</font></a></li>
  <li><a href="#">TOTAL T3 - Total T3 Reagent kit - 7P9420 <font color="green">[R4 - P5]</font></a></li>
  <li><a href="#">SHBG - SHBG Reagent kit - 9P3820 <font color="green">[R4 - P5]</font></a></li>
  <li><a href="#">C-PEPTIDE - C-Peptide Reagent kit - 9P3620 <font color="green">[R4 - P5]</font></a></li>
  <li><a href="#">IPTH - Intact PTH Reagent kit - 8P3134 <font color="green">[R4 - P5]</font></a></li>
  <li><a href="#">EBV VCA G - EBV VCA IgG Reagent kit - 9P2122 <font color="green">[R4 - P5]</font></a></li>
  <li><a href="#">EBV VCA M - EBV VCA IgM Reagent kit - 9P2222 <font color="green">[R4 - P5]</font></a></li>

  <li><a href="#">HAVAB IGM - HAVAb IgM Reagent kit - 2R2822 <font color="green">[R4 - P6]</font></a></li>
  <li><a href="#">HAVAB IGG - HAVAb IgG Reagent kit - 8P2622 <font color="green">[R4 - P6]</font></a></li>
  <li><a href="#">ANTI HBC M - Anti-HBc M Reagent kit - 7P8622 <font color="green">[R4 - P6]</font></a></li>
  <li><a href="#">ANTI HBS - Anti-HBs Reagent kit - 7P8922 <font color="green">[R4 - P6]</font></a></li>
  <li><a href="#">ANTI HCV - Anti HCV Reagent kit - 8P0633 <font color="green">[R4 - P6]</font></a></li>
  <li><a href="#">COV-2 IGG 2 - SARS-CoV-2 IgG 2 Reagent kit - 6S6122 <font color="green">[R4 - P6]</font></a></li>
  <li><a href="#">COV-2 IGM - SARS-CoV-2 IgM Reagent kit - 6R9122 <font color="green">[R4 - P6]</font></a></li>
  <li><a href="#">PROBE COND - Probe Conditioning Solution - 1R5840 <font color="green">[R4 - P6]</font></a></li>
</ul>

<script>
function myFunction() {
    var input, filter, ul, li, a, i, txtValue;
    input = document.getElementById("myInput");
    filter = input.value.toUpperCase();
    ul = document.getElementById("myUL");
    li = ul.getElementsByTagName("li");
    for (i = 0; i < li.length; i++) {
        a = li[i].getElementsByTagName("a")[0];
        txtValue = a.textContent || a.innerText;
        if (txtValue.toUpperCase().indexOf(filter) > -1) {
            li[i].style.display = "";
        } else {
            li[i].style.display = "none";
        }
    }
}
</script>

</body>
</html>

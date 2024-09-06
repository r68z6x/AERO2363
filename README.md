java c
AERO2363 – Aerospace Structures Studio
Advancing Green Aviation through Composite Wing Design
Executive Summary·   Executive summary
The executive summary provides a summary of the report’s essential information and usually is about 100 to 200 words in length. The abstract should summarise:o   background problem and purpose of the report,o   brief details of the approach, procedure and/or methods,o   important results and/or findings,o   major conclusion(s).      Introduction·   Introduction·   Statement of problem and description of main aim(s) and objective(s),·   Background and review of previous work/research and relationship to the current project,·   Explanations of terminology, if necessary·   Method(s) of approach: how the project objectives will be achieved·   Indications of scope and limitations of the project,·      An outline of the material that is presented in the rest of the report.
Static Analysis
The static analysis of the main spar requires analysis of loading applied to an aircraft during cruise conditions. Cruise conditions are used for the static analysis as this is when the wing will be under the highest static load. The analysis is conducted at ‘Rib 9’. Therefore, only loads from Rib 9 to 25 are considered for the analysis. Aircraft wing structure can be found in Appendix A.
Theory and Modelling
The PILATUS PC-9 uses a PIL15M825 airfoil at its root, and a PIL12M825 wing at its tip. These two airfoil geometries are proprietary, so no airfoil data is publicly accessible. The PILATUS airfoils are based on NACA6415 and NACA6412 airfoils, with modifications to reduce the pitching moment of the geometries [1].    By using the NACA derivatives, the calculated bending moments generated in the main spar are larger than reality, leading to a conservative calculation for the composite wing, and a higher Margin of Safety (MOS) for the composite wing. PILATUS geometries were originally modelled, however it was deemed more accurate to use the NACA airfoils, as the modelled geometries were based on assumptions rather than actual geometries.
Using the NACA airfoils also allows for easier use of XFOIL, a program used for analysing the aerodynamic properties of an airfoil.
The PC-9 has a cruising speed of 154.44m/s at an altitude of 7,620m [2]. At this altitude, the speed of sound is 309m/s, and the Mach number for the PC-9 is 0.499. The flow characteristics can be seen below.Density (kg/m3)Temperature (°C)Dynamic Viscosity (Ns/m2)0.552-34.4751.540 * 10-5Table 1. Fluid characteristics at PC-9 cruise
Using these parameters with the mean chord of each section yields a coefficient of lift for that section from which the lift can be defined. Varying Reynold’s number due to varying chord for each wing section is accounted for by varying the Reynold’s number in XFOIL. The table of drag, lift, and moment coefficients can be foun代 写AERO2363 – Aerospace Structures Studio
代做程序编程语言d at appendix [X].
The resulting lift of each section, spanwise lift distribution, and total lift of the wing can be found at appendix [Y].
To simulate the loading conditionso   Input data: list of all input data (material properties  geometry under consideration)o   Results:
Design loads  stresses§   Design loads  stresses (total load on the main spar  its distribution, shear force and bending moment, shear stress  normal stress at the specified rib location)
Unnotched stress analysisThe static analysis begins with the understanding of how the main spar reacts and behaves when subjected to its designed loads. The first step is to draw a FBD (Free body diagram) of the wing, cutting at rib 9 since this is the point we will be focusing on for this project. The FBD will highlight the parameters required such as dz,   dy1 and 2, P1, P2, Py1, Py2, Pz1, and Pz2, as well as the loads, bending moments and the shear stresses.Figure 1: FBD of the Pc9 wing (section cut at rib 9)
Determining the internal stresses present within the main spar is the next step in this part of the static analysis. This involves calculating the applied and principal stresses, which will point out the areas within the beam that undergo the maximum and minimum levels of stress.
Notched stress analysis   §   Notched stress analysis (SCF, maximum localised stress  strain, residual stress  strain after unloading)
Petersons stress concentration factors chart 4.21a
Fracture analysis
Fracture analysis (K-solutions, MOS evaluation for brittle fracture  plastic collapse)
Dynamic Analysis·   Dynamic analysis   of the main sparo   Introduction: scope of the dynamic analysiso   Theory/modelling: assumptions made and theoretical models usedo   Input data: list of all input data (material properties  geometry under consideration)o   Results:
Dynamic analysis the main spar of PC9wings
Introduction:
Theory and modeling：
Input data：
Results：
Safe life approach§   Safe life approach (Load spectrum, accumulated damage, fatigue life)
Damage tolerant method§   Damage tolerant method (Application of LEFM, inspection intervals, fatigue life)Discussion·   Discussion:o   Effect of the residual stress in notched main spar on its fatigue performanceo   Sequential (over) loading in the given load spectrum  their effect on the fatigue life of the main sparo   Credibility of the calculated results (effect of operational conditions, environmental parameters)
Conclusion·   Conclusions are quite often read by managers before the main text of the report and, hence, should summarise the main points clearly.   This section also may include:o   reference to original aim(s) and objective(s) of report,o   application(s) of results,o   limitations and advantages of the findings,o   judgement/evaluation of the author(s).
   



         
加QQ：99515681  WX：codinghelp

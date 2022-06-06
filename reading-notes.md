id: 20220606163206

## Title

Precision Regulation Model of Water  
and Fertilizer for Alfalfa Based on  
Agriculture Cyber-Physical System

## Notes
- regulation of water/nutrient not precise enough to track alfalfa growth dynamically
    - Current methods (field exp/automation) cannot dynamically track growth, so inprecise water/nutrient regulation
- Paper proposes a water/nutrient regularization based on agriculture cyber-physical system (ACPS)
    - "ACPS is the cyber-physical system (CPS) as designed and applied to agriculture"
    - "an ACPS enhances the ability of agricultural systems to engage in real-time communication, precise regulation and self-coordination through the deeper integration of computation with physical processes"
- Processes involved
    - Alfalfa growth (biological process)
    - Changes in soil moisture/fertilizer (physical process)
    - Regularization Strategy (discrete computational process)
- Proposed model (PRMWFA-ACPS) consists of 
    * Biophysical submodel of Alfalfa
        - Alfalfa Dynamic model (continuous dynamic sim process) [22,31,32]
        - Water Balance Model
        - Nitrogen Balance Model [30,37]
        - Alfalfa BioPhys Model (outputs yield)
     * Computational Submodel (discrete)
        - Computes deficit in water/nutrient
     * Cyber-Physical Interaction Submodel
        - Interaction from Phys to Cyber or vice-versa
        - phys->comp: completes sampling function, can discretize bio process
        - comp->phys: Completes and converts data to physical quantity
- Growth dynamics cannot be perceived by sensing
- Most studies ignored crop growth information( proper to plant) in physical environment
  


### Investigate those refs:
[8]-[11], [13]-[20], [25]-[28], [30]

# Reference:

R. Liu, Y. Zhang, Y. Ge, W. Hu and B. Sha, "Precision Regulation Model of Water and Fertilizer for Alfalfa Based on Agriculture Cyber-Physical System," in IEEE Access, vol. 8, pp. 38501-38516, 2020, doi: 10.1109/ACCESS.2020.2975672.
# HFM Integration and Demonstration Functional Area Q3 FY18 - Q4 FY20 Plan
## Planning Team Members
| Name | Organization |
| --- |
| Michael Lawson | Planning Team Lead |
| David Maniaci | Planning Team Member |
| Myra Blaylock | Planning Team Member |
| Sreyas Ananthan | Team Member |
| Matt Barone | Team Member |

## HFM Integration and Demonstration FY20 Target Use Cases
The overall goal of this task is to demonstrate wind farm and wind turbine simulations at a level of fidelity that is needed to advance the scientific understanding of wind plant physics. In order to accomplish this objective, Nalu will need to have the ability to:

**Use Case 1:** Simulate large wind farms using actuator lines and OpenFAST to model the turbines and LES to model aerodynamics.

**Use Case 2:** Simulate two or more blade-resolved turbines with wake interactions using OpenFAST's FEA capabilities to model  turbines and hybrid RANS-LES to model aerodynamics.

## Dependencies between the tasks and other functional areas
* (1) Further McAlester blade and wing V&V work to better understand the computational requirements of blade resolved modeling
* Validation and demonstration of hybrid RANS-LES simulations that are needed to perform blade resolved turbine simulations in realistic atmospheric conditions.
* Demonstration and preliminary validation of utility scale turbine simulation. This work will hopefully be performed using the Siemens 2.3, pending the availability of data, geometry, etc. (1.5 FTE year)
* (2) Developing and demonstrating methodology to integrate overset capabilities for full turbine simulations (should be completed by Q4 2019) (6 FTE months) - Mike
* UQ work area will have the same or similar demonstration cases.  DAKOTA coupling tasks could fit in either area.

## Resources (particular individuals, FTE amounts, compute-time resources) needed
* See excel spreadsheet
* Demonstrating the two use cases listed above will require that the HFM integration and demonstration team integrates, verifies, validates, and demonstrates several components of Nalu as described in detail in the [associated Gantt chart spreadsheet](https://github.com/lawsonro3/hfm_integration_demonstration_plan/blob/master/gantt_chart.xlsx).

## Key credibility assertion steps that need to be executed
In order to demonstrate the credibility of the Nalu code, the team will need to demonstrate and, as much as possible, validate actuator line and blade resolved simulations. Detailed verification of specific components of Nalu will be performed by other Functional Area teams, and the ultimate success of this Functional Area's work is thus dependent on the work of these other Functional Areas.

The specific steps that this Functional Area will take to demonstrate capability are described in the Gantt chart spreadsheet](https://github.com/lawsonro3/hfm_integration_demonstration_plan/blob/master/gantt_chart.xlsx). Dependencies on other Functional Areas are also noted in this spreadsheet.

## Publications
In order to disseminate the results of our work to the wind R&D community, the HFM Integration and Demonstration team plans the following publications:
* One journal publication/s describing the ABL and actuator line wind farm simulation work. **Estimated date: Q4 FY19**
* One conference or journal publication actuator line and Nalu UQ work. **Estimated date: Q3 FY19**
* One publication on the blade resolved simulation work. **Estimated date: Q4 FY20**
* Other conference papers and presentations as appropriate

## Planningn Team Comments Regarding Feedback received from HFM/ECP Leadership Team on 04 May 2018 (via Spague Email)
Comments:
* FTE: 1.03 FTE/year;

Response: After discussing, the Integration and Demonstration Planning Team feels that slightly more effort (i.e. FTEs) is needed to accomplish the stated goals and the Gantt chart will be updated accordingly.

* The demos and validation studies in this functional area should be with integrated capabilities. For example, the ABL-only simulations/validation should be done in the ABL area. Please work with other areas to reconcile overlaps.

Response: Stable and unstable precursors simulations/development will be performed in the `ABL Functional Area`

* Add task on pursuing/developing NDA with Siemens for validation collaboration, or as coordination with related projects.

Response: This task has been added to the Gantt chart

* Coordination with the Integration FA in Exawind to ensure both use cases are fully covered is needed.

Response: Mike L will coordinate this task with the ECP integration and demonstration planning team

* Past experience suggests modeling lift, drag, and moment forces for the range of airfoils along a wind turbine blade is difficult. Coordinate with ECP-Integration/Demonstration and Hybrid RANS-LES to validate the predictive capability for the 2D airfoils along the blade of the final use case.

Response: Dave M will include this task in the Gantt chart, either as a new high level task, or as a sub task rolled into the blade resolved modeling task

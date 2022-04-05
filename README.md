# WRF_forIdealSims

Two versions of WRF to run the idealized WRF-LES simulations to evaluate wind plant blockage.
- WRF_strongStability: WRF with CPM and GAD. The CPM is compiled to add perturbations in the lower 310 m above the surface.
- WRF_weakStability: WRF with CPM, GAD and upwind advection scheme. The CPM is compiled to add perturbations in the lower 486 m above the surface.

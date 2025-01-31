# openCFS-3D-geometry-simp-scheme-pressure-equation
Optimizer used: ipopt, method: SIMP, Boundary Condition at Nozzle_curve: Pressure equation,

running Terminal Commands:

    cfs -m box3d-t_0.3-nx_200-ny_20-nz_20.mesh F3D_distributed_load
    show_density F3D_distributed_load.density.xml
    plotviz.py F3D_distributed_load.plot.dat -x 1 -y 2 4
    For comparison between multiple .dat files: plotviz.py *.plot.dat -x 1 -y 2 4

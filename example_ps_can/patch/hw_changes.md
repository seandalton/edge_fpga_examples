

Add the following to the *.tcl file: 
```tcl
startgroup
set_property -dict [list CONFIG.PSU__CAN1__PERIPHERAL__ENABLE {1} CONFIG.PSU__CAN1__PERIPHERAL__IO {MIO 40 .. 41} CONFIG.PSU__PMU__PERIPHERAL__ENABLE {0}] [get_bd_cells zynq_ultra_ps_e]
endgroup
```

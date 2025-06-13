
   95 invariant.stream.txt
  295 da_state.stream.txt
  265 mpasout.nc.txt

  288 restart.stream.txt
  381 restart_include_invariant.txt
  339 restart.nc.txt

The following two variables appear twice,
one in the invariant stream xml section 
and one in the restart stream xml section 

#ifdef MPAS_CAM_DYCORE  
                        <var name="cell_gradient_coef_x"/>                                                                                                             
                        <var name="cell_gradient_coef_y"/>
#endif  


The following variables are in both invaraint and da_state:
cd sort
comm -12 da_state.stream.txt invariant.stream.txt

albedo12m
greenfrac
isice_lu
isltyp
iswater_lu
ivgtyp
lai12m
landmask
landusef
mminlu
shdmax
shdmin
snoalb
soilf


13 scalars:
qv
qc
qr
qi
qs
qg
ni
nr
ng
nc
nifa
nwfa
volg

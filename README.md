
### 1. Number of variables (excluding scalars) in the sorted txt file
```
   93 invariant.stream.txt
  294 da_state.stream.txt
  252 mpasout.nc.txt

  285 restart.stream.txt
  378 restart_include_invariant.txt
  326 restart.nc.txt
```

### 2. Variables in both invariant and da_state:
```
cd sort
comm -12 da_state.stream.txt invariant.stream.txt
```
Results:
```
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
```

### 3. 13 scalars
```
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
```

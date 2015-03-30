# shallowFoamTutorials
Tutorials for shallow water solver shallowFoam

Contains two tutorial case:

  - pflegerTests are a number of 1D-validation cases, that can be compared with analytical solutions
  - dornbirnerAche is a real flooding scenario of the river Dornbirner Ache in Vorarlberg, Austria

The setups should be self-explanatory. All cases can be run with the 'Allrun' script in the respective directory. dornbirnerAche is setup such that it will be executed in parallel on eight processors. Check Allrun and decomposeParDict for adjustment.

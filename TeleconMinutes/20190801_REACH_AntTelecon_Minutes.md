# Minutes of Antennas Telecon
## Date: 2019-08-01
## Present: 
- [x] Dirk de Villiers
- [x] Brandt Klopper
- [x] Eloy de Lera Acedo
- [x] Nima Razavi
- [x] Nicolas Fagnoni
- [x] John Cumner
- [ ] Quentin Gueuning
- [x] Nafsika Memeletzoglou
- [ ] Steve Carey
- [ ] Christophe Craeye
- [x] Jean Cavillot
- [ ] Christos Kolitsidas
- [x] Iman Farhat
- [x] Ian 

## Discussions
- Brandt presents FoM performance slides for:
    - Elliptical Dipole
    - TEM Horn
    - Conical Sinuous
- More will become available soon
- Discussion on ground plane size for initial design. Option between fixing the size to have same (similar) chromatic effects, or leaving it as free optimization parameter.  Latter option chosen, with decision to limit the maximum size.  Main issue is smaller GPs have slower chromatic variations, but typically lower sensitivity due to ground noise. Sensitivity must be included as FoM, but exact weight uncertain at this stage. Also not expected that any antenna can be made to have small enough ground pick-up to not be of the order of the EoR signal, so we'll have to deal with that anyway.

## Action Items
- Get/nominate repo for all the simulation files (Dirk)
- Brandt should include the EDGES antenna in his FoM screening calculations
- Start antenna performance matrix sheet to compare all the different antennas (Brandt/Dirk)
- Speed up FoM script for optimization purposes (Brandt/Dirk)

## Next Agenda
- Next meeting 2019-08-05
- Quick meeting to get feedback on status of FoM script deployment
- AoB

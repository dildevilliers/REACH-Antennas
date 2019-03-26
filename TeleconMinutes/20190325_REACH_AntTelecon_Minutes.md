# Minutes of Antennas Telecon
## Date: 20190326
## Present: 
Dirk de Villiers, Brandt Klopper, Eloy de Lera Acedo, Nima Razavi, Nicolas Fagnoni, Nafsika Memeletzoglou, John Cummer, Quentin Gueuning

## Discussions
- Brandt presents slides on current simulation work: EDGES (High) and Sinuous Antennas.  EDGES sim looks close to their results.
- Nicolas and Cambridge team also working on similar EDGES (Low) simulations.  CST results don't line up yet - possible difficulty with balun simulation.
- Nima provides summary of receiver/calibration system.  Some important points:
    - |S11| of antenna must be very small since this is a major issue in EDGES calibration.  Noise wave between LNA and antenna.
    - Balun might be a problem here since it is difficult to make well-matched and smooth over wide bandwidth.
    - Receiver will need 50 Ohm coax interface with antenna (most likely)
- Eloy comments:
    - 2 Polarisations are handy for foreground subtraction
    - Could be very difficult to isolate in a co-located system (receiver-cal), so non co-located 2-pol is an option

## Action Items
- Dirk makes repo for slides and meeting minutes
- Brandt and Cambridge team to collaborate on EDGES simulation models
- Stellenbosch starts implementing FOM for antenna beams
- Nima can prepare a comparison between his receiver/calibration system and that of EDGES

## Next Agenda
- Next meeting 20190401
- Cambridge team present simulation results
- Nima presents comparison between REACH and EDGES receivers
- Timeline for antenna project
- Feedback from Stellenbosch about FOM implementation
- Possible face-2-face meeting
- AOB

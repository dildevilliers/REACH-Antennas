# Minutes of Antennas Telecon
## Date: 2020-04-20
## Present: 
- [x] Dirk de Villiers
- [x] Eloy de Lera Acedo
- [x] Nima Razavi
- [ ] Nicolas Fagnoni
- [x] John Cumner
- [x] Quentin Gueuning
- [ ] Nafsika Memeletzoglou
- [x] Steve Carey
- [ ] Christophe Craeye
- [x] Jean Cavillot
- [ ] Christos Kolitsidas
- [ ] Iman Farhat
- [x] Ian Roque 
- [ ] Paul
- [x] Harry Bevins
- [x] Dominic Anstey
- [x] Ergin Dinc
- [x] Will Hadley

## Discussions
- Dirk led discussion on the Antenna simulation.  All agree TD and FD simulations do not agree, and the FD simulation of the current antenna is best given that it is similar to HARP result.
    - Nima is busy with a FEKO model to confirm using commercial MoM
    - Current antenna is not the optimal design by Brandt, and Dirk will forward those to all.
    - Need to do these checks again with the actual antenna with the correct balun and feed.

- Nima discusses the RX (REACH@home) system
    - There are some issues with CW injection mixing into our band
    - Can remove these by noise injection instead of CW
    - Some other spurs also remain, most likely from the ADC
    - These ADC spurs are narrow band and can be flagged and filtered digitally
    - Ian is able to log in and generate data and do some experiments, so RX work is ongoing

- Steve gives update on thermal design
    - looks like 80W input power translates to ~10K temp increase with new cooling fan system
    - Thermal issues seems to be resolved on the design side.  Practical tests will follow at some stage

- Ian and Will gives feedback on the pipeline
    - A pipeline is available to do tests where a know signal is input and the system needs to estimate it
    - Priors have a substantial effect on the posterior estimates
    - Ian experimenting with different priors to get a handle on what is required

## Action Items
- Dirk to send Cambridge/Antenna team the latest CST files from Brandt
- Need to recheck these in FD and TD simulations

## Next Agenda
- Next meeting 2020-05-04 
- TBD
- AoB

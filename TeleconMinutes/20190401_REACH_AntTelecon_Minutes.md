# Minutes of Antennas Telecon
## Date: 20190401
## Present: 
Dirk de Villiers, Brandt Klopper, Eloy de Lera Acedo, Nima Razavi, Nicolas Fagnoni, John Cumner, Quentin Gueuning, Christphe Craeye

## Discussions
- Eloy provided a note on FoM for antenna designs for REACH
- Cambridge team presents slides on current simulations of several antennas with more realistic soil model.
- Nima presents some slides on camparison between REACH and EDGES calibration:
    - Makes the point again that at ~2000K sky, and 200 mK signal, the antenna match must be excellent
    - EDGES calibration possibly underdetermined
    - REACH will measure all elements in the chain in the field and regularly
- Eloy comments (offline):
    - @Quentin. Have you tried with the log spiral in a flat plane? I think Christos looked at something like that and cavity backed.
    - @Christophe, Jean, Nicolas and Quentin. Could we try using Jean’s code to simulate the EDGES antenna on top of a finite ground plane and soil?
    - @Nima. If we measure more parameters in the field to calibrate the receiver, how do we calibrate the VNA or the sources? Still in the lab I assume? So my question is, measuring in the field after a while will be more or less accurate than doing it in the lab and then relying on the stability of the amplifiers? rather than that of the sources or VNA... Do you have any estimations of that?
- Nima response:
    We actually do a full 2-port calibration of the VNA in the field using mechanical standards (Kirkby Microwave 85033).  It's important that they are mechanical standards since the two ports have different physical standards connected.  See the attached picture. We also have the possibility of two ref planes as indicated on the diagram.  Once this calibration is complete, we then measure the various source S11.  These are the parameters we need.
    VNA measurements:  Antenna S11, all sources S11 (up to 7 sources), LNA full 2 port, AMP1 S11 Spectrometer measurements: Spectra from all sources in the field.
    The only lab collected data we may have to rely on is the ENR table of the diode noise source. These diode sources are actually thermally insulated so they are very reliable over temperature.  We also have the full s-parameters of all the switches although I do not believe we will need them for this.
    Depending on how much these parameters vary, we may do this once or twice a day.  In normal operation, we would then need to switch between the antenna, load and noise source. EDGES spends the same amount of time on each calibrator meaning they only observe the sky 1/3 of the time, we may be able to do better than that.

## Further Discussion at EuCAP: Dirk, Eloy and Christos (Timeline)
- Brandt will work on a MATLAB function to calculate FoMs from FEKO/CST file bases inputs.  Will do this in collaboration with Christos, in an effort to use a uniform interface and have a backup version to test implementation (Christos has some Python scripts for this). Target for completion: End of 201904.
- Cambridge team focus on antenna simulations and designs of several options.  Brandt helps where possible.
- Use 201905 to down select the most promising candidates.  These are not final antennas, but will be used for field testing and sorting out installation, interface, manufacturing pipeline, purchasing, and other general issues.
- Brandt visits Cambridge for ~2|3 weeks around end of 201905 for interface and detail design of candidate element(s).
- Manufacturing of first test prototype starts mid 201906, with completion target mid 201907.
- First field tests early 201908.

## Action Items
- Everyone works through the FoM note by Eloy to start discussions next week
- Dirk will look for paper on Karoo soil presented by US EMC team at ICEAA.  Hardie Pienaar also might have some information.
- Brandt and Cambridge team continues to collaborate on EDGES simulation models.
- Cambridge team will upload the conical spiral paper of the BigHorn system
- Stellenbosch continues implementing FOM for antenna beams - see new note by Eloy  
- Christos Kolitsidas to be added to the group

## Next Agenda
- Next meeting 20190408
- Dirk presents initial timeline
- Eloy leads discussion on FoM's
- Brandt feedback on FoM implementation
- Cambridge feedback on element simulations
- Repo/Wiki access
- AOB

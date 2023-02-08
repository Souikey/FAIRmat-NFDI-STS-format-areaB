# Scanning tunneling spectroscopy (STS)
[STS](https://en.wikipedia.org/wiki/Scanning_tunneling_spectroscopy) was developed following the invention of the scanning tunneling microscope (STM) to probe surface electronic structure. Employing a sharp tip on a substrate, current (I) curves are measured without scanning, usually as a function of voltage (I vs V or simply I/V curves) [G. Binnig et al. in Physical Review Letters](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.55.991). A correct measurement of such curves enable intepretation of the material's electronic and vibrational structure. Additionally, curves can be recorded per x,y pixel leading to a I/V, dI/dV and d<sup>2</sup>I/dV<sup>2</sup> mapping or microscopy [R. J. Hamers et.al. in Physical Review Letters](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.56.1972). 

## I/V, dI/dV and d<sup>2</sup>I/dV<sup>2</sup> curves
Today, I/V curves are recored by means of a phase senstive detection device, such as a lock-in amplifier. Depending on the correct usage of the lock-in amplifier, this allows the user to filter the I/V, dI/dV and d<sup>2</sup>I/dV<sup>2 signal and to approximatelly measure the dI/dV and d<sup>2</sup>I/dV<sup>2</sup> data. 

The following are the parameter set involved in STS. Most parameters are recorded during measurment employing the SPECS Group GmbH Nanonis BP5e (not in the order read by the BP5e software)  
	
Parameters marked with + stem from FAIRMat-NFDI consortia discussions

## Parameter description of STS
### File type
+ Background file
+ Reference file
+ Sample file
+ Filename 221122_Au_5K00014	
- Scan>series name	221122_Au_5K	
	
### Spectroscopy resolution (ref...)
- Temperature 1>Temperature 1 (K)	4.92997E+0	
- Lock-in>Modulated signal	Bias (V)	1E-3

- Integration time (s)	150E-6 
- Bias Spectroscopy>Number of sweeps	100	
- Bias Spectroscopy>Sweep Start (V)	-300E-3 	
- Bias Spectroscopy>Sweep End (V)	300E-3	 
- Bias Spectroscopy>Num Pixel	4096	 
- Bias Spectroscopy>Z Avg time (s)	100E-3
- NanonisMain>RT Frequency (Hz)	20E+3	
- NanonisMain>Signals Oversampling	10	
- NanonisMain>Acquisition Period (s)	20E-3	
- NanonisMain>Animations Period (s)	20E-3	
- NanonisMain>Indicators Period (s)	300E-3	
- NanonisMain>Measurements Period (s)	500E-3	

### Tip-sample height and reproducibility (ref...)
- Bias>Bias (V)	100E-3	 
- Current>Current (A)	-5.3429E-15	

- Bias>Calibration (V/V)	1E+0	 
- Bias>Offset (V)	0E+0
- Current>Calibration (A/V)	100E-12	
- Current>Offset (A)	16.2897E-15	
- Current>Gain	Not switchable	
- Z offset (m)	0E+0 
- Settling time (s)	2.1E-3  
- Z-Ctrl hold	TRUE 
- Final Z (m)	N/A
- Start time	23.11.2022 18:55:16	 
- Bias Spectroscopy>Z offset (m)	0E+0	 
- Bias Spectroscopy>1st Settling time (s)	2.1E-3 	
- Bias Spectroscopy>Settling time (s)	2.1E-3	 
- Bias Spectroscopy>Integration time (s)	150E-6	
- Bias Spectroscopy>End Settling time (s)	4E-3	
- Bias Spectroscopy>Z control time (s)	200E-3	
- Bias Spectroscopy>Max Slew rate (V/s)	1E+0	
- Bias Spectroscopy>backward sweep	TRUE	
- Bias Spectroscopy>Z-controller hold	TRUE
- Z-Controller>Controller name	log Current	
- Z-Controller>Controller status	OFF	
- Z-Controller>Setpoint	50E-12	
- Z-Controller>Setpoint unit	A	
- Z-Controller>P gain	6E-12	
- Z-Controller>I gain	39.8241E-9	
- Z-Controller>Time const (s)	150.662E-6	
- Z-Controller>TipLift (m)	0E+0	
- Z-Controller>Switch off delay (s)	0E+0 

### Software filtering (ref...)
- Filter type	Butterworth	 
- Order	1  
- Cutoff frq	0,01

### Hardware filtering (ref...)
- Lock-in>LP Filter Cutoff D1 (Hz)	621.699E+0	
- Lock-in>LP Filter Cutoff D2 (Hz)	621.699E+0	
- Lock-in>LP Filter Order D1	8	
- Lock-in>LP Filter Order D2	8	
- Lock-in>Sync Filter D1	ON	
- Lock-in>Sync Filter D2	ON	

### Lock-in (ref...)
- Bias Spectroscopy>Channels	Current (A);LI Demod 2 X (A);LI Demod 2 Y (A);LI Demod 1 X (A);LI Demod 1 Y (A)	
- Bias Spectroscopy>Reset Bias	TRUE	
- Bias Spectroscopy>Record final Z	FALSE	
- Bias Spectroscopy>Lock-In run	FALSE	
- Lock-in>Lock-in status	ON	
- Lock-in>Modulated signal	Bias (V)	
- Lock-in>Frequency (Hz)	973E+0	
- Lock-in>Amplitude	2E-3	
- Lock-in>Demodulated signal	Current (A)	
- Lock-in>HP Filter Cutoff D1 (Hz)	621.699E+0	
- Lock-in>HP Filter Cutoff D2 (Hz)	621.699E+0	
- Lock-in>HP Filter Order D1	1	
- Lock-in>HP Filter Order D2	1	
- Lock-in>Harmonic D1	1	
- Lock-in>Harmonic D2	2	
- Lock-in>Reference phase D1 (deg)	137.597E+0	
- Lock-in>Reference phase D2 (deg)	-83.6562E+0	
	
### Position
- X (m)	-890.53E-12  
- Y (m)	29.6968E-9 
- Z (m)	130.5E-9
- Z-Controller>Z (m)	130.5E-9	

### Software

- NanonisMain>Session Path	C:\Users\SPM-PEEM\Desktop\DATA_Nanonis\20220711_CreaTec_Service_Benchmarks_LHe\Nanonis-Session-PMD100-HVHU_CreaTec_Service_PalmaLabBerlin220711	
- NanonisMain>SW Version	Generic 5e	
- NanonisMain>UI Release	10771	
- NanonisMain>RT Release	10771	

### Cabling and Piezo
- Outputs>Output 0 Mode	User Output	
- Outputs>Output 1 Mode	User Output	
- Outputs>Output 2 Mode	User Output	
- Outputs>Output 3 Mode	User Output	
- Outputs>Output 4 Mode	User Output	
- Outputs>Output 5 Mode	User Output	
- Outputs>Output 6 Mode	User Output	
- Outputs>Output 7 Mode	User Output	
- Outputs>Output 0 Value	0E+0	
- Outputs>Output 1 Value	0E+0	
- Outputs>Output 2 Value	0E+0	
- Outputs>Output 3 Value	2.5539E+0	
- Outputs>Output 4 Value	0E+0	
- Outputs>Output 5 Value	0E+0	
- Outputs>Output 6 Value	0E+0	
- Outputs>Output 7 Value	0E+0	
- Outputs>Output 0 Name	Input 24 (V)	
- Outputs>Output 1 Name	Bias (V)	
- Outputs>Output 2 Name	Output 2 (V)	
- Outputs>Output 3 Name	T1 Supply voltage (V)	
- Outputs>Output 4 Name	Output 4 (V)	
- Outputs>Output 5 Name	X (m)	
- Outputs>Output 6 Name	Y (m)	
- Outputs>Output 7 Name	Z (m)	
- Outputs>Output 0 Slew Rate	Inf	
- Outputs>Output 1 Slew Rate	Inf	
- Outputs>Output 2 Slew Rate	Inf	
- Outputs>Output 3 Slew Rate	Inf	
- Outputs>Output 4 Slew Rate	Inf	
- Outputs>Output 5 Slew Rate	Inf	
- Outputs>Output 6 Slew Rate	Inf	
- Outputs>Output 7 Slew Rate	Inf	
- Piezo Configuration>Active Calib.	LHe	
- Piezo Configuration>Calib. X (m/V)	3.8E-9	
- Piezo Configuration>Calib. Y (m/V)	3.8E-9	
- Piezo Configuration>Calib. Z (m/V)	900E-12	
- Piezo Configuration>HV Gain X	14.5	
- Piezo Configuration>HV Gain Y	14.5	
- Piezo Configuration>HV Gain Z	14.5	
- Piezo Configuration>Tilt X (deg)	0.318343	
- Piezo Configuration>Tilt Y (deg)	1.584	
- Piezo Configuration>Curvature radius X (m)	Inf	
- Piezo Configuration>Curvature radius Y (m)	Inf	
- Piezo Configuration>2nd order corr X (V/m^2)	0E+0	
- Piezo Configuration>2nd order corr Y (V/m^2)	0E+0	
- Piezo Configuration>Drift X (m/s)	0E+0	
- Piezo Configuration>Drift Y (m/s)	0E+0	
- Piezo Configuration>Drift Z (m/s)	0E+0	
- Piezo Configuration>Drift correction status (on/off)	FALSE	

### Scan parameters
- Scan>Scanfield	3.11737E-9;29.1583E-9;15E-9;15E-9;0E+0	
- Scan>channels	Current (A);Bias (V);Z (m);LI Demod 2 X (A);LI Demod 2 Y (A);LI Demod 1 X (A);LI Demod 1 Y (A)	
- Scan>pixels/line	512	
- Scan>lines	512	
- Scan>speed forw. (m/s)	11.7187E-9	
- Scan>speed backw. (m/s)	11.7187E-9	

### Comments
- Comment01	SYNC & Filter LP 8order WITHDRAW 600 steps, locked Au(111), 50pA, 100 mV set point, 1mV DCA, 973Hz,138 1st H, -84  2nd H	 


### Data Format
[DATA]
Bias calc (V)	Current (A)	LI Demod 2 X (A)	LI Demod 2 Y (A)	LI Demod 1 X (A)	LI Demod 1 Y (A)	Current [bwd] (A)	LI Demod 2 X [bwd] (A)	LI Demod 2 Y [bwd] (A)	LI Demod 1 X [bwd] (A)	LI Demod 1 Y [bwd] (A)	Current (A) [filt]	LI Demod 2 X (A) [filt]	LI Demod 2 Y (A) [filt]	LI Demod 1 X (A) [filt]	LI Demod 1 Y (A) [filt]	Current (A) [bwd] [filt]	LI Demod 2 X (A) [bwd] [filt]	LI Demod 2 Y (A) [bwd] [filt]	LI Demod 1 X (A) [bwd] [filt]	LI Demod 1 Y (A) [bwd] [filt]

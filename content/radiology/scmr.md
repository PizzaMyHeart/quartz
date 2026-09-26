# Magnetic fields

- B0 (torque, projectile)

- B1 (heating/SAR, malfunction) - RF field, B1+ transmit body coil in scanner, B1- receive surface coils

- Gradient (acoustic noise, PNS effects) - Gx, Gy, Gz - localisation and shimming (reduce inhomogeneity)

  

Field gradients for spatial encoding

Slice select gradient 

Readout (frequency) gradient

Phase encoding (y) gradient

k-space centre has contrast information, periphery has contour information

Every echo is a line in k-space

  

SPGR wastes, bSSFP recycles otherwise wasted magnetisation

  

SAR

- Flip angle

- B0

  

PNS

- Slew rate (gradient switching rate)

  

Gad

- 1/1000 any reaction

- 1/20000 severe allergic reaction

- 3/1000000 death

- eGFR < 30 or AKI

- Group II GBCAs can be used in renal failure

  

Gad dose 0.1 - 0.2 mmol/kg

LGE at 10 - 15 minutes

  

Normal T1 of precontrast myocardium and contrast is 600 - 700 ms

Postcontrast myocardium T1 is shortened but not thrombus

500 - 600 ms inversion time for mural thrombus in AMI at 1.5T

Inversion pulse, then scar containing gad regains T1 more rapidly than normal myocardium

2 R-Rs between each inversion pulse preferred for arrhythmia (over 1 R-R)

Thrombus is homogeneously hypointense on PSIR

  

Remodelling and scar post MI takes 2 weeks

  

Bipolar gradients for velocity encoding

  

Flow = Velocity x Area

VENC 200 cm/s for Ao and Pu

VENC > max V to avoid aliasing

Lower VENC stronger gradient, higher VENC weaker gradient

Higher VENC lower precision and more noise

  

Aliasing can cause underestimation of velocity and flow

Cause of phase background - eddy currents in gradient mounts from gradient switching

0.6 cm/s is acceptable

Higher velocity offset with high gradient amplitude, and with oblique instead of transverse plane, worse for Pu than Ao

Best to have perpendicular image plane to vessel (can have up to 10 deg misalignment), otherwise can underestimate flow

Underestimation of velocity in turbulent flow (eddy currents) - can be mitigated by higher VENC and shorter TE

  
  

Planes

3-plane localiser

2Ch localiser: axial and sagittal

SAX localiser (SAO): 2Ch localiser + axial; basal slice just above mitral valve towards apex

Cines all using 2 oblique localisers, 20 - 30 phases

4Ch cine: 2Ch localiser (MV through LV apex) + SAO (MV through TV)

2Ch cine: 4Ch (MV through LV apex) + SAO (parallel to RV insertion)

3Ch cine: SAO (basal through LVOT) + 2Ch (mid MV through LV apex)

Coronal LVOT cine: SAO (LVOT) + 3Ch/sagittal LVOT (mid MV through LVOT)

Radial AoV (also good for ASD): Coronal LVOT + Sagittal LVOT

  

or

Axial localiser -> p2Ch

p2Ch -> p4Ch

p4Ch + p2Ch -> SA (AV groove to apex)

SA + p2Ch -> 4Ch

SA + 4Ch or p4Ch -> 2Ch

SA (aortic valve and posterior wall; snowman) + 2Ch or 4Ch -> 3Ch (sagittal LVOT)

  

SA atria same slice thickness, no gap, end systole, AV groove to posterior wall (alternatively continue posteriorly from SA ventricles with same parameters)

  

Cine sequences (GRE) low TR

1. Spoiled GRE

2a. SSFP: FISP, GRASS

2b. bSSFP: TrueFISP, FIESTA, b-FFE

Single-shot - fill k-space in one heartbeat

  

SSFP parameters

Retrospective gating (prospective if arrhythmia with window 100 ms shorter than RR), acquisition window at least equal to RR interval

Temporal resolution < 25 ms

Phases > 25 (40  
Slice thickness/gap  7 mm/3 mm, 8 mm/2 mm

FOV freq 300 - 400, FOV phase 75%

Matrix 256 x 75

  

Ventricular volume, function and mass - cine MRI is reference technique

  

LV quantification 2D (less accurate) or 3D Simpson's (volumetric, more accurate, discs to cylinder)

Atrial quantification - end systole (max volume), end diastole (minimum volume) and before atrial contraction

Volumes higher on SSFP than spoiled GRE

Myocardial mass = volume (epicardial minus endocardial) x myocardial specific density

  

RV volume can be calculated from SA or transverse

RV wall mass calculations exclude ventricular septum

  

Atrial volumes at end systole (maximum)

For LA use biplane area-length method excluding LAA and pulmonary veins; contour LA endocardium in both 2Ch and 4Ch with mitral annulus as anterior border

Area-length method: Volume = (0.85 x area^2)/length

LAEF = (LAVmax - LAVmin) / LAVmax

  

RA no consensus, but generally includes RAA and excludes IVC and SVC

Max RA volume is during ventricular systole, last cine image before opening of tricuspid valve

  

Myocarditis - STIR

TR should finish mid-to-late diastole (85%)

Acquire every other cardiac cycle

Ratio of global myocardial T2 to skeletal muscle > 2 is abnormal

Pre- and postcontrast imaging < 15s

Difference in SI pre- and post- / precontrast SI >= 45% is abnormal

  
  

Lake Louise myocarditis

Regional or global increased T2 myocardium

Increased global myocardial early gadolinium enhancement relative to skeletal muscle (ratio > 4 is abnormal)

1+ focal lesion with non-ischaemic distribution on LGE

  

Parametric mapping Messroghli 2017 JCMR

Diastolic preferred

Diffuse disease: basal and mid SA +/- long axis

Patchy disease: basal and mid SA + long axis

ROI placement: mid septum SA for global disease (alternatively basal septum SA)

  

ECV mapping requires post-contrast (0.1 - 0.2 mmol/kg non protein-bound, 15 min delay), haematocrit at time of CMR

T2 mapping for myocardial oedema and inflammation (changes also manifest on T1 mapping)

  

Perfusion CMR

3 slices per cardiac cycle (base, mid, apex), each slice is 3 mm and takes 200 ms

Dark-rim artefact - early, lasts < 8 frames, ~1 voxel width

Adenosine infusion 140 mcg/kg/min for 4-6 minutes

Regadenoson 400 mcg bolus (longer half-life)

  

MRA 

Acquisition window can be increased to 4 mm (for larger vessels)

High-resolution noncontrast MRA with T2-prep SSFP ECG-gating and respiratory navigation (no breath-holding). Takes longer to obtain.

ECG-gated contrast MRA uses breath-holding

Dynamic contrast MRA fills centre of k-space only, low spatial resolution

Phase contrast MR to quantify blood flow

Arterial spin-labelling MRA for peripheral vessels (long acquisition time)

  

AoV SA stack for 2D planimetry - 3Ch and coronal LVOT

Measure at peak systole at leaftlet tips

Peak AV velocity - use in-plane flow to find area of peak velocity (aliasing), then do perpendicular through-plane flow here

2D CMR PC can underestimate peak AV velocity compared to Doppler

Scar (LGE) predicts increased mortality after AVR

AR - through-plane at aortic root

Significant AS -> assess for concomitant amyloidosis

AR and MR - LVSV > RVSV

TR and PR - RVSV > LVSV

  

# Congenital 

L-R shunt indications for surgery: right heart dilatation, Qp:Qs > 1.5

  

## ASD

Only secundum ASD amenable to catheter closure

Suspected PH needs catheter monitor before repair

  

RV morphological features

- Apical insertion of tricuspid valve

- LV has smooth septal surface

  

## L-TGA

- Ventricular inversion

- Hyperdynamic LV (high EF, supplies pulmonary circulation)

- RV systolic function

  

## D-TGA

- Needs atrial septostomy to survive until repair (VSD mixing not sufficient)

- Arterial switch: Le Compte to move RPA anterior to aorta, then reimplantation of coronary buttons

- Atrial switch: SVC and IVC baffled to mitral valve

-  Rastelli (TGA/VSD): VSD closure baffling LV to aorta, RV to pulmonary trunk conduit

  

## TOF

- Anterocephalad deviation of the outlet septum

- Pulmonary regurgitation post repair - PR usually laminar flow so less dephasing (use phase contrast)

- Right heart dilatation - RVESVi, RV mass

- Imaging at least every 3 years

  

## HCM 

Septal variant - spiral pattern of hypertrophy counterclockwise from base to apex

Concentric variant - LGE RV insertion sites

Apical variant

LGE > 15% LV mass is indication for primary prevention ICD

  

Fabry

Low native T1

LGE basal inferolateral wall

Can have concentric hypertrophy

  

Iron overload - low T2*

Myocardial T2* < 20 ms predicts heart failure

  

Non-compaction cardiomyopathy - NC/C > 2.3:1 end-diastolic long axis

  

MI

SPECT vs CMR - SPECT ok for transmural but less sensitive for subendocardial

LGE size, microvascular obstruction predict worse outcome after MI

Acute vs chronic MI - acute high T2 (oedema), microvascular obstruction (only in acute not chronic)

Intramyocardial haemorrhage - low T2

Viability assessment - cine (ED thickness; thinning predicts lack of recovery sensitive but not specific), LGE, dobutamine stress

  

Gating

- Retrospective more common, 1.2 heartbeats worth of data collected asynchronously, more artefact in arrthymias 

- Prospective better in arrhythmia (can see valves) but end-diastole will be missing (no data from atrial kick)

- Alternative is real-time imaging (all of k-space for each part of the cardiac cycle, lower temporal resolution)

  

Arrhythmia options

- triggered retrospective with arrhythmia rejection

- real-time cine (lower spatial and temporal resolution)

- compressed sensing real-time cine

  

Arrhythmia imaging - function and LGE (fibrotic substrate is hallmark of arrhythmias)

Respiratory navigator-gated imaging for LGE in arrhythmia (data acquired during end expiration, higher spatial resolution)

AF - MRA to assess pulmonary veins, pre-ablation LA LGE to identify fibrotic substrate

  

Grey zone (mixture of viable myocardium and scar) predicts sudden cardiac death

Voltage mapping can identify epicardial and papillary scarring, grey zone, channels (ablation targets)

  

ICD interprets gradient or RF activity as VT/VF

Artefact

- bSSFP require field homogeneity - reduced in homogeneity by moving generator

- Use SE instead of GRE for localisers, non-balanced GRE cine, reduce TE (increase bandwidth, adjust inversion pulse for LGE)

- Left arm up

- End-inspiratory breath hold (heart moves down with diaphragm away from device)

  

# Pericardial disease

- Echo 1st-line

- SSFP cines (breath hold) or real-time bright-blood GRE (look for respiratory variation in septal motion, ventricular interdependence)

- T1 black blood SE for pericardial thickness

- LGE

- Velocity-encoded flow imaging for ventricular interdependence

- SPAMM (tagging)

- > 4 mm thickness is abnormal

- LGE predicts response to anti-inflammatories

  

# Cardiac masses

- 1st-line TTE, 2nd-line CMR

- First-pass perfusion

- Met vs myxoma - both have heterogeneous LGE but myxoma no first pass perfusion, mets perfuse well

- Fibroma not first-pass perfusion but diffuse LGE

- Thrombus dark on perfusion and LGE
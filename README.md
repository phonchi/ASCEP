# A Speedy and robust Cryo-EM processing Platform (ASCEP)
Cryo-EM Platform Integrates Competitive Algorithms to Meet Current Challenges

## Motion Correction
### Whole Frame Alignment
1. MotionCorr (MotionCorr2, Relion, Warp)
2. Unblur (CisTEM)
3. Full-frame motion correction (CryoSparc)
4. Optical Flow (Xmipp)
### Per-particle based alignment
1. alignparts (CryoSparc(local, patch), alignparts-lmbfgs)
2. Bayesian Polishing (Relion, 3D Reference required)

## CTF Estimation
### Whole Frame
1. ctffind (CisTEM)
2. gctf
### Patch-based/tilt data
1. Patch-Based CTF Estimation (CryoSparc, Warp)
### Per-particel
1. ctf refinement (Relion)

## Particle-pickeing
### Semi-superviesd
1. Topaz
2. Cryolo
### Template-based
1. Relion, CryoSparc
### Automatic
1. DoG, loG

## 2D classification
### MRA-based
1. ISAC
2. CL2D
3. EMAN2
4. SPIDER
### Maximum-likelihood
1. Relion
2. CryoSparc
### Mixed
1. ROME

## Ab-initial 
### Using class-averages
1. Simple
### Using particles
1. CryoSparc

## 3D Refinemnet
1. Relion
2. CryoSparc

## 3D classification
1. Relion


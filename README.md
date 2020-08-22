# TomoRecProcess
To automatically process dataset for cryo subtomogram averaging workflow

## Step 1
Transfer files from remote location to staging server for preprocessing
Globus transfer
Via SSH

## Step 2
Preprocessing align frames and for drift corrections
Tags: **unblur**, **MotionCorr**

## Step 3
CTF estimation
Tags: **ctffind4**, **gCTF**

### Contrast Transfer Function Correction (CTF correction)

## Step 4
Organize files according to Navigation ID

## Step 5
Algin stacks
Tags: [IMOD](https://bio3d.colorado.edu/imod/)

## Step 6

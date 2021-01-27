# Batch Imaging of Labels and Specimens

This workflow is for digitizing specimens from the MAJC by capturing the labels and dorsal habitus of the specimen in a single image.

## Set-up
* Access the imaging system, makesure the space and equipment is free
* Select the drawer you will be digitizing specimens from, bring it to the workstation
* Have MAJC catalog number labels ready


## Verify focus of camera
 __This needs tobe fleshed out__
 Make sure that the camera is level and focused on the stage, take a test image or two to verify and adjust focus and height of camera as needed.
 
## Imaging a specimen
 1. Select the first specimen to image
   1. remove labels using forceps, align labels onthe high part of the stage, arrange labels from top to bottom as they were on the pin
   1. add catalog number label (typically at the end of all other labels except for determination label)
   1. leave any dissection pieces on the pin.  plastic vials below labels may be removed and should be placed on the stage with the labels if there is room
   1. align the pinned specimen with the head pointing up, or the point pointing up, at the same level as the labels, try to plane the specimen to acheive the best flat dorsal view
   1. confirm that all items are located within the outlined corners of the imaging space.
   1. place stage under camera aligned within the taped-out box on the platform, be sure that the labels are oriented to be right-side-up within the image
   1. trigger the shutter on the camera **update with computer-controlled instructions later**
   1. replace all labels onto the pin, being sure to include the catalog number just above the determination label
 1. image next specimen
   1. follow steps as outline above
   1. **if only a header determination label on a single specimen -** then leave the det label on the stage and add the "header determination" tag to the stage.  Use this det label for the whole series and be sure that the det label is returned to the specimen it was originally affixed to.


## Recording your progress
After imaging a set of specimens, create a list of catalog number ranges and the correlating species identifications within those ranges, such as:
* MAJC0001200 - MAJC0001300 Eleodes armata M.A. Johnston 2015
* MAJC0001301 - MAJC0001400 Eleodes longicollis M.A. Johnston 2018
* MAJC0001401 - MAJC0001405 Eleodes longicollis M.A. Johnston 2020
* etc

## Upload images to computer
**Update this later**
All images must be imported to *Adobe Bridge* in an albumn with todays date.
Import images from SD card. Prune out duplicates/bad photos.  Use batch rename tool to serially name images, confirm that true catalog number is labelled corectly.

## Export images
**update this later**
Export images with catalogNumber as file name - export as large jpgs with slight compression
Use Adobe Bridge to export using JPG high profile.
Batch rename '.jpeg' files in command line:
```
for file in *.jpeg; do mv $file ${file%.jpeg}.jpg; done
```
## Upload to ecdysis
**update this later**
Use scp from local directory to copy files to image repository.
Upload to folder /mnt/storage/image_processing/images/ecdysis/MAJC (or subdirectory there)
Upload skeletal file containing catalog numbers and species determinations
run batch image loader.

# Data entry and transcription
**update this later**
Set processing status accordingly
Write guide to include collecting event matching, georeferencing, and OCR text extraction, as needed.

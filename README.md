Telomere length analyzer
========================

## Application
This Excel script calculates the mean telomere length from a telomeric restriction fragmentation (TRF) Southern blot image. Currently, the maximum number of lanes it can process is **20**.

## How to Use
- Evenly partition each lane on the gel image to 30 parts, and measure the color / shade intensity from any gel image software.

- Determine the position of the size ladders / markers in terms of the partition. Set the position of each ladder / marker band in the first section "Ladders".
![step1](img/Step1.png "Step 1: ladder position")

- Combine all the intensity data into one column, and copy to the second section "Volumn".
![step2](img/Step2.png "Step 2: volumn information")

- Setup the sample information in the third section.
![step3](img/Step3.png "Step 3: sample information")

- Run the script by clicking the button in the fourth section.
![step4](img/Step4.png "Step 3: mean telomere length calculation")



## Copyright
This Excel VBA script program was developed while I was working in laboratory of [Dr. David Gilley](http://genetics.medicine.iu.edu/faculty/david-p-gilley-ph-d/) in Indiana University, School of Medicine, Indianapolis. It was improved based on the [TeloRun](http://www4.utsouthwestern.edu/cellbio/shay-wright/research/sw_lab_methods.htm) program developed in the laboratory of [Dr. Jerry Shay and Dr. Woodring Wrigth](http://www4.utsouthwestern.edu/cellbio/shay-wright/) in University of Texas Southwestern Medical Center.


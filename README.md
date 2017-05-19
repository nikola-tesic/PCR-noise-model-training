# PCR-noise-model-training
This workflow is for training of PCR stutter and step models that are later used in the main Microsatellite instability pipeline. Tools used in this workflow are all from lobSTR toolkit (https://github.com/mgymrek/lobstr-code)

Inputs files are:
1. Reads - reads in FASTQ format
2. Index - reference genome

If reads are paired end, they should contain metadata field "Paired end", which needs to be set to "1" and "2".

Workflow should be ran only using the largest male normal sample representing that data submitting center and that sequencing platform, and that models should later be used for all samples that are from same that data submitting center and sequencing platform.

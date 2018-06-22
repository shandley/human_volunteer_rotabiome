# Human Volunteer Rotabiome Study

63 healthy volunteers were enrolled to test how antibiotic pre-treatment altered vaccine immunogenicity.

[[https://github.com/shandley/human_volunteer_rotabiome/graphical_abstract.png]]

## Cohort Break down:

* 21 Control patients
* 21 patients treated with oral vancomycin
* 21 pateinets treated with oral vancomycin, ciprofloxacin and metronidazole

Antibiotics were provided for 7 days (day -3 to -9) prior to vaccination with the following vaccines:

* Pneumo 23
* Rotarix
* Tetanus toxoid

Vaccination outcome was determined by a combination of fecal and serum antibody tests at periods for 28 days. Stool was collected at Day -9 (antibiotic initiation), Day 0 (vaccine administration) and Day 7 (post-vaccination) and subjected to 16S rRNA gene amplicon sequencing. Samples were demultiplexed and preprocessed with dada2 to extract amplicon sequence varaints (ASVs). ASVs were analyzed using R with heavy reliance on PhyloSeq.

## Sample failure rate

There was an unexpectedly high failure rate on the sequencing run with 50 out of the 172 sample failing to produce enough sequences to pass processing in dada2.

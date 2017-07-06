# Processing
General pipelines

## Single-echo BOLD processing pipeline
Files
* Makefile_preproc_all: File to copy the BOLD-preproc.mk file into all subects based on a list of subjects in subjects.txt. Creates a folder with subject name to copy subsequent processed imaged.
* BOLD_preproc.mk: BOLD fMRI preprocessing: Includes motion correction, brain extraction, amoothing, detrending, registration to T1
* t1.txt: Subjects with no corresponding T1 file.

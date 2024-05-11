# A small sample set of the work I did in Named Entity Recognition in 2021.

## For the ones using Conditonal Random Fields, this is the setup to run it. 
  Named Entity Recognition using CRF toolkit
  
  Step 1 : python NER_corpus.py
  
  Step 2 : crf_learn -c 3.0 template train.data model -t
  
  Step 3 : crf_test -m model test.data>result.txt
  
  Step 4 : python NER_accuracy.py
  
  Step 5 : python NER_run.py

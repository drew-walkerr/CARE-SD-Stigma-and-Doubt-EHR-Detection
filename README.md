# CARE-SD-Stigma-and-Doubt-EHR-Detection

The code in this respository provides tools for researchers seeking to identify stigmatizing and doubt marking language in the electronic health record. 
We utilized the MIMIC-III dataset, consisting of de-identified patient notes from Beth Israel Deaconness Medical Center in Boston, MA, from 2002-2012 for training data in this sample.
Sentence-level matching was conducted on expanded lexicons for doubt markers and stigmatizing labels, created using stem lists from literature reviews and word embeddings models, and then matched sentences were randomly selected for annotation, and used to train refined supervised learning classification models. 

These tools are available to other researchers and were developed as part of Drew Walker's doctoral dissertation at Emory University's Department of Behavioral, Social, and Health Education Sciences.

Please reference our citation below when using these tools in future work:

Walker D, Thorne A, Das S, et al. CARE-SD: Classifier-based analysis for recognizing and eliminating stigmatizing and doubt marker labels in electronic health records: model development and validation. Published online May 8, 2024. doi:10.48550/arXiv.2405.05204


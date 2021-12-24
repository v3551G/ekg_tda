# ekg_tda
This is an algorithm which identifies P,Q,S, and T-waves as optimal representative 1-cycles using persistent homology and then measures the PR-interval, QT-interval, ST-segment, QRS-duration, P-wave duration, and T-wave duration based off of the
upper and lower time axis bounds of these representative cycles. Briefly, P,Q,S, and T waves are characterized using dimension one homological features with a persistence and center of mass of representative cycle within certain ranges depending on the specific waveform. For better understanding and intuition about what the topological invariants of the data are and how they're used to measure various intervals of interest and eventually characterize arrhythmias, see "ekg_feature_extraction_intro.docx".

https://github.com/hdlugas/ekg_tda/issues/1#issue-1088458489

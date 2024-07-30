# renewal_chains_with_frequency
Datasets generated for the paper "Experimental comparison of unsupervised methods for deinterleaving pulse trains".
Filename of the form : "sc_65_dis_T_let_5_5000_m_30_ar_50_br_0_bf_1_seq.txt" or "sc_65_dis_T_let_5_5000_m_30_ar_50_br_0_bf_1_targ.txt":
'sc_65' : scenario number 65 (from 0 to 100)
'dis_T' : Disjoint case is True (always True here)
'let_5_5000 : Five letters (or symbols) and 5000 pulses
'm_30' : 30 percent of missing pulses
'ar_50' : maximum of 50 stops
'br_0' : time noise (always zero here)
'bf_1' : frequency noise of variance 1 MHZ
'seq' : the file is the observed sequence
  First line of the file : Symbols
  Second line : Frequencies
  Third line : Times of Arrival
'targ' : ground truth
  First line : Number of the emitter which emitted the corresponding pulse.

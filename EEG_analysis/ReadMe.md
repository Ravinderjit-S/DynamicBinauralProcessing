# EEG Processing of em-seq binaural modulation

This folder contains the code to analyze the EEG data recorded from a em-seq binaural modulation. The following 4 files do the bulk of analysis and figure generation. 

<ol>
<li> AnalyzeBinaural_Mseq.py 
<ol>
<li> Intial processing of EEG data. Filter, remove ocular artifiacts, and decimate. </li>
</ol>
</li>
<li> DynBin_sysFuncs_PCA.py </li>
<ol>
<li> Further clean EEG data by rejecting noisy epochs with large p2p. Compute binaural transfer functions (mcBTRF) and noise floors.</li>
</ol>
<li> DynBin_sysFuncs_averageSubjects_PCA.py </li>
<ol>
<li> This script averages mcBTRFs across subjects and does a PCA analysis to get a sBTRF. Also does comparison with behavior
</li>
</ol>
<li> DynBinProccFig.py </li>
<ol>
<li> This script generates plots to show process for computing sBTRF
</li>
</ol>
</ol>




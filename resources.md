---
title: Resources
layout: page
permalink: /resources/
show_excerpts: false
entries_layout: list
---

## Software

The software offered on this webpage is subject to the [BSD license](bsd_license.md){:target="_blank"}, unless mentioned otherwise.

If you use this software, or a modified version of it, for generating results that are published in a research paper, it would be highly appreciated if you include the appropriate *Key reference* (indicated with each of the software packages below) in your bibliography.

### 3-D Finite Difference Time Domain (FDTD) Room Acoustics Simulator

Julia package containing an implementation of the 3-D finite difference time domain (FDTD) method for simulating spatiotemporal sound fields in rectangular and L-shaped rooms.

**Software:** Julia package \[[GitHub repository](https://github.com/nantonel/JuFdtd){:target="_blank"}\]

**Key reference:** Niccoló Antonello, Toon van Waterschoot, Marc Moonen, and
Patrick A. Naylor, **Identification of surface acoustic impedances
in a reverberant room using the FDTD Method**,
in *Proc. 2014 Int. Workshop Acoustic Signal Enhancement (IWAENC
'14)*, Antibes, France, Sept. 2014, pp. 115-119.
\[[Published](https://doi.org/10.1109/IWAENC.2014.6953349){:target="_blank"}\] \[[Archived](https://ftp.esat.kuleuven.be/pub/stadius//nantonel/14-84.pdf){:target="_blank"}\]

**License:** Copyright (c) 2015, Niccol&oacute; Antonello. All rights reserved. Published under [MIT Expat License](https://github.com/nantonel/JuFdtd/blob/master/LICENSE.md){:target="_blank"}.

### Randomized Image Method

MATLAB code &amp; Julia package containing an implementation of the randomized image method for simulating room impulse responses in rectangular rooms.

**Software:** Two independent implementations of the randomized image method are available:
* MATLAB code \[[GitHub repository](https://github.com/enzodesena/rim){:target="_blank"}\]
* Julia package \[[GitHub repository](https://github.com/nantonel/JuRIM){:target="_blank"}\]

**Key reference:** Enzo De Sena, Niccoló Antonello, Marc Moonen, and Toon van
Waterschoot, **On the modeling of rectangular geometries in room
acoustic simulations**,
*IEEE/ACM Trans. Audio Speech Language Process.*, vol. 23, no. 4,
Apr. 2015, pp. 774-786.  
\[[Published](https://doi.org/10.1109/TASLP.2015.2405476){:target="_blank"}\] \[[Archived](https://lirias.kuleuven.be/retrieve/355227){:target="_blank"}\]

**Additional files:** Sound samples and Matlab examples corresponding to the results published in the *Key reference* \[[webpage](href="http://desena.org/sweep/){:target="_blank"}\]

**License:** Both implementations come with a different license:
* MATLAB code: Copyright (c) 2015, Enzo De Sena. All rights reserved. Published under BSD license.
* Julia package: Copyright (c) 2015, Niccol&oacute; Antonello. All rights reserved. Published under [MIT Expat License](https://github.com/nantonel/JuFdtd/blob/master/LICENSE.md){:target="_blank"}.

### Distributed Estimation of Cross-Correlation Functions

MATLAB package containing an implementation of several distributed algorithms for estimating the cross-correlation functions between a pair of sensor signals in a wireless sensor network.

**Software:** MATLAB functions:
* Monte Carlo simulation script for different values of *M* \[[M (7 KB)](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/15-40/distcorr_mcscript_M.m){:target="_blank"}
* Monte Carlo simulation script for different values of TD \[[M (8 KB)](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/15-40/distcorr_mcscript_TD.m){:target="_blank"}
* ADMM algorithm for consensus deconvolution \[[M (7 KB)](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/15-40/distcorr_admm.m){:target="_blank"}

**Key reference:** Toon van Waterschoot, **Distributed estimation of
cross-correlation functions in ad-hoc microphone arrays**,
in *Proc. 23rd European Signal Process. Conf. (EUSIPCO '15)*, Nice,
France, Sept. 2015, pp. 260-264 (invited paper).  
\[[Published](https://eurasip.org/Proceedings/Eusipco/Eusipco2015/papers/1570104749.pdf){:target="_blank"}\] \[[Archived](https://ftp.esat.kuleuven.be/pub/SISTA/vanwaterschoot/reports/15-40.pdf){:target="_blank"}\]

**Additional files:** These files can be used to reproduce the results in the *Key reference* using the provided MATLAB functions.  
* room impulse responses \[[MAT (0.5 KB)](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/15-40/distcorr_RIRs.mat){:target="_blank"}
* figure generation script \[[M (14 KB)](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/15-40/distcorr_figgenscript_eusipco2015.m){:target="_blank"}

**License:** Copyright (c) 2015, Toon van Waterschoot. All rights reserved. Published under [BSD license](bsd_license.md){:target="_blank"}.

### Biquadratic Parametric Equalizer Filter Design

MATLAB package containing an implementation of a pole-zero placement technique for designing biquadratic (i.e., second-order IIR) parametric equalizer filters.
			  
**Software:** MATLAB function \[[M (3 KB)](https://ftp.esat.kuleuven.be/pub/SISTA/vanwaterschoot/downloads/software/06-177/pareq.m){:target="_blank"} 

**Key reference:** Toon van Waterschoot and Marc Moonen, **A pole-zero placement
technique for designing second-order IIR parametric equalizer
filters**,
*IEEE Trans. Audio, Speech, Lang. Process.*, vol. 15, no. 8, Nov.
2007, pp. 2561-2565.  
*Note: the publisher made a typesetting error in Eqs. (28) and (29). The term "-1" should be included under the square root in both equations. Please refer to the archived version of the paper for the correct equations.*  
\[[Published](https://doi.org/10.1109/TASL.2007.905180){:target="_blank"}\] \[[Archived](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/reports/06-177.pdf){:target="_blank"}\]

**Additional files:** MATLAB script to reproduce the design examples in the *Key reference* \[[M (5 KB)](https://ftp.esat.kuleuven.be/pub/SISTA/vanwaterschoot/downloads/software/06-177/pareq_designexamples.m){:target="_blank"} 

**License:** Copyright (c) 2006, Toon van Waterschoot. All rights reserved. Published under [BSD license](bsd_license.md){:target="_blank"}.

### Double-Talk Robust Acoustic Echo Cancellation

MATLAB package containing an implementation of several prediction-error-method(PEM)-based adaptive filtering algorithms for double-talk robust acoustic echo cancellation.

**Software:** MATLAB functions \[[TAR.GZ (5 KB)](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/05-162/algorithms.tar.gz){:target="_blank"}

**Documentation:** Manual \[[PDF (179 KB)](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/reports/05-162.pdf){:target="_blank"}

**Key reference:** Toon van Waterschoot, Geert Rombouts, Piet Verhoeve, and Marc
Moonen, **Double-talk-robust prediction error identification
algorithms for acoustic echo cancellation**,
*IEEE Trans. Signal Process.*, vol. 55, no. 3, Mar. 2007, pp.
846-858.
\[[Published](https://doi.org/10.1109/TSP.2006.887155){:target="_blank"}\] \[[Archived](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/reports/05-161.pdf){:target="_blank"}\]

**Additional files:** These files can be used to reproduce the results in the *Key reference* using the provided MATLAB functions.  
* room impulse responses \[[MAT (16 KB)](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/05-162/RIR.mat){:target="_blank"}
* sound signals \[[TAR.GZ (1218 KB)](https://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/05-162/signals.tar.gz){:target="_blank"}

**License:** Copyright (c) 2005, Toon van Waterschoot. All rights reserved. Published under [BSD license](bsd_license.md){:target="_blank"}.

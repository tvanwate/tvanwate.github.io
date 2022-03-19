---
title: Resources
layout: page
permalink: /resources/
show_excerpts: false
entries_layout: list
---

## Software

The software offered on this webpage is subject to the [BSD license](bsd_license.html){:target="_blank"}, unless mentioned otherwise.*  

If you use this software, or a modified version of it, for generating results that are published in a research paper, it would be highly appreciated if you include the appropriate *Key reference* (indicated with each of the software packages below) in your bibliography.*

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
* MATLAB code: Copyright (c) 2015, Enzo De Sena. All rights reserved. Published under BSD license.</li>
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

**License:** Copyright (c) 2015, Toon van Waterschoot. All rights reserved. Published under [BSD license](bsd_license.html){:target="_blank"}.

<!---------------------------------------------------------------------------------------------------------------------------->
<br />
		    <table border="0" cellpadding = "0" cellspacing = "0" width = "100%" style="padding: 0px 0px 0px 0px; font-size: 10pt; font-family: sans-serif">
			<tr>
			  <td align="left"><a name="software_pareq"><h3 style="color: #333">Biquadratic Parametric Equalizer Filter Design</h3></a>
			  MATLAB package containing an implementation of a pole-zero placement technique for designing biquadratic (i.e., second-order IIR) parametric equalizer filters.
			  </td>
			</tr>
		    </table>
		    <table border="0" cellpadding = "5" cellspacing = "0" width = "100%" style="padding: 0px 0px 0px 0px; font-size: 10pt; font-family: sans-serif">
			<tr>
			  <td style="color: #666; vertical-align:text-top; width: 93px">Software:</td>
			  <td>MATLAB function <a target="blank" href="ftp://ftp.esat.kuleuven.be/pub/SISTA/vanwaterschoot/downloads/software/06-177/pareq.m">[M (3 KB)]</a></td>
			</tr>
			<tr>
			  <td style="color: #666; vertical-align:text-top; width: 93px">Key reference:</td>
			  <td>Toon van Waterschoot and Marc Moonen, "<a href="ftp://ftp.esat.kuleuven.be/pub/SISTA/vanwaterschoot/abstracts/06-177.html">A pole-zero placement technique for designing second-order IIR parametric equalizer filters</a>", <i>IEEE Trans. Audio, Speech, Lang. Process.</i>, vol. 15, no. 8, Nov. 2007, pp. 2561-2565.</td>
			</tr>
			<tr>
			  <td style="color: #666; vertical-align:text-top; width: 93px">Additional files:</td>
			  <td>MATLAB script to reproduce the design examples in the <i>Key reference</i> <a target="blank" href="ftp://ftp.esat.kuleuven.be/pub/SISTA/vanwaterschoot/downloads/software/06-177/pareq_designexamples.m">[M (5 KB)]</a>
			  </td>
			</tr>
			<tr>
			  <td style="color: #666; vertical-align:text-top; width: 93px">License:</td>
			  <td>Copyright (c) 2006, Toon van Waterschoot. All rights reserved. Published under <a target="blank" href="bsd_license.html">BSD license</a>.</td>
			</tr>
		    </table>
<br />
<!---------------------------------------------------------------------------------------------------------------------------->
<br />
		    <table border="0" cellpadding = "0" cellspacing = "0" width = "100%" style="padding: 0px 0px 0px 0px; font-size: 10pt; font-family: sans-serif">
			<tr>
			  <td align="left"><a name="software_robustaec"><h3 style="color: #333">Double-Talk Robust Acoustic Echo Cancellation</h3></a>
			  MATLAB package containing an implementation of several prediction-error-method(PEM)-based adaptive filtering algorithms for double-talk robust acoustic echo cancellation.
			  </td>
			</tr>
		    </table>
		    <table border="0" cellpadding = "5" cellspacing = "0" width = "100%" style="padding: 0px 0px 0px 0px; font-size: 10pt; font-family: sans-serif">
			<tr>
			  <td style="color: #666; vertical-align:text-top; width: 93px">Software:</td>
			  <td>MATLAB functions <a target="blank" href="ftp://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/05-162/algorithms.tar.gz">[TAR.GZ (7 KB)]</a></td>
			</tr>
			<tr>
			  <td style="color: #666; vertical-align:text-top; width: 93px">Documentation:</td>
			  <td>Manual <a target="blank" href="ftp://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/reports/05-162.pdf">[PDF (179 KB)]</a></td>
			</tr>
			<tr>
			  <td style="color: #666; vertical-align:text-top; width: 93px">Key reference:</td>
			  <td>Toon van Waterschoot, Geert Rombouts, Piet Verhoeve, and Marc Moonen, "<a href="ftp://ftp.esat.kuleuven.be/pub/SISTA/vanwaterschoot/abstracts/05-161.html">Double-talk-robust prediction error identification algorithms for acoustic echo cancellation</a>", <i>IEEE Trans. Signal Process.</i>, vol. 55, no. 3, Mar. 2007, pp. 846-858.</td>
			</tr>
			<tr>
			  <td style="color: #666; vertical-align:text-top; width: 93px">Additional files:</td>
			  <td>These files can be used to reproduce the results in the <i>Key reference</i> using the provided MATLAB functions.  
				<ul>
				    <li>room impulse responses <a target="blank" href="ftp://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/05-162/RIR.mat">[MAT (16 KB)]</a></li>
				    <li>sound signals <a target="blank" href="ftp://ftp.esat.kuleuven.be/pub/sista/vanwaterschoot/downloads/software/05-162/signals.tar.gz">[TAR.GZ (1218 KB)]</a></li>
				</ul>
			  </td>
			</tr>
			<tr>
			  <td style="color: #666; vertical-align:text-top; width: 93px">License:</td>
			  <td>Copyright (c) 2005, Toon van Waterschoot. All rights reserved. Published under <a target="blank" href="bsd_license.html">BSD license</a>.</td>
			</tr>
		    </table>
<br />
<!---------------------------------------------------------------------------------------------------------------------------->
<!---------------------------------------------------------------------------------------------------------------------------->
<br />
            <a name="data"><h2>Data</h2></a>
		    <!--<table border="0" cellpadding = "0" cellspacing = "0" width = "100%" style="padding: 0px 0px 0px 0px; font-size: 10pt; font-family: sans-serif">
			<tr>
			  <td align="left"><h3 style="color: #333">Small Room Impulse Responses</h3>
			  To do
			  </td>
			</tr>
		    </table>
		    <table border="0" cellpadding = "5" cellspacing = "0" width = "100%" style="padding: 0px 0px 0px 0px; font-size: 10pt; font-family: sans-serif">
			<tr>
			  <td style="color: #666; width: 54px">Period:</td>
			  <td>Jan 2007 &ndash; Dec 2011</td>
			</tr>
			<tr>
			  <td style="color: #666; width: 54px">Funding:</td>
			  <td>Belgian Science Policy Office (Interuniversity Attraction Poles Phase VI)</td>
			</tr>
			<tr>
			  <td style="color: #666; width: 54px">Partners:</td>
			  <td>Universit&eacute; Catholique de Louvain, KU Leuven, Ghent University, Vrije Universiteit Brussel, Universit&eacute; de Li&egrave;ge, Universit&eacute; de Mons, Universit&eacute; Libre de Bruxelles</td>
			</tr>
			<tr>
			  <td style="color: #666; width: 54px">URL:</td>
			  <td><a target="blank" href="http://sites.uclouvain.be/dysco/">sites.uclouvain.be/dysco</a></td>
			</tr>
			<tr>
			  <td style="color: #666; width: 54px">My role:</td>
			  <td>Research Fellow</td>
			</tr>
		    </table>-->
        </div>
    </body>
</html>

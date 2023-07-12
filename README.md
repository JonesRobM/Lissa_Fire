# Atto9 Supporting information
## Introduction
HHG is a versatile process, finding utility as both a tool to explore the dynamics and structure of atoms and molecules using the harmonic generation process itself, and as a flexible source of short, bright, coherent pulses of high-frequency radiation for use in further experiments. 

One tool that has mostly lacked from this development is the polarisation of the emitted harmonics, which has been essentially confined to linear polarisations along the polarisation of the driving IR field. The lack of circularly polarised pulses completely eliminates
the extent to which the chiral structures of matter can be investigated.

The immediate response to this problem, of course, is to try to produce high-order harmonics using an elliptically polarised driver, but this does not work. The generation of high-order harmonics is in its essence a recollision-based phenomenon, and in the presence of an elliptical driver the three-step-model electrons will be shifted aside and miss the ion in their oscillations, quickly quenching the harmonic emission.

## Selection Rules
HHG is, at its core, a recollision phenomenon, and bicircular fields are only able to produce high-order harmonics efficiently because electrons that are tunnel-ionised near the peak of each lobe have a large probability of recolliding with the ion.

The harmonic emission, however, is much easier to understand from a frequency domain perspective. For the usual high-order harmonic generation, with a linearly polarized driver, the time-dependent picture of the three-step model can be usefully complemented by a photon picture analogous to the ones from harmonic generation in perturbative nonlinear optics, where we envision $n$ photons of the linear driver at photon energy $\omega$ as combining to form a single harmonic photon at energy $n\omega$.



\begingroup
\fontsize{10pt}{12pt}\selectfont

\begin{tikzpicture}[
   scale=0.5,
   level/.style={thick},
   photon/.style={thick,->,shorten >=0.5pt,shorten <=0.5pt,>=stealth},
 ]    
 \providelength{\smap} \setlength{\smap}{2cm} % small photon
 \providelength{\bigp} \setlength{\bigp}{3cm} % big photon
 \providelength{\sep} \setlength{\sep}{0.35cm} % (1/2) separation between the up and down arrows of each diagram
 \providelength{\lvlwidth} \setlength{\lvlwidth}{0.75cm} % (1/2) width of the horizontal 'level' lines
%
 \draw[level] (-\lvlwidth,  0cm) -- (\lvlwidth,  0cm);
 \draw[level] (-\lvlwidth,7\smap) -- (\lvlwidth,7\smap);
 \draw[photon] (-\sep, 0\smap) -- (-\sep, 1\smap) node[midway, left] {\begin{turn}{90}$\omega,\linpol$\end{turn}};
 \draw[photon] (-\sep, 1\smap) -- (-\sep, 2\smap) node[midway, left] {\begin{turn}{90}$\omega,\linpol$\end{turn}};
 \draw[photon] (-\sep, 2\smap) -- (-\sep, 3\smap) node[midway, left] {\begin{turn}{90}$\omega,\linpol$\end{turn}};
 \draw[photon] (-\sep, 3\smap) -- (-\sep, 4\smap) node[midway, left] {\begin{turn}{90}$\omega,\linpol$\end{turn}};
 \draw[photon] (-\sep, 4\smap) -- (-\sep, 5\smap) node[midway, left] {\begin{turn}{90}$\omega,\linpol$\end{turn}};
 \draw[photon] (-\sep, 5\smap) -- (-\sep, 6\smap) node[midway, left] {\begin{turn}{90}$\omega,\linpol$\end{turn}};
 \draw[photon] (-\sep, 6\smap) -- (-\sep, 7\smap) node[midway, left] {\begin{turn}{90}$\omega,\linpol$\end{turn}};
 \draw[photon] (\sep,7\smap) -- (\sep,  0cm) node[midway,right] {\begin{turn}{90}$7\omega,\linpol$\end{turn}};
%
\end{tikzpicture}

\endgroup





<p float="left">
  <img src="/Figs/Liss_Tref.gif" width="300" />
  <img src="/Figs/Liss_CoRot.gif" width="300" /> 
</p>

<p float="left">
<img src="/Figs/Liss_Abs_Neg.jpeg" width = 250 />
<img src="/Figs/Liss_Abs_Plus.jpeg" width = 250 />
</p>

Because of the three-fold symmetry of the field each of these recollisions, with their attendant bursts of XUV radiation, is necessarily mirrored by two other identical sets of trajectories and radiation bursts, trailing each other by a third of a period of the fundamental and rotated with respect to each other by 120°.


<p float="left">
  <img src="/Figs/Tref_Wheel.png" width = 500 />
</p>

<p float="left">
  <img src="/Figs/Liss_Figs_AC.png" width = 500 />
</p>

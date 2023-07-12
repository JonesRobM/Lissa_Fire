# Atto9 Supporting information
## Introduction
HHG is a versatile process, finding utility as both a tool to explore the dynamics and structure of atoms and molecules using the harmonic generation process itself, and as a flexible source of short, bright, coherent pulses of high-frequency radiation for use in further experiments. 

One tool that has mostly lacked from this development is the polarisation of the emitted harmonics, which has been essentially confined to linear polarisations along the polarisation of the driving IR field. The lack of circularly polarised pulses completely eliminates
the extent to which the chiral structures of matter can be investigated.

The immediate response to this problem, of course, is to try to produce high-order harmonics using an elliptically polarised driver, but this does not work. The generation of high-order harmonics is in its essence a recollision-based phenomenon, and in the presence of an elliptical driver the three-step-model electrons will be shifted aside and miss the ion in their oscillations, quickly quenching the harmonic emission.

## Selection Rules
HHG is, at its core, a recollision phenomenon, and bicircular fields are only able to produce high-order harmonics efficiently because electrons that are tunnel-ionised near the peak of each lobe have a large probability of recolliding with the ion.

The harmonic emission, however, is much easier to understand from a frequency domain perspective. For the usual high-order harmonic generation, with a linearly polarized driver, the time-dependent picture of the three-step model can be usefully complemented by a photon picture analogous to the ones from harmonic generation in perturbative nonlinear optics, where we envision $n$ photons of the linear driver at photon energy $\omega$ as combining to form a single harmonic photon at energy $n\omega$.

With bicircular drivers, on the other hand, the emission can combine n photons of the fundamental with n ± 1 photons of its oppositely-polarized second harmonic, leaving one net unit of angular momentum which can be discharged with a harmonic photon. 

## Bicurcular Fields

An arbitrary bichromatic field with relative frequencies $p\omega$ and $q\omega$ may be written as,
```math
\underline{E}(t) = Re\left[ \underline{E}_{p}e^{-(ip\omega t +\varphi_{p})} +  \underline{E}_{q}e^{-i(q\omega t + \varphi_{q})}  \right]
```
which each field may be assumed to have its own unique phase, $\varphi$.

In the simplest non-trivial case where the ratio is $2:1$, we may construct the general family of such fields. It is natural to represent them as their Lissajous figure, the parametric form of their transverse field amplitudes.

<p float="left">
  <img src="/Figs/Liss_Figs_AC.png" width = 300 />
</p>

Neglecting trivial cases, such as one of the drivers having zero amplitude, two regimes emerge: evidence of three-fold symmetry within the Lissajous figure, and none whatsover. One may visualise these respectively as counter-rotating and co-rotating.

<p float="left">
  <img src="/Figs/Liss_Tref.gif" width="300" />
  <img src="/Figs/Liss_CoRot.gif" width="300" /> 
  <img src="/Figs/Liss_Abs_Neg.jpeg" width = 300 />
  <img src="/Figs/Liss_Abs_Plus.jpeg" width = 300 />
</p>

In the context of performing ultrafast experiments with bicurcular fields, it is precisely the field associated with the three-fold symmetric Lissajous figure which is expected to drive elliptically polarised harmonics, due to the selection rules discussed earlier. This is because of the three-fold symmetry of the field for each of these recollisions, with their attendant bursts of XUV radiation. As it is necessarily mirrored by two other identical sets of trajectories and radiation bursts, trailing each other by a third of a period of the fundamental and rotated with respect to each other by 120°.

However, the issue, and motivation for this research, is that it is not a simple task to determine the nature of the polarisation of the fields. Moreover, there is not a formally defined or known topological space to house bichromatic fields. Therefore, this project is expanding on the work of E. Pisanty in [Nature Photonics 13 no. 8, 569 (2019)](https://www.nature.com/articles/s41566-019-0450-2), where a scheme was proposed to provide a characterisation tool for the trefoil polarisation state using higher order moments of the field tensor $\underline{\underline{M}} = <E_{i}E_{j}>$

𝑇_(𝑙,𝑛)= 〈├ (𝐸┤_𝑥+i𝐸_𝑦 )^𝑙 (𝐸_𝑥^2+𝐸_𝑦^2 )^((𝑛−𝑙)/2) 〉  .
![image](https://github.com/JonesRobM/Lissa_Fire/assets/52043020/5d2e8873-b273-4780-b1fc-92ba5c9760f7)


<p float="left">
  <img src="/Figs/Tref_Wheel.png" width = 300 />
</p>


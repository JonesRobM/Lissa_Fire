# Atto9 Supporting information
[![Contributors][contributors-shield]][contributors-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

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

However, the issue, and motivation for this research, is that it is not a simple task to determine the nature of the polarisation of the fields. Moreover, there is not a formally defined or known topological space to house bichromatic fields. Therefore, this project is expanding on the work of E. Pisanty in [Nature Photonics 13 no. 8, 569 (2019)](https://www.nature.com/articles/s41566-019-0450-2), where a scheme was proposed to provide a characterisation tool for the trefoil polarisation state using higher order moments of the field tensor $\underline{\underline{M}} = \langle E_{i}E_{j}\rangle$ into $\langle E_{i}E_{j}...E_{k}\rangle$. 

In the former case, the full state of monochromatic polarisation states may be described and mapped to the Poincaré sphere. However, in the latter, number of independent degrees of freedom renders such a description as ``difficult''.

Therefore, this issue is subverted by choosing to describe the polarisation states via their representations $l$, whose quantity are determined by the highest order of the high-order field moments. 
![image](https://github.com/JonesRobM/Lissa_Fire/assets/52043020/5d2e8873-b273-4780-b1fc-92ba5c9760f7)

These decompositions are described as tensor moments, and were used to reconstruct the bicurcular field via the $T_{1,3}$ and $T_{3,3}$, whose complex arguments are respectively given as $2\pi$ and $2\pi/3$.

<p float="left">
  <img src="/Figs/Tref_Wheel.png" width = 300 />
</p>

Given its initial success, the continuation of this work will hopefully allow us to realise 

<!-- CONTACT -->
## Contact

Robert Jones - robert.m.jones@kcl.ac.uk

Project Link: [https://github.com/JonesRobM/Lissa_Fire/]([https://github.com/your_username/repo_name](https://github.com/JonesRobM/Lissa_Fire/))

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Attosecond Quantum Physics Laboratory
Department of Physics, King’s College London](https://www.attokings.com)
* [Emilio Pisanty]([https://flexbox.malven.co/](https://episanty.github.io/))
* Royal Society University Research Fellowship funding under grant URF\R1\211390

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 

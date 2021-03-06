.. Automatically generated Sphinx-extended reStructuredText file from DocOnce source
   (https://github.com/hplgit/doconce/)

.. |nbsp| unicode:: 0xA0
   :trim:

.. Document title:

Introduction and Motivation
%%%%%%%%%%%%%%%%%%%%%%%%%%%

:Authors: `Morten Hjorth-Jensen <http://computationalphysics.no>`__, National Superconducting Cyclotron Laboratory and Department of Physics and Astronomy, Michigan State University, East Lansing, MI 48824, USA & Department of Physics, University of Oslo, Oslo, Norway
:Date: July 6-24 2015

.. !split

Introduction
============

To understand why matter is stable, and thereby shed light on the limits of 
nuclear stability, is one of the 
overarching aims and intellectual challenges 
of basic research in nuclear physics. To relate the stability of matter
to the underlying fundamental forces and particles of nature as manifested in nuclear matter, is central
to present and planned rare isotope facilities. 
Important properties of nuclear systems which can reveal information about these topics 
are for example masses, and thereby binding energies, and density distributions of nuclei.  
These are quantities which convey important information on 
the shell structure of nuclei, with their 
pertinent magic numbers and shell closures or the  eventual disappearence of the latter 
away from  the valley of stability.

Neutron-rich nuclei are particularly interesting for the above endeavour. As a particular chain
of isotopes becomes more and more neutron rich, one reaches finally the limit of stability, the so-called
dripline, where one additional neutron makes the next isotopes unstable with respect 
to the previous ones. The appearence or not of magic numbers and shell structures,
the formation of neutron skins and halos
can thence be probed via investigations of quantities like  the binding energy
or the charge radii and neutron rms radii of neutron-rich nuclei. 
These quantities have in turn important 
consequences for theoretical models of nuclear structure and their application in astrophysics.
For example, the neutron radius of :math:`\,{}^{208}\mbox{Pb}`, recently extracted from the PREX 
experiment at Jefferson Laboratory  can be used to constrain the equation of state of 
neutron matter. A related quantity to the
neutron rms radius :math:`r_n^{\mathrm{rms}}=\langle r^2\rangle_n^{1/2}` is the neutron skin 
:math:`r_{\mathrm{skin}}=r_n^{\mathrm{rms}}-r_p^{\mathrm{rms}}`,
where :math:`r_p^{\mathrm{rms}}` is the corresponding proton rms radius.  
There are several properties which relate the thickness of the neutron skin to quantities in nuclei and 
nuclear matter, such as the symmetry energy at the saturation point for nuclear matter, the slope
of the equation of state for neutron matter
or the low-energy electric dipole strength due to the `pigmy dipole resonance <http://iopscience.iop.org/1402-4896/2013/T152>`__.

Having access to precise measurements of masses, radii, and
electromagnetic moments for a wide range of nuclei allows to study
trends with varying neutron excess. A quantitative description of
various experimental data with quantified uncertainty still remains a
major challenge for nuclear structure theory.  Global theoretical
studies of isotopic chains, such as the Ca chain shown in the figure below here, make it possible to test systematic
properties of effective interactions between nucleons. Such calculations also
provide critical tests of limitations of many-body methods. As one
approaches the particle emission thresholds, it becomes increasingly
important to describe correctly the coupling to the continuum of
decays and scattering channels. While the
full treatment of antisymmetrization and short-range correlations has
become routine in first principle  approaches (to be defined later) to nuclear bound states, the
many-body problem becomes more difficult when long-range correlations
and continuum effects are considered.

.. figure:: fig-intro/careach.png
   :width: 500

   Expected experimental information on the calcium isotopes that can be obtained at FRIB. The limits for detailed spectroscopic information are around :math:`A\sim 60`

The aim of this first section is to present some of the experimental data which can be used to extract 
information about correlations in nuclear systems. In particular, we will start with a theoretical analysis of a quantity called the separation energy for neutrons or protons. This quantity, to be discussed below, is defined as the difference between two binding energies (masses) of neighboring nuclei. As we will see from various figures below and exercises as well, the separation energies display a varying behavior as function of the number of neutrons or protons. These variations from one nucleus to another one, laid the foundation for the introduction of so-called magic numbers and a mean-field picture in order to describe nuclei theoretically.

With a mean- or average-field picture we mean that a given nucleon (either a proton or a neutron) moves in an average potential field which is set up by all other nucleons in the system. Consider for example a nucleus like :math:`\,{}^{17}\mbox{O}` with nine neutrons and eight protons. Many properties  of this nucleus can be interpreted in terms of a picture where we can view it as
one neutron on top of :math:`\,{}^{16}\mbox{O}`. We infer from data and our theoretical interpretations that this additional neutron behaves almost as an individual neutron which *sees* an average interaction set up by the remaining 16 nucleons in   :math:`\,{}^{16}\mbox{O}`. A nucleus like :math:`\,{}^{16}\mbox{O}` is an example of what we in this course will denote as a good closed-shell nucleus. We will come back to what this means later.

Since we want to develop a theory capable of interpreting data in terms of our laws of motion and the pertinent forces,
we can think of this neutron as a particle which moves in a potential field. We can hence attempt at solving our equations of motion (Schroedinger's equation in our case) for this system along the same lines as we did in atomic physics when we solved Schroedinger's equation for the hydrogen atom. We just need to define a model for our effective single-particle potential. 

A simple potential model which enjoys quite some popularity in nuclear physics, is the three-dimensional harmonic oscillator. This potential model captures some of the physics of deeply bound single-particle states but fails in reproducing 
the less bound single-particle states. A parametrized, and more realistic,  potential model which is widely used in nuclear physics, is the so-called Woods-Saxon potential. Both the harmonic oscillator and the Woods-Saxon potential models define computational problems that can easily be solved (see below), resulting (with the appropriate parameters) in a rather good reproduction of experiment for nuclei which can be approximated as one nucleon on top (or one nucleon removed) of a so-called closed-shell system.

To be able to interpret a nucleus in such  a way requires at least that we are capable of parametrizing the abovementioned
interactions in order to reproduce say the excitation spectrum of a nucleus like :math:`\,{}^{17}\mbox{O}`. 

With such a parametrized interaction we are able to solve Schroedinger's equation for the motion of one nucleon in a given field. A nucleus is however a true and complicated many-nucleon system, with extremely many degrees of freedom and complicated correlations, rendering the ideal solution of the many-nucleon Schroedinger equation an impossible enterprise. It is much easier to solve a single-particle problem with say a Woods-Saxon potential. Using such a potential hides however many of the complicated correlations and interactions which we see in nuclei. Such an effective single-nucleon potential is for example not capable of 
describing properties like the binding energy or the rms radius of a given nucleus. 

An improvement to these simpler single-nucleon potentials is given by the Hartree-Fock method, where the variational principle is used to define a mean-field which the nucleons move in. There are many different classes of mean-field methods.
An important difference between these methods and the simpler parametrized mean-field potentials like the harmonic oscillator and the Woods-Saxon potentials, is that the resulting equations contain information about the nuclear forces present in our models for solving Schroedinger's equation. Hartree-Fock and other mean-field methods like density functional theory form core topics in later lectures.

The aim of this section is to present some of the experimental data we will confront theory with. In particular, we will focus on separation and shell-gap energies and use these to build a picture of nuclei in terms of (from a philosophical stand we would call this  a reductionist approach) a single-particle picture. The harmonic oscillator will serve as an excellent starting point in building nuclei from the bottom and up. Here we will neglect nuclear forces, these are introduced in the next section when we discuss the Hartree-Fock method. 

The aim of this course is to develop our physics intuition of nuclear systems using  a theoretical approach  where we describe data in terms of 
the motion of individual nucleons and their mutual interactions. 

**How our theoretical pictures and models can be used to interpret data is in essence what this course is about**. Our narrative will lead us along a path where we start with single-particle models and end with the theory of the nuclear shell-model. The latter will be used to understand and analyze excitation spectra and decay patterns of nuclei, linking our theoretical understanding with interpretations of experiment. The way we build up our theoretical descriptions and interpretations follows what we may call a standard reductionistic approach, that is we start with what we believe are our effective degrees of freedom (nucleons in our case) and interactions amongst these and solve thereafter the underlying equations of motions. This defines the nuclear many-body problem, and mean-field approaches like Hartree-Fock theory and the nuclear shell-model represent different approaches to our solutions of Schroedinger's equation. 

We start our tour of experimental data and our interpretations by considering the chain of oxygen isotopes. In the exercises below you will be asked to perform similar analyses for other chains of isotopes.

The oxygen isotopes are the heaviest isotopes for which the drip line is well established.  The drip line is defined as the point where adding one more nucleon leads to an unbound nucleus. Below we will see that we can define the dripline by studying the separation energy. Where the neutron (proton) separation energy changes sign as a function of the number of neutrons (protons) defines the neutron (proton) drip line.

The oxygen isotopes are simple enough to be described by some few selected single-particle degrees of freedom.  

* Two out of four stable even-even isotopes exhibit a doubly magic nature, namely :math:`\,{}^{22}\mbox{O}` (:math:`Z=8`, :math:`N=14`) and :math:`\,{}^{24}\mbox{O}` (:math:`Z=8`, :math:`N=16`).

* The structure of :math:`\,{}^{22}\mbox{O}` and :math:`\,{}^{24}\mbox{O}` is assumed to be governed by the evolution of the :math:`1s_{1/2}` and :math:`0d_{5/2}`  one-quasiparticle states.

* The isotopes :math:`\,{}^{25}\mbox{O}`, :math:`\,{}^{26}\mbox{O}`, :math:`\,{}^{27}\mbox{O}` and :math:`\,{}^{28}\mbox{O}` are outside the drip line, since the :math:`0d_{3/2}` orbit is not bound.

 Many experiments worldwide!
These isotopes have been studied in series of recent experiments. Some of these experiments and theoretical interpretations are discussed in the following articles:

* :math:`\,{}^{24}\mbox{O}` and lighter:  C. |nbsp| R. |nbsp| Hoffman *et al.*, Phys. |nbsp| Lett. |nbsp| B **672**, 17 (2009); R. |nbsp| Kanungo *et al*., Phys. |nbsp| Rev. |nbsp| Lett.~**102**, 152501 (2009); C. |nbsp| R. |nbsp| Hoffman *et al*., Phys. |nbsp| Rev. |nbsp| C **83**, 031303(R) (2011); Stanoiu *et al*., Phys. Rev. C **69**, 034312 (2004)

* :math:`\,{}^{25}\mbox{O}`: C. |nbsp| R. |nbsp| Hoffman *et al*., Phys. |nbsp| Rev. |nbsp| Lett. **102**,152501  (2009). 

* :math:`\,{}^{26}\mbox{O}`: E. |nbsp| Lunderberg *et al*., Phys. |nbsp| Rev. |nbsp| Lett. **108**, 142503 (2012). 

* :math:`\,{}^{26}\mbox{O}`: Z. |nbsp| Kohley  *et al*., Study of two-neutron radioactivity in the decay of 26O, Phys. |nbsp| Rev. |nbsp| Lett., **110**, 152501 (2013). 

* Theory: Oxygen isotopes with three-body forces,  Otsuka *et al*., Phys. |nbsp| Rev. |nbsp| Lett. **105**, 032501  (2010).  Hagen *et al.*, Phys. |nbsp| Rev. |nbsp| Lett., **108**, 242501 (2012). 

.. !split

Masses and Binding energies
===========================
Our first approach in analyzing data theoretically, is to see if we can use experimental information to 

* Extract information about a *so-called* single-particle  behavior

* And interpret such a behavior in terms of the underlying forces and microscopic physics

The next step is to see if we could use these interpretations to say something about shell closures and magic numbers. Since we focus on single-particle properties, a quantity we can extract from experiment is the separation energy for protons and neutrons. Before we proceed, we need to define quantities like masses and binding energies.   Two excellent reviews on 
recent trends in the determination of nuclear masses can be found in the work of `Pearson et al. <http://journals.aps.org/rmp/abstract/10.1103/RevModPhys.75.1021>`__ and `Blaum et al. <http://iopscience.iop.org/1402-4896/2013/T152/014017/>`__

A basic quantity which can be measured for the ground states of nuclei is the atomic mass :math:`M(N, Z)` of the neutral atom with atomic mass number :math:`A` and charge :math:`Z`. The number of neutrons is :math:`N`.

Atomic masses are usually tabulated in terms of the mass excess defined by

.. math::
        
        \Delta M(N, Z) =  M(N, Z) - uA,
        

where :math:`u` is the Atomic Mass Unit 

.. math::
        
        u = M(^{12}\mathrm{C})/12 = 931.49386 \hspace{0.1cm} \mathrm{MeV}/c^2.
        

In this course we will mainly use 
data from the 2003 compilation of `Audi, Wapstra and Thibault <http://www.sciencedirect.com/science/journal/03759474/729/1>`__.

The nucleon masses are

.. math::
        
        m_p = 938.27203(8)\hspace{0.1cm} \mathrm{MeV}/c^2 = 1.00727646688(13)u,
         

and

.. math::
        
        m_n = 939.56536(8)\hspace{0.1cm} \mathrm{MeV}/c^2 = 1.0086649156(6)u.
        

In the 2003 mass evaluation there are 2127 nuclei measured with an accuracy of 0.2
MeV or better, and 101 nuclei measured with an accuracy of greater than 0.2 MeV. For
heavy nuclei one observes several chains of nuclei with a constant :math:`N-Z` value whose masses are obtained from the energy released in :math:`\alpha`-decay.

The nuclear binding energy is defined as the energy required to break up a given nucleus
into its constituent parts of :math:`N` neutrons and :math:`Z` protons. In terms of the atomic masses :math:`M(N, Z)` the binding energy is defined by

.. math::
        
        BE(N, Z) = ZM_H c^2 + Nm_n c^2 - M(N, Z)c^2 ,
        

where :math:`M_H` is the mass of the hydrogen atom and :math:`m_n` is the mass of the neutron.
In terms of the mass excess the binding energy is given by

.. math::
        
        BE(N, Z) = Z\Delta_H c^2 + N\Delta_n c^2 -\Delta(N, Z)c^2 ,
        

where :math:`\Delta_H c^2 = 7.2890` MeV and :math:`\Delta_n c^2 = 8.0713` MeV.

The following python program reads in the experimental data on binding energies and, stored in the file bindingenergies.dat,  plots them as function of the mass number :math:`A`. One notices clearly a saturation of the binding energy per nucleon at :math:`A\approx 56`.

.. code-block:: text

        import numpy as np
        from  matplotlib import pyplot as plt
        # Load in data file
        data = np.loadtxt("datafiles/bindingenergies.dat")
        # Make arrays containing x-axis and binding energies as function of A
        x = data[:,2]
        bexpt = data[:,3]
        plt.plot(x, bexpt ,'ro')
        plt.axis([0,270,-1, 10.0])
        plt.xlabel(r'$A$')
        plt.ylabel(r'Binding energies in [MeV]')
        plt.legend(('Experiment'), loc='upper right')
        plt.title(r'Binding energies from experiment')
        plt.savefig('expbindingenergies.pdf')
        plt.savefig('expbindingenergies.png')
        plt.show()

A popular and physically intuitive model which can be used to parametrize 
the experimental binding energies as function of :math:`A`, is the so-called 
the liquid drop model. The ansatz is based on the following expression

.. math::
         
        BE(N,Z) = a_1A-a_2A^{2/3}-a_3\frac{Z^2}{A^{1/3}}-a_4\frac{(N-Z)^2}{A},
        

where :math:`A` stands for the number of nucleons and the $a_i$s are parameters which are determined by a fit 
to the experimental data.  

To arrive at the above expression we have assumed that we can make the following assumptions:

 * There is a volume term :math:`a_1A` proportional with the number of nucleons (the energy is also an extensive quantity). When an assembly of nucleons of the same size is packed together into the smallest volume, each interior nucleon has a certain number of other nucleons in contact with it. This contribution is proportional to the volume.

 * There is a surface energy term :math:`a_2A^{2/3}`. The assumption here is that a nucleon at the surface of a nucleus interacts with fewer other nucleons than one in the interior of the nucleus and hence its binding energy is less. This surface energy term takes that into account and is therefore negative and is proportional to the surface area.

 * There is a Coulomb energy term :math:`a_3\frac{Z^2}{A^{1/3}}`. The electric repulsion between each pair of protons in a nucleus yields less binding. 

 * There is an asymmetry term :math:`a_4\frac{(N-Z)^2}{A}`. This term is associated with the Pauli exclusion principle and reflectd the fact that the proton-neutron interaction is more attractive on the average than the neutron-neutron and proton-proton interactions.

We could also add a so-called pairing term, which is a correction term that
arises from the tendency of proton pairs and neutron pairs to
occur. An even number of particles is more stable than an odd number. 
Performing a least-square fit to data, we obtain the following numerical values for the various constants
* :math:`a_1=15.49` MeV

* :math:`a_2=17.23` MeV

* :math:`a_3=0.697` MeV

* :math:`a_4=22.6` MeV

The python below here allows you to perform a fit of teh above parameters using nonlinear least squares curvefitting.

The following python program reads now in the experimental data on binding energies as well as the results from the above liquid drop model and plots these energies as function of the mass number :math:`A`. One sees that for larger values of :math:`A`, there is a better agreement with data. 

.. code-block:: text

        import numpy as np
        from  matplotlib import pyplot as plt
        # Load in data file
        data = np.loadtxt("datafiles/bindingenergies.dat")
        # Make arrays containing x-axis and binding energies as function of
        x = data[:,2]
        bexpt = data[:,3]
        liquiddrop = data[:,4]
        plt.plot(x, bexpt ,'b-o', x, liquiddrop, 'r-o')
        plt.axis([0,270,-1, 10.0])
        plt.xlabel(r'$A$')
        plt.ylabel(r'Binding energies in [MeV]')
        plt.legend(('Experiment','Liquid Drop'), loc='upper right')
        plt.title(r'Binding energies from experiment and liquid drop')
        plt.savefig('bindingenergies.pdf')
        plt.savefig('bindingenergies.png')
        plt.show()

This  python program reads now in the experimental data on binding energies and performs a nonlinear least square fitting of the data. In the example here we use only the parameters :math:`a_1` and :math:`a_2`, leaving it as an exercise to the reader to perform the fit for all four paramters. The results are plotted and compared with the experimental values.  To read more about non-linear least square methods, see for example the text of M.J. Box, D. Davies and W.H. Swann, Non-Linear optimisation Techniques, Oliver & Boyd, 1969.

.. code-block:: text

        import numpy as np
        from scipy.optimize import curve_fit
        from  matplotlib import pyplot as plt
        # Load in data file
        data = np.loadtxt("datafiles/bindingenergies.dat")
        # Make arrays containing A on x-axis and binding energies
        A = data[:,2]
        bexpt = data[:,3]
        # The function we want to fit to, only two terms here
        def func(A,a1, a2):
            return a1*A-a2*(A**(2.0/3.0))
        # function to perform nonlinear least square with guess for a1 and a2
        popt, pcov = curve_fit(func, A, bexpt, p0 = (16.0, 18.0))
        a1  = popt[0]
        a2 = popt[1]
        liquiddrop = a1*A-a2*(A**(2.0/3.0))
        
        plt.plot(A, bexpt ,'bo', A, liquiddrop, 'ro')
        plt.axis([0,270,-1, 10.0])
        plt.xlabel(r'$A$')
        plt.ylabel(r'Binding energies in [MeV]')
        plt.legend(('Experiment','Liquid Drop'), loc='upper right')
        plt.title(r'Binding energies from experiment and liquid drop')
        plt.savefig('bindingenergies.pdf')
        plt.savefig('bindingenergies.png')
        plt.show()

We are now interested in interpreting experimental binding energies  in terms of a single-particle picture.
In order to do so, we  consider first energy conservation for nuclear transformations that include, for
example, the fusion of two nuclei :math:`a` and :math:`b` into the combined system :math:`c`

.. math::
        
        {^{N_a+Z_a}}a+ {^{N_b+Z_b}}b\rightarrow {^{N_c+Z_c}}c
        

or the decay of nucleus :math:`c` into two other nuclei :math:`a` and :math:`b`

.. math::
        
        ^{N_c+Z_c}c \rightarrow  ^{N_a+Z_a}a+ ^{N_b+Z_b}b
        

In general we have the reactions

.. math::
        
        \sum_i {^{N_i+Z_i}}i \rightarrow  \sum_f {^{N_f+Z_f}}f
        

We require also that the number of protons and neutrons (the total number of nucleons) is conserved in the initial stage and final stage, unless we have processes which violate baryon conservation, 

.. math::
        
        \sum_iN_i = \sum_f N_f \hspace{0.2cm}\mathrm{and} \hspace{0.2cm}\sum_iZ_i = \sum_f Z_f.
        

.. !split

:math:`Q`-values and separation energies
========================================

The above processes can be characterized by an energy difference called the :math:`Q` value, defined as

.. math::
        
        Q=\sum_i M(N_i, Z_i)c^2-\sum_f M(N_f, Z_f)c^2=\sum_i BE(N_f, Z_f)-\sum_i BE(N_i, Z_i)
        

Spontaneous decay involves a single initial nuclear state and is allowed if :math:`Q > 0`. In the decay, energy is released in the form of the kinetic energy of the final products. Reactions involving two initial nuclei are called endothermic (a net loss of energy) if :math:`Q < 0`. The reactions are exothermic (a net release of energy) if :math:`Q > 0`.

Let us study the Q values associated with the removal of one or two nucleons from
a nucleus. These are conventionally defined in terms of the one-nucleon and two-nucleon
separation energies. The neutron separation energy is defined as 

.. math::
        
        S_n= -Q_n= BE(N,Z)-BE(N-1,Z),
        

and the proton separation energy reads

.. math::
        
        S_p= -Q_p= BE(N,Z)-BE(N,Z-1).
        

The two-neutron separation energy is defined as

.. math::
        
        S_{2n}= -Q_{2n}= BE(N,Z)-BE(N-2,Z),
        

and  the two-proton separation energy is given by

.. math::
        
        S_{2p}= -Q_{2p}= BE(N,Z)-BE(N,Z-2),
        

Using say the neutron separation energies (alternatively the proton separation energies)

.. math::
        
        S_n= -Q_n= BE(N,Z)-BE(N-1,Z),
        

we can define the so-called energy gap for neutrons (or protons) as 

.. math::
        
        \Delta S_n= BE(N,Z)-BE(N-1,Z)-\left(BE(N+1,Z)-BE(N,Z)\right),
        

or 

.. math::
        
        \Delta S_n= 2BE(N,Z)-BE(N-1,Z)-BE(N+1,Z).
        

This quantity can in turn be used to determine which nuclei are magic or not. 
For protons we would have 

.. math::
        
        \Delta S_p= 2BE(N,Z)-BE(N,Z-1)-BE(N,Z+1).
        

We leave it as an exercise to the reader to define and interpret the two-neutron or two-proton gaps. 

The following python programs can now be used to plot the separation energies and the energy gaps for the oxygen isotopes.  The following python code reads the separation energies from file for all oxygen isotopes from :math:`A=13` to :math:`A=25`, The data are taken from the file *snox.dat*.  This files contains the separation energies and the shell gap energies.

.. code-block:: text

        
        import numpy as np
        from  matplotlib import pyplot as plt
        # Load in data file
        data = np.loadtxt("datafiles/snox.dat")
        # Make arrays containing x-axis and binding energies as function of
        x = data[:,1]
        y = data[:,2]
        
        plt.plot(x, y,'b-+',markersize=6)
        plt.axis([4,18,-1, 25.0])
        plt.xlabel(r'Number of neutrons $N$',fontsize=20)
        plt.ylabel(r'$S_n$ [MeV]',fontsize=20)
        plt.legend(('Separation energies for oxygen isotpes'), loc='upper right')
        plt.title(r'Separation energy for the oxygen isotopes')
        plt.savefig('snoxygen.pdf')
        plt.savefig('snoxygen.png')
        plt.show()

Here we display the python program for plotting the corresponding results for shell gaps for the oyxgen isotopes. 

.. code-block:: text

        
        import numpy as np
        from  matplotlib import pyplot as plt
        # Load in data file
        data = np.loadtxt("datafiles/snox.dat")
        # Make arrays containing x-axis and binding energies as function of
        x = data[:,1]
        y = data[:,3]
        
        plt.plot(x, y,'b-+',markersize=6)
        plt.axis([4,18,-7, 12.0])
        plt.xlabel(r'Number of neutrons $N$',fontsize=20)
        plt.ylabel(r'$\Delta S_n$ [MeV]',fontsize=20)
        plt.legend(('Shell gap energies for oxygen isotpes'), loc='upper right')
        plt.title(r'Shell gap energies for the oxygen isotopes')
        plt.savefig('gapoxygen.pdf')
        plt.savefig('gapoxygen.png')
        plt.show()

Since we will focus in the beginning on single-particle degrees of freedom and mean-field approaches before we
start with nuclear forces and many-body approaches like the nuclear shell-model, there are some features to be noted

* In the discussion of the liquid drop model and binding energies, we note that the total binding energy is not that different from the sum of the individual neutron and proton masses. 

One may thus infer that intrinsic properties of nucleons in a nucleus are close to those of free nucleons.
* In the discussion of the neutron separation energies for the oxygen isotopes, we note  a clear staggering effect between odd and even isotopes with the even ones being more bound (larger separation energies). We will later link this to strong pairing correlations in nuclei.

* The neutron separation energy becomes negative at :math:`\,{}^{25}\mbox{O}`, making this nucleus unstable with respect to the emission of one neutron. A nucleus like :math:`\,{}^{24}\mbox{O}` is thus the last stable oxygen isotopes which has been observed. "Oxygen-26":"ournals.aps.org/prl/abstract/10.1103/PhysRevLett.108.142503" . has been found to be unbound with respect to :math:`\,{}^{24}\mbox{O}`.

* We note also that there are large shell-gaps for some nuclei, meaning that more energy is needed to remove one nucleon. These gaps are used to define so-called magic numbers. For the oxygen isotopes we see a clear gap for :math:`\,{}^{16}\mbox{O}`. We will interpret this gap as one of several experimental properties that define so-called magic numbers. In our discussion below we will make a first interpretation using  single-particle states from the harmonic oscillator and the Woods-Saxon potential. 

In the exercises below you will be asked to perform a similar analysis for other chains of isotopes and interpret the results. 

.. !split

Radii
=====

The root-mean-square (rms) charge radius has been measured for the ground states of many
nuclei. For a spherical charge density, :math:`\rho(\boldsymbol{r})`, the mean-square radius is defined by

.. math::
        
        \langle r^2\rangle = \frac{ \int  d \boldsymbol{r} \rho(\boldsymbol{r}) r^2}{ \int  d \boldsymbol{r} \rho(\boldsymbol{r})},
        

and the rms radius is the square root of this quantity denoted by

.. math::
        
        R =\sqrt{ \langle r^2\rangle}.
        

Radii for most stable
nuclei have been deduced from electron scattering form
factors and/or from the x-ray transition energies of muonic atoms. 
The relative radii for a
series of isotopes can be extracted from the isotope shifts of atomic x-ray transitions.
The rms radius for the nuclear point-proton density, :math:`R_p` is obtained from the rms charge radius by:

.. math::
        
        R_p = \sqrt{R^2_{\mathrm{ch}}- R^2_{\mathrm{corr}}},
        

where

.. math::
        
        R^2_{\mathrm{corr}}= R^2_{\mathrm{op}}+(N/Z)R^2_{\mathrm{on}}+R^2_{\mathrm{rel}},
        

where 

.. math::
        
        R_{\mathrm{op}}= 0.875(7) \mathrm{fm}.
        

is the rms radius of the proton, :math:`R^2_{\mathrm{on}} = 0.116(2)` $\mbox{fm}^{2}$ is the
mean-square radius of the neutron and :math:`R^2_{\mathrm{rel}} = 0.033` $\mbox{fm}^{2}$ is the relativistic Darwin-Foldy correction. There are also smaller nucleus-dependent relativistic spin-orbit and
mesonic-exchange corrections that should be included.

.. !split

Definitions
===========

We will now introduce the potential models we have discussex above, namely the harmonic oscillator and the Woods-Saxon potentials.  In order to proceed, we need some definitions.

We define an operator as :math:`\hat{O}` throughout. Unless otherwise specified the total number of nucleons is
always :math:`A` and :math:`d` is the dimension of the system.  In nuclear physics
we normally define the total number of particles to be :math:`A=N+Z`, where
:math:`N` is total number of neutrons and :math:`Z` the total number of
protons. In case of other baryons such as isobars :math:`\Delta` or various
hyperons such as :math:`\Lambda` or :math:`\Sigma`, one needs to add their
definitions.  When we refer to a single neutron we will use the label :math:`n` and when we refer to a single proton we will use the label :math:`p`. Unless otherwise specified, we will simply call these particles for nucleons.

The quantum numbers of a single-particle state in coordinate space are
defined by the variables 

.. math::
        
        x=(\boldsymbol{r},\sigma), 
        

where 

.. math::
        
        \boldsymbol{r}\in {\mathbb{R}}^{d},
        

with :math:`d=1,2,3` represents the spatial coordinates and :math:`\sigma` is the eigenspin of the particle. For fermions with eigenspin :math:`1/2` this means that

.. math::
        
         x\in {\mathbb{R}}^{d}\oplus (\frac{1}{2}),
        

and the integral

.. math::
        
        \int dx = \sum_{\sigma}\int d^dr = \sum_{\sigma}\int d\boldsymbol{r},
        

and

.. math::
        
        \int d^Ax= \int dx_1\int dx_2\dots\int dx_A.
        

Since we are dealing with protons and neutrons we need to add isospin as a new degree of freedom.

Including isospin :math:`\tau` we have 

.. math::
        
        x=(\boldsymbol{r},\sigma,\tau), 
        

where 

.. math::
        
        \boldsymbol{r}\in {\mathbb{R}}^{3},
        

For nucleons, which are fermions with eigenspin :math:`1/2` and isospin :math:`1/2` this means that

.. math::
        
         x\in {\mathbb{R}}^{d}\oplus (\frac{1}{2})\oplus (\frac{1}{2}),
        

and the integral

.. math::
        
        \int dx = \sum_{\sigma\tau}\int d\boldsymbol{r},
        

and

.. math::
        
        \int d^Ax= \int dx_1\int dx_2\dots\int dx_A.
        

We will use the standard nuclear physics definition of isospin, resulting in :math:`\tau_z=-1/2` for protons and :math:`\tau_z=1/2` for neutrons.

The quantum mechanical wave function of a given state with quantum numbers :math:`\lambda` (encompassing all quantum numbers needed to specify the system), ignoring time, is

.. math::
        
        \Psi_{\lambda}=\Psi_{\lambda}(x_1,x_2,\dots,x_A),
        

with :math:`x_i=(\boldsymbol{r}_i,\sigma_i,\tau_i)` and the projections of :math:`\sigma_i` and :math:`\tau_i` take the values
:math:`\{-1/2,+1/2\}`. 
We will hereafter always refer to :math:`\Psi_{\lambda}` as the exact wave function, and if the ground state is not degenerate we label it as 

.. math::
        
        \Psi_0=\Psi_0(x_1,x_2,\dots,x_A).
        

Since the solution :math:`\Psi_{\lambda}` seldomly can be found in closed form, approximations are sought. In this text we define an approximative wave function or an ansatz to the exact wave function as 

.. math::
        
        \Phi_{\lambda}=\Phi_{\lambda}(x_1,x_2,\dots,x_A),
        

with

.. math::
        
        \Phi_{0}=\Phi_{0}(x_{1},x_{2},\dots,x_{A}),
        

being the ansatz for the ground state.  

The wave function :math:`\Psi_{\lambda}` is sought in the Hilbert space of either symmetric or anti-symmetric :math:`N`-body functions, namely

.. math::
        
        \Psi_{\lambda}\in {\cal H}_A:= {\cal H}_1\oplus{\cal H}_1\oplus\dots\oplus{\cal H}_1,
        

where the single-particle Hilbert space :math:`\hat{H}_1` is the space of square integrable functions over :math:`\in {\mathbb{R}}^{d}\oplus (\sigma)\oplus (\tau)` resulting in

.. math::
        
        {\cal H}_1:= L^2(\mathbb{R}^{d}\oplus (\sigma)\oplus (\tau)).
        

Our Hamiltonian is invariant under the permutation (interchange) of two particles.
Since we deal with fermions however, the total wave function is antisymmetric.
Let :math:`\hat{P}` be an operator which interchanges two particles.
Due to the symmetries we have ascribed to our Hamiltonian, this operator commutes with the total Hamiltonian,

.. math::
        
        [\hat{H},\hat{P}] = 0,
        

meaning that :math:`\Psi_{\lambda}(x_1, x_2, \dots , x_A)` is an eigenfunction of 
:math:`\hat{P}` as well, that is

.. math::
        
        \hat{P}_{ij}\Psi_{\lambda}(x_1, x_2, \dots,x_i,\dots,x_j,\dots,x_A)=
        \beta\Psi_{\lambda}(x_1, x_2, \dots,x_j,\dots,x_i,\dots,x_A),
        

where :math:`\beta` is the eigenvalue of :math:`\hat{P}`. We have introduced the suffix :math:`ij` in order to indicate that we permute particles :math:`i` and :math:`j`.
The Pauli principle tells us that the total wave function for a system of fermions
has to be antisymmetric, resulting in the eigenvalue :math:`\beta = -1`.   

The Schrodinger equation reads 

.. math::
   :label: eq:basicSE1
        
        \hat{H}(x_1, x_2, \dots , x_A) \Psi_{\lambda}(x_1, x_2, \dots , x_A) = 
        E_\lambda  \Psi_\lambda(x_1, x_2, \dots , x_A), 
        

where the vector :math:`x_i` represents the coordinates (spatial, spin and isospin) of particle :math:`i`, :math:`\lambda` stands  for all the quantum
numbers needed to classify a given :math:`A`-particle state and :math:`\Psi_{\lambda}` is the pertaining eigenfunction.  Throughout this course,
:math:`\Psi` refers to the exact eigenfunction, unless otherwise stated.

We write the Hamilton operator, or Hamiltonian,  in a generic way 

.. math::
        
        	\hat{H} = \hat{T} + \hat{V} 
        

where :math:`\hat{T}`  represents the kinetic energy of the system

.. math::
        
        	\hat{T} = \sum_{i=1}^A \frac{\mathbf{p}_i^2}{2m_i} = \sum_{i=1}^A \left( -\frac{\hbar^2}{2m_i} \mathbf{\nabla_i}^2 \right) =
        		\sum_{i=1}^A t(x_i)
        

while the operator :math:`\hat{V}` for the potential energy is given by

.. math::
   :label: eq:firstv
        
        	\hat{V} = \sum_{i=1}^A \hat{u}_{\mathrm{ext}}(x_i) + \sum_{ji=1}^A v(x_i,x_j)+\sum_{ijk=1}^Av(x_i,x_j,x_k)+\dots
        
        

Hereafter we use natural units, viz. |nbsp| :math:`\hbar=c=e=1`, with :math:`e` the elementary charge and :math:`c` the speed of light. This means that momenta and masses
have dimension energy. 

The potential energy part includes also an external potential :math:`\hat{u}_{\mathrm{ext}}(x_i)`.

In a non-relativistic approach to atomic  physics, this external potential is given by the attraction an electron feels from the atomic nucleus. The latter being much heavier than the involved electrons, is often used to define a natural center of mass. In nuclear physics there is no such external potential. It is the nuclear force which results in binding in nuclear systems. In a non-relativistic framework, the nuclear force contains two-body, three-body and more complicated degrees of freedom. The potential energy reads then  

.. math::
        
        	\hat{V} = \sum_{ij}^A v(x_i,x_j)+\sum_{ijk}^Av(x_i,x_j,x_k)+\dots
        

Three-body and more  complicated forces arise since we are dealing with protons and neutrons as effective degrees of freedom. We will come back to this topic later. Furthermore, in large parts of these lectures we will assume that the potential energy can be approximated by a two-body interaction only. Our Hamiltonian reads then

.. math::
   :label: eq:firstH
        
        	\hat{H} = \sum_{i=1}^A \frac{\mathbf{p}_i^2}{2m_i}+\sum_{ij}^A v(x_i,x_j).
        
        

.. !split

A modified Hamiltonian
======================

It is however, from a computational point of view, convenient to introduce an external potential :math:`\hat{u}_{\mathrm{ext}}(x_i)` by adding and substracting it to the original Hamiltonian. 
This means that our Hamiltonian can be rewritten as 

.. math::
        
            \hat{H} = \hat{H}_0 + \hat{H}_I 
            = \sum_{i=1}^A \hat{h}_0(x_i) + \sum_{i < j=1}^A \hat{v}(x_{ij})-\sum_{i=1}^A\hat{u}_{\mathrm{ext}}(x_i),
        

with

.. math::
        
          \hat{H}_0=\sum_{i=1}^A \hat{h}_0(x_i) =  \sum_{i=1}^A\left(\hat{t}(x_i) + \hat{u}_{\mathrm{ext}}(x_i)\right).
        

The interaction (or potential energy term) reads now

.. math::
        
          \hat{H}_I=  \sum_{i < j=1}^A \hat{v}(x_{ij})-\sum_{i=1}^A\hat{u}_{\mathrm{ext}}(x_i).
        

In nuclear physics the one-body part :math:`u_{\mathrm{ext}}(x_i)` is often approximated by a harmonic oscillator potential or a
Woods-Saxon potential. However, this is not fully correct, because as we have discussed, nuclei are self-bound systems and there is no external confining potential. As we will see later, *the :math:`\hat{H}_0` part of the hamiltonian cannot be used to compute the binding energy of a nucleus since it is not based on a model for the nuclear forces*. That is, the binding energy is not the sum of the individual single-particle energies. 

Why do we introduce the  Hamiltonian  in the form

.. math::
        
            \hat{H} = \hat{H}_0 + \hat{H}_I? 
        

There are many reasons for this. Let us look at some of them, using the harmonic oscillator in three dimensions as our starting point. For the harmonic oscillator we know that

.. math::
        
          \hat{h}_0(x_i)\psi_{\alpha}(x_i)=\varepsilon_{\alpha}\psi_{\alpha}(x_i),  
        

where the eigenvalues are :math:`\varepsilon_{\alpha}` and the eigenfunctions are :math:`\psi_{\alpha}(x_i)`. The subscript :math:`\alpha` represents quantum numbers like the orbital angular momentum :math:`l_{\alpha}`, its projection :math:`m_{l_{\alpha}}` and the   
principal quantum number :math:`n_{\alpha}=0,1,2,\dots`. 

The eigenvalues are

.. math::
        
        \varepsilon_{\alpha} = \hbar\omega \left(2n_{\alpha}+l_{\alpha}+\frac{3}{2}\right).
        

The following mathematical properties of the  harmonic oscillator are handy. 
 * First of all we have a complete basis of orthogonal eigenvectors. These have well-know expressions and can be easily be encoded. 

 * With a complete basis :math:`\psi_{\alpha}(x_i)`, we can construct a new basis :math:`\phi_{\tau}(x_i)` by expanding in terms of a harmonic oscillator basis, that is  

.. math::
        
        \phi_{\tau}(x_i)=\sum_{\alpha} C_{\tau\alpha}\psi_{\alpha}(x_i),
        

where :math:`C_{\tau\alpha}` represents the overlap between the two basis sets. 
 * As we will see later, the harmonic oscillator basis allows us to compute in an expedient way matrix elements of the interactions between two nucleons.  Using the above expansion we can in turn represent nuclear forces in terms of new basis, for example the  Woods-Saxon basis  to be discussed later here.

The harmonic oscillator (a shifted one by a negative constant) provides also a very good approximation to most bound single-particle states. Furthermore, it serves as a starting point in building up our picture of nuclei, in particular how we define magic numbers and systems with one nucleon added to (or removed from) a closed-shell core nucleus. The figure here shows 
the various harmonic oscillator states, with those obtained with a Woods-Saxon potential as well, including a spin-orbit splitting (to be discussed below).

.. figure:: fig-intro/singleparticle.png
   :width: 500

   Single-particle spectrum and quantum numbers for a harmonic oscillator potential and a Woods-Saxon potential with and without a spin-orbit force

In nuclear physics the one-body part :math:`u_{\mathrm{ext}}(x_i)` is often 
approximated by a harmonic oscillator potential. However,  as we also noted with the Woods-Saxon potential there is no 
external confining potential in nuclei. 

What many people do then, is to add and subtract a harmonic oscillator potential,
with 

.. math::
        
        \hat{u}_{\mathrm{ext}}(x_i)=\hat{u}_{\mathrm{ho}}(x_i)= \frac{1}{2}m\omega^2 r_i^2,
        

where :math:`\omega` is the oscillator frequency. This leads to 

.. math::
        
            \hat{H} = \hat{H_0} + \hat{H_I} 
            = \sum_{i=1}^A \hat{h}_0(x_i) + \sum_{i < j=1}^A \hat{v}(x_{ij})-\sum_{i=1}^A\hat{u}_{\mathrm{ho}}(x_i),
        

with 

.. math::
        
          H_0=\sum_{i=1}^A \hat{h}_0(x_i) =  \sum_{i=1}^A\left(\hat{t}(x_i) + \hat{u}_{\mathrm{ho}}(x_i)\right).
        

Many practitioners use this as the standard Hamiltonian when doing nuclear structure calculations. 
This is ok if the number of nucleons is large, but still with this Hamiltonian, we do not obey translational invariance.  How can we cure this?

 In setting up a translationally invariant Hamiltonian  
 the following expressions are helpful.
 The center-of-mass (CoM)  momentum is

.. math::
        
            P=\sum_{i=1}^A\boldsymbol{p}_i,
         

 and we have that

.. math::
        
         \sum_{i=1}^A\boldsymbol{p}_i^2 =
         \frac{1}{A}\left[\boldsymbol{P}^2+\sum_{i < j}(\boldsymbol{p}_i-\boldsymbol{p}_j)^2\right]
         

 meaning that

.. math::
        
         \left[\sum_{i=1}^A\frac{\boldsymbol{p}_i^2}{2m} -\frac{\boldsymbol{P}^2}{2mA}\right]
         =\frac{1}{2mA}\sum_{i < j}(\boldsymbol{p}_i-\boldsymbol{p}_j)^2.
         

 In a similar fashion we can define the CoM coordinate

.. math::
        
             \boldsymbol{R}=\frac{1}{A}\sum_{i=1}^{A}\boldsymbol{r}_i,
         

 which yields

.. math::
         
         \sum_{i=1}^A\boldsymbol{r}_i^2 =
         \frac{1}{A}\left[A^2\boldsymbol{R}^2+\sum_{i < j}(\boldsymbol{r}_i-\boldsymbol{r}_j)^2\right].
         

 If we then introduce the harmonic oscillator one-body Hamiltonian

.. math::
        
              H_0= \sum_{i=1}^A\left(\frac{\boldsymbol{p}_i^2}{2m}+
        	   \frac{1}{2}m\omega^2\boldsymbol{r}_i^2\right),
         

 with :math:`\omega` the oscillator frequency,
 we can rewrite the latter as 

.. math::
   :label: eq:obho
         
              H_{\mathrm{HO}}= \frac{\boldsymbol{P}^2}{2mA}+\frac{mA\omega^2\boldsymbol{R}^2}{2}
        	    +\frac{1}{2mA}\sum_{i < j}(\boldsymbol{p}_i-\boldsymbol{p}_j)^2
        	    +\frac{m\omega^2}{2A}\sum_{i < j}(\boldsymbol{r}_i-\boldsymbol{r}_j)^2.
             
         

Alternatively, we could write it as	

.. math::
        
         H_{\mathrm{HO}}= H_{\mathrm{CoM}}+\frac{1}{2mA}\sum_{i < j}(\boldsymbol{p}_i-\boldsymbol{p}_j)^2
        	    +\frac{m\omega^2}{2A}\sum_{i < j}(\boldsymbol{r}_i-\boldsymbol{r}_j)^2,
         

The center-of-mass term is defined as

.. math::
         
              H_{\mathrm{CoM}}= \frac{\boldsymbol{P}^2}{2mA}+\frac{mA\omega^2\boldsymbol{R}^2}{2}.
         

 The translationally invariant one- and two-body  Hamiltonian reads for an A-nucleon system,

.. math::
   :label: eq:ham
         
        
        \hat{H}=\left[\sum_{i=1}^A\frac{\boldsymbol{p}_i^2}{2m} -\frac{\boldsymbol{P}^2}{2mA}\right] +\sum_{i < j}^A V_{ij} \; ,
         

 where :math:`V_{ij}` is the nucleon-nucleon interaction. Adding zero as here

.. math::
        
         \sum_{i=1}^A\frac{1}{2}m\omega^2\boldsymbol{r}_i^2-
         \frac{m\omega^2}{2A}\left[\boldsymbol{R}^2+\sum_{i < j}(\boldsymbol{r}_i-\boldsymbol{r}_j)^2\right]=0.
         

we can then rewrite the Hamiltonian as 

.. math::
        
         \hat{H}=\sum_{i=1}^A \left[ \frac{\boldsymbol{p}_i^2}{2m}
         +\frac{1}{2}m\omega^2 \boldsymbol{r}^2_i
         \right] + \sum_{i < j}^A \left[ V_{ij}-\frac{m\omega^2}{2A}
         (\boldsymbol{r}_i-\boldsymbol{r}_j)^2
         \right]-H_{\mathrm{CoM}}.
         

The Woods-Saxon potential is a mean field potential for the nucleons (protons and neutrons) 
inside an atomic nucleus. It represent an average potential that a given nucleon feels from  the forces applied on each nucleon. 
The parametrization is

.. math::
        
        \hat{u}_{\mathrm{ext}}(r)=-\frac{V_0}{1+\exp{(r-R)/a}},
        

with :math:`V_0\approx 50` MeV representing the potential well depth, :math:`a\approx 0.5` fm 
length representing the "surface thickness" of the nucleus and :math:`R=r_0A^{1/3}`, with :math:`r_0=1.25` fm and :math:`A` the number of nucleons.
The value for :math:`r_0` can be extracted from a fit to data, see for example `M. |nbsp| Kirson <http://www.sciencedirect.com/science/article/pii/S037594740600769X>`__.

The following python code produces a plot of the Woods-Saxon potential with the above parameters. 

.. code-block:: text

        import numpy as np
        from  matplotlib import pyplot as plt
        from matplotlib import rc, rcParams
        import matplotlib.units as units
        import matplotlib.ticker as ticker
        rc('text',usetex=True)
        rc('font',**{'family':'serif','serif':['Woods-Saxon potential']})
        font = {'family' : 'serif',
                'color'  : 'darkred',
                'weight' : 'normal',
                'size'   : 16,
                }
        v0 = 50
        A = 100
        a = 0.5
        r0 = 1.25
        R = r0*A**(0.3333)
        x = np.linspace(0.0, 10.0)
        y = -v0/(1+np.exp((x-R)/a))
        
        plt.plot(x, y, 'b-')
        plt.title(r'{\bf Woods-Saxon potential}', fontsize=20)     
        plt.text(3, -40, r'Parameters: $A=20$, $V_0=50$ [MeV]', fontdict=font)
        plt.text(3, -44, r'$a=0.5$ [fm], $r_0=1.25$ [fm]', fontdict=font)
        plt.xlabel(r'$r$ [fm]',fontsize=20)
        plt.ylabel(r'$V(r)$ [MeV]',fontsize=20)
        
        # Tweak spacing to prevent clipping of ylabel
        plt.subplots_adjust(left=0.15)
        plt.savefig('woodsaxon.pdf', format='pdf')

From the plot we notice that the potential
* rapidly approaches zero as :math:`r` goes to infinity, reflecting the short-distance nature of the strong nuclear force.

* For large :math:`A`, it is approximately flat in the center.

* Nucleons near the surface of the nucleus experience a large force towards the center.

We have introduced a single-particle Hamiltonian

.. math::
        
          H_0=\sum_{i=1}^A \hat{h}_0(x_i) =  \sum_{i=1}^A\left(\hat{t}(x_i) + \hat{u}_{\mathrm{ext}}(x_i)\right),
        

with an external and central symmetric potential :math:`u_{\mathrm{ext}}(x_i)`, which is often 
approximated by a harmonic oscillator potential or a Woods-Saxon potential. Being central symmetric leads to a degeneracy 
in energy which is not observed experimentally. We see this from for example our discussion of separation energies and magic numbers. There are, in addition to the assumed magic numbers from a harmonic oscillator basis of :math:`2,8,20,40,70\dots` magic numbers like :math:`28`, :math:`50`, :math:`82` and :math:`126`. 

To produce these additional numbers, we need to add a phenomenological spin-orbit force which lifts the degeneracy, that is

.. math::
        
        \hat{h}(x_i) =  \hat{t}(x_i) + \hat{u}_{\mathrm{ext}}(x_i) +\xi(\boldsymbol{r})\boldsymbol{ls}=\hat{h}_0(x_i)+\xi(\boldsymbol{r})\boldsymbol{ls}. 
        

We have introduced a modified single-particle Hamiltonian

.. math::
        
        \hat{h}(x_i) =  \hat{t}(x_i) + \hat{u}_{\mathrm{ext}}(x_i) +\xi(\boldsymbol{r})\boldsymbol{ls}=\hat{h}_0(x_i)+\xi(\boldsymbol{r})\boldsymbol{ls}. 
        

We can calculate the expectation value of the latter using the fact that

.. math::
        
        \xi(\boldsymbol{r})\boldsymbol{ls}=\frac{1}{2}\xi(\boldsymbol{r})\left(\boldsymbol{j}^2-\boldsymbol{l}^2-\boldsymbol{s}^2\right).
        

For a single-particle state with quantum numbers :math:`nlj` (we suppress :math:`s` and :math:`m_j`), with :math:`s=1/2`, we obtain the single-particle energies

.. math::
        
        \varepsilon_{nlj} = \varepsilon_{nlj}^{(0)}+\Delta\varepsilon_{nlj}, 
        

with :math:`\varepsilon_{nlj}^{(0)}` being the single-particle energy obtained with :math:`\hat{h}_0(x)` and

.. math::
        
        \Delta\varepsilon_{nlj}=\frac{C}{2}\left(j(j+1)-l(l+1)-\frac{3}{4}\right).
        

The spin-orbit force gives thus an additional contribution to the energy

.. math::
        
        \Delta\varepsilon_{nlj}=\frac{C}{2}\left(j(j+1)-l(l+1)-\frac{3}{4}\right),
        

which lifts the degeneracy we have seen before in the harmonic oscillator or Woods-Saxon potentials. The value :math:`C` is the radial
integral involving :math:`\xi(\boldsymbol{r})`. Depending on the value of :math:`j=l\pm 1/2`, we obtain 

.. math::
        
        \Delta\varepsilon_{nlj=l-1/2}=\frac{C}{2}l,
        

or

.. math::
        
        \Delta\varepsilon_{nlj=l+1/2}=-\frac{C}{2}(l+1),
        

clearly lifting the degeneracy. Note well that till now we have simply postulated the spin-orbit force in *ad hoc* way.
Later, we will see how this term arises from the two-nucleon force in a natural way. 

With the spin-orbit force, we can modify our Woods-Saxon potential to 

.. math::
        
        \hat{u}_{\mathrm{ext}}(r)=-\frac{V_0}{1+\exp{(r-R)/a}}+V_{so}(r)\boldsymbol{ls},
        

with

.. math::
        
        V_{so}(r) = V_{so}\frac{1}{r}\frac{d f_{so}(r)}{dr},
        

where we have 

.. math::
        
        f_{so}(r) = \frac{1}{1+\exp{(r-R_{so})/a_{so}}}.
        

We can also add, in case of proton, a Coulomb potential. The Woods-Saxon potential has been widely used in parametrizations of
effective single-particle potentials. **However, as was the case with the harmonic oscillator, none of these potentials are linked directly to the nuclear forces**. Our next step is to build a mean field based on the nucleon-nucleon interaction.
This will lead us to our first and simplest many-body theory, Hartree-Fock theory.  

The Woods-Saxon potential does allow for closed-form or analytical solutions of the eigenvalue problem

.. math::
        
          \hat{h}_0(x_i)\psi_{\alpha}(x_i)=\varepsilon_{\alpha}\psi_{\alpha}(x_i).  
        

For the harmonic oscillator in three dimensions we have closed-form expressions for the energies and analytical solutions for the eigenstates,
with the latter given by either Hermite polynomials (cartesian coordinates) or Laguerre polynomials (spherical coordinates).

To solve the above equation is however rather straightforward numerically. 

.. !split

Numerical solution of the single-particle Schroedinger equation
===============================================================

We will illustrate the numerical solution of Schroedinger's equation by solving it for the harmonic oscillator in three dimensions.
It is straightforward to change the harmonic oscillator potential with a Woods-Saxon potential, or any other type of potentials. 

We are interested in the solution of the radial part of Schroedinger's equation for one nucleon. 
The angular momentum part  is given by the so-called Spherical harmonics. 

The radial equation reads

.. math::
        
          -\frac{\hbar^2}{2 m} \left ( \frac{1}{r^2} \frac{d}{dr} r^2
          \frac{d}{dr} - \frac{l (l + 1)}{r^2} \right )R(r) 
             + V(r) R(r) = E R(r).
        

In our case :math:`V(r)` is the harmonic oscillator potential :math:`(1/2)kr^2` with
:math:`k=m\omega^2` and :math:`E` is
the energy of the harmonic oscillator in three dimensions.
The oscillator frequency is :math:`\omega` and the energies are

.. math::
        
        E_{nl}=  \hbar \omega \left(2n+l+\frac{3}{2}\right),
        

with :math:`n=0,1,2,\dots` and :math:`l=0,1,2,\dots`.

Since we have made a transformation to spherical coordinates it means that 
:math:`r\in [0,\infty)`.  
The quantum number
:math:`l` is the orbital momentum of the nucleon.   Then we substitute :math:`R(r) = (1/r) u(r)` and obtain

.. math::
        
          -\frac{\hbar^2}{2 m} \frac{d^2}{dr^2} u(r) 
               + \left ( V(r) + \frac{l (l + 1)}{r^2}\frac{\hbar^2}{2 m}
                                            \right ) u(r)  = E u(r) .
        

The boundary conditions are :math:`u(0)=0` and :math:`u(\infty)=0`.

We introduce a dimensionless variable :math:`\rho = (1/\alpha) r`
where :math:`\alpha` is a constant with dimension length and get

.. math::
        
          -\frac{\hbar^2}{2 m \alpha^2} \frac{d^2}{d\rho^2} u(\rho) 
               + \left ( V(\rho) + \frac{l (l + 1)}{\rho^2}
                 \frac{\hbar^2}{2 m\alpha^2} \right ) u(\rho)  = E u(\rho) .
        

Let us specialize to :math:`l=0`. 
Inserting :math:`V(\rho) = (1/2) k \alpha^2\rho^2` we end up with

.. math::
        
          -\frac{\hbar^2}{2 m \alpha^2} \frac{d^2}{d\rho^2} u(\rho) 
               + \frac{k}{2} \alpha^2\rho^2u(\rho)  = E u(\rho) .
        

We multiply thereafter with :math:`2m\alpha^2/\hbar^2` on both sides and obtain

.. math::
        
          -\frac{d^2}{d\rho^2} u(\rho) 
               + \frac{mk}{\hbar^2} \alpha^4\rho^2u(\rho)  = \frac{2m\alpha^2}{\hbar^2}E u(\rho) .
        

We have thus

.. math::
        
          -\frac{d^2}{d\rho^2} u(\rho) 
               + \frac{mk}{\hbar^2} \alpha^4\rho^2u(\rho)  = \frac{2m\alpha^2}{\hbar^2}E u(\rho) .
        

The constant :math:`\alpha` can now be fixed
so that

.. math::
        
        \frac{mk}{\hbar^2} \alpha^4 = 1,
        

or 

.. math::
        
        \alpha = \left(\frac{\hbar^2}{mk}\right)^{1/4}.
        

Defining

.. math::
        
        \lambda = \frac{2m\alpha^2}{\hbar^2}E,
        

we can rewrite Schroedinger's equation as

.. math::
        
          -\frac{d^2}{d\rho^2} u(\rho) + \rho^2u(\rho)  = \lambda u(\rho) .
        

This is the first equation to solve numerically. In three dimensions 
the eigenvalues for :math:`l=0` are 
:math:`\lambda_0=3,\lambda_1=7,\lambda_2=11,\dots .`

We use the standard
expression for the second derivative of a function :math:`u`

.. math::
   :label: eq:diffoperation
        
            u''=\frac{u(\rho+h) -2u(\rho) +u(\rho-h)}{h^2} +O(h^2),
            
         

where :math:`h` is our step.
Next we define minimum and maximum values for the variable :math:`\rho`,
:math:`\rho_{\mathrm{min}}=0`  and :math:`\rho_{\mathrm{max}}`, respectively.
You need to check your results for the energies against different values
:math:`\rho_{\mathrm{max}}`, since we cannot set
:math:`\rho_{\mathrm{max}}=\infty`. 

With a given number of steps, :math:`n_{\mathrm{step}}`, we then 
define the step :math:`h` as

.. math::
        
          h=\frac{\rho_{\mathrm{max}}-\rho_{\mathrm{min}} }{n_{\mathrm{step}}}.
        

Define an arbitrary value of :math:`\rho` as 

.. math::
        
            \rho_i= \rho_{\mathrm{min}} + ih \hspace{1cm} i=0,1,2,\dots , n_{\mathrm{step}}
        

we can rewrite the Schroedinger equation for :math:`\rho_i` as

.. math::
        
        -\frac{u(\rho_i+h) -2u(\rho_i) +u(\rho_i-h)}{h^2}+\rho_i^2u(\rho_i)  = \lambda u(\rho_i),
        

or in  a more compact way

.. math::
        
        -\frac{u_{i+1} -2u_i +u_{i-1}}{h^2}+\rho_i^2u_i=-\frac{u_{i+1} -2u_i +u_{i-1} }{h^2}+V_iu_i  = \lambda u_i,
        

where :math:`V_i=\rho_i^2` is the harmonic oscillator potential.

Define first the diagonal matrix element

.. math::
        
           d_i=\frac{2}{h^2}+V_i,
        

and the non-diagonal matrix element 

.. math::
        
           e_i=-\frac{1}{h^2}.
        

In this case the non-diagonal matrix elements are given by a mere constant. *All non-diagonal matrix elements are equal*.

With these definitions the Schroedinger equation takes the following form

.. math::
        
        d_iu_i+e_{i-1}u_{i-1}+e_{i+1}u_{i+1}  = \lambda u_i,
        

where :math:`u_i` is unknown. We can write the 
latter equation as a matrix eigenvalue problem 

.. math::
   :label: eq:sematrix
        
            \left( \begin{array}{ccccccc} d_1 & e_1 & 0   & 0    & \dots  &0     & 0 \\
                                        e_1 & d_2 & e_2 & 0    & \dots  &0     &0 \\
                                        0   & e_2 & d_3 & e_3  &0       &\dots & 0\\
                                        \dots  & \dots & \dots & \dots  &\dots      &\dots & \dots\\
                                        0   & \dots & \dots & \dots  &\dots       &d_{n_{\mathrm{step}}-2} & e_{n_{\mathrm{step}}-1}\\
                                        0   & \dots & \dots & \dots  &\dots       &e_{n_{\mathrm{step}}-1} & d_{n_{\mathrm{step}}-1}
        
                     \end{array} \right)      \left( \begin{array}{c} u_{1} \\
                                                                      u_{2} \\
                                                                      \dots\\ \dots\\ \dots\\
                                                                      u_{n_{\mathrm{step}}-1}
                     \end{array} \right)=\lambda \left( \begin{array}{c} u_{1} \\
                                                                      u_{2} \\
                                                                      \dots\\ \dots\\ \dots\\
                                                                      u_{n_{\mathrm{step}}-1}
                     \end{array} \right) 
              
         

or if we wish to be more detailed, we can write the tridiagonal matrix as

.. math::
   :label: eq:matrixse
        
            \left( \begin{array}{ccccccc} \frac{2}{h^2}+V_1 & -\frac{1}{h^2} & 0   & 0    & \dots  &0     & 0 \\
                                        -\frac{1}{h^2} & \frac{2}{h^2}+V_2 & -\frac{1}{h^2} & 0    & \dots  &0     &0 \\
                                        0   & -\frac{1}{h^2} & \frac{2}{h^2}+V_3 & -\frac{1}{h^2}  &0       &\dots & 0\\
                                        \dots  & \dots & \dots & \dots  &\dots      &\dots & \dots\\
                                        0   & \dots & \dots & \dots  &\dots       &\frac{2}{h^2}+V_{n_{\mathrm{step}}-2} & -\frac{1}{h^2}\\
                                        0   & \dots & \dots & \dots  &\dots       &-\frac{1}{h^2} & \frac{2}{h^2}+V_{n_{\mathrm{step}}-1}
        
                     \end{array} \right)  
         
         

Recall that the solutions are known via the boundary conditions at
:math:`i=n_{\mathrm{step}}` and at the other end point, that is for  :math:`\rho_0`.
The solution is zero in both cases.

The following python program is an example of how one can obtain the eigenvalues for a single-nucleon moving in a harmonic oscillator potential. It is rather easy to change the onebody-potential with ones like a Woods-Saxon potential. 

* The c++ and Fortran versions of this program can be found `here <https://github.com/NuclearStructure/PHY981/tree/master/doc/pub/spdata/programs>`__. 

* The c++  program uses the c++ library `armadillo <http://arma.sourceforge.net/>`__. 

* To install armadillo see the `guidelines <http://www.uio.no/studier/emner/matnat/fys/FYS4411/v14/guides/installing-armadillo/>`__. 

* For mac users I recommend using `*brew* <http://brew.sh/>`__.

* If you use ipython notebook, you can run c++ programs following the instructions `here <http://nbviewer.ipython.org/github/dragly/cppmagic/blob/master/example.ipynb>`__

The code sets up the Hamiltonian matrix by defining the the minimun and maximum values of :math:`r` with a
maximum value of integration points.  These are set in the initialization function. It plots the 
eigenfunctions of the three lowest eigenstates.

.. code-block:: text

        #Program which solves the one-particle Schrodinger equation 
        #for a potential specified in function
        #potential(). This example is for the harmonic oscillator in 3d
        
        from  matplotlib import pyplot as plt
        import numpy as np
        #Function for initialization of parameters
        def initialize():
            RMin = 0.0
            RMax = 10.0
            lOrbital = 0
            Dim = 400
            return RMin, RMax, lOrbital, Dim
        # Here we set up the harmonic oscillator potential
        def potential(r):
            return r*r
        
        #Get the boundary, orbital momentum and number of integration points
        RMin, RMax, lOrbital, Dim = initialize()
        
        #Initialize constants
        Step    = RMax/(Dim+1)
        DiagConst = 2.0 / (Step*Step)
        NondiagConst =  -1.0 / (Step*Step)
        OrbitalFactor = lOrbital * (lOrbital + 1.0)
        
        #Calculate array of potential values
        v = np.zeros(Dim)
        r = np.linspace(RMin,RMax,Dim)
        for i in xrange(Dim):
            r[i] = RMin + (i+1) * Step;
            v[i] = potential(r[i]) + OrbitalFactor/(r[i]*r[i]);
        
        #Setting up tridiagonal matrix and find eigenvectors and eigenvalues
        Hamiltonian = np.zeros((Dim,Dim))
        Hamiltonian[0,0] = DiagConst + v[0];
        Hamiltonian[0,1] = NondiagConst;
        for i in xrange(1,Dim-1):
            Hamiltonian[i,i-1]  = NondiagConst;
            Hamiltonian[i,i]    = DiagConst + v[i];
            Hamiltonian[i,i+1]  = NondiagConst;
        Hamiltonian[Dim-1,Dim-2] = NondiagConst;
        Hamiltonian[Dim-1,Dim-1] = DiagConst + v[Dim-1];
        # diagonalize and obtain eigenvalues, not necessarily sorted
        EigValues, EigVectors = np.linalg.eig(Hamiltonian)
        # sort eigenvectors and eigenvalues
        permute = EigValues.argsort()
        EigValues = EigValues[permute]
        EigVectors = EigVectors[:,permute]
        # now plot the results for the three lowest lying eigenstates
        for i in xrange(3):
            print EigValues[i]
        FirstEigvector = EigVectors[:,0]
        SecondEigvector = EigVectors[:,1]
        ThirdEigvector = EigVectors[:,2]
        plt.plot(r, FirstEigvector**2 ,'b-',r, SecondEigvector**2 ,'g-',r, ThirdEigvector**2 ,'r-')
        plt.axis([0,4.6,0.0, 0.025])
        plt.xlabel(r'$r$')
        plt.ylabel(r'Radial probability $r^2|R(r)|^2$')
        plt.title(r'Radial probability distributions for three lowest-lying states')
        plt.savefig('eigenvector.pdf')
        plt.savefig('eigenvector.png')
        plt.show()
        

.. --- begin exercise ---

Exercise 1: Masses and binding energies
---------------------------------------

The data on binding energies can be found in the file bedata.dat at the github address of the `Nuclear Structure course at MSU, PHY981 <https://github.com/NuclearStructure/PHY981/tree/master/doc/pub/spdata/programs>`__

**a)**
Write a small program which reads in the proton and neutron numbers and the binding energies 
and make a plot of all neutron separation energies for the chain of oxygen (O), calcium (Ca), nickel (Ni), tin (Sn) and lead (Pb) isotopes, that is you need to plot

.. math::
        
        S_n= BE(N,Z)-BE(N-1,Z).
        

Comment your results.

**b)**
In the same figures, you should also include the liquid drop model results of Eq. |nbsp| (2.17) of Alex Brown's text, namely

.. math::
        
        BE(N,Z)= \alpha_1A-\alpha_2A^{2/3}-\alpha_3\frac{Z^2}{A^{1/3}}-\alpha_4\frac{(N-Z)^2}{A},
        

with :math:`\alpha_1=15.49` MeV, :math:`\alpha_2=17.23` MeV, :math:`\alpha_3=0.697` MeV and :math:`\alpha_4=22.6` MeV.
Again, comment your results.

**c)**
Make also a plot of the binding energies as function of :math:`A` using the data in the file on binding energies and the above liquid drop model.  Make a figure similar to figure 2.5 of Alex Brown where you set the various parameters :math:`\alpha_i=0`. Comment your results.

**d)**
Use the liquid drop model to find the neutron drip lines   for Z values up to 120.
Analyze then the fluorine isotopes and find, where available the corresponding experimental data, and compare the liquid drop model predicition with experiment. 
Comment your results.
A program example in C++ and the input data file *bedata.dat* can be found found at the github repository for the `course <https://github.com/NuclearStructure/PHY981/tree/master/doc/pub/spdata/programs>`__

.. --- end exercise ---

.. --- begin exercise ---

Exercise 2: Eigenvalues and eigenvectors for various single-particle potentials
-------------------------------------------------------------------------------

The program for finding the eigenvalues of the harmonic oscillator are in the `github folder <https://github.com/NuclearStructure/PHY981/tree/master/doc/pub/spdata/programs>`__.

You can use this program to solve the exercises below, or write your own using your preferred programming language, be it python, fortran or c++ or other languages. Here I will mainly provide fortran, python and c++.

**a)**
Compute the eigenvalues of the five lowest states with a given orbital momentum and oscillator frequency :math:`\omega`. Study these results as functions of the the maximum value of :math:`r` and the number of integration points :math:`n`, starting with  :math:`r_{\mathrm{max}}=10`. Compare the computed ones with the exact values and comment your results.

**b)**
Plot thereafter the eigenfunctions as functions of :math:`r` for the lowest-lying state with a given orbital momentum :math:`l`.

**c)**
Replace thereafter the harmonic oscillator potential with a Woods-Saxon potential using the parameters discussed above. Compute the lowest five eigenvalues and plot the eigenfunction of the lowest-lying state. How does this compare with the harmonic oscillator? Comment your results and possible implications for nuclear physics studies.

.. --- end exercise ---

.. --- begin exercise ---

Exercise 3: Operators and Slater determinants
---------------------------------------------

Consider the Slater determinant

.. math::
        
        \Phi_{\lambda}^{AS}(x_{1}x_{2}\dots x_{N};\alpha_{1}\alpha_{2}\dots\alpha_{N})
        =\frac{1}{\sqrt{N!}}\sum_{p}(-)^{p}P\prod_{i=1}^{N}\psi_{\alpha_{i}}(x_{i}).
        

where :math:`P` is an operator which permutes the coordinates of two particles. We have assumed here that the 
number of particles is the same as the number of available single-particle states, represented by the
greek letters :math:`\alpha_{1}\alpha_{2}\dots\alpha_{N}`.

**a)**
Write  out :math:`\Phi^{AS}` for :math:`N=3`.

**b)**
Show that

.. math::
        
        \int dx_{1}dx_{2}\dots dx_{N}\left\vert
        \Phi_{\lambda}^{AS}(x_{1}x_{2}\dots x_{N};\alpha_{1}\alpha_{2}\dots\alpha_{N})
        \right\vert^{2} = 1.
        

**c)**
Define a general onebody operator :math:`\hat{F} = \sum_{i}^N\hat{f}(x_{i})` and a general  twobody operator :math:`\hat{G}=\sum_{i>j}^N\hat{g}(x_{i},x_{j})` with :math:`g` being invariant under the interchange of the coordinates of particles :math:`i` and :math:`j`. Calculate the matrix elements for a two-particle Slater determinant

.. math::
        
        \langle\Phi_{\alpha_{1}\alpha_{2}}^{AS}|\hat{F}|\Phi_{\alpha_{1}\alpha_{2}}^{AS}\rangle,
        

and

.. math::
        
        \langle\Phi_{\alpha_{1}\alpha_{2}}^{AS}|\hat{G}|\Phi_{\alpha_{1}\alpha_{2}}^{AS}\rangle.
        

Explain the short-hand notation for the Slater determinant.
Which properties do you expect these operators to have in addition to an eventual permutation
symmetry?

.. --- end exercise ---

.. --- begin exercise ---

Exercise 4: First simple shell-model calculation
------------------------------------------------

We will now consider a simple three-level problem, depicted in the figure below. This is our first and very simple model of a possible many-nucleon (or just fermion) problem and the shell-model.
The single-particle states are labelled by the quantum number :math:`p` and can accomodate up to two single particles,  viz., every single-particle state  is doubly degenerate (you could think of this as one state having spin up and the other spin down). 
We let the spacing between the doubly degenerate single-particle states be constant, with value :math:`d`.  The first state
has energy :math:`d`. There are only three available single-particle states, :math:`p=1`, :math:`p=2` and :math:`p=3`, as illustrated
in the figure.

**a)**
How many two-particle Slater determinants can we construct in this space? 

We limit ourselves to a system with only the two lowest single-particle orbits and two particles, :math:`p=1` and :math:`p=2`. We assume that we can write the Hamiltonian as

.. math::
        
               \hat{H}=\hat{H}_0+\hat{H}_I,
        

and that the onebody part of the Hamiltonian with single-particle operator :math:`\hat{h}_0` has the property

.. math::
        
        \hat{h}_0\psi_{p\sigma} = p\times d \psi_{p\sigma},
        

where we have added a spin quantum number :math:`\sigma`. 
We assume also that the only two-particle states that can exist are those where two particles are in the 
same state :math:`p`, as shown by the two possibilities to the left in the figure.
The two-particle matrix elements of :math:`\hat{H}_I` have all a constant value, :math:`-g`.

**b)**
Show then that the Hamiltonian matrix can be written as 

.. math::
        
        \left(\begin{array}{cc}2d-g &-g \\
        -g &4d-g \end{array}\right),
        

**c)**
Find the eigenvalues and eigenvectors.  What is mixing of the state with two particles in :math:`p=2`  to the wave function with two-particles in :math:`p=1`? Discuss your results in terms of a linear combination of Slater determinants.

**d)**
Add the possibility that the two particles can be in the state with :math:`p=3` as well and find the Hamiltonian matrix, the eigenvalues and the eigenvectors. We still insist that we only have two-particle states composed of two particles being in the same level :math:`p`. You can diagonalize numerically your :math:`3\times 3` matrix.
This simple model catches several birds with a stone. It demonstrates how we can build linear combinations
of Slater determinants and interpret these as different admixtures to a given state. It represents also the way we are going to interpret these contributions.  The two-particle states above :math:`p=1` will be interpreted as 
excitations from the ground state configuration, :math:`p=1` here.  The reliability of this ansatz for the ground state, 
with two particles in :math:`p=1`,
depends on the strength of the interaction :math:`g` and the single-particle spacing :math:`d`.
Finally, this model is a simple schematic ansatz for studies of pairing correlations and thereby superfluidity/superconductivity  
in fermionic systems. 

.. figure:: fig-intro/simplemodel.png
   :width: 500

   Schematic plot of the possible single-particle levels with double degeneracy. The filled circles indicate occupied particle states. The spacing between each level :math:`p` is constant in this picture. We show some possible two-particle states

.. --- end exercise ---

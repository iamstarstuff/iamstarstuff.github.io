---
layout: post
title: Cosmic Muon Tracker
description: Dissertation - M.Sc Physics
---

# Intro

Cosmic Muon Tracker (CMT) is a portable charged particle (Muon) Tracker, which is used to track and acquire live muon trajectories. Eight layers of Resistive Plate Chambers (RPCs) are used to track Muons by ionisation. Each Muon event from the tracker is processed by the FPGA based data acquisition system and generates events based on coincidence. Events are also displayed using LEDs in real-time. CMT can be used to plot angular distribution of muons, counting rate of strips and their dependence on ambient parameters such as temperature, relative humidity and barometric pressure, which are recorded by the DAQ (Data acquisition module).

## Muons
The muon is an elementary particle belonging to the family of leptons (2nd generation),
and one of the nature’s fundamental “building blocks of matter”. The other members of the
lepton family are the Electron and Tau. Muons were discovered by Carl D. Anderson and
Seth Neddermeyer at Caltech in 1936, while studying cosmic radiation. The existence of the
muon was confirmed in 1937 by J. C. Street and E. C. Stevenson's cloud chamber
experiment.

Muons are 1/2 spin particles, similar to electrons with electric charge of -1e but with a
much greater mass. Muons have a mass of 105.7 $\frac{MeV}{c^2}$, which is about 207 times that of
the electron. They participate in electromagnetic and weak interactions, but not in strong
interactions. Due to their mass, muons are unstable and while passing through matter can
decay into two ways via weak force, either captured by the nucleus to emit a neutron or by
spontaneous decay to produce an electron (or positron) and two neutrinos.

$$N(t) = N(0)\exp^{-\frac{t}{\tau}}$$

Where $N(0)$ is the initial population of muons, $N(t)$ is the population of muons at time $t$ and $\tau$ is the muon lifetime. The muon lifetime is measured to be **$\tau = 2.19703 \mu s$**.

## Source of Cosmic Muons

The earth’s upper atmosphere is bombarded by the primary cosmic radiation, which is
mainly composed of protons and heavier nuclei (Helium, Carbon, Oxygen) (98%) and
electrons (2%). The primary source of cosmic rays are supernovae. They collide with the
atmospheric nuclei and produce a shower of particles including neutral and charged pions,
known as secondary cosmic rays. Many of the new particles are very short- lived and do not
survive to reach sea level, but positive and negative pions created in the process decay into
highly energetic muons which travel almost at the speed of light and are detectable at
ground level.

![cosmic rays](https://astronuclphysics.info/KosmZareniSek.gif)

# Resistive Plate Chambers

The Resistive Plate Chamber (RPC) is a gaseous charged particle detector which uses
a constant and uniform electric field produced by two parallel electrode plates which are
made up of a material with high bulk resistivity. RPC was introduced in 1981 by R. Santonico
and R. Cardarelli as a practical alternative to the remarkable localised discharge spark
Counters. RPC is based on essentially the same principle as that of Pestov’s Planar Spark
Chamber.

Its working concepts are based on the detection of gaseous ionization produced by
charged particles traversing the active area of the detector, large avalanche of electron
under a strong uniform electric. A gas mixture namely R134a, iso-butane (C4H10) and SF6,
which is ionised by charged particles traversing the detector, is flown through the gap
between the electrodes. The electrodes which we are using in this experiment are glass
electrodes, coated with a layer of graphite on outer side.

The glass RPC’s have been proposed as the active element in the iron calorimeter
(ICAL) detector for the India-based Neutrino Observatory (INO). RPCs are used in almost all
big high energy physics experiment presently operational, either for trigger or timing
measurement, whereas INO is going to us this for both triggering and tracking of charge
particles. Single and double gap RPCs have also found application in cosmic ray experiments
as well as in Astro-particle physics.

<p align="center">
  <img src="{{ '/assets/images/CMT.png' }}"/>
</p>



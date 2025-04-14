# Welcome

Dear visitor,

Welcome to my personal coding page.

---

# Contact
For information about me, check out my ORCID or research portal profile below. If you have any requests or questions, drop me an email. 

- Email address: benjaminbolling at icloud dot com
- ORCID: [0000-0002-6650-5365](https://orcid.org/0000-0002-6650-5365) [![ORCID](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-6650-5365)
- [LU Research Portal](https://portal.research.lu.se/en/persons/benjamin-bolling)

---

# Coding projects

### Published in papers but not open source:
- Multi-Dimensional Spectrogram Application for Live Visualization and Manipulation of Large Waveforms ([go to](#spec))
- Dynamic Control Room Interfaces for Complex Particle Accelerator Systems ([go to](#dynamic))

### Published in papers and open source:
-  A Shift Scheduling tool ([go to](#rsw))
- MAX IV soft RF sweeper ([go to](#sweep))
- DynaGUI ([go to](#dynagui))

### Not published in papers but open source:
- SPMTUI ([go to](#spmtui))

---

# Descriptions of projects

---

## Multi-Dimensional Spectrogram Application for Live Visualization and Manipulation of Large Waveforms <a name="spec"></a>

Collect, manipulate and visualize large waveforms at high repetition rates (tested with up to 14Hz) in real time or archived data in 2D (using heatmaps) or 3D, utilizing Python and the pure-python graphics and GUI library PyQtGraph and PyQt5 with Python-OpenGL bindings.

[Link to Publication](https://doi.org/10.18429/JACoW-ICALEPCS2023-TUMBCMO12)

---

## Dynamic Control Room Interfaces for Complex Particle Accelerator Systems <a name="dynamic"></a>

Commissioning of complex machines for the first time is the same as commissioning something one knows nothing about. This paper describes three well-used dynamic control room interfaces.

[Link to Publication](https://doi.org/10.18429/JACoW-ICALEPCS2023-TUMBCMO07)

---

## Shift Scheduling tool <a name="rsw"></a>

A Computational Approach to Generate Multi-Shift Rotational Workforce Schedules. 

Phase 1: The algorithm takes into account a list of inputs (constraints) and returns all possible solutions. The schedule maker can then select the most feasible solution(s) to proceed with.

Phase 2: A feasible solution was selected and is constructed to its final shape, and is then ready for exportation (in .txt or .CSV format).

[![DOI](https://joss.theoj.org/papers/10.21105/joss.03431/status.svg)](https://doi.org/10.21105/joss.03431)

[Link to RSW repo](https://github.com/benjaminbolling/RSW)

---

## MAX IV soft RF sweeper <a name="sweep"></a>
A very simple tool for slowly changing a storage ring's master oscillator's radio-frequency (RF). The steps in the application are small enough for the storage ring's orbit feedback to adjust the orbit such that sensitive beamlines do not register a disturbing fluctuation (in terms of beam intensity and position). Using this tool, the user can define how much the ring's RF is to be changed. The application was part of a publication, see link below.

[Link to Publication](https://www.mdpi.com/2410-390X/4/3/26)

[Link to Application](https://github.com/benjaminbolling/MAXIVsoftRFsweeper)

---

## DynaGUI <a name="dynagui"></a>

DynaGUI stands for Dynamic Graphical User Interface and is a method to construct temporary, permanent and/or a set of GUI:s for users in a simple and fast manner. Developed during shift works at a particle accelerator, the initial goal was to fill in some functions that were then missing: Fast dynamic construction of new control system GUI:s for various purposes. The code is fully built in Python.

[![DOI](https://joss.theoj.org/papers/10.21105/joss.01942/status.svg)](https://doi.org/10.21105/joss.01942)

[Link to DynaGUI repo](https://github.com/benjaminbolling/DynaGUI)

---

## SPMTUI <a name="dynagui"></a> spmtui
SPMTUI stands for Simple Project Management Text-based User Interface and was made for myself for logging and keeping track of tasks and projects to do, in progress, and completed. The code is fully built in Python. SPMTUI functionalities includes:
- Commands with tab-completion
- Colour-coded states of each task
- Description of each task
- Logbook tracking of task initiation and changes (both manual and automatic entries)

[Link to SPMTUI repo](https://github.com/benjaminbolling/SPMTUI)

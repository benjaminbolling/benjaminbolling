# Welcome

Dear visitor,

Welcome to my personal coding page. For information about me, check out my ORCID or research portal profile below. If you have any requests or questions, drop me an email. 

<table>
<tr>
<th> Contact information </th>
<th> GitHub statistics </th>
</tr>
<tr>
<td>

- Email address:
  - git username at icloud dot com
- ORCID: [0000-0002-6650-5365](https://orcid.org/0000-0002-6650-5365) [![ORCID](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-6650-5365)
- [LU Research Portal](https://portal.research.lu.se/en/persons/benjamin-bolling)
- [![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/benjamin-b-a320475b/)

</td>
<td>

![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=benjaminbolling&hide_border=true&show_icons=true&bg_color=151515&title_color=fb4362&icon_color=fb4362&text_bold=false&text_color=9e9e9e)

</td>
</tr>
</table>

---

# Coding Projects
A small collection of 5 coding projects.

### Published in papers but not open source:
- Multi-Dimensional Spectrogram Application for Live Visualization and Manipulation of Large Waveforms ([go to](#spec))
- Dynamic Control Room Interfaces for Complex Particle Accelerator Systems ([go to](#dynamic))

### Open source:
- A Shift Scheduling tool ([go to](#rsw)) (published as a SW paper)
- DynaGUI ([go to](#dynagui)) (published as a SW paper)
- SPMTUI ([go to](#spmtui))

---

# About me
Here are some personal preferences when it comes to programming, writing, and analysing data. The only reason to have them here is because they make my profile page look fancy with all these badges.

| Programming languages (in a descending order) |
| --- |
| ( ... this is very political and I am heavily biased ... ) |
| [![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#) &rarr; ![Julia](https://img.shields.io/badge/-Julia-9558B2?logo=julia&logoColor=white) &rarr; [![Rust](https://img.shields.io/badge/Rust-%23000000.svg?e&logo=rust&logoColor=white)](#) &rarr; [![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)](#) &rarr; [![C++](https://img.shields.io/badge/C++-%2300599C.svg?logo=c%2B%2B&logoColor=white)](#) &rarr; [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#) &rarr; [![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?logo=openjdk&logoColor=white)](#) |

| Data Science packages | Writing |
| --- | --- | --- |
| [![NumPy](https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&logoColor=fff)](#) [![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)](#) [![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff)](#) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?logo=scipy&logoColor=%white) | [![Markdown](https://img.shields.io/badge/Markdown-%23000000.svg?logo=markdown&logoColor=white)](#) ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?logo=latex&logoColor=white) |

| CI: | AI: | OS: | IDE: |
| --- | --- | --- | --- |
| [![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?logo=gitlab&logoColor=fff)](#) [![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white)](#) | [![ChatGPT](https://img.shields.io/badge/ChatGPT-74aa9c?logo=openai&logoColor=white)](#) ![GitHub Copilot](https://img.shields.io/badge/github_copilot-8957E5?logo=github-copilot&logoColor=white) | [![macOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=F0F0F0)](#) [![Arch Linux](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff)](#) [![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)](#) | [![Visual Studio Code](https://custom-icon-badges.demolab.com/badge/Visual%20Studio%20Code-0078d7.svg?logo=vsc&logoColor=white)](#) [![PyCharm](https://img.shields.io/badge/PyCharm-000?logo=pycharm&logoColor=fff)](#) |

---

# Descriptions of the coding projects
Beneath is a short description of the small collection of 5 coding projects.

## Multi-Dimensional Spectrogram Application for Live Visualization and Manipulation of Large Waveforms <a name="spec"></a>

Collect, manipulate and visualize large waveforms at high repetition rates (tested with up to 14Hz) in real time or archived data in 2D (using heatmaps) or 3D, utilizing Python and the pure-python graphics and GUI library PyQtGraph and PyQt5 with Python-OpenGL bindings.

[Link to Publication](https://doi.org/10.18429/JACoW-ICALEPCS2023-TUMBCMO12)


## Dynamic Control Room Interfaces for Complex Particle Accelerator Systems <a name="dynamic"></a>

Commissioning of complex machines for the first time is the same as commissioning something one knows nothing about. This paper describes three well-used dynamic control room interfaces.

[Link to Publication](https://doi.org/10.18429/JACoW-ICALEPCS2023-TUMBCMO07)


## Shift Scheduling tool <a name="rsw"></a>

A Computational Approach to Generate Multi-Shift Rotational Workforce Schedules. 

Phase 1: The algorithm takes into account a list of inputs (constraints) and returns all possible solutions. The schedule maker can then select the most feasible solution(s) to proceed with.

Phase 2: A feasible solution was selected and is constructed to its final shape, and is then ready for exportation (in .txt or .CSV format).

[![DOI](https://joss.theoj.org/papers/10.21105/joss.03431/status.svg)](https://doi.org/10.21105/joss.03431)

[Link to RSW repo](https://github.com/benjaminbolling/RSW)


## DynaGUI <a name="dynagui"></a>

DynaGUI stands for Dynamic Graphical User Interface and is a method to construct temporary, permanent and/or a set of GUI:s for users in a simple and fast manner. Developed during shift works at a particle accelerator, the initial goal was to fill in some functions that were then missing: Fast dynamic construction of new control system GUIs for various purposes. The code is fully built in Python.

[![DOI](https://joss.theoj.org/papers/10.21105/joss.01942/status.svg)](https://doi.org/10.21105/joss.01942)

[Link to DynaGUI repo](https://github.com/benjaminbolling/DynaGUI)


## SPMTUI <a name="dynagui"></a> spmtui
SPMTUI stands for Simple Project Management Text-based User Interface and was made for myself for logging and keeping track of tasks and projects to do, in progress, and completed. The code is fully built in Python. SPMTUI functionalities includes:
- Commands with tab-completion
- Colour-coded states of each task
- Description of each task
- Logbook tracking of task initiation and changes (both manual and automatic entries)

I ended up not using this tool but instead rely on structured [![Markdown](https://img.shields.io/badge/Markdown-%23000000.svg?logo=markdown&logoColor=white)](#) weekly planning checklists instead. 

[Link to SPMTUI repo](https://github.com/benjaminbolling/SPMTUI)

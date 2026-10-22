<p align="center">
  <img src="https://bonograph.co.in/docs/img/logo.png" alt="Bonograph logo" width="96">
</p>

<h1 align="center">Bonograph</h1>

<p align="center"><b>Plot. Analyze. Publish.</b><br>
A free statistics and graphing program for scientists - on your own computer, with no internet connection needed.</p>

<p align="center">
  <a href="https://github.com/Bonograph/Bonograph_download/releases/latest"><b>Download the latest version</b></a> ·
  <a href="https://bonograph.co.in">Website</a> ·
  <a href="https://bonograph.co.in/docs/">Documentation</a> ·
  <a href="https://bonograph.co.in/docs/learn.html">Learn statistics</a>
</p>

---
# Bonograph_download
Ah yes, the iconic software download repository! Why bother with coding when you can simply grab software? It's so much easier! 😏

Bonograph turns a table of measurements into the right test and a figure ready for a paper. Enter or paste your
data, and it suggests the analysis that fits, shows the checks on what that test assumes next to the result, and
writes the methods and results text for your report.

## What it does

- **97 analyses**: t tests, ANOVA (one-, two- and three-way, nested, repeated measures), non-parametric tests,
  correlation, linear, multiple and nonlinear regression, dose-response and curve fitting, survival analysis
  (Kaplan-Meier, log-rank, Cox), contingency tables, method agreement, multivariate methods, power and sample size,
  and more.
- **80 graph types**: lines, bars, markers, box and violin plots, heatmaps, survival curves, parts of a whole, polar
  graphs, side histograms, panels, zoom insets - and animated graphs that save as GIF files. Every graph is ready for
  publication, in light or dark.
- **8 kinds of table** that know what your data mean: X and Y, Columns, Repeats, Counts, Parts of a whole, Time to an
  event, and more.
- **Checks on every result**: Q-Q plots, residual plots and tests of equal spread beside each result, so you can see
  whether the test suits your data.
- **Methods and results text** for your report, written for you and ready to copy.
- **Molecular dynamics**: RMSD, flexibility, contacts and interaction fingerprints from a simulation trajectory.

## Download

Get the newest version from the
[**Releases page**](https://github.com/Bonograph/Bonograph_download/releases/latest), under **Assets**. Bonograph is
also available in the Microsoft Store.

| System | File | Needs |
|---|---|---|
| Windows | `Bonograph-Setup-<version>.exe` | 64-bit Windows 10 or 11 |
| Linux | `Bonograph-<version>-x86_64.AppImage`, or `.tar.gz` | 64-bit Ubuntu 22.04, Debian 12, Fedora 36 or newer |
| macOS (beta) | `Bonograph-<version>-macOS-AppleSilicon.dmg` or `-Intel.dmg` | macOS 13 Ventura or newer |

### Windows

Run the installer. It installs for your user account and needs no administrator rights. Windows may warn about an
unknown publisher, because the installer is not yet signed: click **More info**, then **Run anyway**.

### Linux

**AppImage** - one file, nothing to install:

```bash
chmod +x Bonograph-<version>-x86_64.AppImage
./Bonograph-<version>-x86_64.AppImage
```

**.tar.gz** - adds a menu entry and opens `.bono` session files with Bonograph:

```bash
tar xf Bonograph-<version>-linux-x86_64.tar.gz
bash Bonograph-<version>/install.sh
```

If no window opens, your desktop may be missing a library that Qt needs:
`sudo apt install libxcb-cursor0 libxkbcommon-x11-0 libegl1`

### macOS

Open the `.dmg` and drag Bonograph onto **Applications**. Choose the Apple Silicon file for any Mac sold since 2020,
and the Intel file for older Macs. The first time you open it, macOS says it cannot verify the app, because it is not
notarised by Apple: click **Done**, then open **System Settings > Privacy & Security**, click **Open Anyway** near the
bottom, and confirm. After that it opens normally. macOS support is in beta - please report anything that goes wrong.

## Your data stay on your computer

Bonograph works offline. Your data, sessions and results never leave your computer. The only request the program
makes is an optional check for a newer version - a plain "list the releases" sent to GitHub, with no name, identifier
or data in it - which you can switch off in the **Help** menu. See the
[privacy page](https://bonograph.co.in/docs/privacy.html).

## Learn more

- [First steps](https://bonograph.co.in/docs/first-steps.html) - install, make a table, a graph and a first test
- [Analyses](https://bonograph.co.in/docs/analyses.html) - which analysis answers which question
- [Graphs](https://bonograph.co.in/docs/graphs.html) - every graph type, with an example of each
- [Learn statistics](https://bonograph.co.in/docs/learn.html) - choosing a test, P values, effect sizes, checking
  assumptions and reporting results, for any researcher

## Using Bonograph in a publication

Bonograph is free to use, for research and teaching alike. If you publish results or figures you made with it,
please say in your publication that you used Bonograph, with the version number (shown under
**Help > About Bonograph & credits**).

## Problems, questions and suggestions

- **Report a problem**: open an [issue](https://github.com/Bonograph/Bonograph_download/issues) or write to
  bonograph@atomicmail.io. Please include the version, the kind of table and the analysis or graph you used, what
  you did, and what happened. A session file (`.bono`) helps - remove any data that must stay private first.
- **Suggest an analysis or a graph**: tell us what you want to learn from your data and, if you can, a paper or
  textbook that shows the method.

## Licence

Bonograph is free to download and use under its [terms of use](LICENSE.txt), which the installer shows and asks you
to accept. Bonograph™ and the Bonograph logo are trademarks of Yashkumar Rathod.

Bonograph is built on open-source libraries, each under its own licence: Python, Qt and PySide6, NumPy, SciPy,
Matplotlib, MDAnalysis, ProLIF, RDKit and others. The full list, with every licence text, is in the folder
`third_party_licences` beside the installed program and in **Help > About Bonograph & credits**.

**Qt and PySide6** are used under the GNU Lesser General Public License version 3 (LGPLv3). They ship as separate
library files beside the program, and you may replace them with your own build of the same version. The source
code of Qt and Qt for Python (PySide6) is available from
[download.qt.io](https://download.qt.io/official_releases/QtForPython/); on request we will also send you the exact
source of the versions we distribute, for at least three years after each release.

---

<p align="center">© 2026 Yashkumar Rathod · <a href="https://bonograph.co.in">bonograph.co.in</a></p>

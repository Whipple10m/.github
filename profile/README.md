# Whipple 10m

This site is dedicated to the preservation of code and documentation from the Whipple 10 meter gamma-ray telescope, which operated at the Fred Lawrence Whipple Observatory (FLWO) from 1968 to 2011.

[Kildea et al., Astroparticle Physics, 28, 2, 182-195, (2007)](https://www.sciencedirect.com/science/article/abs/pii/S0927650507000746) provide the details of the Whipple 10m system (camera, telescope, DAQ) during the period from 1997-2006, in the so-called GRANITE era. The article is also [available from its author](https://kildealab.com/publication/elsevier13/elsevier13.pdf) (last downloaded 2024-11-19). The code here comes largely from this period of time.

### Python Whipple data reader

We have developed a pure Python reader of the Whipple data from the GRANITE epoch from 1994 to 2011, which was stored in `FZ` format based on the CERN `ZEBRA` system. See the [pyfzreader repository](https://github.com/Whipple10m/pyfzreader).

### Online and offline software components

Some of the major software components during this period were:

- The high-voltage system, written by Rod Lessard at Purdue (missing from this site).
- [The tracking controller](https://github.com/Whipple10m/Track), written by Kevin Harris at FLWO.
- [Granite](https://github.com/Whipple10m/Granite), the data-acquisition system, written by Glenn Sembrowski at Purdue.
- [GDF](https://github.com/Whipple10m/GDF), the GRANITE data format, written by Joachim Rose at Leeds.
- [Quicklook](https://github.com/Whipple10m/Quicklook), the online analysis package, written by many people.
- [canalyze](https://github.com/Whipple10m/canalyze), the Dublin/Purdue analysis package written by Rod Lessard at UCD & Purdue
- [wuparam](https://github.com/Whipple10m/wuparam), the Washington University analysis package written by Karl Kosack at Wash U
- [WhippleDB](https://github.com/Whipple10m/WhippleDB), the log-sheet database written by Steve Fegan at U. Arizona and FLWO

### Papers and documentation

In addition we have a [repository to host papers and documentation](https://github.com/Whipple10m/Documentation) describing the Whipple system and the results of its scientific programme.

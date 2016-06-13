# Score-Informed Analysis of Tuning, Intonation, Pitch Modulation, and Dynamics in Jazz Solos

## Summary 

This repository is a collection of raw analysis data from a study on score-Informed analysis of tuning, intonation, pitch modulation, and dynamics in jazz solos.
The experiments are based on a subset of 264 solos taken from the publically available [Weimar Jazz Database (WJD)](http://jazzomat.hfm-weimar.de/dbformat/dbcontent.html) focussing on reed and brass instruments.

## Files



| File  | Description   |
|---|---|
| `f0.zip`  | Raw fundamental frequency contours for **all** 299 solos in the WJD (`csv` files containing frame-wise contour values, two columns: time [seconds], f0 [Hz])  |
| `intensity.zip`  | Raw fundamental frequency contours for **all** 299 solos in the WJD (`csv` files containing frame-wise contour values, two columns: time [seconds], intensity [dB])  |
| `score.zip`  |  Solo melody transcription for **all** 299 solos in the WJD (`csv` files containing note-wise score parameters, three columns: MIDI pitch, onset [seconds], durations [seconds]) |
| `wjazzdb`  | sqlite database from the WJD   |
| `pandas_data_frames.zip`  | 3 `DataFrame` objects (see `pandas` python library) exported to `CSV` format, contain raw experiment analysis data |

## Python Code

* The Python code for tuning estimation, score-informed f0-tracking and loudness tracking is currently bundled in the `pymus` python package ([Link (pypi)](https://pypi.python.org/pypi/pymus/)). 
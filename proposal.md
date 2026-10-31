# Community Software Analysis Proposal

## Software: *SimPEG*

SimPEG (Simulation and Parameter Estimation in Geophysics) is a free, open-source
Python library for figuring out what is underground from measurements taken at
the surface. It can simulate what instruments would measure for a given
underground model (the forward problem), and it can work backward from real
measurements to estimate the underground model (the inverse problem). It
supports several kinds of measurements, including gravity, magnetics,
electrical resistivity, induced polarization, electromagnetics, and Richards equation. The inverse problem is hard because there are
far more unknowns than measurements and small noise in the data can cause large
errors (ill conditioned), so SimPEG adds regularization. Its main users are geophysics researchers and students, as well as
people in mining, groundwater, and environmental work who want open tools they
can inspect and extend instead of closed commercial software.


### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL |  https://github.com/simpeg/simpeg  |
| Main/documentation website |  https://simpeg.xyz and docs at https://docs.simpeg.xyz  |
| Year project was started | 2013  |
| Number of contributors in the past year | 8 people |
| Number of contributors in the lifetime of the project |  49 |
| Number of distinct affiliations | >10 |
| Where do development discussions take place? | GitHub issues and PRs, a Discourse forum, Mattermost chat, and weekly open meetings (Wednesdays 3 PM Pacific)  |
| Typical number of emails/comments per week? | ~14 active issue/PR discussion threads per week |
| Typical number of commits per week? | 1.3 on average (70 in the past year) |
| Typical commit size | about 200 lines on average |
| How does the project accept contributions? | Pull requests on GitHub   |
| Does the project have an automated test suite? | yes (pytest) |
| Does the project use continuous integration? | yes |
| Does the project have an AI contribution policy? | No |
| Are any legal/licensing steps required to contribute? | No |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [x] I have installed the software
- [x] I have run at least one example
- [x] I have run the test suite
- [x] The test suite passes

### Notes/concerns/risks

The install didn't include a library called "choclo", which made a lot of tests fail the first time I ran it.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.

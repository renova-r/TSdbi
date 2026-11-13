# TSdbi 2017.4.1.9001

Renova release, based on CRAN TSdbi 2017.4-1 (archived on CRAN 2022-09-04).

- `man/TSdbi-package.Rd`: the `\link[TSSQLite]`, `\link[TSMySQL]` and `\link[TSPostgreSQL]` references to `TSdbiMethods` became plain text naming those packages, and a trailing comma was removed.
- `man/TSget.Rd`: `\link[tframePlus]{changeTSrepresentation}` became the plain code text `tframePlus::changeTSrepresentation`.
- `DESCRIPTION`: `Author` changed from "Paul Gilbert <email>" to "Paul Gilbert [aut, cre]" and an equivalent `Authors@R` entry (same person, roles and address) was added; `Maintainer` is unchanged (metadata only).
- `DESCRIPTION`: `Version` set to `2017.4.1.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL text) was added; the `License` field is unchanged.
- `README.md` was added and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.

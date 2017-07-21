# globus-labs

Material for the Globus Labs web site.
https://globus.github.io/globus-labs

## Adding New Publications

Procedure for adding new publication

1. Add the publication as a PDF to `./pubs`
	- No file name format required. Recommended: `<first author surname>-<journal abbreviation>-<year>.pdf`

2. Add a "yaml" file to describe the publication to `./_publications`:
	- File name should start with "YEAR-MONTH-DAY" (ex: 2017-07-21).
	- Follow the format of `2016-08-15-Tchoua.markdown`. All fields except `doi` and `pages` are required
	- Filename is the name of the file, not the full path (i.e., `A.pdf` not `pubs/A.pdf`)
	
3. Add both files into the git repo

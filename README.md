# resosuma-data

This repository holds data on activity in the research software sustainability
space ("the space"). *resosuma* is short for *re*search *so*ftware
*su*stainability *ma*p.

Activities in the space are recorded as a relation (*action*) between *actors*
and *actees*.

The data file `resosuma-{semver}.csv` holds the data in the CSV format.
The three columns correspond to the *actor* (col 1), *action* (col 2), and
*actee* (col 3) respectively.

## Version history

- `resosuma-0.1.0.csv` is a mapping of Daniel S. Katz' original visualization of
the research software sustainability space, as presented in a talk [1].

## Contributions

Contributions to the data is strongly encouraged.

Please create an issue to request being made a team member.

If you find an activity that is missing from the data, please fork the 
repository, add the new activity to the CSV file, rename the file with a new 
version number (these additions would be a new feature, so increment the second 
integer in the version number by one), and submit a pull request.

If you think that the model can be improved more fundamentally, please open an
issue to discuss your ideas.

# Processing

The CSV data can be processed with the 
[*resosuma* package for Python](https://github.com/research-software/resosuma).

# License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />*resosuma-data* is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

# References

[1] D. S. Katz, ‘Research Software Sustainability: WSSSPE & URSSI’, Apr. 2018 [Online].
[https://doi.org/10.6084/m9.figshare.6081248.v1](https://doi.org/10.6084/m9.figshare.6081248.v1).


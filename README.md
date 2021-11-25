# Remote Assessment Aid

A website to showcase different remote assessment methods to use instead of the offline variants based on your group size.

[view page here](https://werkgroep-toetsen-op-afstand.github.io/assessment-selection-tool/)

## Command to create symbolic links

```
dir=office_hours; size=large; ln -s ../../$size/$dir/_index.md; ln -s ../../$size/$dir/tips.md; ln -s ../../$size/$dir/tools.md; ln -s ../../$size/$dir/what.md; ln -s ../../$size/$dir/why.md
```

brew upgrade hugo

# Add config file

blogdown::install_hugo("0.88.1")

# set config file to hugo version 0.88.1
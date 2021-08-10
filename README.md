# trait-viz

A javascript library for visalizing trait data stored in a document store. 
This code base was developd with the [biscicol-server](https://biscicol.org/) API and toolset.

This code was adapted from  https://github.com/fullscale/elastic.js

This code-base is meant to be added as sub-module to consuming applications. 

Cloning a project using this sub-module
```
git clone --recurse-submodules https://github.com/BNHM/AmphibianDiseasePortalNewInterface.git
```
If you clone and forget the above:
```
cd trait-viz
git submodule update --init --recursive
```

updating trait-viiz with latest changes
```
cd trait-viz
git fetch
git merge
```

NOTE: I would ideally like to be able to add these javascript libraries dynamically using `<script src=""><script>` but, unfortunately, i could not
get this implementation to work.

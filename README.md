# singularity-fiji

A [singularity container](https://github.com/sylabs/singularity) build definition file to run [ImageJ/Fiji](https://imagej.net/).

Build:

`sudo singularity build --nv fiji.sif fiji.def`

Run [GUI]:

`singularity run --nv fiji.sif`

or:

`singularity run --nv fiji.sif -h`

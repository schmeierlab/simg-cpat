# Singularity config for simg-cpat container

A [Singularity Hub](https://www.singularity-hub.org/) definition for learning purposes.
An associated tutorial on genomics can be found at [http://reproducible.sschmeier.com](http://reproducible.sschmeier.com).

If [Singularity](http://singularity.lbl.gov) is installed locally, the container can be build (needs root access) locally like this:

```bash
sudo singularity build simg-cpat.simg Singularity
```

The container can alos be downloaded from [Singularity Hub](https://www.singularity-hub.org/) without root access to the local machine like this:

```bash
singularity pull --name "simg-cpat.simg" sschmeier/simg-cpat:latest 
```

Then, it can be used, e.g.:

```bash
singularity exec simg-cpat.simg cpat.py
```

# HackathonTemplate

1. Recreate your workflow in `workflow/`
2. Go to HackathonTemplate:
3. Use `spack env create -d .` to create an environment and commit `spack.yaml`
4. Run `pack -e . add spec` to add a spec (e.g. python)
5. Run `spack -e . concretize` to concretize and make sure spack can install everything - ask us for help if it can't.
6. Run `spack -e . env depfile -o Makefile` to make a makefile; you can run the make file to install things. If it breaks, ask us.
7. Run `spack env activate .` to make hte installed content avaliable for you.
8. Use https://github.com/JuliaCI/PkgTemplates.jl to setup a Julia package

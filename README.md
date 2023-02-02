# HackathonTemplate

1. Recreate your workflow in `workflow/`
2. Go to HackathonTemplate:
3. Use `spack env create -d .` to create an environment
4. Commit `spack.yaml`
5. Run `spack -e . add spec` to add a spec (e.g. python)
6. Update the spack.yaml as needed.
7. Run `spack -e . concretize` to concretize and make sure spack can install everything - ask us for help if it can't.
8. Run `spack -e . env depfile -o Makefile` to make a makefile; you can run the make file to install things. If it breaks, ask us.
9. Run `spack env activate .` to make the installed content avaliable for you.
10. Use https://github.com/JuliaCI/PkgTemplates.jl to setup a Julia package

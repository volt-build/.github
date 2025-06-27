# Volt (Volt-build)

It is a super small and speed focused build system I wrote in Go because of the hate of shell scripts which don't function properly. 
volt is designed to be modular, reproducible, and declarative from the start. 

I'm currently planning to add compilation to volt-build and making the default a JIT compiler instead of an interpreter, for speed. 

Important repos:

- [engine](https://github.com/volt-build/volt-engine)  Going to be the engine which powers volt-build's compiler (Not ready yet. Check arena package of volt-build itself for a small reference). 
- [build-system](https://github.com/volt-build/volt-build)  The source code of the build system itself.

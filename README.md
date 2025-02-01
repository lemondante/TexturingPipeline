TexturingPipeline
--------------------------------------------------------------------------------

Welcome to my project that textures 3D reconstructions from images.
This project focuses on 3D reconstructions generated using structure from
motion and multi-view stereo techniques, however, it is not limited to this
setting.

Dependencies
--------------------------------------------------------------------------------

The code and the build system have the following prerequisites:

- cmake (>= 3.1)
- git
- make
- CGAL (5.2.1)
- openMP
- oneTBB(install to /usr/local/lib)
- libpng, libjpg, libtiff
- GMP MPFR Ceres

Compilation ![Build Status](https://travis-ci.org/nmoehrle/mvs-texturing.svg)
--------------------------------------------------------------------------------

1.  `git clone https://github.com/StormPhoenix/TexturingPipeline`
2.  `cd TexturingPipeline`
3.  `mkdir build && cd build && cmake ..`
4.  `make` (or `make -j` for parallel compilation)

If you find your make process failed, it may because your conda environment is conflict with your apt pkg manager. Use command like 
`export LD_LIBRARY_PATH=/usr/local/lib:/usr/lib/x86_64-linux-gnu:$LD_LIBRARY_PATH`
to force your make-tool find your dynamic lib, especially oneTbb library.

References
--------------------------------------------------------------------------------
- [TexturingPipeline](https://github.com/StormPhoenix/TexturingPipeline)
- [mvs-texturing](https://github.com/nmoehrle/mvs-texturing.git)
- [openMVS](https://github.com/cdcseacave/openMVS)

Contact
--------------------------------------------------------------------------------
https://github.com/StormPhoenix/TexturingPipeline

For further questions you may contact us at
stormphoenix@pku.edu.cn

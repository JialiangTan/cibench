**********
Welcome to the world of CIBENCH!
**********
Enjoy the collection of 12 benchmarks and their optimization methods, they are:

Bzip2-1.0.6
Backprop, Hotspot3D, LavaMD and Srad_v2 from Rodinia Benchmark Suite
FFT from GNU scientific library
msgrate from NERSC8 Trinity Benchmarks
USQCD Chroma
Hmmer, H264ref and Povray from SPEC CPU2006 Benchmark Suite
Hoard 

Above benchmarks can be compiled individually in their folder, or you can compile them together by following commands:

Use "make org" to compile the original version

Use "make opt" to compile the optimized version


To install USQCD Chroma and GSL, please see the guidance inside corresponding folders

Due to the copyright of SPEC Benchmark Suite, we will not release the code of Hmmer, H264ref and Povray here, please refer to our paper "What Every Scientific Programmer Should Know AboutCompiler Optimizations?" for the detailed optimization methods
Listing our running commands for your reference:
hmmer: ./hmmer nph3.hmm swiss41
h264ref: ./h264ref -d foreman_ref_encoder_baseline.cfg
povray: ./povray SPEC-benchmark-ref.ini


If you have insights or questions towards CIBENCH please send email to jtan02@email.wm.edu, thanks!


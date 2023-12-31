# Lennard-Jones-potential_by_T.Watanabe
MD simulation for Ar with Lennard-Jones potential

## code
LJc.c : MD with LJ potential by T. Watanabe

## usage
gcc -O3 LJc.c

./a.out

outputs are LJ.dat, LJ.xyz

## visualization with mathematica

MD-LJ-20231026.nb : Mathematica notebook : input=LJ.xyz

<img width="674" alt="MD_LJ_20231026" src="https://github.com/chibaf/Lennard-Jones_potential_by_T.Watanabe/assets/1296728/70b5c9bb-7268-4ef7-97da-13d90b678e70">


## plot with gnu octave

usage: 

octave:88> a=readLJ("LJ.dat");

octave:82> plotLJ(a)

<img width="869" alt="MD_LJ_EN_20231027" src="https://github.com/chibaf/Lennard-Jones_potential_by_T.Watanabe/assets/1296728/e1db8a5b-ec54-4ba1-8490-6fde27afe2b5">


## ref
分子動力学法と原子間ポテンシャル｜森北出版株式会社 2023 
https://www.morikita.co.jp/books/mid/092251

AtomEye: atomistic configuration viewer http://li.mit.edu/Archive/Graphics/A/

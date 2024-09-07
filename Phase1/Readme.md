## Phase 1

This Phase of my work under Prof. Shukla was done on Abinit.

The Band structures obtained for the 2D Materials was much smaller than those reported in literature.

One of the Reasons for this was the use of a much sparser k-point grid than was required. Another reason was the naivety I showed in selecting the unit cell for the lattice under consideration. For a 2D material, a large number of unit cells with varieties in the number of atoms and the position of those atoms is available on *Materials Project*, which is what I used as my primary source for defining my input files.

I initially tried running my calculations by using Quantum Espresso codes but ran into an unknown "Buffer Overflow" error(memory overflowing from a single unit of RAM which shouldn't happen as the memory is usually divided between different units) which I was not able to resolve. As a result, I resorted to Abinit Codes, which gave better documentation but considerably poorer support community.

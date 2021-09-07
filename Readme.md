In 1926, Erwin Schrödinger published the first accounts of his now famous wave equation. He later shared the Nobel prize with Paul A. M. Dirac in 1933 for this discovery. Schrödinger’s wave function seemed extremely promising, as it contains all of the information available about a system. Unfortunately, most practical systems of interest consist of many interacting electrons, and the effort required to find solutions to Schrödinger’s equation increases exponentially with the number of electrons, limiting this approach to systems with a small number of relevant electrons. Even if this rough estimate is off by an order of magnitude, a system with 100 electrons is still very small, for example, two Ru atoms if all the electrons are counted, or perhaps ten Pt atoms if only the valence electrons are counted. Thus, the wave function method, which has been extremely successful in studying the properties of small molecules, is unsuitable for studies of large, extended solids. Interestingly, this difficulty was recognized by Dirac as early as 1929, when he wrote “The underlying physical laws necessary for the mathematical theory of a large part of physics and the whole of chemistry are thus completely known, and the difficulty is only that the application of these laws leads to equations much too complicated to be soluble.<br/>
In 1964, Hohenberg and Kohn showed that the ground state total energy of a system of interacting electrons is a unique functional of the electron density. By definition, a function returns a number when given a number. For example, in f(x)=x^2, f(x) is the function, and it equals four when x=2. A functional returns a number when given a function. Thus, in g(f(x))=∫_0^π f(x) dx, g(f(x)) is the functional, and it is equal to two when f(x)=sin(x). Hohenberg and Kohn further identified a variational principle that appeared to reduce the problem of finding the ground state energy of an electron gas in an external potential (i.e., in the presence of ion cores) to that of the minimization of a functional of the three-dimensional density function. Unfortunately, the definition of the functional involved a set of 3N-dimensional trial wave functions.<br/>
In 1965, Kohn and Sham made a significant breakthrough when they showed that the problem of many interacting electrons in an external potential can be mapped exactly to a set of noninteracting electrons in an effective external potential. This led to a set of self-consistent, single particle equations known as the Kohn-Sham (KS) equations:

In Kohn–Sham density functional theory, the total energy of a system is expressed as a functional of the charge density as:<br/>
![image](https://user-images.githubusercontent.com/50455870/132374211-16a67c0d-b734-48b6-a98f-0c750d0c3e3c.png)

where Ts is the Kohn–Sham kinetic energy, which is expressed in terms of the Kohn–Sham orbitals as:<br/>
![image](https://user-images.githubusercontent.com/50455870/132374303-f20a031f-fe77-49a7-a58f-fbe0743e8d19.png)

Vext is the external potential acting on the interacting system (at minimum, for a molecular system, the electron–nuclei interaction), Eh is the Hartree (or Coulomb) energy:<br/>
![image](https://user-images.githubusercontent.com/50455870/132374693-d8961d35-d417-4ee7-8ad8-5b9499f29ead.png)

and Exc is the exchange–correlation energy. The Kohn–Sham equations are found by varying the total energy expression with respect to a set of orbitals, subject to constraints on those orbitals, to yield the Kohn–Sham potential as:<br/>
![image](https://user-images.githubusercontent.com/50455870/132375024-fa0b340c-8e6d-4394-9d18-9caa4098e6b0.png)

where the last term<br/>
![image](https://user-images.githubusercontent.com/50455870/132375179-86707f6c-a021-4091-857a-d4e5a8694307.png)

is the exchange–correlation potential. This term, and the corresponding energy expression, are the only unknowns in the Kohn–Sham approach to density functional theory. An approximation that does not vary the orbitals is Harris functional theory.

The Kohn–Sham orbital energies εi, in general, have little physical meaning (see Koopmans' theorem). The sum of the orbital energies is related to the total energy as:<br/>
![image](https://user-images.githubusercontent.com/50455870/132375298-2453f076-acf7-49b3-a2cf-13b31274fd21.png)

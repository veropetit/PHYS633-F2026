# L11 Source Function

Week 6, Tuesday

Notebook: L11-SourceFunction-template.ipynb

## Material covered and references

The change in intensity in the case of pure emission (the solution is a quite simple, straight integral, for once!).

***Micro-objectives***
- 11.1: I can list the two different ways that intensity can be gained going through matter
- 11.2: I can list and describe the factors that contributes to an element of emission ($dI$)
- 11.3: I can derive the equation for intensity as a function of position $I(s)$, and I can calculate and sketch it if given a functional form for the characteristics of the matter (e.g. $\rho(s)$, $\kappa(s)$, etc).

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Gray Chap 5
>* Leblanc 3.6

---

* The formal solution of the radiative transfer equation. This solution is expressed in terms of the optical depth $\tau$, and make use of a quantity called the source function $S_\lambda = j_\lambda/\kappa_\lambda$, and has units of intensity.
 
* The source function is what the intensity will become after going through a number of optical depth. Of course, the intensity might not be able to become equal to the source function, if the source function itself varies significantly over a few optical depth. 

***Micro-objectives:***
- 11.4: I can state and explain all of the terms in the formal solution of radiative transfer.
- 11.5: I can derive the equation for the solution of radiative transfer for constant density, opacity, and source function, starting from the formal solution.
- 11.6: I can make a sketch of $I(s)$ for constant density, opacity, and source function.
- 11.7: I can calculate the solution for $I(s)$ if given a simple functional form for e.g. $\rho(s)$ or $S(\tau)$.

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Gray Chap 7 (note that Gray do a flat atmosphere geometry straight from the start - this is where the $\cos(\theta)$ are coming from)
>* Leblanc 3.4, 3.6 (same remark as Gray)
>* Rybicki 1.4 (in this textbook, $\alpha = \kappa * \rho$, and $j = $ our $j * \rho$)
>* Mullan 2.5


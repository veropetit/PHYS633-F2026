# L16 Analytical Estimate

Week 9, Thursday


## Material covered and references



We started making our first approximation that the opacity doesn't depend on wavelength (called the "grey" case). From this we found some simple relations between $\tilde{J}$, $\tilde{F}$, $\tilde{S}$, and $\tilde{K}$, but we are still short one equation. 

***Micro-objectives***
- 16.1: I can explain which part of our system of 9 equations we can use to solve for the temperature if the opacity does not depend on wavelengths. 
- 16.2: I can explain what the "moments" equations of transfert are from a math point of view. 
- 16.3: I can show mathematically and explain each step of we got from the transfert equation ($dI/d_\tau = I(\tau)-S(\tau)$) to the relations we will use to solve for the temperature (equations #1 and #2 in the slides.)


> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Gray chap 7
>* Leblanc  4.2 (note that Leblanc uses $H = F/4\pi$)



---

* We considered the case were the optical depth is very large (called the Eddington approximation). 

* Mathematically, we decomposed the source function at a Taylor expansion, kepping only the first term because tau is very large. The other mathematical approximation we did was that instead of integrating from $\tau$ to $\infty$, we only go from $\tau$ to $\tau+\tau$, which we found a good approximation for large $\tau$. By doing a change of variable for $x$ being the "distance from" $\tau$ ($x = |\tau' -\tau|$), it enables us to combine both integral together, greatly simplifying the math. 

***Micro-objectives***

- 16.4: With words and sketches, I can explain the "large optical depth" approximation we made to simplify the flux equation (you can gloss over the exact math of the taylor expansion and the chain of equations by part -- unless you are a math enthusiast of course!). 
- 16.5: I can solve the set of 3 approximate equations to get $T(\tau)$. 
- 16.6: I can explain how to get the $q(\tau_z)$ function. 


> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Leblanc 3.8 

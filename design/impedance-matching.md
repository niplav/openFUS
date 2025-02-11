# [Design](/design.md) → Impedance Matching: Lens & backing

We need to impedence match the [lens](/design/lens.md) (PP; 2.4 MRayl) and the piezoceramic (PZT-5H; 35 MRayl).

To do that, we can make a quarter-wave transformer layer, which needs to have an acoustic impedance of:

sqrt(2.4 * 35) = 9.17

We want this to be epoxy-based, since it'll be easy to customize, spread, and serve a dual purpose as an adhesive ("glue") for the lens. Ideally, we'd also want it to be conductive, so that it can used to power the piezoceramic. A good candidate is silver-epoxy, which is sometimes used as a matching layer.

### Applying it

Current idea:
1. Calculate speed-of-sound & then wavelength in the epoxy
2. Calculate epoxy volume: 30mm diameter * quater-wave thickness
3. Calculate epoxy weight: volume * density
4. Use a high-precision scale to place that amount of epoxy in the middle of the piezoceramic disc
5. Press the piezoceramic disc into the lens, spreading the epoxy evenly, and let it cure. (Probably inside of tube that prevents it from spilling out the sides)
6. Let it cure

### Silver epoxy suppliers

Here are my <u>guesses</u> for the impedence of different pre-mixed silver-epoxies.

**EM-Tec AG29**

Estimated impedence (by reported mixture): 8.61 MRayls
Estimated impedence (by density): 8.20 MRayls

https://www.microtonano.com/EM-Tec-conductive-silver-filled-epoxy

**Em-Tec AG32**

Estimated impedence (by reported mixture): 6.25 MRayls

https://www.microtonano.com/EM-Tec-conductive-silver-filled-epoxy

**CircuitWorks CW2400**

Estimated impedence (by density): 10.5 MRayls
Estimated impedence (by mechanical properties, as analyzed by ChatGPT): 10 MRayls

https://eu.mouser.com/ProductDetail/Chemtronics/CW2400

**Bondline BONDLINE 2080**

Estimated impedence (by density): 10.18 MRayls

**MG 8330S**

Estimated impedence (by density): 7.73 MRayls

**MG 8330D**

Estimated impedence (by density): 8.20 MRayls

**MG 8331D**

Estimated impedence (by density): 5.78 MRayls
Study [claimed](https://www.sciencedirect.com/science/article/pii/S0041624X1100254X?casa_token=rEts8rk1DtkAAAAA:Y7WaGLIGJZaJsn3oteEy97Z95EHWwbJtJlq0JVtY42URWapPmIVmnqNNXl0wkAGefCOGL3JBvUY) it was 2.6 MRayls. ???

**MG 8331S**

Estimated impedence (by density): 5.84 MRayls

### Non-silver epoxy matching layers

**AZ31B magnesium-alloy**

Reported impedence: 10.5 MRayls
https://www.sciencedirect.com/science/article/abs/pii/S0041624X22001500

**Parylene**

**Epo-Tek 301**
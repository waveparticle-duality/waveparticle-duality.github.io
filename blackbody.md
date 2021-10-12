---
title: "Black Body Radiation"
---

{% include navigation.html %}
{% include latex.html %}

# Black Body

## Introduction

You may remember a few years back when the 1000 degree knife challenge was popular on YouTube. <img src="https://lh3.googleusercontent.com/tWeun_ZBT5Xipn6DKIet9FPbJXcZtuI8zsrZJnoLsFMUBySbigwDD9u-rt_F5xIL7NxUasZhQqh9dYsvPm-bhQiL-BrejM7LtuGmysecvYUDUUS79lJcUpA1fmsE7oxuKgu4C_Xr=s0" alt="img" style="zoom: 50%;" />

If you look at the thumbnails on these videos, you will realize that the knives are shown to be glowing red (or badly photoshopped to appear as such). Why do we associate really hot things to this red glow? Do really hot things in general give a glow?

It turns out that all normal matter does emit electro-magnetic radiation when its temperature is above absolute zero. At high enough temperatures, there is enough electro-magnetic radiation in the visible spectrum (a.k.a. light) that we can observe a glow coming out from the material. 

We call an object a black body if it absorbs all electro-magnetic waves that fall on it. A black body is an idealized version of the object we want to study as most objects reflect light that falls onto it, which is how you “see” an object. 

It turns out that for black bodies, the color of the glow depends only on the temperature of the object. The following chart shows us the colors that we observe for certain temperatures. We can actually use this chart as a rough estimate for the temperature of stars, by making the assumption that they are black bodies.

<img src="https://lh3.googleusercontent.com/0AvgP8NNoTXckbB_U7s_kfP0JScFtXWt37EYsNzh_idezUPKJ1gwmLEE9_aawRshGWz0AmbiXfaKuGGWaRqSAOK33AzBypx3Se2j8CMb3YyXi99pe8CDzuxshp9976rhy677umt-=s0" alt="img" style="zoom:50%;" />

From the color of the sun, we can determine that the temperature on the sun’s surface is about $$6000$$ to $$7000$$ degrees Kelvin, which is close to the actual temperature of $$5772$$ Kelvin.

![img](https://lh5.googleusercontent.com/nwvzLkamiJ4dpAaHQgO0WAYxuBzP13Q7yQ1VXblerNg9YmOwGscIEdcMZ-8J5_jIF0oX1vohiHMMPisJwop0cQ8nR3M9zh1j7tzyeFD4GY1prFe3NvWzUWg6Zq5WpZbiZgmx09mO=s0)

So when different colors are observed from different stars in the night sky. We know the reason why some stars are red-dish, some are blue-ish and some are white-ish. This is because the stars have different surface temperatures.

<img src="https://lh3.googleusercontent.com/A4oUIa_Qj3K35LHYjRqiPotcgBYw2hQrKEhFPOYzl3UlMIZsgVGp8Rm8M1X0eGbGN7RE6gCYkG_xnfFtVqV-YMxNerJwHD2GkHRpWwyEhNnVuEZ_2_nIbTLQ3eb8zSe9CRaNpDcK=s0" alt="img" style="zoom: 33%;" />

But scientists wanted to know why certain temperatures gave off different colors of glow. They could collect data of the spectrum of wavelengths emitted by objects of different temperatures but physicists could not figure out why they followed this peculiar curve.

<img src="https://lh4.googleusercontent.com/QVhIcqTfAdG1G0nhZc8wN0XxxpIpRlVrJL8bZUK2l3yZrnM2SwqhboG8IAPjiatIUstMiRuwSNPUWDvo4W8X-0eyABQPYFD7Q22ha5K4emMKEmWdOemy8pXBzL892MerM8ZSM0om=s0" alt="img" style="zoom:25%;" />

However, physicists could find out a few formulas empirically (by fitting equations to their data without justification).

Firstly, we have the Stefan-Boltzmann Law that states that is $$P=\sigma AeT^4$$. Where $$P$$ is the power emitted, $$\sigma=5.67010^{-8} ~Wm^{-2}K$$ is a constant known as the Stefan-Boltzmann constant, $$A$$ is the surface area of the object, $$e$$ is the emissivity of the object (so black bodies have $$e=1$$ since it is a perfect absorber and emitter of radiation) and T is the temperature (in Kelvin) of the object.

Secondly, we have Wien’s displacement law that states that $$\lambda_{peak}T=2.89810^{-3} ~mK$$. Where peak is the wavelength of radiation of light that is emitted out the most. 

We know that the wavelength of visible light is between $$400~nm$$ and $$700~nm$$. We can find that the temperature for where the peak wavelength is visible light is around $$4140~K$$ to $$7245~K$$. This roughly matches up with the color observed by the blackbodies as when the peak radiation is in the visible spectrum, the entire spectrum of light will be emitted roughly equally and we observe white-ish light (because combining all colors of light gives us white light). When peak is lower or higher, we observe blue-ish and red-dish light respectively.

After many failed attempts by physicist to model the wavelength spectrum, it seemed that Max Planck had finally figured out a way to do it. But he had to make two very bold and novel assumptions that would soon split the physics community apart. 

- Energy of oscillators in a black body is quantized (takes on discrete values), given by $$E_n = nhf$$
- Oscillators emit or absorb energy when they transition from one quantum state to another. If the transition is to a lower adjacent state, then the energy emitted is $$E = hf.$$
- Planck did not believe in atoms and statistical mechanics. However, Planck was not able to reconcile his equation with other continuous laws (e.g. Maxwell’s wave equation), and had to resort to Boltzmann’s atomic law of entropy to fit the curve and make his equation work.


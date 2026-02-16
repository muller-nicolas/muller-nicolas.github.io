---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a theoretical physicist working at the interface of fluid dynamics, quantum fluids, and turbulence in geophysical and astrophysical systems. My research combines advanced numerical simulations with theoretical modeling to investigate nonlinear systems in fluid dynamics.

A central focus of my work is **superfluid turbulence**, an out-of-equilibrium regime governed by the dynamics of quantum vortices, topological defects carrying quantized circulation. I study the similarities and differences between classical and quantum turbulence, with particular emphasis on **energy cascades** and **intermittency**. By exploring how universal turbulent features emerge from fundamentally different microscopic physics, my goal is to contribute to the development of improved theoretical models of turbulence.

A related line of research concerns **magnetohydrodynamic turbulence** in geophysical and astrophysical contexts. I am particularly interested in dynamo processes in planetary interiors, especially the **geodynamo** responsible for generating Earth’s magnetic field. My research examines magnetic field reversals and the interplay between fluid motion and magnetic induction in rapidly rotating conductive systems. I also study turbulence in magnetized plasmas such as the **solar wind**, and the complex interplay between density fluctuations, magnetic fields and vorticity.


Short bio
---

I obtained my degree in Physics at [{{ site.data.authors.UBA.name }}]({{ site.data.authors.UBA.url }}) in 2019. I obtained my PhD degree in Physics in 2022 at the [{{ site.data.authors.OCA.name }}]({{ site.data.authors.OCA.url }}) in Nice under the supervision of [{{ site.data.authors.GK.name }}]({{ site.data.authors.GK.url }}), where I studied the dynamics of quantum vortices in superfluid turbulence. After holding a short postdoctoral position there, in September 2023 I moved to Paris to work at [{{ site.data.authors.LPENS.name }}]({{ site.data.authors.LPENS.url }}) as a postdoctoral researcher in collaboration with [{{ site.data.authors.FP.name }}]({{ site.data.authors.FP.url }}) and [{{ site.data.authors.CG.name }}]({{ site.data.authors.CG.url }}), studying polarity reversals in the geodynamo. 
In September 2025, I started a postdoctoral position at the [{{ site.data.authors.LPP.name }}]({{ site.data.authors.LPP.url }}) from the École Polytechnique in Palaiseau, where my research focuses on the theoretical and numerical study of wave turbulence in the solar wind, and I work in collaboration with [{{ site.data.authors.SG.name }}]({{ site.data.authors.SG.url }}). 

<span style="font-size: 0.8em;">
Last updated: February 2026
</span>

---

News
======
<!-- - Welcome to my personal website! -->
{% for post in site.categories.news limit:5 %}
  <p>
    <strong>{{ post.date | date: "%B %Y" }}</strong> — 
    <a href="{{ post.url }}">{{ post.title }}</a>
  </p>
{% endfor %}


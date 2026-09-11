---
layout: default
title: Home
---

<div style="display: flex; align-items: center; justify-content: center; flex-wrap: wrap;">
  <div style="flex: 0; order: 2;">
    <img src="{{ site.baseurl }}/img.jpg" alt="My Image" title="My Image"
         style="border-radius: 50%; width: auto; height: 200px; object-fit: cover; aspect-ratio: 1 / 1;" />
         <br><br>
        <p style="text-align: center;"><span style="font-size: 80%;">marco.badran[at]math.ethz.ch</span></p>
  </div>
  <div style="flex: 1; order: 1;">
    <h3>Welcome!</h3>
    <p>I am a postdoctoral researcher at <a href="https://bidsa.unibocconi.eu/">Bocconi University</a>, where I work with <a href="https://poisson.phc.dm.unipi.it/~pigati/">Alessandro Pigati</a> as part of the ERC project <a href="https://bidsa.unibocconi.eu/erc-starting-grant-101165368-magnetic-minimal-submanifolds-arbitrary-geometries-nodal-sets-towards">MAGNETIC</a>.</p>
    <p>Previously, I was a postdoctoral researcher at <a href="https://ethz.ch/">ETH Zürich</a>, working with <a href="https://people.math.ethz.ch/~serraj/">Joaquim Serra</a> within the ERC project <a href="https://cordis.europa.eu/project/id/948029">StableIF</a>, and a Ph.D. student at the <a href="https://www.bath.ac.uk/departments/department-of-mathematical-sciences/">University of Bath</a> under the supervision of <a href="https://researchportal.bath.ac.uk/en/persons/manuel-del-pino">Manuel del Pino</a>.</p>
    <p>My research lies at the intersection of geometric analysis and variational PDEs. I am particularly interested in minimal submanifolds—especially in higher codimension—and in geometric problems arising from gauge theory and phase transitions, including the abelian Higgs, Ginzburg–Landau, and Allen–Cahn models. I also study harmonic maps and nonlocal geometric problems, as well as the construction of solutions to nonlinear PDEs using gluing techniques.</p>
    <p>You can find a recent CV <a href="CurriculumVitae/CurriculumVitae.pdf">here</a>.</p>
  </div>
</div>

<style>
  /* Media query for screens smaller than 768px (phones, small tablets) */
  @media (max-width: 768px) {
    div[style*="display: flex;"] {
      flex-direction: column; /* Stack items vertically */
      align-items: center; /* Center items */
    }
    div[style*="flex: 0;"] {
      order: 1; /* Image comes first */
    }
    div[style*="flex: 1;"] {
      order: 2; /* Text comes second */
    }
    img {
      margin-bottom: 20px; /* Adds space between the image and text */
    }
  }

  /* For larger screens (default layout) */
  @media (min-width: 769px) {
    div[style*="display: flex;"] {
      flex-direction: row; /* Side by side */
    }
    div[style*="flex: 1;"] {
      order: 1; /* Text on the left */
    }
    div[style*="flex: 0;"] {
      order: 2; /* Image on the right */
    }
  }
</style>

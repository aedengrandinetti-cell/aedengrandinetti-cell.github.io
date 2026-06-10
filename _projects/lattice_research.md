---
layout: page
title: Vascularization Lattice Research
description: Scaffold design for artificial vascular dialysis access grafts
img: assets/img/lattice_product_truncated_octahedron.jpg
importance: 1
category: work
---

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/cube_lattice_1st.png" title="First cube lattice prototype" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

To start tackling the problem of creating a lattice for an artificial graft that would be used for vascular dialysis access, I started with a simple cube with holes on the faces. Consistent with previous UW research, the pore size of the opening of each cube should be about 40 microns. To increase the connectivity between nearby cells, and hopefully improve vascularization, I decided to use this prototype that I made in Onshape.

---

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/onshape_CAD.jpg" title="Truncated octahedron CAD in Onshape" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

From this starting point, the PhD students in the Ratner Lab told me to reduce the empty space outside of the cells. In order to tackle this, I called back on my materials science learning, where I visualized atomic lattices and packing factors. I chose the Wigner-Seitz cell of the Body Centered Cubic crystal structure as inspiration — the truncated octahedron — and used that as my unit cell to tessellate through space. This lattice, and other polyhedral lattices (such as the rhombic dodecahedral lattice corresponding to the Face Centered Cubic crystal structure) were the first I was going to try due to their presence in active research in the biomaterials field. All of my parts and assembly were created in Onshape, which I taught myself throughout this process.

---

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/prusa_slicing.png" title="Slicing in PrusaSlicer" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/lattice_print_bed.png" title="Lattice on print bed" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

From here I began the printing process to visualize my lattice in real life so that I could further iterate on its design, or go in a different direction. I worked through various issues with PrusaSlicer and print stability to get to my final products.

---

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/lattice_product_truncated_octahedron.jpg" title="Final truncated octahedron lattice" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This was the final product of a small period of rapid prototyping. I am in the process of parametrically modelling a graded gyroid surface for this same purpose, as they perform better in literature.

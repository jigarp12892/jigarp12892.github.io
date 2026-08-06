---
title: "LPBF visualizations"
excerpt: "Interactive 3D views of the LPBF scan envelope on a downskin overhang: laser path layout and delivered heat input."
collection: portfolio
---

These figures illustrate how a **scan envelope** is placed on a down-facing (downskin) overhang in laser powder bed fusion (LPBF). Both scenes use the same schematic parallelepiped part, powder bed under the overhang, and envelope footprint on the downskin face. Drag to rotate; scroll to zoom.

## Scan path on the 3D part

The textured patch shows the 2D scan recipe (borders and hatch lines) mapped onto the downskin face. A vertical laser beam marks one hatch pass. This is the geometry used when projecting process parameters onto overhang surfaces.

<iframe
  title="Scan path on 3D part"
  src="{{ site.baseurl }}/files/lpbf_viz/scan_path_on_3dpart.html"
  width="100%"
  height="640"
  style="border: 1px solid #ddd; border-radius: 4px;"
  loading="lazy"
  allowfullscreen></iframe>

<p style="margin-top: 0.5rem;"><a href="{{ site.baseurl }}/files/lpbf_viz/scan_path_on_3dpart.html" target="_blank" rel="noopener">Open full screen</a></p>

## Heat input on the scan envelope

Same part and envelope placement, with the patch colored by **delivered area energy density** (AED, J/mm²) from the scan lines. Warmer colors indicate higher local heat input along borders and hatches within the envelope.

<iframe
  title="Heat input on scan envelope"
  src="{{ site.baseurl }}/files/lpbf_viz/heatinput_scanenv_on_3dpart.html"
  width="100%"
  height="640"
  style="border: 1px solid #ddd; border-radius: 4px;"
  loading="lazy"
  allowfullscreen></iframe>

<p style="margin-top: 0.5rem;"><a href="{{ site.baseurl }}/files/lpbf_viz/heatinput_scanenv_on_3dpart.html" target="_blank" rel="noopener">Open full screen</a></p>

# cern-dimuon-resonance-analysis
# CERN Open Data: Dimuon Resonance Reconstruction

A Python-based high-energy physics analysis pipeline utilizing CERN Open Data, `uproot`, and `awkward` to parse collision events and reconstruct invariant mass resonance peaks ($J/\psi$ and $Z$ bosons).

## Project Overview
* **Data Source:** CMS Open Data Portal (DoubleMuon dataset)
* **Libraries Used:** `uproot`, `awkward`, `numpy`, `matplotlib`
* **Physics Goal:** Isolate opposite-sign muon pairs, compute 4-vector relativistic invariant masses, and identify particle resonance signatures.

## Key Results
The invariant mass spectrum cleanly isolates the $J/\psi$ peak (~3.1 GeV/$c^2$) and the $Z$ boson peak (~91 GeV/$c^2$).

![Resonance Spectrum](z_boson_reconstruction.png)

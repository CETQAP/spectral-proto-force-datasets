# Spectral Proto-Force Datasets

This repository contains datasets and analysis scripts supporting the research article "Spectral Proto-Force Theory: Experimental Evidence for a Novel Fundamental Interaction" by Zuhair Ahmed, published on Research Square. The datasets include collider simulation data and precision spectroscopy data to validate the spectral proto-force.

## Repository Structure
- **collider_simulation/**: Data and scripts for Monte Carlo simulations of proton-proton collisions at 13.6 TeV.
  - `data/invariant_mass_spectra.csv`: Processed invariant mass spectra.
  - `data/raw_collision_events_metadata.txt`: Metadata for raw data.
  - `scripts/`: Python scripts for analysis and visualization.
  - `figures/`: Figure 1 (invariant mass spectrum).
- **spectroscopy/**: Data and scripts for cesium hyperfine transition measurements.
  - `data/cesium_hyperfine_transitions.dat`: Raw frequency measurements.
  - `data/frequency_shifts.csv`: Processed frequency shifts.
  - `data/spectroscopy_metadata.txt`: Metadata for experiments.
  - `scripts/`: Python scripts for analysis and visualization.
  - `figures/`: Figure 2 (frequency shifts).
- **external_data_links.txt**: Links to large raw data files hosted on Open Science Framework.
- **LICENSE**: CC-BY 4.0 license.

## Data Access
- Small files (<100 MB) are hosted directly on GitHub.
- Large raw collider data (~500 GB) is hosted on Open Science Framework: [https://osf.io/spectralprotoforce2025/collider/raw_collision_events_13.6TeV.h5].

## Usage
1. Clone the repository: `git clone https://github.com/[username]/spectral-proto-force-datasets.git`
2. Install dependencies: `pip install numpy scipy pandas matplotlib`
3. Run analysis scripts to reproduce results or generate figures.
4. Access raw collider data via the OSF link for full event analysis.

## Citation
Ahmed, Z. (2025). Spectral Proto-Force Theory: Experimental Evidence for a Novel Fundamental Interaction, PREPRINT (Version 1) available at Research Square [https://doi.org/10.21203/rs.3.rs-XXXXX/v1].

## Contact
Zuhair Ahmed, drzuhairahmed@thecetqap.com

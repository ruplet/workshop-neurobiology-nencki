# Workshop on spatial memory and neuroscience

* This is an archive of original files from 2018.*

Archive of files from workshop on spatial memory and neuroimaging of mice brain.
Workshop was organized in June 2018 by Polish Children's Fund thanks to Nencki Institute of Experimental Biology, Polish Academy of Sciences.

## Contents

- `data/microscopy/participant_01..03/` - microscopy images collected during the workshop by participants
- `data/eye_tracking/raw/` - eye-tracking position tables
- `notebooks/01_eye_tracking_exploration.ipynb` - eye-tracking plots
- `notebooks/02_eye_tracking_animation.ipynb` - gaze animation
- `notebooks/03_microscopy_fragment_demo.ipynb` - microscopy image demo

## Run notebooks

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebooks/03_microscopy_fragment_demo.ipynb
```

The recommended tool to view neuro microsocpy images is [ImageJ Fiji](https://imagej.net/Fiji/Downloads).


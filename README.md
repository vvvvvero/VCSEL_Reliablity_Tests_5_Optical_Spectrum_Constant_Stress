# VCSEL Reliability Tests - Series 5: Optical Spectrum Constant Stress

## Series Context

This repository is part of the Veronica GaoZhan VCSEL Reliability Test Series.

- Series ID: VGZ-VRLS
- Track: Single-device reliability progression
- Position: 5
- Protocol name: stress_cycle_spectroscopy
- Author: Veronica GaoZhan

## Repository Purpose

Series 5 provides constant-stress optical spectroscopy cycling workflows,
aligned with the same linear/log timing definition used in the LIV stress-cycle tests.

## Included Scripts

- b1500_stress_cycle_spectroscopy.py: B1500 + spectrometer constant-stress cycle test GUI.

## Quick Start

```bash
python b1500_stress_cycle_spectroscopy.py
```

## Standard Session Fields (Series V1)

Runs should include these common identifiers in metadata and outputs:

- project_id
- wafer_id
- device_id
- session_id
- parent_session_id
- protocol_name
- protocol_version
- schema_version

## Output Files

Typical outputs per run:

- iv_cycle_XXX.csv
- stress_cycle_XXX.csv
- meas_spectra_cycle_XXX.csv
- stress_spectra_cycle_XXX.csv
- stress_current_cycle_XXX.csv
- cycle_summary.csv

## Related Series Repositories

- Series 1 (LIV Step Stress): https://github.com/vvvvvero/Laser_Optical_Reliablity_Tests_1_Step_Stress
- Series 2 (LIV Constant Stress): https://github.com/vvvvvero/VCSEL_Reliablity_Tests_2_LIV_Constant_Stress
- Series 3 (LIV Stress Recovery): https://github.com/vvvvvero/VCSEL_Reliablity_Tests_3_LIV_Stress_Recovery
- Series 5 (Optical Spectrum Constant Stress): https://github.com/vvvvvero/VCSEL_Reliablity_Tests_5_Optical_Spectrum_Constant_Stress

## Citation

If you use this repository in research, please cite:

```text
GaoZhan, V. (2026). VCSEL Reliability Tests - Series 5: Optical Spectrum Constant Stress.
Retrieved from https://github.com/vvvvvero/VCSEL_Reliablity_Tests_5_Optical_Spectrum_Constant_Stress
```

## License

MIT License

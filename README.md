# Battery Electric Vehicle (BEV) Powertrain Modelling using MATLAB/Simulink

An academic electric-vehicle powertrain modelling project investigating the behaviour of an electric drive system, its components, and energy consumption using MATLAB and Simulink.

## Project overview

The project studies a battery-electric-vehicle (BEV) drivetrain, including electric motor and power-electronics components. The original coursework considers vehicle performance and energy consumption over a drive cycle.

**Project scope:** simulation and analysis, not production vehicle control or a validated physical powertrain.

## Simulink models

Both original model files are available in this repository:

| Model | Description | Open |
| --- | --- | --- |
| `BEV_Components_OctNov24.slx` | Powertrain component-level Simulink model | [View model](models/BEV_Components_OctNov24.slx) |
| `BEV_Milg_OctNov24.slx` | BEV system / drive-cycle Simulink model | [View model](models/BEV_Milg_OctNov24.slx) |

The source `.slx` binaries are included as uploaded. GitHub cannot render these models as interactive Simulink diagrams; download and open them in MATLAB/Simulink.

## Repository structure

```text
BEV-Powertrain-MATLAB-Simulink/
├── models/
│   ├── BEV_Components_OctNov24.slx
│   └── BEV_Milg_OctNov24.slx
├── docs/
│   └── PRESENTATION_GUIDE.md
├── .gitignore
└── README.md
```

## How to open and explore

1. Clone the repository, or download it via **Code → Download ZIP**.
2. Launch MATLAB with Simulink. Depending on the contents of each model, further toolboxes (such as Simscape or electrical-domain libraries) may be required.
3. Open `models/BEV_Components_OctNov24.slx` and inspect the component-level subsystems and model parameters.
4. Open `models/BEV_Milg_OctNov24.slx` and inspect the BEV system and drive-cycle configuration.
5. Check for external dependencies, missing referenced data or version incompatibilities before simulation.
6. If the dependencies are satisfied, run the models and inspect the generated signals, plots and logs.

**Verification status:** The two files' presence has been verified on GitHub. They have not been executed or independently validated in this environment; model compatibility, dependencies and numerical results are therefore not guaranteed.

## Technical areas demonstrated

- Battery electric vehicle (BEV) powertrain modelling
- MATLAB and Simulink
- Electric motor and power-electronics system representation
- Vehicle performance and drive-cycle analysis
- Energy consumption modelling and simulation workflows

## Presentation

See the [presentation guide](docs/PRESENTATION_GUIDE.md) for a six-part walkthrough covering motivation, system architecture, model components, drive-cycle analysis, results and limitations.

## Notes and limitations

The original coursework report has not been published because it contains personal/student-identifying information. Generated Simulink caches and temporary files are also excluded.

Where numerical findings are mentioned elsewhere, they should be treated as originally reported academic results unless independently reproduced from these models.

---

**Project repository:** [CORETRAITSTECHNOLOGIES/BEV-Powertrain-MATLAB-Simulink](https://github.com/CORETRAITSTECHNOLOGIES/BEV-Powertrain-MATLAB-Simulink)

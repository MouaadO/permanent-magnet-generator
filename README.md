# Permanent Magnet Synchronous Generator Simulation

A MATLAB/Simulink study of a permanent-magnet synchronous generator under open-circuit and loaded conditions. Models use the dq representation to explore electrical output and electromechanical behavior.

## Tools used

MATLAB, Simulink and Simscape Electrical Specialized Power Systems blocks.

## How to run

1. Open this folder in MATLAB.
2. Run `generator_parameters`.
3. Open `generator_open_circuit.slx`, `generator_loaded.slx` or `generator_loaded_variant.slx`.
4. Check the inputs and load settings, run the model and inspect the scopes.

## Files

| File | Purpose |
| --- | --- |
| `generator_parameters.m` | Electrical and mechanical machine parameters |
| `generator_open_circuit.slx` | Open-circuit study |
| `generator_loaded.slx` | Loaded generator model |
| `generator_loaded_variant.slx` | Alternative supplied loaded model |

## Limitations

The original folder was labelled PMSM, but the accompanying report describes generator operation. Both supplied loaded variants are retained; their differences should be reviewed in Simulink before comparing results.

## Project context

Prepared from academic project files. Collaborative work remains team work; personal names are omitted from this public copy. Original technical comments and interfaces may be in French. No new license has been assigned.

## Technical report

[Read the original French technical report](docs/permanent-magnet-generator-report.pdf). Personal names and document metadata were removed from this copy. Technical content is preserved and may describe earlier study settings.

## Verification status

Source structure and reference names were inspected. MATLAB startup did not complete in this environment, so MATLAB and Simulink execution could not be verified.

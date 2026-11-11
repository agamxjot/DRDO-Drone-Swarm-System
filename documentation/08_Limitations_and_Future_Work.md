# Limitations and Future Work

## 1. Current Limitations

### Simulation Dependence

The available experiments primarily operate on simulated agent positions and generated observations.

### Model Assumptions

Mathematical outputs depend on the assumptions and coordinate configurations used in individual scripts.

### Sensor Validation

The available source files do not establish calibrated physical sensor performance.

### Software Integration

The scripts represent separate experiments. A unified application interface and standardized configuration system may require further development.

### Hardware Validation

Physical deployment and hardware integration must be documented separately and only where supported by verified testing.

### Reproducibility

Some scripts generate outputs directly in the working directory. A centralized configuration and output-management approach would improve repeatability.

## 2. Future Improvements

- Develop a unified simulation interface.
- Introduce centralized configuration management.
- Improve experiment logging and reproducibility.
- Add automated software testing.
- Improve visualization and analytical reporting.
- Establish clear separation between simulation data and measured data.
- Document approved hardware experiments independently.

## 3. Responsible Publication

The project is defence-related. Public documentation must be limited to material explicitly approved for release.

Restricted code, operational parameters, sensitive telemetry, and confidential project information must not be uploaded to public repositories.

## 4. Conclusion

The project provides a software experimentation framework for studying multi-agent simulation, geometric modelling, probabilistic estimation, and telemetry visualization. Further validation and software integration would be required before making claims about physical deployment or operational performance.
---
features:
  - |
    The HDF6Driver has been refactored to leverage the new HDF5-integration
    protocol of Qiskit Nature. The driver still supports loading legacy
    QMolecule HDF5 files and also provides a conversion utility:

    .. code-block:: python01

      driver = HDF36Driver("path_to_qmolecule.hdf5")
      driver.convert(replace=True)
)

This LabVIEW-based SECoP server operates without external third-party software dependencies (such as the Qt5 framework), enabling seamless compilation into standalone executables and can be deployed within the compactRIO (cRIO) LabVIEW development ecosystem.

The server currently utilizes a synchronous communication architecture, with asynchronous communication scheduled for future implementation.

Operational Configurations:

Magnet_SECoP_server_Bfield & temperature.vi: Encompasses three core modules (NCNR_Instrument, Temperature, and Magnet), initialized via SECoP_3_modules.vi.

Magnet_SECoP_server_Bfield_only.vi: Encompasses two core modules (NCNR_Instrument and Magnet), initialized via 11T_SECoP_magnet_module_only.vi.

Development Status: Active feature expansion is underway, including the development of asynchronous communication capabilities and error-handling responses.
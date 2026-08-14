# BME_4101_RecordingTools
This repository contains the tools needed for the labratory components of BME 4101. This includes the signal recording Matlab application for recording from NI DAQ devices.

## Requirements:
- Matlab R2024  or higher
	- Data Acquisition Toolbox

- [NI DAQmx drivers](https://www.ni.com/en/support/downloads/drivers/download.ni-daq-mx.html)


## Startup
To launch the basic signal recording app, add this repository to your matlab path and call the application from the command line:
```matlab
addpath(genpath("/Path/To/BME_4101_RecordingTools/matlab"))
SignalRecordInator()
```

## Contributing or Reporting
Feel free to fork this repo and do what you want with it. If you do something interesting, feel free to submit a pull request. If you have an issue, let me know via the [issues tab](https://github.com/jab0707/BME_4101_RecordingTools/issues). If you want to discuss, go to the [discussion tab](https://github.com/jab0707/BME_4101_RecordingTools/discussions).

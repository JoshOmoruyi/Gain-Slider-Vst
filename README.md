Gain Slider Plugin

This project is a simple yet functional Gain Slider audio plugin built using C++ and the JUCE framework. It includes both frontend UI components and backend DSP logic, making it a great introductory project for learning audio plugin development.

The plugin outputs a clean, adjustable gain control and can be loaded into any DAW that supports VST3 plugins.

⸻

Technologies Used
	•	C++
	•	JUCE Framework

⸻

Platform Notes

Windows

If you are using Windows, it’s recommended to build the project using Visual Studio 2022.
Opening the provided .sln file will let you compile and run the plugin directly.

Plugin Compatibility

This plugin works in any DAW that supports VST3 format, including:
	•	FL Studio
	•	Ableton Live
	•	Reaper
	•	Studio One
	•	Cubase
	•	Bitwig
	•	And more

⸻

Tutorial Reference

This plugin was built following the tutorial below:
https://www.youtube.com/watch?v=KgxHyTL9HVQ

⸻

Future Improvements
	•	Custom UI layout and styling
	•	Input/output metering
	•	Parameter smoothing
	•	Preset management
	•	Additional controls (pan, mix, DSP filters)
Windows Build Instructions

Requirements
	•	Visual Studio 2022 (Desktop Development with C++)
	•	Windows 10/11 SDK (included with VS)
	•	VST3 SDK — JUCE includes it automatically

Steps
	1.	Clone or download the repository.
	2.	Open Projucer (inside your JUCE folder).
	3.	Open the .jucer project file (or generate one if using CMake).
	4.	Select your platform exporter:
	•	Visual Studio 2022 Exporter
	5.	Click Save and Open in IDE.
	6.	Build the project inside Visual Studio:
	•	Debug or Release
	7.	The compiled plugin will appear in:
/Builds/VisualStudio2022/x64/Debug/
/Builds/VisualStudio2022/x64/Release/

Plugin Install Location (Windows)

Copy the .vst3 file into
C:\Program Files\Common Files\VST3\
macOS Build Instructions

Requirements
	•	Xcode (latest)
	•	Command Line Tools
	•	VST3 + AU support (JUCE includes VST3; AU is built-in on macOS)

Steps
	1.	Open Projucer and load your .jucer file.
	2.	Add a macOS exporter:
	•	Xcode (MacOSX)
	3.	Click Save and Open in IDE.
	4.	Build in Xcode:
	•	Select MySynth - Standalone or MySynth - VST3
	5.	After compiling, the plugin appears in:
Builds/MacOSX/build/Debug/
Builds/MacOSX/build/Release/

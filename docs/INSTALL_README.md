# DelphiLint

DelphiLint is an IDE package for RAD Studio that provides on-the-fly code analysis and linting, powered by
[SonarDelphi](https://github.com/integrated-application-development/sonar-delphi).

For more information, visit the [DelphiLint repository](https://github.com/integrated-application-development/delphilint).

## System Requirements

* Microsoft Edge 79.0.309+
* Delphi 11 Alexandria or newer
* [Java 11+](https://adoptium.net/temurin/releases/?package=jre&version=17) — must be available via `JAVA_HOME`

## Installation

1. Run `install.bat` (or `install.ps1` directly in PowerShell).
2. Restart the Delphi IDE if it was already open.
3. Done!

> **Note:** If `JAVA_HOME` is not set or points to a Java version below 11, you will be prompted to configure the
> Java executable path on first use via `DelphiLint > Settings... > Set up external resources`.

## First Use

1. Open a Delphi project in the IDE.
2. Open the source file you want to analyze.
3. Click `DelphiLint > Analyze This File`.

The DelphiLint window will show the analysis status and any detected issues inline in the editor.

## Configuration

* `DelphiLint > Settings...` — configure Java path, SonarQube connection, and other options.
* See [Configuration](https://github.com/integrated-application-development/delphilint/blob/main/docs/CONFIGURATION.md)
  for full details on project-level settings.

## License

Licensed under the [GNU Lesser General Public License, Version 3.0](http://www.gnu.org/licenses/lgpl.txt).

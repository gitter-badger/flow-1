# Version 2.2.0 (UNRELEASED)
- Implement watching for new ports.

# Version 2.1.2
- Better error message for native library extraction.
- Fix packaging of distributed jars for ARM systems (#13).
- Build:
    - Upgrade debian source package helpers and dependencies.
    - Remove explicit publishing information (now published to bintray).

# Version 2.1.1
- Upgrade to Akka 2.3.10
- Upgrade to Scala 2.11.6 and 2.10.5
- Upgrade to SBT 0.13.8
- Refactor build:
    - remove unique version constraints, reverts to use of standard "SNAPSHOT" versions
    - uniformize project names and directories
	- simplify project settings
- Update documentation

# Version 2.1.0
- Remove dependencies on scala-io
- Upgrade to Akka 2.3.9
- Upgrade to Scla 2.11.5

# Version 2.0.9
- Fix termios initialization issues (#12)

# Version 2.0.8
- Upgrade to Akka dependency 2.3.8 (version 2.3.7 is skipped)
- Upgrade to Scala 2.11.4
- Upgrade sbt version to 0.13.7

# Version 2.0.6
- Fix version incoherency problem.

# Version 2.0.5
- Upgrade to Akka dependency 2.3.6

# Version 2.0.4
- Upgrade to Akka dependency 2.3.5

# Version 2.0.3
- Upgrade to Akka dependency 2.3.4

# Version 2.0.2
- Upgrade to Akka dependency 2.3.3 (merge #10)
- Add support for Scala 2.11 (merge #10)
- Remove Scala version from native fat jar.

# Version 2.0.1
- Use system actor for manager.

# Version 2.0
- Use of direct buffers to increase performance when receiving and transmititng data.
- Remove need to register to receive incoming data from an operator. A port is now opened by a client who will be the sole actor to receive messages from the operator.
- Migrate native build to Autotools (C compiler is not called through sbt anymore).
- Add debian packaging.
- Add mac packaging.
- Upgrade Akka dependency to 2.3.2.

# Version 1.2
- Upgrade Akka dependency to 2.3.0. (merge #3)

# Version 1.1
- Restructure build for easier cross-compilation. (fixes #1)

# Version 1.0
- Initial release.

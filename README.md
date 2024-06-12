# mMS4X Flasher Changelog
**v1.3.0**

- Switched to installers for all supported platforms
- Added support for TCUs (SMG2, GS8.60.0, GS8.60.4, GS20)
- Moved licence lookup to "C:/ProgramData/MS4x Flasher" or "/var/lib/ms4x-flasher"
- VIN included in save filename when reading
- Refactor application to not use FTDI drivers
- Optimize memory usage and performance
- Migrated to .NET 7

**v1.2.7**
- Added: Support for multi byte ecu addresses
- Updated: Migrated to .NET5
- Updated: FTDI drivers 2.12.36.4 included
- Optimization: Minor bugfixes

**v1.1.3**
- Added: Action log
- Added: Checksum corrector for local files
- Added: DTC reader (with raw HEX output)
- Optimization: Various bugfixes

**v1.03**
- Optimization: New encryption settings for less AV false positives

**v1.02**
- Updated: Icon changed to new logo
- Optimization: MS42 fullflash bug fixed
- Optimization: Minor spelling fixes

**v1.01**
- Updated: Hardware ID will show at startup if an FTDI cable is detected

**v1.0**
- Initial release

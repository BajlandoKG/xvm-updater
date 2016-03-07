## XVM Updater v2.8 ##
Adaptations for the new XVM release:
  * Removed the "show win chances" option.
  * Removed the "enable stats" option.

---

## XVM Updater v2.7.2 ##
  * Switched from Windows ShellUnzip to Abbrevia TAbUnzipper.
  * Fixed the bug causing the wrong detection of the WoT installation directory.
  * Optimized application icon and reduced EXE size.

---

## XVM Updater v2.7.1 ##
  * Added CONFIG\_RTC in order to provide backward compatibility with the older configuration boot files.
  * Minor graphical changes.
  * Minor code optimizations.

---

## XVM Updater v2.7 ##
  * Removed now unused code.
  * Improved automatic folder detection.
  * Added last nightly revision dynamical display.
  * Fixed the silent access violation causing a wrong game version detection.
  * Fixed rare cases of HTML code display in drop-down menus.
  * Added Dutch translation.
  * Fixed Russian translation.
  * Fixed Polish translation.

---

## XVM Updater v2.6 ##
  * Fixed a bug causing the 'Keep the old configuration' option to malfunction.
  * Added Finnish translation.
  * Fixed German translation.

---

## XVM Updater v2.5 ##
Adaptations for the new XVM release:
  * Added an option to enable player stats display.
  * Deleted the option to enable the minimap.
  * Deleted now unused functions in the code.

---

## XVM Updater v2.4 ##
  * Code optimizations.
  * Added .NET Framework 3.5 and Visual C++ 2005 SP1 detection and if needed, installation.
  * Fixed World of Tanks installation folder selection (clicking on 'No' would not close the window).
  * Fixed custom configs download for old WoT versions.
  * Fixed the %TEMP% variable which was causing the Dokan installer to display an "OS unsupported" error on Windows 8 configurations.
  * Fixed a minor bug in translations displaying.
  * Improved the visual aspect of the progress bar when a library installer is running or files are being extracted.
  * XVM Updater is now able to self-elevate on a limited Windows user account (running with limited rights leaded to numerous issues).
  * You can now close the program at any time.

---

## XVM Updater v2.3 ##
  * Added Hungarian language.
  * Minor code optimizations.
  * Fixed a critical bug causing the end of the installation ​sc​ri​pt (shortcut creation and temporary files cleaning) to not being processed.
  * Fixed minimap enabling procedure (added support of code comments).
  * Fixed UTF-8 handling in all configuration editing procedures (UTF-8 characters were replaced by '?').

---

## XVM Updater v2.2 ##
  * Multilanguage support (currently English, French, German, Polish, Russian, Ukrainian).
  * Minor interface modifications to fit all languages.
  * Fixed rare bug causing Desktop shortcut to not being created.
  * Fixed character encoding bug in Minimap enabling procedure.

---

## XVM Updater v2.1.1 ##
  * Fixed unknown bug that caused game version verification to raise an access violation error silently.
  * Fixed a critical bug causing a "list index out of bounds" exception in rare cases.

---

## XVM Updater v2.1 ##
  * Fixed minor interface bugs.
  * Definitely fixed compatibility mode for Windows 8.
  * Added 'Enable Minimap feature' option.

---

## XVM Updater v2.0.1 ##
  * Minor code optimizations.
  * Fixed Win7 compatibility mode for Windows 8.
  * Fixed incorrect error message.
  * Fixed some utility functions.
  * Reworked code to avoid antivirus program false-positives.

---

## XVM Updater v2.0 ##
  * Code optimizations.
  * Removed reports sending.
  * Fixed minor display bug in the french version.
  * Fixed progress bar display bug when the installation is finished.
  * Modified manual selection of the Wot installation directory (now "worldoftanks.exe" has to exist).
  * Modified user interface: removed 'About' section and some controls were reworked.
  * Added XVM test versions support (dynamically loaded at runtime).
  * Added XVM configuration file choice (dynamically loaded at runtime).
  * Added Windows 8 support for Dokan installation (activated compatibility mode for Windows 7).
  * Changed program icon.
  * Sourcecode is now available under GPL license.

---

## XVM Updater v1.1.1 ##
  * Minor interface modifications.
  * Minor code optimizations & fixes.
  * Fixed download errors handling.
  * Fixed 'Keep old XVM configuration file' option:
    1. Backup of your current config file will be made if the file exists.
    1. The current config file will be preserved even if an old config file exists.
  * Greatly reduced application size (now ~450 kB).

---

## XVM Updater v1.1 ##
  * Greatly improved WoT installation folder auto-detect.
  * Improved a few translations/message boxes.
  * Improved graphical user interface.
  * Improved ​sc​ri​pt interpreting procedure.
  * Fixed an error appearing randomly at the end of processing.
  * Fixed an error appearing if a drive wasn't ready.
  * Added win chances display option.
  * Sc​ri​pt source can now be forced from command line (ex: "XVM\_Updater.exe TEST.​sc​ri​pt").
  * Install/update procedure can now be stopped when the current action is finished.
  * If an error appear while downloading, error reason is now displayed.

---

## XVM Updater v1.0.1 ##
  * Fixed memory violation errors.
  * Fixed bad verification of system files.
  * Improved WoT installation folder auto-detect.

---

## XVM Updater v1.0 ##
  * All final features implemented.
  * Code reworking.
  * Added report sending support.
  * Added manual localization support (french/english).
  * Added working links in About section.
  * Added redirected files download support.
  * Install/update procedure now look at WoT client version (in order to provide the right update ​sc​ri​pt when the game is getting a newer version).
  * Install/update procedure now check if the WoT client is not working before processing (otherwise files copy gets stuck).
  * Fixed bug in IF\_NEXISTS function (block was never executed).
  * Fixed bug in %WINDOWS% variable replacing.
  * Fixed bug in %WOTOLDVERSION% variable replacing.
  * Fixed minor bugs in ​sc​ri​pt parsing procedure.
  * Fixed minor bug when a download fails.
  * Changed application icon.

---

## XVM Updater v1.0  RC1 ##
  * First release of this utility, only for test purposes.
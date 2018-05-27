# UiPath Learning

Workflows cover below topics:
1. Introduction to UiPath
2. Variables, Data Types & Control Flows
3. Data Manipulation
4. Recording
5. Advanced UI Interaction
6. Selectors
7. Excel & Data Tables
8. PDF

## Pre-Requisites

### Install Excel Activities Package

For reading CSV files, we require the excel activities package to be installed.

1. Under `Activities` pane, choose `Manage Packages` option.
2. Enable `Filter Activities` check box and select `Available` expand option.
3. Search for `Excel` and install the package `UiPath.Excel.Activities`.

### Install PDF Activities Package

For reading CSV files, we require the excel activities package to be installed.

1. Under `Activities` pane, choose `Manage Packages` option.
2. Enable `Filter Activities` check box and select `Available` expand option.
3. Search for `PDF` and install the package `UiPath.PDF.Activities`.

If PDF text selection is not working then follow below steps:

1. Enable `Accessibility Setup Assistant`.

   Open Adobe Reader DC – without a document/s being open – and navigate to Edit > Accessibility > Setup Assistant.

   Check “Set all accessibility options” and click Next.

   Choose default options for the rest and click Done.

2. De-select and then re-select the Adobe Acrobat Reader preferences:

    `Edit > Preferences > Accessibility`

    Use document structure for tab order when no explicit tab order is specified

    Enable assistive technology support

Step 2 needs to be performed again if Adobe reader is closed.

### Install Browser Extensions

For web recording activities, we require the browser extensions to be installed.

Go to `Setup -> Setup Extensions` option and choose the approriate browser extensions to install.

If you face any issues, please refer below links for debugging:

[IE Troubleshooting](https://www.uipath.com/kb-articles/internet-explorer-automation-troubleshooting)

[Chrome Troubleshooting](https://studio.uipath.com/docs/chrome-extension)
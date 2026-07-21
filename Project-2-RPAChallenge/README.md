# Project-2-RPAChallenge 🤖

## Overview
This is an RPA (Robotic Process Automation) project that automates the RPA Challenge website. It includes workflows for:
- Launching the application
- Filling forms with data
- Capturing screenshots
- Sending email reports

## Workflows

### Main.xaml
Main orchestration workflow that coordinates all subprocesses.

### LaunchApp.xaml
Launches the RPA Challenge website in Edge browser.

### RPAChallenge_FillForm.xaml
Fills the form with data from a DataTable (extracted from Excel).

### RPAChallenge_ReadSuccessMessage.xaml
Reads the success message after form submission.

### Output_SaveScreenshot.xaml
Captures and saves a screenshot of the completed form.

## Technologies
- **UiPath Studio**: Version 26.0.196.0
- **Activities**: Excel, UIAutomation, System activities
- **Target Framework**: Windows

## How to Run
1. Open project in UiPath Studio
2. Ensure dependencies are installed
3. Click Run or execute via Orchestrator

## Created
July 2026

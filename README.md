![logo](https://github.com/Hazem-Mrad/deepflow-automation/assets/114618938/6da2781e-2fb0-4e40-9b3e-340eeebe6eaa)
# Deepflow Evaluation Sheet Automation - Automatic Upload to Drive

This Python script automates the process of uploading Deepflow evaluation sheets to Google Drive and verifies the generated files' existence. It ensures consistency between the member lists.

## Steps to Run:

### 1. Prerequisites:
- Python installed on your system.
- Required Python packages: openpyxl, Google Drive API.

### 2. Modify Files:
- Replace the placeholders in the script with the appropriate paths, such as the member names list and output folder.
- Ensure the credentials.json file is updated with the required information.

### 3. Execution:
- Run the Python script.
- It will verify that the member names list and the generated files in the 'Result' folder match.
- It will use Google Drive API to upload the generated evaluation sheets to a specific Drive folder.

### 4. Uploading to Google Drive:
- The script will authenticate the user using the provided credentials.json file.
- It will search for the specified Drive folder and upload the generated evaluation sheets to this folder.
- Make sure the target Drive folder exists and its ID or name is correctly set in the script.

## File Description:
- `automatic_upload_drive.py`: Python script for automatic uploading of Deepflow evaluation sheets to Google Drive.
- `credentials.json`: File containing API credentials for Google Drive access.

## Usage:
1. Modify the script parameters and paths.
2. Update the credentials.json file with the necessary information.
3. Run the Python script to upload the evaluation sheets to Google Drive and verify the consistency of lists.

3. Run the Python script to upload the evaluation sheets to Google Drive and verify the consistency of lists.


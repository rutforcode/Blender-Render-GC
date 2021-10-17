# Blender-Render-GC
### This repository contains python scripts for Rendering Blender Projects on Google Collaborator.

# Setup
### Make sure to read the instructions carefully!

> ### If you have other resources used in the Blender project and chose to make all paths relative, pack all of them into a zip archive. Alternatively, you can pack all external file.

- blender_version : Version of blender used to render the scene.

- blend_file_path : Path to the blend file after unpacking the zip archive. If blend file is used, this is automatically ignored.

- upload_type : Select the type of upload method. gdrive_relative pulls everything from the folder specified.

- drive_path : Path to your blend/zip file relative to the root of your Google Drive if google_drive is selected. Must state the file and its extension (.zip/.blend) unless gdrive_relative is selected.

- url_blend : Specify the URL to the blend/zip file if url is selected.

- animation : Specify whether animation or still image is rendered. If still image is used, put the frame number in start_frame.

- start_frame, end_frame : Specify the start and end frame for animation. You may put same value such as zero for both input to set the default frame in the blend file.

- download_type : Select the type of download method. gdrive_direct enables the frames to be outputted directly to Google Drive (zipping will be disabled).

- output_name : Name of the output frames, do NOT include .blend! (## for frame number)

- zip_files : Archive multiple animation frames automatically into a zip file.

- drive_output_path : Path to your frames/zip file in Google Drive.

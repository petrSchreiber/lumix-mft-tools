# Copy from Card

Tool to copy files from connected SD card to hard drive.

It follows fixed structure allowing to easily jump in time later:
`<root directory>/YYYY/MM/DD`

## How to use?
After launching the tool, you will be prompted to enter source and target directory.

Source should be the SD card connected to your PC.

Destination should be directory under which the `YYYY/MM/DD` subdirectories will be created for you and files copied.

Files are pre-sorted in the following way:
- `YYYY/MM/DD`
  - for raw photos
- `YYYY/MM/DD/jpg`
  - jpegs, if any found
- `YYYY/MM/DD/video`  
  - any video files found

## Known limitations
Copy is performed sequentially.

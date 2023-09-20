# GUI for Music Manager

This Python application helps you manage and filter your music collection. It offers two main features:

1. **Music Management:**
   - Organize your music files by renaming them based on their tags. 
   - Handles various music file formats, including MP3, FLAC, WAV, and many more.
   - It offers quite a variety of file name formats to choose from:
     - Title
     - Title - Artist
     - Artist - Title
     - Title - Album
     - Title - Album Artist
   - It lets you choose a file name separator for separating tags:
     - Hyphen  --  "Name - Name"
     - Small brackets  --  "Name (Name)"
   - It lets you choose the destination folder names in different formats:
     - Artist
     - Album
     - Album Artist
   - You can keep track of files with the help of a feedback box (displays counter and details).


2. **File Filtering:**
   - Quickly filter and separate specific file types (e.g., MP3, M4A, txt, bmp, docs, mp4, etc.) from your collection.
   - Choose your own file type to filter. You can add custom file types to the filter.
   - Helps you keep your collection organized by separating different music file types.
   - Here too, you will get a feedback box to make it easier to track your files.


2. **Filter Duplicates:**
> *Think Twice before choosing single tag option for this filter operation.*
- this doesnot check for the extensions so i recommend to first filter file using the program File Filtering.
## Features

- Easy-to-use GUI for managing music collection.
- Organize music in a variety of formats as you like.
- Clear feedback messages for each operation.
- Option to filter specific file formats (not just limited to music files).

## Getting Started

1. **Download:**
   - Download the latest release from the [Releases](https://github.com/shivathapaa/GUI-for-Music-Manager/releases) section.
   - Extract the downloaded archive to your preferred location on your computer.

2. **Running the Application:**
   - Locate and run the application (e.g., `musicManager.exe`) inside the extracted folder.

3. **Using the Music Collection Manager:**
   - Select the source and destination folders for your music collection.
   - Choose variety of format options for ([refer above](#gui-for-music-Manager)):
     - File Naming
     - Tag Separating
     - Dest. Folder Naming
   - Click "Click to rename and manage!" to organize your music collection.

4. **Using the File Filtering Feature:**
   - Select the source and destination folders for your music collection.
   - Add any file type extensions that you want to separate.
   - You can also delete the file type extensions that you have added without the need for closing the application.
   - Click "Filter Music" to separate specific music file formats (e.g., MP3, M4A, txt, bmp, docs, etc.) from your collection.

5. **Clearing Messages:**
   - Use the "Clear Messages" button within the application to clear feedback messages.

## Dependencies

- No external Python dependencies are required when using the built executable.

## Screenshots

- Don't judge by the looks!😉
<p align="center">
 <img src="./images/musicManager.png" alt="Music Manager" width="45%">
 <img src="./images/filterFiles.png" alt="Filter Files" width="45%">
</p>

## License

This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to [TinyTag](https://pypi.org/project/tinytag/) for their library.

## Usage Instructions / Known Bugs

- There are no known bugs to date.
- This application has been tested with extreme cases to extend for reliability check.
- It has been tested with hundreds of music files. (Gives 100% accuracy. No doubt!)
- In spite of the best performance, I still recommend you to back up your files before using the application.
- You should be responsible for your own files.
- If you notice any problem, please raise an [issue](https://github.com/shivathapaa/GUI-for-Music-Manager/issues).

## Future Updates

- I am open to suggestions.

<br>

I hope it will be helpful! Enjoy your music!

---

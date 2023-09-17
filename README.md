# File_organizer
File Organizer moves files to the appropriate destination directories based on their file extensions. It makes it easy for you to clean up and organize files in your folders.

## How to Use

1. Make sure you have Python installed on your computer.

2. Copy the `app.py` script into the directory you want to organize.

3. Edit the `file_extensions` dictionary inside the `app.py` script to match your preferences. You can add or remove file extensions and specify the corresponding destination directories.

4. Open a terminal or command prompt.

5. Navigate to the directory where you've saved the `app.py` script.

6. Run the script by executing the following command:

  ```bash
   python app.py
  ```

## Example Extension and Destination Settings
```python
file_extensions = {
    'pdf': 'PDF',
    'png': 'Images',
    'jpg': 'Images',
    'jpeg': 'Images',
    'zip': 'Archives',
    'docx': 'Documents',
    'mp4': 'Videos',
    # Add more file extensions here
}
```






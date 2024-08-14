https://ffmpeg.org/download.html
download the package with exe files for Windows
make ffmpeg accessible via command line:
  add ffmpeg to the PATH environment variable
    # Step 1: Open the Environment Variables
Right-click on "This PC" or "Computer" on your desktop or in File Explorer, and select "Properties".
Click on "Advanced System Settings" on the left.
In the "System Properties" window, click on the "Environment variables..." button.
    # Step 2: Change the PATH variable
In the "Environment Variables" window, you'll see two sections: "User variables for [your username]" and "System variables".
Find the variable called Path under "System Variables" and select it. Then click on "Edit...".
In the window that appears, click "New" and add the path to the folder where you extracted ffmpeg. For example, this could be C:ffmpegbin (where the ffmpeg.exe is located).
Click "OK" to close the window.
    # Step 3: Check the Addition
Open a new Command Prompt (cmd.exe) and type ffmpeg followed by Enter.
If everything is set up correctly, you should now see the FFmpeg banners and options instead of an error message.

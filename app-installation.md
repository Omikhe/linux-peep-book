# .deb file
To install a .deb file on a Debian-based Linux system (like Ubuntu), you can use one of these methods:

### 1. Using dpkg (terminal):
   Navigate to the directory containing the .deb file and run:
   ```
   sudo dpkg -i filename.deb
   ```
   If there are missing dependencies, follow up with:
   ```
   sudo apt-get install -f
   ```
### 2. Using apt (terminal): Navigate to the directory containing the .deb file and run:
   ```
   sudo apt install ./filename.deb
   ```
   This method can handle dependencies automatically.

### 3. Using the graphical interface:
   Double-click the .deb file, which should open your system's package installer. Click "Install" and enter your password when prompted.
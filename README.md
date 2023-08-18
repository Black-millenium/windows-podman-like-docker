# Using Podman as Docker on Windows

1. Install Python and `pip`/`pip3` (will be automatically installed with Python) on Windows:

   ```winget install Python.Python.3.11 -v 3.11.4```

2. Install `podman-compose` using `pip` or `pip3`:

   ```pip3 install podman-compose```

3. Copy the files `docker.bat` and `docker-compose.bat` to the bin directory of the Podman installation. The default directory is `C:\Program Files\RedHat\Podman`)

4. Restart your terminal

5. ???????

6. PROFIT!  

7. To validate the installation, use the following commands:

   ```docker --version``` 
   
   and
   
   ```docker-compose --version```

   The expected command output should be like this: 

   ```powershell
   PS C:\Users\black> docker --version
   podman version 4.6.1
   
   PS C:\Users\black> docker-compose --version
   podman-compose version: 1.0.6
   ['podman', '--version', '']
   using podman version: 4.6.1
   podman-compose version 1.0.6
   podman --version
   podman version 4.6.1
   exit code: 0 
   ```
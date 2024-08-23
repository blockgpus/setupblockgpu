# Running `blockgpu.deb` on Linux

1. **Install the .deb package:**

   ```bash
   sudo dpkg -i blockgpu_1.0.0_amd64.deb
   ```

# Run the blockgpu application:
  Running blockgpu.appimage on Linux
  
  ```
   ./blockgpu.appimage
  ```
## Running BlockGPU on Windows using WSL

**To run BlockGPU on Windows, you'll need to have WSL (Windows Subsystem for Linux) set up. Follow the instructions in the video below to get started:**

   [![Watch the video](https://img.youtube.com/vi/YByZ_sOOWsQ/0.jpg)](https://www.youtube.com/watch?v=YByZ_sOOWsQ)

**Once you've completed the setup, you can install the `.deb` file by running the following commands:**

```bash
   # Step 1: Update your package list
   sudo apt update

   # Step 2: Install the `.deb` file using dpkg
   sudo dpkg -i /path/to/your/blockgpu.deb

   # Step 3: Fix any dependency issues
   sudo apt-get install -f
```



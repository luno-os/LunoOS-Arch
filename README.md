# LunoOS-Arch

**This OS is still under construction!**

*How to install*

- If you happen to already have an Arch Linux install:
    - Download the requiered packages via pacman with:
        `sudo pacman -Sy archiso`

    - Clone the repository
    
    - Build the ISO with the following command:
        `mkarchiso -v -o /path/to/output_dir /path/to/repository/releng/`

    - *Bonus*
        - You're able to edit the ISO to your liking. Who knows? Maybe you think we put too much bloat into it. **No guaranty provided though**

- If you don't have an Arch Linux install:
    - Just download the ISO from the "releases" section

# Latest changes (17.07.2025):

- Added Nvidia and Intel drivers for live env:
    - `nvidia` and `nvidia-open`
    - `mesa` and `lib32-mesa`
    - `vulkan-intel` and `lib32-vulkan-intel`

# Still to do:

- Troubleshoot autologin for sddm/plasma
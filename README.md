# NOTICE
Edited to work with google drive links and my personal use . my A035M

# Universal-Super-Patcher-For-Samsung-Devices
- This tool can create ODIN flashable super.tar
- After running this workflow you'll get a .7z file in the releases section.
- Extract that 7z file you'll get your super.tar with custom gsi.
- Then Flash that super.tar using ODIN in AP Section.
- You must have to select a custom phh gsi with Android Version greater than or equal to Your Stock Rom 


# How to Use this

<br>⚬ Fork into your github and use via github actions</br>

<br>1. Add Direct link of GSI</br>

- You can directly use the link of gsi (.xz) from Github.
- Like This:
```sh
https://github.com/ponces/treble_build_aosp/releases/download/v2023.12.01/aosp-arm64-ab-gapps-14.0-20231201.img.xz
```
- If you use link form sourceforge.net;
<br>⚬ Copy downlad link of your gsi you'll get a link like this:</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-20.x/lineage-20.1-20231116-UNOFFICIAL-arm64_bgN.img.xz/download
 ```
<br>⚬ Then delete the /download at the end of the link, it will be like the link below;</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-20.x/lineage-20.1-20231116-UNOFFICIAL-arm64_bgN.img.xz
 ```
<br>⚬ The link must be end with .xz</br>
<br>2. Add Rom Name</br>
<br>⚬ Then add the rom name it should be [rom_name]-[version]-[device version]-[arm64]-[gapps_or_vanila].7z<br>
like this LineageOS-20.1-a035fxxnn-arm64-gapps.7z

<br>3. Add Baseband Version </br>

<br>4. Add Super Img Link
  - Use super.zip(Recommended to reduce downloading time)
  - Use direct Link or remove /download from the ending of link if you use sourceforge link
  - Link must be end like super.img , super.zip or super.xz
 # Wait for 20-25 minutes to finish the build 
 # Credits:
 These people have helped this project in some way or another, so they should be the ones who receive all the credit:
- [Phhusson](https://github.com/phhusson)
- [bruh™](https://github.com/Exynos-nibba)
- [gauravv.x1](https://github.com/gauravv-x1)

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Contributors][contributors-shield]][contributors-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
    <a href="https://github.com/Pluto-Data-Science">
        <img src=".images/logo_placeholder.jpg" alt="drawing" width="200" style="display: block; margin: 0 auto;">
    </a>

  <h3 align="center">A Beginners Guide to Python and VScode</h3>

  <p align="center">
    This is a beginners guide to setting up and using python and visual studio code.
    <br />
    <a href="https://github.com/PDS-callum/A-Beginners-Guide-to-Using-Python-and-VScode"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="mailto: cpmwaller@gmail.com">Request Detail</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- GETTING STARTED -->
# Python

To run this code you will need to have a publicly accessibly install of Python. This is done differently depending on your platform but is generally fairly straightforward.

If you don't know what you're doing then avoid pre-releases. These are less stable and likely lack appropriate support from the packages you want to use.

## Windows

**1. Install python**

Installable versions of Python can be found on the official Python downloads page: https://www.python.org/downloads/windows/

Here, you'll find versions for 32-bit, 64-bit, and ARM64 systems. The image below illustrates the available options.

<img src=".images\windows_python_install_versions.png">

**Choosing the Right Version:**

**CPU Architecture:** In brackets, you'll see the CPU architecture that each installer is designed for. Most likely, you'll need the **64-bit** version. However, you can easily check your Windows PC's architecture by following these steps:
  1. Press the Windows key.
  2. Type "system information" and launch the System Information app.
  3. Look for the "System Type" value under "System Summary." This will indicate whether you have a 32-bit or 64-bit system.

**Here's a quick breakdown of the architectures:**

  - **32-bit:**
      - Limited to around 4GB of RAM.
      - More common in older systems.
      - Primarily used in specific scenarios like Raspberry Pi.
  - **64-bit:**
      - Standard architecture for modern desktops and laptops.
      - Can address much larger amounts of RAM.
  - **ARM (ARM64):**
      - Advanced RISC Machine (Reduced Instruction Set Computing).
      - Primarily used in embedded systems and specific use cases.

**2. Run the install file**
1. Once the download is complete, double-click the downloaded installer file (e.g., python-3.x.x-amd64.exe).
2. In the installation wizard, it's highly recommended to check the box next to "Add Python 3.x to PATH." This allows you to run Python commands directly from your command prompt or terminal.
3. Click "Install Now" and follow any additional on-screen instructions.

## Mac

**1. Install python**

Installable versions of Python can be found on the official Python downloads page: https://www.python.org/downloads/macos/

Unlike Windows, MacOS installs do not have much variety in CPU architectures, as shown below.

<img src=".images\mac_python_install_versions.png"> 

Most likely, you'll need the **64-bit** version. However, you can easily check your Mac PC's architecture by following these steps:
  1. Open the command prompt.
  2. Run...
    
    uname -m

**2. Run the install file**
1. Once the download is complete, double-click the downloaded installer file (e.g., python-x.x.x-macosx.pkg).
3. Click "Install Now" and follow any additional on-screen instructions.

## Linux (Ubuntu)

**1. Install python**

In Linux the entire install can be done from the command line. This is probably true for Mac, but the above instructions are easier for a beginner.
  1. Open the command prompt.
  2. Check if you already have python installed. If you don't then the below commands will return "not found" error...
    
    python --version
    python3 --version
    
  3. Run these four commands to ensure your system is up to date...
    
    sudo apt-get update
    sudo apt-get upgrade
    sudo apt update
    sudo apt upgrade
    
  4. Install the desired python version...
    
    sudo apt-get install pythonx.x

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Visual Studio Code



<p align="right">(<a href="#readme-top">back to top</a>)</p>



# Install Git



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
# Contact

My GitHub: [https://github.com/PDS-callum](https://github.com/PDS-callum)

Project Link: [https://github.com/PDS-callum/A-Beginners-Guide-to-Using-Python-and-VScode](https://github.com/PDS-callum/A-Beginners-Guide-to-Using-Python-and-VScode)

<a href="mailto: cpmwaller@gmail.com">Email me</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/badge/Contributors-1-blue
[contributors-url]: https://github.com/PDS-callum
[license-shield]: https://img.shields.io/badge/License-MIT-green
[license-url]: https://github.com/PDS-callum/centriole_size_analysis/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/callum-waller-a68354a1/

[pandas]: https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white
[pandas-url]: https://pandas.pydata.org
[plotly]: https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white
[plotly-url]: https://plotly.com
[numpy]: https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white
[numpy-url]: https://numpy.org
[cv]: https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white
[cv-url]: https://opencv.org

[product-screenshot]: .images/screenshot.png
[logo]: .images/logo_placeholder.jpg
[logo-url]: https://github.com/Pluto-Data-Science
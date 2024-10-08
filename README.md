# Grant's dotfiles
<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/grjsmith/dotfiles">
    <img src="images/grants_dotfiles.png" alt="screenshot of desktop with terminal config" width="800">
  </a>

<h1 align="center">Grant's dotfiles</h1>

  <p align="center">
    My Linux customisations.
    <br />
    <a href="https://github.com/grjsmith/dotfiles"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/grjsmith/dotfiles/issues">Report Bug</a>
    ·
    <a href="https://github.com/grjsmith/dotfiles/issues">Request Feature</a>
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

<!-- ABOUT THE PROJECT -->
## About The Project
These are my dotfiles. I'm saving them here so I don't have to customise them again when I rebuild my laptop and so I can synchronise them across multiple machines.
<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [LSCOLORS](https://github.com/sharkdp/lscolors)
* [LSD](https://github.com/lsd-rs/lsd)
* [Nerd Fonts, Cousine](https://github.com/ryanoasis/nerd-fonts)
* [Neofetch](https://github.com/dylanaraps/neofetch)
* [Fish shell](https://fishshell.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
### Prerequisites

* [On Windows install WSL](https://learn.microsoft.com/en-us/windows/wsl/install)
* Download Debian from the Microsoft Store
* Install LSCOLORS, LSD, Nerd Fonts, Cousine, Neofetch and Fish
* Set the terminal font to Cousine Nerd Font Mono. Note Windows terminal can take some convincing to use the font. You'll know it's working when 'lsd -al' shows folder icons
* On Linux install the Cousine Nerd Fonts with the following command:
```
cd ~/.local/share/fonts && curl -fLO https://github.com/ryanoasis/nerd-fonts/raw/HEAD/patched-fonts/Cousine/Regular/CousineNerdFont-Regular.ttf
```
* To set fish as the default shell run the command:
```
chsh -s /usr/bin/fish
```

#### Windows Terminal Configuration

**Colors**
Screen text:

* #2DE2E6

Screen Background:

* #262335

### Installation
* Download the files and folders from the Github repo to ~/HOME
* Profit?

### Notes
#### Linux
To make this work  on Linux (Mint) on my old Macbook Pro
```
.config/lsd/themes/custom.yaml
```
Has been copied to
```
.config/lsd/colors.yaml
```
This isn't necessary on WSL Debian or native Debian 12. Although the instructions imply it's necessary everywhere.

#### Tested on:
* Windows 10 and 11 with Debian 11 and 12 running on WSL
* Linux Mint 22 (Wilma)
* Linux Debian 12 (Bookworm)


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
<!--## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>-->

<!-- ROADMAP -->
## Roadmap

* Still working on Btop config

See the [open issues](https://github.com/grjsmith/dotfiles/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Grant Smith - [@grjsmith](https://twitter.com/grjsmith) - grant@nextgendevops.com

Project Link: [https://github.com/grjsmith/dotfiles](https://github.com/grjsmith/dotfiles)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
* Thanks to the Rainmeter team for the awesome tutorials
* Thanks to Nick/Stangowner for the Afterburner/Rainmeter instructions and example code.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

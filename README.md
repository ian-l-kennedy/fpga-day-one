# fpga-day-one
<p>My collection of all things useful for HDL/RTL development for FPGAs that are not substantial enough to have their own repository. These examples are just enough to nudge you in the right direction. Often getting started feels the slowest. These solutions should help speed that up and get you to a nice pace sooner rather than later.</p>

<p>This repository also includes information of how I establish my development environment. I share what tools I use and how I install them.</p>

<p>Enjoy!</p>

**Please consider supporting my open source work :]**<br /> 
<p><a href="https://www.buymeacoffee.com/iankennedy"><img src="https://github.com/ian-l-kennedy/ian-l-kennedy/blob/main/coffee.gif" width="85" height="85" /></a> <a href="https://www.buymeacoffee.com/iankennedy"><img src="https://github.com/ian-l-kennedy/ian-l-kennedy/blob/main/buy_cof_button.png" width="200" height="50"/></a><a href="https://www.buymeacoffee.com/iankennedy"></p>
  
**Thank you, Open Source Community!**
<p>None of my work would have happened if I were not inspired by the countless Open Source developers and mentors out there in the community. The willingness to teach, share, and aid that is shared by so many great engineers is truly amazing! Throughtout this repo there are instructions that I may have discovered using someone else's guidance. URLs to the pages that I used are at the bottom of this README, [here](#urls-of-useful-tools-and-reference)</p>

# Table of Contents
Table of Contents courtesy of https://luciopaiva.com/markdown-toc/
- [My Dev Machine](#my-dev-machine)
  - [Windows 10 OS](#windows-10-os)
  - [Mac OS](#mac-os)
  - [Ubuntu OS](#ubuntu-os)
  - [TCL](#tcl)
- [Simple Examples](#simple-examples)
  - [SPAR (Synthesis, Place And Route)](#spar-synthesis-place-and-route)
    - [SPAR Vivado](#spar-vivado)
    - [SPAR Diamond](#spar-diamond)
    - [SPAR Libero](#spar-libero)
    - [SPAR Quartus](#spar-quartus)
  - [Simulation](#simulation)
    - [Simple](#simple)
    - [From SW, Not HDL](#from-sw-not-hdl)
- [Reference/Resource Articles](#referenceresource-articles)
- [Interesting Articles](#interesting-articles)
- [URLs of Useful Tools and Reference](#urls-of-useful-tools-and-reference)
- [Other Project Ideas](#other-project-ideas)


<p>For more useful projects and articles, please visit https://ian-l-kennedy.github.io</p>

<p>I am always interested in learning, so please feel free to add examples that you find useful and pull request. I am always interested in networking and meeting new like minded people too! So, please use my contact form https://ian-l-kennedy.github.io/contact if you would like to share contact information and chat.</p>

# My Dev Machine
In all my experience with EDA tools so far in the field of FPGA/RTL/HDL development, I have noticed that the Linux versions of almost all the tools are more stable and released more frequent than Windows versions. I will have a strong bias to Linux throught my documents.

## Windows 10 OS
[Back to the Table of Contents](#table-of-contents)
### Terminal
### WSL: Windows Subsystem for Linux
### RDP for WSL
### VPN Kit for WSL

## Mac OS
[Back to the Table of Contents](#table-of-contents)
### iTerm
### Microsoft Remote Desktop
### TeamViewer
### References
* [The fastest and easiest way to install Ruby on a Mac in 2023](https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/?utm_source=stackoverflow&utm_campaign=51126403)
* [DS_Store Files (What & How to Open,Hide,Delete & Disable)](https://iboysoft.com/wiki/ds-store.html)

## Ubuntu OS
[Back to the Table of Contents](#table-of-contents)
### General Settings
### NeoVim, Tmux
### RDP
### TeamViewer Host
### Quartus Lite
### QuestaSim
### Diamond
### Xilinx Vivado
### Libero SoC
### YoSys
### Language Servers
### Verilator
### GHDL

## TCL 
  Downloaded https://core.tcl-lang.org/tcllib/technote/cd3a11c3065120d491009e64a19f7676176045cd
unzip and run installer:
sudo tclsh /tools/lib/tcl/tcllib/tcllib-1.20/installer.tcl
attempt:
package require <something> 

# Examples
[Back to the Table of Contents](#table-of-contents)
## SPAR (Synthesis, Place And Route)
### SPAR Vivado
### SPAR Diamond
### SPAR Libero
### SPAR Quartus
## Simulation
### Simple
[Back to the Table of Contents](#table-of-contents)
#### Simulation XSIM
#### Simulation QuestaSim
#### Simulation Verilator
#### Simulation GHDL
#### Simulation IcarusVerilog
### From SW, Not HDL
#### QuestaSim DPI-C for SystemVerilog and Verilog
#### QuestaSim FLI for VHDL
#### 
  
# Reference/Resource Articles
[Back to the Table of Contents](#table-of-contents)
* http://outputlogic.com/?page_id=321
http://outputlogic.com/my-stuff/circuit-cellar-january-2010-crc.pdf
  https://learn.microsoft.com/en-us/windows/wsl/install
https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=en-us&gl=us&rtc=1
https://github.com/sakai135/wsl-vpnkit
 
https://askubuntu.com/questions/52230/how-do-i-extract-a-rpm-file
 
- https://github.com/Tech-Bandit/wsl2-gui-rdp / https://www.youtube.com/watch?v=smR3i4i4kaQ
- https://hub.tcno.co/windows/wsl/desktop-gui/ / https://www.youtube.com/watch?v=QC7a9nowsz8
https://www.youtube.com/watch?v=EAxRNoRRvFQ
  https://ecotrust-canada.github.io/markdown-toc/
https://stackoverflow.com/questions/60441221/double-click-to-select-text-in-windows-terminal-selects-only-one-word
# Interesting Articles
[Back to the Table of Contents](#table-of-contents)
* https://stackoverflow.blog/2020/06/05/why-the-developers-who-use-rust-love-it-so-much/
https://discord.com/blog/why-discord-is-switching-from-go-to-rust#:%7E:text=Discord%20is%20a%20product%20focused,and%20messages%20you%20have%20read
https://www.geeksforgeeks.org/rust-vs-c-will-rust-replace-c-in-future/
https://doc.rust-lang.org/book/title-page.html
https://www.rust-lang.org/
  https://faultlore.com/blah/c-isnt-a-language/
https://www.youtube.com/watch?v=QpAhX-gsHMs
https://www.youtube.com/watch?v=w3_e9vZj7D8&t=690s
  http://www.sugawara-systems.com/veritak_sv_tutorial/dpi.htm#:~:text=Main%20advantage%20of%20using%20DPI,a%20value%20of%20C%20type.
https://sutherland-hdl.com/papers/2004-SNUG-paper_Verilog_PLI_versus_SystemVerilog_DPI.pdf
  https://media.ccc.de/v/35c3-9670-safe_and_secure_drivers_in_high-level_languages#t=491
https://www.infoq.com/news/2021/04/rust-linux-kernel-development/
https://www.youtube.com/watch?v=wREGR7QQHco
https://www.youtube.com/watch?v=RyY01fRyGhM
https://www.youtube.com/watch?v=zF34dRivLOw
https://youtu.be/-lYeJeQ11OI

https://youtu.be/rAl-9HwD858
# URLs of Useful Tools and Reference
[Back to the Table of Contents](#table-of-contents)
 * https://github.com/ohmybash/oh-my-bash
https://neovim.io/
  
https://github.com/junegunn/vim-plug
  
https://www.latticesemi.com/latticediamond
https://www.latticesemi.com/en/Support/Licensing/DiamondAndiCEcube2SoftwareLicensing/DiamondFree
  
https://www.xilinx.com/support/download.html
https://www.xilinx.com/member/forms/download/xef.html?filename=Xilinx_Unified_2022.2_1014_8888.tar.gz
https://www.xilinx.com/member/forms/download/xef.html?filename=Xilinx_ISE_DS_Lin_14.7_1015_1.tar
https://www.xilinx.com/getlicenseuse
https://www.intel.com/content/www/us/en/software-kit/660904/intel-quartus-prime-lite-edition-design-software-version-20-1-1-for-linux.html
https://downloads.intel.com/akdlm/software/acdsinst/20.1std.1/720/ib_installers/ModelSimSetup-20.1.1.720-linux.run
https://downloads.intel.com/akdlm/software/acdsinst/20.1std.1/720/ib_installers/QuartusLiteSetup-20.1.1.720-linux.run
https://www.microchip.com/en-us/products/fpgas-and-plds/fpga-and-soc-design-tools/fpga/libero-software-later-versions
https://www.microchipdirect.com/fpga-software-products?_ga=2.233404892.397944140.1675713531-42661341.1670955989
https://www.microchip.com/en-us/products/fpgas-and-plds/fpga-and-soc-design-tools/fpga/licensing
# Other Project Ideas
  What if I could pick two signals in a port map (one input and one output) and get theocratical path hierarchy and latency?
<p align="center">
  <img alt="🎚️ContrastEQ" src="https://user-images.githubusercontent.com/62103572/182627173-11e9cf29-0115-4058-abd1-2cf337185515.png">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/y/EliaFantini/ContrastEQ-VHDL-module-of-a-contrast-equalizer-for-FPGAs">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/EliaFantini/ContrastEQ-VHDL-module-of-a-contrast-equalizer-for-FPGAs">
  <img alt="Lines of code" src="https://img.shields.io/tokei/lines/github/EliaFantini/ContrastEQ-VHDL-module-of-a-contrast-equalizer-for-FPGAs">
  <img alt="GitHub code size" src="https://img.shields.io/github/languages/code-size/EliaFantini/ContrastEQ-VHDL-module-of-a-contrast-equalizer-for-FPGAs">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/EliaFantini/ContrastEQ-VHDL-module-of-a-contrast-equalizer-for-FPGAs">
  <img alt="GitHub file count" src="https://img.shields.io/github/directory-file-count/EliaFantini/ContrastEQ-VHDL-module-of-a-contrast-equalizer-for-FPGAs">
  <img alt="GitHub follow" src="https://img.shields.io/github/followers/EliaFantini?label=Follow">
  <img alt="GitHub fork" src="https://img.shields.io/github/forks/EliaFantini/ContrastEQ-VHDL-module-of-a-contrast-equalizer-for-FPGAs?label=Fork">
  <img alt="GitHub watchers" src="https://img.shields.io/github/watchers/EliaFantini/ContrastEQ-VHDL-module-of-a-contrast-equalizer-for-FPGAs?abel=Watch">
  <img alt="GitHub star" src="https://img.shields.io/github/stars/EliaFantini/ContrastEQ-VHDL-module-of-a-contrast-equalizer-for-FPGAs?style=social">
</p>
ConstrastEQ is a VHDL module of a contrast equalizer to be implemented on FPGAs. A contrast equalizer is a module that maximizes contrast in images by taking the minimum and maximum pixel values and making them 0 and 255 respectively, scaling all other pixels' values accordingly.
<p align="center">
  <img width="auto" alt="image" src="https://user-images.githubusercontent.com/62103572/182632308-21e6a24f-616b-4f13-acc2-c607bf12392b.png">
</p>
This project was made as an assignment of Logic Networks' course (2020/2021), and consisted in the design and implementation of a module in VHDL language starting from a specification in natural language of its behaviour. The following is a finite state machine schema, describing the behavior of the module:
<p align="center">
  <img width="auto" alt="Immagine 2022-08-03 154824" src="https://user-images.githubusercontent.com/62103572/182632234-15ef17cb-b223-45a5-be58-ed7f55472f8f.png">
</p>

A detailed explanation of how the module works and how it was tested is in the *doc* folder, in *Report_reti_logiche.pdf*. Unfortunately the report had to be written in italian, we suggest the use of automatic translation tools.
## Authors
- [Elia Fantini](https://www.github.com/EliaFantini)
- [Mauro Famà](https://github.com/maurofama99)
## How to use
The file *retilogiche.vhd* in the **code** folder has to be opened by the software **Xilinx Vivado** or similar softwares and has to be synthetized on a FPGA. For our tests, we used a simulated *xc7a200tfbg484-1* FPGA.

## Contents
* In the **code** folder there is the code written in VHDL language of the implemented module and two testbench.
* The documentation (in italian) of the project is in the **doc** folder.
* In the **spec** folder there are the specifications and project rules provided by the teachers (in italian).

## 🛠 Skills
VHDL language. Usage of Xilinx Vivado software, testing and benchmarking of the final module.
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://eliafantini.github.io/Portfolio/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/-elia-fantini/)

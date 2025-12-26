# Taiwan NSTC CM03 Template

This folder contains the LaTeX template for Taiwan NSTC (National Science and Technology Council) CM03 proposals.

## Directory Structure and File Descriptions

- **main.tex**: The main entry point for the LaTeX document. It sets up the document class, imports the style package, and includes the content sections.
- **CM03.doc**: The official MS Word template file from NSTC, included for reference.
- **cm03.sty**: Custom style package defining the layout, fonts (including Traditional Chinese support via XeCJK), and other formatting settings specific to the CM03 form.
- **kaiu.ttf**: The "BiauKai" (標楷體) TrueType font file, used for rendering Traditional Chinese characters.
- **figures/**: Directory for storing image files used in the document.
- **sections/**: Directory containing the content for different parts of the proposal.
  - `background.tex`: Content for the Background section (Content of Research Plan).
  - `methods.tex`: Content for the Research Methods section.
  - `expected_outcomes.tex`: Content for the Expected Outcomes section.

## Important Usage Note

> [!IMPORTANT]
> **Compiler Setting**: You must change the compiler (access from the bottom-left cogwheel logo) to **XeLaTeX** or **LuaLaTeX** for Chinese characters to render correctly.
>
> 1. Click on the **Menu** (cogwheel icon) in the top-left corner of the Overleaf editor.

## Attribution

This template was revised from [國科會研究計畫內容CM03](https://www.overleaf.com/latex/templates/guo-ke-hui-yan-jiu-ji-hua-nei-rong-cm03/hhcjzcqjmzjq) by Chen Wen-sheng.

## License

Creative Commons CC BY 4.0


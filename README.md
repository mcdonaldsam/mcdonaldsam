<h1 align="center">Sam McDonald</h1>

<p align="center">
  Financial modeller who builds the tools Excel is missing.<br>
  Rust · C# · Excel · Python
</p>

<p align="center">
  <a href="https://gxlshouse.com"><img alt="gxlshouse" src="https://img.shields.io/badge/gxlshouse-see_every_cell_behind_a_number-11120f?style=flat-square"></a>
  <a href="https://github.com/PSU3D0/formualizer/pulls?q=is%3Apr+author%3Amcdonaldsam+is%3Amerged"><img alt="formualizer: 20 merged PRs" src="https://img.shields.io/badge/formualizer-20_merged_PRs-7c3aed?style=flat-square&logo=rust&logoColor=white"></a>
  <a href="https://hub.xerj.org"><img alt="XERJ Corpus Hub contributor" src="https://hub.xerj.org/contributors/mcdonaldsam/badge.svg"></a>
</p>

---

### Building

**[gxlshouse](https://gxlshouse.com)**: see every cell behind a number.
An Excel add-in that traces any formula to the cells that feed it and the
cells it feeds, in the workbook you have open, unsaved edits included. A
deterministic Rust engine reads a whole client model in milliseconds, so
tracing keeps up with you. One file to install. [Join us →](https://gxlshouse.com)

### Open source

I contribute to **[formualizer](https://github.com/PSU3D0/formualizer)**, an
embeddable spreadsheet engine in Rust, mostly by making it give the answer
Excel gives. Most fixes are measured in Excel first, and every one is pinned by a regression test.

| Area | Merged work |
|---|---|
| **Formula parser** | range operators beside calls, names and deleted ends · quoted 3D sheet spans · empty table specifiers · `#REF!#REF!` name decay · left-associative `^` · brackets kept when printing · unions with constants refused · error positions as byte offsets |
| **Array formulas** | `SUMIF(S)` / `COUNTIF(S)` / `AVERAGEIF(S)` over array criteria · `ISNUMBER` and the other `IS*` functions element by element · `XLOOKUP` / `XMATCH` and `MATCH` / `VLOOKUP` / `HLOOKUP` / `LOOKUP` over an array of lookup values |
| **Speed** | `SUM(1/COUNTIF(A:A,A:A))` in one pass instead of one walk per row |
| **Excel parity** | real odd roots of negative numbers in `^` and `POWER` · error criteria matching error cells |
| **Workbooks** | linked workbooks' defined names served from the link cache · rich-value metadata on formula caches · saved dynamic-array spill cells on load |

[All merged pull requests →](https://github.com/PSU3D0/formualizer/pulls?q=is%3Apr+author%3Amcdonaldsam+is%3Amerged)

### Toolbox

![Rust](https://img.shields.io/badge/Rust-11120f?style=flat-square&logo=rust&logoColor=white)
![C#](https://img.shields.io/badge/C%23-11120f?style=flat-square&logo=dotnet&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square)
![Python](https://img.shields.io/badge/Python-11120f?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-11120f?style=flat-square&logo=typescript&logoColor=white)

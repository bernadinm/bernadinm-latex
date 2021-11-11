# Easy Intro to LaTeX

## Getting Started

1. Download LaTeX software to your machine.

#### **With Nix**
This how to install it with Nix package manager.

```bash
nix-env -iA nixpkgs.texlive.combined.scheme-basic
```

2. Download the sample LaTeX document

```bash
curl -O https://raw.githubusercontent.com/latex3/latex2e/master/base/sample2e.tex
```

3. Generate the PDF document from LaTeX document

```bash
pdflatex sample2e.tex
```

4. Results

```
pdflatex sample2e.tex 
This is pdfTeX, Version 3.141592653-2.6-1.40.22 (TeX Live 2021/NixOS.org) (preloaded format=pdflatex)
 restricted \write18 enabled.
entering extended mode
(./sample2e.tex
LaTeX2e <2020-10-01> patch level 4
L3 programming layer <2021-02-18>
(/nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/
tex/latex/base/article.cls
Document Class: article 2020/04/10 v1.4m Standard LaTeX document class

(/nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/
tex/latex/base/size10.clo))
(/nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/
tex/latex/l3backend/l3backend-pdftex.def) (./sample2e.aux)
(/nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/
tex/latex/base/omscmr.fd) [1{/nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texliv
e-combined-2021/share/texmf-var/fonts/map/pdftex/updmap/pdftex.map}] [2]
[3] (./sample2e.aux) ){/nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-comb
ined-2021/share/texmf/fonts/enc/dvips/cm-super/cm-super-ts1.enc}</nix/store/8sm
4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/fonts/type1/pub
lic/amsfonts/cm/cmbx12.pfb></nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive
-combined-2021/share/texmf/fonts/type1/public/amsfonts/cm/cmex10.pfb></nix/stor
e/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/fonts/type
1/public/amsfonts/cm/cmmi10.pfb></nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-te
xlive-combined-2021/share/texmf/fonts/type1/public/amsfonts/cm/cmmi7.pfb></nix/
store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/fonts/
type1/public/amsfonts/cm/cmr10.pfb></nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj
-texlive-combined-2021/share/texmf/fonts/type1/public/amsfonts/cm/cmr12.pfb></n
ix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/fon
ts/type1/public/amsfonts/cm/cmr17.pfb></nix/store/8sm4068scgfy41f2sn67zhmip0bz8
2yj-texlive-combined-2021/share/texmf/fonts/type1/public/amsfonts/cm/cmr6.pfb><
/nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/f
onts/type1/public/amsfonts/cm/cmr7.pfb></nix/store/8sm4068scgfy41f2sn67zhmip0bz
82yj-texlive-combined-2021/share/texmf/fonts/type1/public/amsfonts/cm/cmr8.pfb>
</nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/texmf/
fonts/type1/public/amsfonts/cm/cmsy10.pfb></nix/store/8sm4068scgfy41f2sn67zhmip
0bz82yj-texlive-combined-2021/share/texmf/fonts/type1/public/amsfonts/cm/cmsy7.
pfb></nix/store/8sm4068scgfy41f2sn67zhmip0bz82yj-texlive-combined-2021/share/te
xmf/fonts/type1/public/amsfonts/cm/cmti10.pfb></nix/store/8sm4068scgfy41f2sn67z
hmip0bz82yj-texlive-combined-2021/share/texmf/fonts/type1/public/cm-super/sfrm1
000.pfb>
Output written on sample2e.pdf (3 pages, 142125 bytes).
Transcript written on sample2e.log.
```

5. Open the PDF document


```bash
chromium-browser sample2e.pdf
```

OR

```bash
google-chrome-stable sample2e.pdf 
```

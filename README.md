# In-TeX/LaTeX

In-TeX/LaTeX is a script program based on the LaTeX typesetting system that provides formula typesetting solutions for InDesign. It has the following characteristics:

    Cross-platform: This solution mainly relies on the cross-platform LaTeX system. InDesign is developed using JavaScript, Adobe's ExtendScript, to ensure cross-platform use, whether it is Windows or Mac systems.

    Running speed: Because the generation of formulas is completely dependent on LaTeX compilation, the speed of LaTeX compilation largely determines the speed of script running. For this reason, this solution also provides a way to intelligently switch the engine. Fast pdflatex engine compilation, when the formula contains Chinese, use the xelatex engine that supports Chinese. It also provides support for the fastest compiling ApTeX (Asiatic pTeX) engine (new name for platex-ng).

    Ease of use: It has functions such as insert conversion, acquisition and modification, code restoration, batch processing, formula adjustment, etc., and provides a way to use LaTeX templates, which is a major feature of this solution, and can cope with more complex LaTeX application scenarios through custom templates.

    Extensibility: This solution is not only suitable for typesetting of mathematical, physical and chemical formulas, but LaTeX has rich macro package resources. Use your imagination to directly convert LaTeX code into PDF output results in InDesign, and insert various data charts, drawings, etc. Rendered in your InDesign layout.

    Version restrictions: This solution is mainly developed in JavaScript language, and the interface completely relies on Adobe ExtendScript ScriptUI. There will be some small differences in different system platforms and different InDesign versions, and even cause confusion in operation performance differences, so it is specially limited to at least InDesign CS6 environment to run.

How is it different from others' formula typesetting solutions:

    Based on LaTeX , perfect formula.
    Cross-platform. At least other domestic solutions just give PC solutions.
    More extensibility. Based on LaTeX, a lot of extensions can be added besides the typesetting of mathematical formulas. Typesetting such as physical and chemical formulas is also feasible, and the LaTeX macro package is very rich, and even the drawing function can be integrated into InDesign to automatically convert data into charts, etc. , these are features that MathType cannot match. So, even if you're already using someone else's MathType formula typesetting solution, but others don't have that functionality, choosing this solution is a great addition.
    Compared with the free formula tools based on LaTeX made by Japanese like IDMath, this solution has more functions and user-friendly design operations. You are pleasantly surprised.

In-TeX/LaTeX installation and use
1. LaTeX system environment installation
Windows users:

No matter which LaTeX distribution you are using, but at least your LaTeX environment must have Perl and Ghostscript installed, the version requirements are at least Perl5, and Ghostscript must meet >= 8.0. If your installed LaTeX system does not have these or the version is too low, please Install or upgrade the new version. If there is no pdfcrop in your LaTeX environment, you need to install it yourself. As long as the LaTeX distribution is not too old, it usually comes with pdfcrop. For those who are inconvenient to install or upgrade the latest version of LaTeX, especially those old users of the CTeX suite, such as CTeX 2.4.6, I recommend using TeXLive green made by netizens and containing relatively new and not too old ctex packages Installed version, such as TeXLive2016 green version (introduction and download will be attached later), because this solution does not rely on the environment variables of LaTeX in the system to run under Windows, it is a good choice for users who do not like to toss to use the green version of TeXLive.

In short, there is no special case to recommend installing the TeXLive release version, and it is the latest version (Note: TeXLive2018 no longer supports XP system), and it is very convenient to update and maintain various macro packages. If you are familiar with the LaTeX system, you can completely customize your LaTeX environment. For example, choose W32TeX, and install and control the size of the volume according to your needs. The aforementioned Perl and Ghostscript environments must also be installed and meet the version requirements.
Mac users:

It is recommended to install MacTeX 2018. The latest ctex macro package has been updated, adding automatic recognition support for the font library in the new OSX system.
2. In-TeX/LaTeX script installation

After unzipping, copy the InTeXLaTeX folder directly to the

InDesign program installation path\Scripts\Scripts Panel\

(For example, using IDCS6, it may be C:\Program Files (x86)\Adobe\Adobe InDesign CS6\Scripts\Scripts Panel\ under PC, /Applications/Adobe InDesign CS6/Scripts/Scripts Panel/ under Mac)

Then start your InDesign. Find the script panel in Window-Utilities and open it. Open Application-InTeXLaTeX in the panel. Find the InTeXLaTeX.jsx file and double-click to run it. Follow the prompts to configure the LaTeX engine and play with LaTeX formulas. .

Free users: The authorization file of the free version is automatically generated, and the functions that require payment cannot be used.

Paid users: It needs to run under a special plug-in authorization environment, and use another authorization file to run the full function. After paying for the purchase, please contact the author for related operation matters.
3. Use of In-TeX/LaTeX

It is very simple to use, just follow the prompts. For more functions, please refer to the provided video demonstration and template (provided in the technical support QQ group Guangzhiyuan InDesign 1 group 10569122 sharing). The version without paid license does not support the functions of batch conversion formula and adjustment formula (Note: The free version only supports automatic adjustment of the current row formula), and there will be a prompt when the operation involves restricted functions. If you need these functions, please contact the author to purchase the license. If the free version has met your needs and you are looking forward to more complete functional upgrades, click the help button in the interface, scan the QR code and Alipay to sponsor it for 9.97 ￥! The most important thing is to join the InTeXLaTeX technical support group Guangzhiyuan InDesign 1 group 10569122 to get instant help, feedback questions and discuss technology. After all, LaTeX is not a simple typesetting software. The more you know, the more fun, the less confusion and the less detours.
Fourth, LaTeX resources
Forums and websites, etc.

http://bbs.ctex.org/forum.php Chinese TeX Community

http://www.latexstudio.net LaTeX Studio

https://zhuanlan.zhihu.com/LaTeX All about TeXnique (things that can improve your understanding of TeX)

https://weibo.com/latexstudio LaTeX technology typesetting Sina Weibo

https://weibo.com/cooldtp @ Guangzhiyuan Skin Sina Weibo (the latest information about this solution and InDesign)

InTeXLaTeX official technical support QQ group: Guangzhiyuan InDesign 1 group 10569122

LaTeX technical exchange 5000 people QQ group (91940767) (pay to join the group, there are many LaTeX technical masters to communicate)
LaTeX Chinese data related

lshort Chinese version, Introduction to LaTeX (Liu Haiyang), LaTeX2e Complete Learning Manual Second Edition (Hu Wei), etc.
TeXLive/MacTeX etc. download
1. TeX package download

http://www.latexstudio.net/page/texsoftware
2. Download the green version TeXLive

texlive2018+sumatrapdf(32bit)+texstudio(32bit) portable version Baidu network disk download:

https://pan.baidu.com/s/1ZC7Ivg1cI64-Jl6FhP-irA

Password: ks13

Introduction of TeXLive 2016 ISO green free installation version for windows:

http://bbs.ctex.org/forum.php?mod=viewthread&tid=152717

TeXLive 2016 ISO green free installation version for windows Baidu network disk download (please select TeXLIve2016.iso.xz under the /TeX folder to download, please refer to the description of the TeXLive2016.txt file for related information):

https://pan.baidu.com/s/1brg3hj5
3. W32TeX download

http://w32tex.org/index-en.html
4. ApTeX (Asiatic pTeX/ptex-ng) project

https://github.com/clerkma/ptex-ng

https://github.com/clerkma/ptex-ng-dist
5. Download Perl & Ghostscript

ActivePerl (please pay attention to the checked options when installing, it is not recommended to install the accompanying editor): https://www.activestate.com/activeperl/downloads

Ghostscript: https://www.ghostscript.com/download/gsdnld.html

Finally, I especially recommend a free tool that can capture OCR formula pictures as LaTeX formula codes - Mathpix, both Mac and Win versions are available, allowing you to enter formulas with less effort:

https://www.mathpix.com/
6. Links posted on the CTEX forum (for updates)

http://bbs.ctex.org/forum.php?mod=viewthread&tid=155312

PUB@September 1, 2018 By Skin in Nanning

Sina Weibo: @ Guangzhiyuan Skin

Contact: QQ150062840

Technical support: QQ group 10569122 

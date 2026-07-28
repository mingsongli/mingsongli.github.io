---
layout: page
title: Downloads
--- 
<section id ="matlab1">
<h2>Current version</h2>
<p><b>The current version of Acycle is v3.0.</b></p>
<p><b>Released July 28, 2026.</b></p>
<p><strong>Important:</strong> The standalone edition of Acycle v3.0 requires <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer"><strong>MATLAB Runtime R2026a</strong></a>. It is not compatible with MATLAB Runtime R2020b.</p>
<br />

<h2>v3.0 What's new</h2>

<ol>
    <li>
        <p><b>NEW: Rebuilt graphical user interface.</b></p>
        <p>The graphical user interface has been comprehensively rebuilt in programmatic MATLAB code. The legacy GUIDE framework and its <code>.fig</code> dependencies have been removed, providing a cleaner and more maintainable foundation for future development while making Acycle easier for AI-assisted tools to inspect and invoke directly.</p>
    </li>
    <li>
        <p><b>NEW: COCO 2.0.</b></p>
        <p>COCO and eCOCO have been substantially redesigned. COCO 2.0 brings together adaptive and fixed-target analyses, blocked and interleaved cross-validated COCO workflows, improved AR(1) Monte Carlo significance testing, clearer resolution and reliability diagnostics, enhanced visualization, and expanded workbook and figure exports.</p>
        <p>Special thanks to Prof. Stephen Meyers for his valuable suggestions.</p>
    </li>
    <li>
        <p><b>NEW: Expanded statistical analysis tools.</b></p>
        <p>New Univariate and Bivariate menus provide summary statistics, one- and two-sample tests, ANOVA, normality tests, chi-square goodness-of-fit tests, correlation, covariance, and linear regression.</p>
    </li>
    <li>
        <p><b>IMPROVED: EEMD and EMD variance reporting.</b></p>
        <p>The variance of each intrinsic mode function (IMF), together with its percentage contribution to the total variance, is now included as comments in the output table header.</p>
        <p>Special thanks to Prof. Zhengtang Guo for his valuable suggestions.</p>
    </li>
    <li>
        <p><b>IMPROVED: Native macOS keyboard shortcuts.</b></p>
        <p>Acycle now supports the standard Command+C, Command+V, and Command+X shortcuts on macOS.</p>
    </li>
    <li>
        <p><b>FIXED: COCO/eCOCO “Middle Age” option.</b></p>
        <p>A bug that could prevent the “Middle Age” option from functioning correctly when user-defined orbital periods were selected has been corrected.</p>
    </li>
    <li>
        <p><b>FIXED: Recurrence-analysis DET calculation.</b></p>
        <p>The determinism (DET) calculation in recurrence analysis has been corrected. We thank Zhixin Wang of Peking University for debugging and correcting this issue.</p>
    </li>
    <li>
        <p><b>FIXED: Spectral and wavelet analysis issues.</b></p>
        <p>The MTM bandwidth calculation has been corrected; SWA processing has been stabilized for long series containing more than 10,000 data points; and the wavelet chi-square calculation has been updated for compatibility with modern MATLAB releases.</p>
    </li>
</ol>

<h2>v2.7 What's new</h2>
<p>1. COCO: Save the correct COCO figure; use the invpretile function to calculate percentiles;</p>
<p>2. eCOCO: Save data in an Excel file;</p>
<p>3. Curve Fitting: estimate the optimal span using the Generalized Cross-Validation (GCV) method;</p>
<p>4. Japanese version is ready (Thank Prof. Masayuki Ikeda);</p>
<p>5. CENOGRID (Westerhold et al., 2020, Science, doi: 10.1126/science.aba6853);</p>
<p>6. Dynamic filter: bug-free;</p>
<p>7. Insolation/astronomical solutions: debug. Start from 0. Thanks, Lucas Lourens!</p>
<p>8. Undatable: Age-depth modeling in Matlab. Thank Lougheed, B. C. and Obrochta, S. P. for permission.</p>
<p>9. Prof. Graham Weedon's SWA method included! Thank Graham!</p>
<p>10. MTM + SWA method (NEW)</p>
<p>11. Principal Component: language debug</p>
<br />
</section>


<section id ="matlab2">
        <h2>Acycle 3.0 MATLAB version</h2>
        <br />
        <p>Option 1: <a href="https://disk.pku.edu.cn/link/AAA07381DE3BE84E37A007820B4D4964FB" target="_blank" rel="noopener noreferrer">Acycle3MatLab.zip</a> @ disk.pku.edu.cn.</p>
        <p>Expires: 2029-08-27 17:30</p>
</section>
<br />

<section id ="standalone">
        <h2>Standalone versions</h2>
        <br />
        <h3>Acycle v3.0 for macOS</h3>
        <br />
        <p><a href="https://disk.pku.edu.cn/link/AAA365DA86831B4A0684705BE11000BDCF" target="_blank" rel="noopener noreferrer">Acycle_Mac_3_0.zip</a> [via Dropbox <a href ="https://www.dropbox.com/sh/t53vjs539gmixnm/AAC0BqTR0U5xghKwuVc1Iwbma?dl=0" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/color/48/000000/dropbox.png" alt="Dropbox" class="rounded" height="32" width="32"></a>, Baidu Cloud <a href ="https://pan.baidu.com/s/14-xRzV_-BBrE6XfyR_71Nw" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/material/24/000000/baidu-cloud.png" alt="Baidu Cloud" class="rounded"></a>]</p>
        <p>Expires: 2029-08-27 17:28</p>
        <p><img src="https://img.icons8.com/material/24/000000/xbox-cross.png" height="32" width="32"> <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/matlab.png" height="32" width="32"> MATLAB Runtime R2026a for macOS</a></p>
        <p>*: This software is a stand-alone program. It was tested in the Mac OS Ventura (13.4).</p>
        <p>**: <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer">MATLAB Runtime R2026a</a> (free) is required for the Acycle stand-alone software version 3.0. MATLAB Runtime R2020b is not compatible with Acycle v3.0.</p>
        <br />
        <h3>Acycle v3.0 for Windows</h3>
        <br />
        <p><a href="https://disk.pku.edu.cn/link/AA7720700B2D2044BAA19F75BA2CA6A13D" target="_blank" rel="noopener noreferrer">Acycle_Windows_3_0.rar</a> [via Dropbox <a href ="https://www.dropbox.com/sh/t53vjs539gmixnm/AAC0BqTR0U5xghKwuVc1Iwbma?dl=0" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/color/48/000000/dropbox.png" alt="Dropbox" class="rounded" height="32" width="32"></a>, Baidu Cloud <a href ="https://pan.baidu.com/s/14-xRzV_-BBrE6XfyR_71Nw" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/material/24/000000/baidu-cloud.png" alt="Baidu Cloud" class="rounded"></a>]</p>
        <p>Expires: 2029-08-27 17:29</p>
        <p><img src="https://img.icons8.com/material/24/000000/xbox-cross.png" height="32" width="32"> <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/matlab.png" height="32" width="32"> MATLAB Runtime R2026a for Windows</a></p>
        <p>*: This software is a stand-alone program. It was tested in Windows 10.</p>
        <p>**: <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer">MATLAB Runtime R2026a</a> (free) is required for the Acycle stand-alone software version 3.0. MATLAB Runtime R2020b is not compatible with Acycle v3.0.</p>
</section>


<section id ="download">
<br />
        <h2>Download Users' Guide</h2>
        <br />
        <p>More information: <a href="https://acycle.org/manual/" target="_blank" rel="noopener noreferrer">Users' Guide</a>.</p>
        <br />
        <p>更多详情: <a href="https://acycle.org/manual/" target="_blank" rel="noopener noreferrer">用户指南中文版</a>.</p>
        <br />
        <h2>Download Acycle Papers </h2>
        <br />
        <a href="/docs/Li-et-al-2019-Acycle-software.pdf" target="_blank" rel="noopener noreferrer"> Li et al., 2019 Computers & Geosciences </a>
        <br />
        <br />
        <b>Li et al., 2025 Science China Earth Sciences</b> - "Acycle: Enhanced time-series analysis software for geoscience research and education"<br>
        <a href="https://doi.org/10.1007/s11430-025-1848-7" target="_blank" rel="noopener noreferrer">[View Paper]</a> | 
        <a href="https://www.sciengine.com/cfs/files/files/fs/2019610391851565056" target="_blank" rel="noopener noreferrer">[Supplementary Materials]</a><br>
        <p style="font-size: 0.9em; margin-top: 5px;">This paper presents standardized recommendations for reporting data and parameters; following these recommendations will improve the reproducibility and reliability of research results. The supplementary materials include a demonstration case study and an Excel file for parameter documentation.</p>
</section>

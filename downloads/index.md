---
layout: page
title: Downloads
---
<section id="matlab1">
<h2>Current versions</h2>
<p><b>The current MATLAB and macOS versions of Acycle are v3.0.3.</b></p>
<p><b>The Windows standalone version remains v3.0.2.</b></p>
<p><b>Acycle v3.0.3 was released August 1, 2026.</b></p>
<p><strong>Important:</strong> The standalone editions listed below require <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer"><strong>MATLAB Runtime R2026a</strong></a> <strong>Update 4</strong>. They are not compatible with MATLAB Runtime R2020b.</p>
<br />

<h2>v3.0.3 What's new</h2>

<ol>
    <li>
        <p><b>FIXED: Cross-platform folder and file-list handling.</b></p>
        <p>Each user's current data folder is now stored in the user's Acycle settings. File lists are rebuilt safely, preventing stale or mismatched selections after analysis outputs are saved.</p>
    </li>
    <li>
        <p><b>IMPROVED: Refresh behavior throughout Acycle.</b></p>
        <p>Manual refresh clears the current selection, while automatic refreshes preserve a valid selection by file name. Spectral, wavelet, filtering, recurrence, correlation, interpolation, transformation, age-model, and other affected workflows now use the same safe refresh process.</p>
    </li>
    <li>
        <p><b>IMPROVED: COCO/eCOCO startup and depth-unit handling.</b></p>
        <p>The window now opens in COCO mode by default. If the main-window unit remains <code>unit</code>, Acycle treats it as metres after a non-blocking warning so the analysis can continue.</p>
    </li>
    <li>
        <p><b>FIXED: COCO/eCOCO result saving.</b></p>
        <p>Result windows are protected while data and figures are saved, preventing incomplete exports if a window is closed too early. COCO/eCOCO saves numerical results, FIG files, and vector PDF files only, without bitmap images.</p>
    </li>
    <li>
        <p><b>TESTED: File-list, GUI-refresh, and output-saving regressions.</b></p>
        <p>Automated tests and end-to-end MATLAB R2026a GUI checks cover working-directory storage, selection handling, refresh behavior, and COCO/eCOCO output saving with irregularly sampled data.</p>
    </li>
</ol>

<br />
</section>

<section id="matlab2">
        <h2>Acycle 3.0.3 MATLAB version</h2>
        <br />
        <p>Option 1: <a href="https://disk.pku.edu.cn/link/AA8E19661D535045438208545141E64EFF" target="_blank" rel="noopener noreferrer">Acycle3.0.3_MatLab.zip</a> @ disk.pku.edu.cn.</p>
        <p><b>Folder Name:</b> Acycle<br /><b>Expires:</b> 2029-08-31 14:47</p>
        <p>Option 2: Source code (zip/tar.gz): <a href="https://github.com/mingsongli/acycle/releases/tag/v3.0.3" target="_blank" rel="noopener noreferrer">Acycle v3.0.3 on GitHub</a>.</p>
</section>
<br />

<section id="standalone">
        <h2>Standalone versions</h2>
        <br />
        <h3>Acycle v3.0.3 for macOS (M Chip)</h3>
        <br />
        <p><a href="https://disk.pku.edu.cn/link/AA8E19661D535045438208545141E64EFF" target="_blank" rel="noopener noreferrer">Acycle3.0.3_AppleMChip_Runtime2026a.zip</a> (for Macs with Apple M-series chips only) [via Dropbox <a href="https://www.dropbox.com/sh/t53vjs539gmixnm/AAC0BqTR0U5xghKwuVc1Iwbma?dl=0" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/color/48/000000/dropbox.png" alt="Dropbox" class="rounded" height="32" width="32"></a>]</p>
        <p><b>Folder Name:</b> Acycle<br /><b>Expires:</b> 2029-08-31 14:47</p>
        <p><strong>Intel Chip is coming.</strong></p>
        <p><img src="https://img.icons8.com/material/24/000000/xbox-cross.png" alt="" height="32" width="32"> <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/matlab.png" alt="" height="32" width="32"> MATLAB Runtime R2026a</a> Update 4 for macOS</p>
        <p>*: This software is a stand-alone program. It was tested in macOS Sonoma Version 14.4.</p>
        <p>**: <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer">MATLAB Runtime R2026a</a> Update 4 (free) is required for the Acycle stand-alone software version 3.0.3. MATLAB Runtime R2020b is not compatible with Acycle v3.0.3.</p>
        <br />
        <h3>Acycle v3.0.2 for Windows</h3>
        <br />
        <p>Compressed package: <a href="https://disk.pku.edu.cn/link/AA8E19661D535045438208545141E64EFF" target="_blank" rel="noopener noreferrer">Acycle3.0.2_Windows_R2026aUpdate4.zip</a> [via Dropbox <a href="https://www.dropbox.com/sh/t53vjs539gmixnm/AAC0BqTR0U5xghKwuVc1Iwbma?dl=0" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/color/48/000000/dropbox.png" alt="Dropbox" class="rounded" height="32" width="32"></a>]</p>
        <p>Installer: <a href="https://disk.pku.edu.cn/link/AA8E19661D535045438208545141E64EFF" target="_blank" rel="noopener noreferrer">Acycle3.0.2_Windows_R2026aUpdate4_Installer.zip</a></p>
        <p><b>Folder Name:</b> Acycle<br /><b>Expires:</b> 2029-08-31 14:47</p>
        <p><img src="https://img.icons8.com/material/24/000000/xbox-cross.png" alt="" height="32" width="32"> <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/matlab.png" alt="" height="32" width="32"> MATLAB Runtime R2026a</a> Update 4 for Windows</p>
        <p>*: This software is a stand-alone program. It was tested in Windows 10.</p>
        <p>**: <a href="https://www.mathworks.com/products/compiler/matlab-runtime.html" target="_blank" rel="noopener noreferrer">MATLAB Runtime R2026a</a> Update 4 (free) is required for the Acycle stand-alone software version 3.0.2. MATLAB Runtime R2020b is not compatible with Acycle v3.0.2.</p>
</section>

<section id="startup-fix">
        <br />
        <h2>Startup Fix</h2>
        <br />
        <h3>Windows</h3>
        <p>If Acycle 3.0.2 does not open and the console reports a missing module or DLL, follow the repair instructions for MATLAB Runtime R2026a Update 4.</p>
        <p><a href="/downloads/startup-fix/windows/" target="_blank" rel="noopener noreferrer">Windows Startup Fix (English / 中文)</a></p>
        <br />
        <h3>macOS</h3>
        <p>1. If Acycle does not respond and Terminal reports that <code>libmwlaunchermain.dylib</code> cannot be loaded, see the diagnosis and temporary runtime-library-path workaround.</p>
        <p><a href="/downloads/startup-fix/macos-runtime-path/" target="_blank" rel="noopener noreferrer">macOS Runtime Library Path Startup Issue Report (English / 中文)</a></p>
        <p>2. If macOS reports that Acycle “is damaged and can’t be opened,” follow the Gatekeeper quarantine-removal instructions.</p>
        <p><a href="/downloads/startup-fix/macos-gatekeeper/" target="_blank" rel="noopener noreferrer">macOS Gatekeeper Startup Fix (English / 中文)</a></p>
</section>

<section id="download">
<br />
        <h2>Download Users' Guide</h2>
        <br />
        <p>More information: <a href="https://acycle.org/manual/" target="_blank" rel="noopener noreferrer">Users' Guide</a>.</p>
        <br />
        <p>更多详情: <a href="https://acycle.org/manual/" target="_blank" rel="noopener noreferrer">用户指南中文版</a>.</p>
        <br />
        <h2>Download Acycle Papers</h2>
        <br />
        <a href="/docs/Li-et-al-2019-Acycle-software.pdf" target="_blank" rel="noopener noreferrer">Li et al., 2019 Computers &amp; Geosciences</a>
        <br />
        <br />
        <a href="https://doi.org/10.1007/s11430-025-1848-7" target="_blank" rel="noopener noreferrer">Li et al., 2025 Science China Earth Sciences</a>
        <br />
        “Acycle: Enhanced time-series analysis software for geoscience research and education”
        <br />
        <a href="https://www.sciengine.com/cfs/files/files/fs/2019610391851565056" target="_blank" rel="noopener noreferrer">[Supplementary Materials]</a>
        <br />
        <p style="font-size: 0.9em; margin-top: 5px;">This paper presents standardized recommendations for reporting data and parameters; following these recommendations will improve the reproducibility and reliability of research results. The supplementary materials include a demonstration case study and an Excel file for parameter documentation.</p>
</section>

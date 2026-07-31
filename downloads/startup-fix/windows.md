---
layout: page
title: Acycle 3.0.2 - Windows Startup Fix
permalink: /downloads/startup-fix/windows/
---

## Content / 内容

1. English: Acycle 3.0.2 - Windows Startup Fix
2. 中文：Acycle 3.0.2 - Windows 启动修复

---

## English Instructions

**Author:** Zhixin Wang

## Applies to

- Windows 64-bit
- Acycle 3.0.2
- MATLAB Runtime R2026a Update 4

Use this fix if Acycle does not open and the black console shows messages such as:

```text
Loading ...\libmwagentproxycredentialserviceclient.dll failed
The specified module could not be found
not connected
Update encountered failures
```

The MATLAB Runtime installation may be missing:

```text
libmwflproxycredentialapi.dll
```

## How to fix it

1. Close Acycle and its black console window.

2. Install the full 64-bit MATLAB Runtime R2026a Update 4. Extract the Runtime ZIP completely, then run `setup.exe` as administrator. [Official download](https://www.mathworks.com/products/compiler/matlab-runtime.html).

3. Open this folder:

   ```text
   C:\Program Files\MATLAB\MATLAB Runtime\R2026a\bin\win64
   ```

   If Runtime was installed in another location, open its `R2026a\bin\win64` folder instead.

4. Copy `libmwflproxycredentialapi.dll` from this repair folder into the `bin\win64` folder above. Approve the Windows administrator prompt.

   If the file already exists, do not replace it unless Acycle support asks you to do so.

5. Confirm that the final file exists here:

   ```text
   C:\Program Files\MATLAB\MATLAB Runtime\R2026a\bin\win64\libmwflproxycredentialapi.dll
   ```

6. Start Acycle again. Keep the black console window open. The first launch may take 10-60 seconds.

## If the DLL disappears again

Check Windows Security or third-party antivirus quarantine. Restore the official MathWorks DLL if it was removed, allow the MATLAB Runtime folder, and repeat the copy step.

## Important

- Do **not** copy this DLL into `C:\Windows\System32`.
- Do **not** rename the DLL.
- Use this file only with 64-bit MATLAB Runtime R2026a Update 4.
- DLL SHA-256:

  ```text
  7F0EAB9B0BDE06C1F96C122772F1E80F814E54C9CD9E71C10E2D5283FFC39830
  ```

---

## 中文说明：Acycle 3.0.2 - Windows 启动修复

**作者：** 王之鑫

## 适用环境

- 64 位 Windows
- Acycle 3.0.2
- MATLAB Runtime R2026a Update 4

如果 Acycle 无法打开，黑色控制台出现以下信息，可以使用本修复：

```text
加载 ...\libmwagentproxycredentialserviceclient.dll 失败
找不到指定的模块
not connected
更新时遇到故障
```

原因可能是 MATLAB Runtime 安装时遗漏了：

```text
libmwflproxycredentialapi.dll
```

## 修复步骤

1. 关闭 Acycle 和它的黑色控制台窗口。

2. 安装完整的 64 位 MATLAB Runtime R2026a Update 4。必须先完整解压 Runtime ZIP，再以管理员身份运行 `setup.exe`。[官方下载地址](https://www.mathworks.com/products/compiler/matlab-runtime.html)。

3. 打开以下文件夹：

   ```text
   C:\Program Files\MATLAB\MATLAB Runtime\R2026a\bin\win64
   ```

   如果 Runtime 安装在其他位置，请打开对应的 `R2026a\bin\win64` 文件夹。

4. 将本修复文件夹中的 `libmwflproxycredentialapi.dll` 复制到上述 `bin\win64` 文件夹。Windows 请求管理员权限时，请点击“是”或“继续”。

   如果目标位置已经存在该文件，请不要覆盖，除非 Acycle 技术支持要求这样做。

5. 确认最终文件位于：

   ```text
   C:\Program Files\MATLAB\MATLAB Runtime\R2026a\bin\win64\libmwflproxycredentialapi.dll
   ```

6. 重新启动 Acycle。请保留黑色控制台窗口。第一次启动可能需要 10-60 秒。

## 如果 DLL 再次消失

请检查 Windows 安全中心或第三方杀毒软件的隔离区。如果该文件被删除，请恢复这个 MathWorks 官方 DLL，允许 MATLAB Runtime 文件夹，然后重新执行复制步骤。

## 重要提示

- 不要把这个 DLL 复制到 `C:\Windows\System32`。
- 不要重命名这个 DLL。
- 这个文件只用于 64 位 MATLAB Runtime R2026a Update 4。
- DLL SHA-256：

  ```text
  7F0EAB9B0BDE06C1F96C122772F1E80F814E54C9CD9E71C10E2D5283FFC39830
  ```

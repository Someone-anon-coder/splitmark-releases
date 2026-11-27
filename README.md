# Splitmark: downloads

Installers for **Splitmark**, a Windows app that splits one combined PDF (invoices, statements,
payslips) into separate files and names each one from text on its pages, such as the invoice
number and customer.

**Get it:** [Microsoft Store](https://apps.microsoft.com/detail/9N6SXDRKVV0M) (recommended: signed by Microsoft, updates itself) ·
[latest installer](https://github.com/Someone-anon-coder/splitmark-releases/releases/latest) · **Website and help:**
<https://splitmark.aayush-c2684.workers.dev>

This repository holds release files only; it contains no source code.

## Install

The easiest way is the [Microsoft Store](https://apps.microsoft.com/detail/9N6SXDRKVV0M). Both versions are the same app with the same
free trial, and the same licence key works in either. To use the direct installer instead:

1. Download `Splitmark-Setup-<version>.exe` from the latest release.
2. Optional: check it against `SHA256SUMS.txt` in the same release. In PowerShell:
   ```
   Get-FileHash .\Splitmark-Setup-1.0.0.exe
   ```
3. Run it. It installs for your user only and needs no administrator rights.

The installer is not code-signed yet, so Windows SmartScreen may show "Windows protected your
PC". Choose **More info**, then **Run anyway**. The Microsoft Store version does not show this.

Windows 10 (1809 or later) and Windows 11, 64-bit. No Python needed.

## Free and paid

Without a licence Splitmark saves up to 10 files per run, with every feature. A one-time licence
(USD 49, 2 PCs) removes the limit. See the
[website](https://splitmark.aayush-c2684.workers.dev/#pricing).

Your PDFs never leave your PC; the only network call is licence activation. See the
[privacy policy](https://splitmark.aayush-c2684.workers.dev/privacy).

## Support

boringware@outlook.com

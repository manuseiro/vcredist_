# Microsoft Visual C++ Redistributable Packages

> [!NOTE]
> Mais informações você pode encontrar na [documentação](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads) da Microsoft.
 
## Microsoft Visual C++ 2005 Redistributable Package
  * [x64](https://download.microsoft.com/download/8/B/4/8B42259F-5D70-43F4-AC2E-4B208FD8D66A/vcredist_x64.EXE) *8.0.61000 (EOL)* `Microsoft.VCRedist.2005.x64`<br>
  * [x86](https://download.microsoft.com/download/8/B/4/8B42259F-5D70-43F4-AC2E-4B208FD8D66A/vcredist_x86.EXE) *8.0.61001 (EOL)* `Microsoft.VCRedist.2005.x86`
## Microsoft Visual C++ 2008 Redistributable Package
  * [x64](https://download.microsoft.com/download/5/D/8/5D8C65CB-C849-4025-8E95-C3966CAFD8AE/vcredist_x64.exe) *9.0.30729.6161 (EOL)* `Microsoft.VCRedist.2008.x64`<br>
  * [x86](https://download.microsoft.com/download/5/D/8/5D8C65CB-C849-4025-8E95-C3966CAFD8AE/vcredist_x86.exe) *9.0.30729.6161 (EOL)* `Microsoft.VCRedist.2008.x86`
## Microsoft Visual C++ 2010 Redistributable Package
  * [x64](https://download.microsoft.com/download/E/E/0/EE05C9EF-A661-4D9E-BCE2-6961ECDF087F/vcredist_x64.exe) *10.0.40219.473 (EOL)* `Microsoft.VCRedist.2010.x64`<br>
  * [x86](https://download.microsoft.com/download/E/E/0/EE05C9EF-A661-4D9E-BCE2-6961ECDF087F/vcredist_x86.exe) *10.0.40219.473 (EOL)* `Microsoft.VCRedist.2010.x86`
## Microsoft Visual C++ 2012 Redistributable Package
  * [x64](https://download.microsoft.com/download/1/6/B/16B06F60-3B20-4FF2-B699-5E9B7962F9AE/VSU_4/vcredist_x64.exe) *11.0.61030 (EOL)* `Microsoft.VCRedist.2012.x64`<br>
  * [x86](https://download.microsoft.com/download/1/6/B/16B06F60-3B20-4FF2-B699-5E9B7962F9AE/VSU_4/vcredist_x86.exe) *11.0.61030 (EOL)* `Microsoft.VCRedist.2012.x86`
## Microsoft Visual C++ 2013 Redistributable Package
  * [x64](https://aka.ms/highdpimfc2013x64enu) *12.0.40664* `Microsoft.VCRedist.2013.x64` <br>
  * [x86](https://aka.ms/highdpimfc2013x86enu) *12.0.40664* `Microsoft.VCRedist.2013.x86` 
## Microsoft Visual C++ 2015-2022 Redistributable Package
  * [x64](https://aka.ms/vs/17/release/VC_redist.x64.exe) *always lastest permalink (14.38.33135)* `Microsoft.VCRedist.2015+.x64` <br>
  * [x86](https://aka.ms/vs/17/release/VC_redist.x86.exe) *always lastest permalink (14.38.33135)* `Microsoft.VCRedist.2015+.x86` <br>

> [!WARNING]
> [App Installer](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) deve ser instalado no Win10/11.
 
> [!TIP]
> Você pode instalar todos os pacotes redistribuíveis do Visual C++ usando apenas um comando abaixo

## CMD

> [!TIP]
> Você pode salvá-lo e executá-lo como arquivo em lote (.bat).

```batch
winget install --id=Microsoft.VCRedist.2005.x86 -e  && winget install --id=Microsoft.VCRedist.2005.x64 -e  && winget install --id=Microsoft.VCRedist.2008.x86 -e  && winget install --id=Microsoft.VCRedist.2008.x64 -e  && winget install --id=Microsoft.VCRedist.2010.x86 -e  && winget install --id=Microsoft.VCRedist.2010.x64 -e  && winget install --id=Microsoft.VCRedist.2012.x86 -e  && winget install --id=Microsoft.VCRedist.2012.x64 -e  && winget install --id=Microsoft.VCRedist.2013.x86 -e  && winget install --id=Microsoft.VCRedist.2013.x64 -e  && winget install --id=Microsoft.VCRedist.2015+.x86 -e  && winget install --id=Microsoft.VCRedist.2015+.x64 -e 
```
## PowerShell
```powershell
winget install --id=Microsoft.VCRedist.2005.x86 -e  ; winget install --id=Microsoft.VCRedist.2005.x64 -e  ; winget install --id=Microsoft.VCRedist.2008.x86 -e  ; winget install --id=Microsoft.VCRedist.2008.x64 -e  ; winget install --id=Microsoft.VCRedist.2010.x86 -e  ; winget install --id=Microsoft.VCRedist.2010.x64 -e  ; winget install --id=Microsoft.VCRedist.2012.x86 -e  ; winget install --id=Microsoft.VCRedist.2012.x64 -e  ; winget install --id=Microsoft.VCRedist.2013.x86 -e  ; winget install --id=Microsoft.VCRedist.2013.x64 -e  ; winget install --id=Microsoft.VCRedist.2015+.x86 -e  ; winget install --id=Microsoft.VCRedist.2015+.x64 -e 

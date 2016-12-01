# Fix-bug-build-tool-C-on-node-js-npm

This bug happens when installing Chimp. 


Link to fix: 
- https://www.npmjs.com/package/windows-build-tools
- https://github.com/nodejs/node-gyp/issues/802
- https://blogs.msdn.microsoft.com/vcblog/2015/11/02/announcing-visual-c-build-tools-2015-standalone-c-tools-for-build-environments/

1. Install SDKSETUP.EXE (for Win10. If using win 7 or 8, you should search and download SDK for win 7 or 8)
2. Install visualcppbuildtools_full.exe
3. Run command "npm install --global windows-build-tools"
	+  [Windows Vista / 7 only] requires .NET Framework 4.5.1 (Currently not installed automatically by this package)
4. Install Chimp: npm install -g chimp

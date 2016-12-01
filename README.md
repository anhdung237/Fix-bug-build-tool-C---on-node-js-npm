# Fix-bug-build-tool-C-on-node-js-npm

This bug happens when installing Chimp. 


Link to fix: 
- https://www.npmjs.com/package/windows-build-tools
- https://github.com/nodejs/node-gyp/issues/802
- https://blogs.msdn.microsoft.com/vcblog/2015/11/02/announcing-visual-c-build-tools-2015-standalone-c-tools-for-build-environments/

1. npm install --global windows-build-tools
	+  [Windows Vista / 7 only] requires .NET Framework 4.5.1 (Currently not installed automatically by this package)
2. Install Chimp: npm install -g chimp

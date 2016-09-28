
> execSync@1.0.2 install C:\git\angular2\angularCliNodeModules\node_modules\execSync
> node install.js

[execsync v1.0.2] Attempting to compile native extensions.
{ Error: spawn node-gyp ENOENT
    at exports._errnoException (util.js:1007:11)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:182:32)
    at onErrorNT (internal/child_process.js:348:16)
    at _combinedTickCallback (internal/process/next_tick.js:74:11)
    at process._tickCallback (internal/process/next_tick.js:98:9)
    at Function.Module.runMain (module.js:577:11)
    at startup (node.js:160:18)
    at node.js:456:3
  code: 'ENOENT',
  errno: 'ENOENT',
  syscall: 'spawn node-gyp',
  path: 'node-gyp',
  spawnargs: [ 'rebuild' ] }
[execSync v1.0.2]
    Native code compile failed!!
    Will try to use win32 extension.

> node-zopfli@2.0.1 install C:\git\angular2\angularCliNodeModules\node_modules\node-zopfli
> node-pre-gyp install --fallback-to-build

[node-zopfli] Success: "C:\git\angular2\angularCliNodeModules\node_modules\node-zopfli\lib\binding\node-v48-win32-x64\zopfli.node" is installed via remote

> node-sass@3.10.0 install C:\git\angular2\angularCliNodeModules\node_modules\node-sass
> node scripts/install.js

Start downloading binary at https://github.com/sass/node-sass/releases/download/v3.10.0/win32-x64-48_binding.node
Binary downloaded and installed at C:\git\angular2\angularCliNodeModules\node_modules\node-sass\vendor\win32-x64-48\binding.node

> node-sass@3.10.0 postinstall C:\git\angular2\angularCliNodeModules\node_modules\node-sass
> node scripts/build.js

"C:\git\angular2\angularCliNodeModules\node_modules\node-sass\vendor\win32-x64-48\binding.node" exists.
 testing binary.
Binary is fine; exiting.
npm WARN saveError ENOENT: no such file or directory, open 'C:\git\angular2\angularCliNodeModules\package.json'
C:\git\angular2\angularCliNodeModules
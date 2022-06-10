npm WARN deprecated puppeteer@10.4.0: Version no longer supported. Upgrade to @latest
npm ERR! code 1
npm ERR! path /Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas
npm ERR! command failed
npm ERR! command sh -c node-pre-gyp install --fallback-to-build
npm ERR! Failed to execute '/usr/local/bin/node /usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js configure --fallback-to-build --module=/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas/build/Release/canvas.node --module_name=canvas --module_path=/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas/build/Release --napi_version=8 --node_abi_napi=napi --napi_build_version=0 --node_napi_label=node-v108' (1)
npm ERR! node-pre-gyp info it worked if it ends with ok
npm ERR! node-pre-gyp info using node-pre-gyp@1.0.6
npm ERR! node-pre-gyp info using node@18.3.0 | darwin | arm64
npm ERR! node-pre-gyp info check checked for "/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas/build/Release/canvas.node" (not found)
npm ERR! node-pre-gyp http GET https://github.com/Automattic/node-canvas/releases/download/v2.8.0/canvas-v2.8.0-node-v108-darwin-unknown-arm64.tar.gz
npm ERR! node-pre-gyp ERR! install response status 404 Not Found on https://github.com/Automattic/node-canvas/releases/download/v2.8.0/canvas-v2.8.0-node-v108-darwin-unknown-arm64.tar.gz 
npm ERR! node-pre-gyp WARN Pre-built binaries not installable for canvas@2.8.0 and node@18.3.0 (node-v108 ABI, unknown) (falling back to source compile with node-gyp) 
npm ERR! node-pre-gyp WARN Hit error response status 404 Not Found on https://github.com/Automattic/node-canvas/releases/download/v2.8.0/canvas-v2.8.0-node-v108-darwin-unknown-arm64.tar.gz 
npm ERR! gyp info it worked if it ends with ok
npm ERR! gyp info using node-gyp@9.0.0
npm ERR! gyp info using node@18.3.0 | darwin | arm64
npm ERR! gyp info ok 
npm ERR! gyp info it worked if it ends with ok
npm ERR! gyp info using node-gyp@9.0.0
npm ERR! gyp info using node@18.3.0 | darwin | arm64
npm ERR! gyp info find Python using Python version 3.8.9 found at "/Applications/Xcode.app/Contents/Developer/usr/bin/python3"
npm ERR! gyp info spawn /Applications/Xcode.app/Contents/Developer/usr/bin/python3
npm ERR! gyp info spawn args [
npm ERR! gyp info spawn args   '/usr/local/lib/node_modules/npm/node_modules/node-gyp/gyp/gyp_main.py',
npm ERR! gyp info spawn args   'binding.gyp',
npm ERR! gyp info spawn args   '-f',
npm ERR! gyp info spawn args   'make',
npm ERR! gyp info spawn args   '-I',
npm ERR! gyp info spawn args   '/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas/build/config.gypi',
npm ERR! gyp info spawn args   '-I',
npm ERR! gyp info spawn args   '/usr/local/lib/node_modules/npm/node_modules/node-gyp/addon.gypi',
npm ERR! gyp info spawn args   '-I',
npm ERR! gyp info spawn args   '/Users/ludvigkindstrand/Library/Caches/node-gyp/18.3.0/include/node/common.gypi',
npm ERR! gyp info spawn args   '-Dlibrary=shared_library',
npm ERR! gyp info spawn args   '-Dvisibility=default',
npm ERR! gyp info spawn args   '-Dnode_root_dir=/Users/ludvigkindstrand/Library/Caches/node-gyp/18.3.0',
npm ERR! gyp info spawn args   '-Dnode_gyp_dir=/usr/local/lib/node_modules/npm/node_modules/node-gyp',
npm ERR! gyp info spawn args   '-Dnode_lib_file=/Users/ludvigkindstrand/Library/Caches/node-gyp/18.3.0/<(target_arch)/node.lib',
npm ERR! gyp info spawn args   '-Dmodule_root_dir=/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas',
npm ERR! gyp info spawn args   '-Dnode_engine=v8',
npm ERR! gyp info spawn args   '--depth=.',
npm ERR! gyp info spawn args   '--no-parallel',
npm ERR! gyp info spawn args   '--generator-output',
npm ERR! gyp info spawn args   'build',
npm ERR! gyp info spawn args   '-Goutput_dir=.'
npm ERR! gyp info spawn args ]
npm ERR! /bin/sh: pkg-config: command not found
npm ERR! gyp: Call to 'pkg-config pixman-1 --libs' returned exit status 127 while in binding.gyp. while trying to load binding.gyp
npm ERR! gyp ERR! configure error 
npm ERR! gyp ERR! stack Error: `gyp` failed with exit code: 1
npm ERR! gyp ERR! stack     at ChildProcess.onCpExit (/usr/local/lib/node_modules/npm/node_modules/node-gyp/lib/configure.js:261:16)
npm ERR! gyp ERR! stack     at ChildProcess.emit (node:events:527:28)
npm ERR! gyp ERR! stack     at ChildProcess._handle.onexit (node:internal/child_process:291:12)
npm ERR! gyp ERR! System Darwin 21.5.0
npm ERR! gyp ERR! command "/usr/local/bin/node" "/usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js" "configure" "--fallback-to-build" "--module=/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas/build/Release/canvas.node" "--module_name=canvas" "--module_path=/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas/build/Release" "--napi_version=8" "--node_abi_napi=napi" "--napi_build_version=0" "--node_napi_label=node-v108"
npm ERR! gyp ERR! cwd /Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas
npm ERR! gyp ERR! node -v v18.3.0
npm ERR! gyp ERR! node-gyp -v v9.0.0
npm ERR! gyp ERR! not ok 
npm ERR! node-pre-gyp ERR! build error 
npm ERR! node-pre-gyp ERR! stack Error: Failed to execute '/usr/local/bin/node /usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js configure --fallback-to-build --module=/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas/build/Release/canvas.node --module_name=canvas --module_path=/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas/build/Release --napi_version=8 --node_abi_napi=napi --napi_build_version=0 --node_napi_label=node-v108' (1)
npm ERR! node-pre-gyp ERR! stack     at ChildProcess.<anonymous> (/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/@mapbox/node-pre-gyp/lib/util/compile.js:89:23)
npm ERR! node-pre-gyp ERR! stack     at ChildProcess.emit (node:events:527:28)
npm ERR! node-pre-gyp ERR! stack     at maybeClose (node:internal/child_process:1090:16)
npm ERR! node-pre-gyp ERR! stack     at ChildProcess._handle.onexit (node:internal/child_process:302:5)
npm ERR! node-pre-gyp ERR! System Darwin 21.5.0
npm ERR! node-pre-gyp ERR! command "/usr/local/bin/node" "/Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/.bin/node-pre-gyp" "install" "--fallback-to-build"
npm ERR! node-pre-gyp ERR! cwd /Users/ludvigkindstrand/Downloads/create-10k-nft-collection-2.0.0/node_modules/canvas
npm ERR! node-pre-gyp ERR! node -v v18.3.0
npm ERR! node-pre-gyp ERR! node-pre-gyp -v v1.0.6
npm ERR! node-pre-gyp ERR! not ok

npm ERR! A complete log of this run can be found in:
npm ERR!
  
  
  
  
  Need help :(

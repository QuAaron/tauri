# tauri
tauriPlay
    - frontend framework and a Rust core.
# prerequests
electron由于内置chromium而导致软件打包体积过大、和内存消耗的问题
但是跨操作系统的application，要支持同一套ui本身是难以绕开浏览器的
electron : chrominum + nodejs
tauri: webview2 + rust
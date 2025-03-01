# 以 Docker 啟動各種 OS
## [Windows](https://github.com/dockur/windows)
```bash
cd Windows
docker-compose -f docker-compose-dockur-windows.yml up -d
cd ..
```
## Ubuntu
```bash
cd Linux
docker-compose -f docker-compose-kasm-ubuntu.yml up -d
cd ..
```
## [dockur/macos](https://github.com/dockur/macos)
```bash
cd MacOS
docker-compose -f docker-compose-dockur-macos-13.yml up -d
cd ..
```
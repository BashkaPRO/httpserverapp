# httpserverapp

Sample application for [C++ http server](https://github.com/awwit/httpserver).

## Dependencies

Common:

* [gnutls](https://www.gnutls.org/)

Linux: `dl`, `pthread`, `gnutls`

Windows: `ws2_32.lib`, `libgnutls.dll.a`

## Build

Linux:

```sh
git clone https://github.com/awwit/httpserverapp.git
cd httpserverapp
mkdir build
cd build
qbs build -f ./../projects/qt-creator/httpserverapp.qbs release
```

Windows:

```sh
git clone https://github.com/awwit/httpserverapp.git
cd httpserver
mkdir build
cd build
devenv ./../projects/msvs/httpserverapp.sln /build
```

# License

The source codes are licensed under the
[MIT](https://opensource.org/licenses/MIT),
the full text of the license is located in the [LICENSE](LICENSE) file.

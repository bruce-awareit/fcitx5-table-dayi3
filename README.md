# Fcitx5 的大易三碼輸入法模組

* 在 Arch Linux 中，必需先安裝的套件
    - fcitx5-chinese-addon，extra-cmake-modules，boost

* 在 Arch Linux 安裝大易三碼輸入法模組

```bash
    $ mkdir build
    $ cd build
    $ wget https://raw.githubusercontent.com/bruce-awareit/fcitx5-table-dayi3/main/PKGBUILD
    $ makepkg
    $ sudo pacman -U fcitx5-table-dayi3-$(pkgver)-$(pkgrel)-$(arch)-pkg.tar.xz
    $ fcitx5-configtool
```

* 參考資料
    - 大易公司：<http://www.dayi.com>
    - dayi-fcitx 專案：<https://github.com/twManu/dayi-fcitx>
    - fcitx5-table-extra 專案：<https://github.com/fcitx/fcitx5-table-extra>

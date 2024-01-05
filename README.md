# leisquid/kawaii-gcc

![GitHub License](https://img.shields.io/github/license/leisquid/kawaii-gcc)

Forked from [Bill-Haku/kawaii-gcc](https://github.com/Bill-Haku/kawaii-gcc).

## 省流

```sh
git clone https://github.com/leisquid/kawaii-gcc
cd ./kawaii-gcc
sudo make
```

会在 `/usr/share/locale/zh_CN/LC_MESSAGES/` 生成一份 `gcc.mo`。如果你的 GCC 需要依赖指定版本的 locale 的话，那么请将 `gcc.mo` 重命名为 `gcc-<主版本号>.mo`。

您可以去 [./src/zh-kawaii.po](./src/zh-kawaii.po) 修改您的定制 kawaii 文本。

详细资料，请看 [./README-zh.md](./README-zh.md) 或 [./README-original.md](./README-original.md)。

此致。

leisquid

24.1.5

# Third-party notices

JINX Client includes or can use the following third-party components.

## mpv

- Component: `vendor/mpv/mpv.exe`
- Version in this package: `mpv v0.41.0-689-g9e06c3248`
- Windows build source: https://github.com/shinchiro/mpv-winbuild-cmake/releases
- Upstream project: https://github.com/mpv-player/mpv
- License status: mpv is GPLv2+ by default. It can be built as LGPLv2.1+ only when GPL-only parts and GPL-linked libraries are excluded. The bundled Windows binary should be treated as GPL-family software unless the exact build configuration proves otherwise.
- Source access: users can obtain the corresponding upstream source and build scripts from the links above. If JINX Client is redistributed publicly, keep this notice with the package and provide the exact mpv build asset name and source/build links used for that release.

JINX Client launches mpv as a separate executable and controls it through JSON IPC. mpv is not modified in this package.

## Anime4K

- Component: `vendor/anime4k/*.glsl`
- Upstream project: https://github.com/bloc97/Anime4K
- License: MIT License
- Required notice: keep `vendor/anime4k/LICENSE` with binary and source distributions.

## WPF-UI

- Component: WPF-UI NuGet package
- Upstream project: https://github.com/lepoco/wpfui
- License: MIT License

## CommunityToolkit.Mvvm

- Component: CommunityToolkit.Mvvm NuGet package
- Upstream project: https://github.com/CommunityToolkit/dotnet
- License: MIT License

## Microsoft .NET runtime

- Component: .NET 8 Windows desktop runtime files when publishing self-contained builds
- Upstream project: https://github.com/dotnet/runtime
- License: MIT License and third-party notices from Microsoft .NET

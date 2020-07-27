# Microcharts

**Microcharts** is an extremely simple charting library for a wide range of platforms (see *Compatibility* section below), with shared code and rendering for all of them!

read our [wiki](https://github.com/dotnet-ad/Microcharts/wiki) to learn more about how to use this library.

## About

This project is just simple drawing on top of the awesome [SkiaSharp](https://github.com/mono/SkiaSharp) library. The purpose is not to have an heavily customizable charting library. If you want so, simply fork the code, since all of this is fairly simple. Their is no interaction, nor animation at the moment.

## Contributions

Contributions are welcome! If you find a bug please report it and if you want a feature please report it.

If you want to contribute code please file an issue and create a branch off of the current dev branch and file a pull request.

More info on how you can help can be found [here](https://github.com/dotnet-ad/Microcharts/wiki/Contributing).

## Gallery

![animation gallery](assets/animations.gif)

![gallery](assets/Gallery.png)

## Install

Available on NuGet

**NET Standard 2.0, Xamarin.iOS, Xamarin.Android, UWP**

[![NuGet](https://img.shields.io/nuget/v/Microcharts.svg?label=NuGet)](https://www.nuget.org/packages/Microcharts/)


**Xamarin.Forms (.NET Standard 2.0)**

[![NuGet](https://img.shields.io/nuget/v/Microcharts.Forms.svg?label=NuGet)](https://www.nuget.org/packages/Microcharts.Forms/)

## Tutorials

* [Video: Charts for Xamarin Forms](https://www.youtube.com/watch?v=tmymWdmf1y4) by [@HoussemDellai](https://github.com/HoussemDellai)

## Compatibility

Built in views are provided for **UWP**, **Xamarin.Forms**, **Xamarin.iOS** and **Xamarin.Android**, **Xamarin.macOS**, but any other **.NET Standard 2.0** [SkiaSharp](https://github.com/mono/SkiaSharp) supported platform is also compatible (see one of the included `ChartView` implementations for more details).

## License

MIT © [Aloïs Deniel](https://aloisdeniel.com) & [Ed Lomonaco](https://edlomonaco.dev)

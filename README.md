# Gempyodal

by Marcus Zou | 14 Oct 2025



## Intro

This is a project to apply the open-source resources available in the market to open up an opportunity of building a light-weight platform for GeoModelling in energy sector.

== It's too late since there are many commercial and free apps in the market?

== No, nothing is late if you power it up and keep it going, even push it to the end.



## Mindset

1- Start up with Python since most of the open-source apps are based on Python;

2- will migrate to Rust platform to archive a stronger and stabler infrastructure.



> [!NOTE]
>
> May modify the structure of this README as needed, without in-advance notice. 



----

## Subject - 1 - Gempy

### Day 1 - Getting started with GemPy

#### Normal Installation starts here

The below will install `GemPy` with the minimal required dependencies.

```shell
pip install gempy
```

For visualization in 2-D and 3-D, the additional package `gempy-viewer` can be used and installed with the dependency of `PyVista`:

```
$ pip install pyvista gempy-viewer
```

#### Enhanced Installation Options

For additional features, `GemPy` offers enhanced installation options:

- Base Features: For the majority of functionalities, install with base dependencies:

  ```
  pip install gempy[base]
  ```

- Optional Features: To access optional features such as data download support, install with optional dependencies:

  ```
  pip install gempy[opt]
  ```

- Development Version: For development purposes, including testing tools:

  ```
  pip install gempy[dev]
  ```

Note: Some advanced functionalities in `GemPy` require PyTorch. For installation, please follow the instructions on the [PyTorch installation page](https://pytorch.org/get-started/locally/).

Here is my config of hardware:

> OS: Windows 11 IoT Enterprise LTSC x86_64
> Host: Precision 7820 Tower
> Kernel: WIN32_NT 10.0.26200.6584 (25H2)
> Shell: PowerShell 7.5.3
> Terminal: Windows Terminal 1.22.12111.0
> Terminal Font: FiraMono Nerd Font (10pt)
> CPU: 2 x Intel(R) Xeon(R) Silver 4116 (48) @ 4.00 GHz
> GPU 1: NVIDIA Quadro P5000 @ 1.73 GHz (15.85 GiB) [Discrete]
> GPU 2: NVIDIA Quadro P5000 @ 1.73 GHz (15.85 GiB) [Discrete]



Then Give a try of `pytorch`, which takes quite a while:

```shell
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu126
```



#### Getting started

Let's rock and roll.



----

## Subject 2 - LASIO



## Credits

GemPy v3.0: [gempy.org](https://gempy.org)

LasIO
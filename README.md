# AutoBenchMark

**Version 0.2.2**<br>
이 프로그램은 벤치 마크 사이트로부터 최신 CPU와 GPU 성능 점수와 순위를 추출 프로그램입니다.<br>
csv, xlsx, xls 확장자로 결과를 보여줍니다.<br>
CPU 정보는 모델 이름, 점수로 작성됩니다.<br>
GPU 정보는 모델 이름, 점수로 작성됩니다.<br>

This program is a program that extracts the latest CPU and GPU performance scores and rankings from benchmark sites.<br>
The Output Data is saved as a csv, xlsx and xls file.
CPU information is written by model name and score.<br>
GPU information is written by model name and score.<br>

## 사용법(Usage)
```
사용법: AutoBench [--help] [--version] <csv|xlsx|xls> <command> [<args>]
         <csv|xlsx|xls>         csv,xlsx 또는 xls 확장자로 내보냅니다.(기본은 .csv)
         공백(cpu&gpu)           CPU와 GPU 둘 다 추출합니다.
         cpu                    CPU 데이터만 추출합니다.
         gpu                    GPU 데이터만 추출합니다.
```

```
Usage: AutoBench [--help] [--version] <csv|xlsx|xls> <command> [<args>]
         <csv|xlsx|xls>         Export to csv, xlsx or xls files.(default .csv)
         blank(cpu&gpu)         Extract both CPU and GPU Data
         cpu                    Extract Only CPU Data
         gpu                    Extract Only GPU Data
```

## 다운로드(Download)
|  | ![Windows](https://icongr.am/devicon/windows8-original.svg) Windows | ![Linux](https://icongr.am/devicon/linux-original.svg) Linux | ![Apple](https://icongr.am/devicon/apple-original.svg) MacOS |
|-|-|-|-|
| x64 |  [Windows 64bit](https://sourceforge.net/projects/autobench/files/v0.2.2/Windows%28x64%29/) |  [Linux 64bit](https://sourceforge.net/projects/autobench/files/v0.2.2/Linux64/) | [MacOS](https://sourceforge.net/projects/autobench/files/v0.2.2/MacOS/) |
| x86 | [Windows 32bit](https://sourceforge.net/projects/autobench/files/v0.2.2/Windows%28x86%29/) | [Linux 32bit](https://sourceforge.net/projects/autobench/files/v0.2.2/Linux32/) | [MacOS](https://sourceforge.net/projects/autobench/files/v0.2.2/MacOS/) |

## 빌드 방법(How To Build)
[PyInstaller](https://pyinstaller.readthedocs.io/en/stable/usage.html)
```
pip install pytinstaller
pyinstaller -D -F -n AutoBench.v0.2.2_ -i icon.ico AutoBench.py
```

## Git Release
```
git tag -a vz.x.y -m ""
git push origin vz.x.y
```

# 원본 사이트(Source Site)

[CPU Benchmark Site](https://www.cpubenchmark.net/)<br>
[GPU Benchmark Site](https://www.videocardbenchmark.net/)

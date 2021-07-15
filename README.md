# Customized heap allocator for EMC project

## Description

This customized heap allocator helps dynamic memory allocation to PCIe memory space for c/c++ programs.(No source code changes required).  Currently, it only supports our [customized driver](https://github.com/celery1124/mem_driver) on aarch64.  It's ported from [jemalloc](https://github.com/jemalloc/jemalloc) version 4.4.0.

For more details, please read our papers [HMMU](https://cesg.tamu.edu/wp-content/uploads/2012/02/TCAD3012213-Hardware-Memory-Mgmt-for-Future-Mobile-Hybrid-Memory-Systems.pdf) and [OpenMem](https://cesg.tamu.edu/wp-content/uploads/2012/02/OpenMem-Hardware-Software-Cooperative-Management-for-Mobile-Memory-System.pdf).

## Build

```bash
./autogen.sh
make
make install
```



## Cite our work

```bibtex
@ARTICLE{Wen-HMMU,
  author={Wen, Fei and Qin, Mian and Gratz, Paul V. and Reddy, A. L. Narasimha},
  journal={IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems}, 
  title={Hardware Memory Management for Future Mobile Hybrid Memory Systems}, 
  year={2020},
  volume={39},
  number={11},
  pages={3627-3637},
  doi={10.1109/TCAD.2020.3012213}}
```


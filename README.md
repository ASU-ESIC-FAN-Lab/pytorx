<!-- ---
markdown:
  image_dir: /assets
  path: README.md
  ignore_from_front_matter: true
  absolute_image_path: false 
--- -->

<p align="center">
  <img src="./imgs/pytorx_logo3.jpeg" alt="PytorX: s" width="800">
  <br>
</p>

<p align="center">PytorX helps you evaluate Neural Network performance on Crossbar Accelerator.</p>

Features
--------------------------------------------------------------------------------

* **Built on pytorch and GPU enabled**
* **Evaluation for Research of Device/Circuit/Architecture** 

<!-- * **Monitor integrated** — The functions -->

Getting Started with PytorX
------------------------------

This project aims at building an easy-to-use framework for neural network mapping on crossbar-based accelerator with resistive memory (e.g., ReRAM, MRAM, etc.).


- [Dependencies](#Dependencies)
- [Usage](#Usage)
- [Example](#Example)


If you find this project useful to you, please cite [our work](https://arxiv.org/abs/1807.07948):
```
@inproceedings{He2019NIA,
  title={Noise Injection Adaption: End-to-End ReRAM Crossbar Non-ideal Effect Adaption for Neural Network Mapping},
  author={He, Zhezhi and Lin, Jie and Ewetz, Rickard and Yuan, Jiann-Shiun and Fan, Deliang},
  booktitle={Proceedings of the 56th Annual Design Automation Conference},
  pages={105},
  year={2019},
  organization={ACM}
}
```
### Dependencies:

* Python 3.6 (Anaconda)
* Pytorch 1.1 
* cuDNN 

**TO-DO**: add a docker container for easy test.

### Usage

Set the environment variable [`PYTHONPATH`](https://docs.python.org/3/using/cmdline.html#envvar-PYTHONPATH) to locate the library. For example, assume we cloned pytorch repository on the home directory ~. then we can added the following line in ~/.bashrc. 

```bash {.line-numbers}
export PYTORX_HOME=/path/to/pytorx
export PYTHONPATH=$PYTORX_HOME/python${PYTHONPATH}
```
sample code on author's machine:
```bash {.line-numbers}
export PYTORX_HOME=/Users/elliot/Dropbox/Github/PytorX
export PYTHONPATH=$PYTORX_HOME/python:${PYTHONPATH}
```

Then you are ready to go~

### Example



## Model-Agnostic Meta-Learning

> Python 3.6 and tensorflow 1.15

### Directory Tree 

- `📂 models`
  - `📄 backbone_resnet18.py`: Model define for backbone feature extractor
  - `📄 XtarNet.py`: Model define for meta-update modules
- `📂 params`
  - `📄 backbone_resnet18.params`: Weight stored after training backbone feature extractor
  - `📄 XtarNet.params`: Weight stored after training meta-update modules
- `📂 script`
  - `📄 run.sh`: Shell script file for experimentation
- `📂 tools`
  - `📄 main.py`
  - `📄 maml.py`
  - `📄 special_grads.py`
  - `📄 utils.py`
- `📂 data`
  - `📄 miniImagenet_proc_images.py`
  - `📄 data_generator.py`

### Original Source

- https://github.com/cbfinn/maml
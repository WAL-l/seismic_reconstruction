# Reconstuct

## Setup

### 1. Code

```bash
git clone https://github.com/andreas128/RePaint.git
```

### 2. Environment
```bash
pip install numpy torch blobfile tqdm pyYaml pillow    # e.g. torch 1.7.1+cu110.
```

### 4. Run example
```bash
python test.py --conf_path confs/example.yml
```
Find the output in `./log/example/inpainted`

*Note: After refactoring the code, we did not reevaluate all experiments.*

<br>


## Details on data



**How to prepare the test data?**

one file for the data which is ".npy"
one file for mask
The masks have the value 255 for known regions and 0 for unknown areas (the ones that get generated).





# Acknowledgement

This work was supported by the ETH Zürich Fund (OK), a Huawei Technologies Oy (Finland) project, and an Nvidia GPU grant.

This repository is based on [guided-diffuion](https://github.com/openai/guided-diffusion.git) from OpenAI.

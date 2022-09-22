# TensorFlow_Env_Conda_Installation

### 创建环境 Create the Environment

打开Terminal终端，输入 

Open the Terminal and type
```
conda create -n tf tensorflow
```

创建新虚拟环境环境，名称为`tf`，根据要求输入确认`y`。

Create a new virtual environment environment with the name `tf` and enter the confirmation `y` as required.

### 激活环境 Activate the Environment

在使用环境之前需要先激活，在Terminal中输入命令:

You need to activate the environment before you can use it, enter the command in Terminal:

```
conda activate tf
```

<img width="585" alt="image" src="https://user-images.githubusercontent.com/60737865/191792364-9748e161-c94a-4af6-aeda-2381cd028072.png">

### 安装其它包 Install other packages

安装所需要的其它 Python 包，安装在其他环境（如base）中的不会同步过来。例如：

Install any other Python packages you need; those installed in other environments (such as base) will not be synced over. For example,


```
conda install pip
```

```
conda install numpy
```

```
conda install pandas
```

```
conda install scikit-learn
``` 

### 运行 Operation

每次使用之前，先激活环境.

Activate the environment before each use.
```
conda activate tf
```

然后如果要使用jupyter，可以在终端中继续输入：

Then to use jupyter, you can continue in the terminal by typing.
```
jupyter notebook
```

然后在其中运行tensorflow。例如：

Then run tensorflow in it. e.g.
```
import tensorflow
from tensorflow import keras
from tensorflow.keras.layers import Dense, Dropout
from tensorflow.keras.models import Sequential
```

### Using Anaconda-Navigator

如果你习惯使用交互界面，那么在创建环境之后的步骤都可以在navigator中进行。

If you are used to using the interactive interface, then the steps after creating the environment can all be done in navigator.

<img width="1200" alt="image" src="https://user-images.githubusercontent.com/60737865/191797874-21b8e562-927c-45c4-a67e-224840bb8d10.png">
可以在这个Environment界面中，激活环境后安装新的包。

You can install new packages after activating the environment in this Environment screen.

<img width="1192" alt="image" src="https://user-images.githubusercontent.com/60737865/191798380-d354c2f7-dc32-4363-ad0c-fa66c4f25224.png">
或者在这里启动笔记本。

Or launch the notebook here.

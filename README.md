# SnakeAI

本项目基于卷积神经网络代理

### 文件结构

```bash
├───main
│   ├───logs
│   ├───trained_models_mlp
```

## 运行指南

本项目基于 Python 编程语言，第三方库 [Pygame](https://www.pygame.org/news)、[OpenAI Gym](https://github.com/openai/gym)、[Stable-Baselines3](https://stable-baselines3.readthedocs.io/en/master/) 

### 模型训练

```bash
cd XXXX/snake-ai/main
python train_cnn.py
```

### 损失查看

```bash
cd XXXX/snake-ai/main
tensorboard --logdir=logs/
```

### 模型测试

```
cd XXXX/snake-ai/main
python test_cnn.py
```


- # Stable Baselines官方文档中文版

  > 起这个名字有点膨胀了。
  >
  > 网上没找到关于Stable Baselines使用方法的中文介绍，故翻译部分[官方文档](https://stable-baselines.readthedocs.io/en/master/index.html)。非专业出身，如有错误，请指正。
  >
  > 官方文档中文版汇总：Github：<https://github.com/DBWangML/stable-baselines-zh>    

  [Stable Baselines](https://github.com/hill-a/stable-baselines)是一组基于OpenAI [Baselines](https://github.com/openai/baselines)的改进版强化学习(RL: Reinforcement Learning)实现。

  Github网址： https://github.com/hill-a/stable-baselines   

  RL Baselines Zoo(预训练agents集合)：https://github.com/araffin/rl-baselines-zoo 

  RL Baselines zoo也提供一个简单界面，用于训练、评估agents以及超参数微调。

  你可以在Medium上查看一篇详细介绍Stable Baselines的文章：《[Stable Baselines: OpenAI Baselines的分支：让强化学习更容易](https://towardsdatascience.com/stable-baselines-a-fork-of-openai-baselines-reinforcement-learning-made-easy-df87c4b2fc82)》

- ## 与OpenAI Baselines的主要区别

  此工具集源自OpenAI Baselines的一个分支，进行了主体结构重塑和代码清理：

  - 统一算法结构
  - PEP8兼容（统一代码风格）
  - 文档化的函数和类
  - 更多的测试&更多的代码覆盖

- ## 用户向导

  - ### 安装

    - 预备知识
    - 稳定版本
    - 最新版本
    - 用Docker图片

  - ### 开始

  - ### 强化学习资源

  - ### RL算法

  - ### 案例

    - 先用Colab Notebook在线试试吧
    - 基础用法：训练、保存、载入
    - 多重处理：释放向量化环境的力量
    - 使用Callback：监控训练
    - Atari游戏
    - Mujoco：标准化输入特征
    - 自定义策略网络
    - 获取并调整模型参数
    - 迭代策略
    - 事后经验回放(HER)
    - 持续学习
    - 记录视频
    - 好处：制作训练好智体的GIF图片

  - ### 矢量化环境

    - [DummyVecEnv](https://stable-baselines.readthedocs.io/en/master/guide/vec_envs.html#dummyvecenv) 
    - [SubprocVecEnv](https://stable-baselines.readthedocs.io/en/master/guide/vec_envs.html#subprocvecenv) 
    - [Wrappers](https://stable-baselines.readthedocs.io/en/master/guide/vec_envs.html#wrappers) 

  - ### 使用自定义环境

  - ### 自定义策略网络

    - 案例

  - ### Tensorborad集成

    - 基础用法
    - 遗留集成

  - ### [RL Baselines Zoo](https://stable-baselines.readthedocs.io/en/master/guide/rl_zoo.html) 

    - 安装
    - 训练智体
    - 享受训练有素的智体
    - 超参数优化
    - Colab Notebook:在线尝试！

  - ### 预训练（克隆行为）

    - 轨迹生成专家
    - 用克隆行为预训练模型
    - 专家数据集的数据结构 

  - ### 处理NaN和inf 

    - 如何以及为何
    - Numpy参数
    - Tensorflow参数
    - VecCheckNan封装
    - 深度学习模型超参数
    - 数据集中的缺失值

  - ### 深度学习算法

    - [Base RL Class](https://stable-baselines.readthedocs.io/en/master/modules/base.html)
    - [Policy Networks](https://stable-baselines.readthedocs.io/en/master/modules/policies.html)
    - [A2C](https://stable-baselines.readthedocs.io/en/master/modules/a2c.html)
    - [ACER](https://stable-baselines.readthedocs.io/en/master/modules/acer.html)
    - [ACKTR](https://stable-baselines.readthedocs.io/en/master/modules/acktr.html)
    - [DDPG](https://stable-baselines.readthedocs.io/en/master/modules/ddpg.html)
    - [DQN](https://stable-baselines.readthedocs.io/en/master/modules/dqn.html)
    - [GAIL](https://stable-baselines.readthedocs.io/en/master/modules/gail.html)
    - [HER](https://stable-baselines.readthedocs.io/en/master/modules/her.html)
    - [PPO1](https://stable-baselines.readthedocs.io/en/master/modules/ppo1.html)
    - [PPO2](https://stable-baselines.readthedocs.io/en/master/modules/ppo2.html)
    - [SAC](https://stable-baselines.readthedocs.io/en/master/modules/sac.html)
    - [TRPO](https://stable-baselines.readthedocs.io/en/master/modules/trpo.html) 

  - ### Common

    - [Probability Distributions](https://stable-baselines.readthedocs.io/en/master/common/distributions.html)
    - [Tensorflow Utils](https://stable-baselines.readthedocs.io/en/master/common/tf_utils.html)
    - [Command Utils](https://stable-baselines.readthedocs.io/en/master/common/cmd_utils.html)
    - [Schedules](https://stable-baselines.readthedocs.io/en/master/common/schedules.html) 

  - ### Misc

    - [Changelog](https://stable-baselines.readthedocs.io/en/master/misc/changelog.html) 更新日志
    - [Projects](https://stable-baselines.readthedocs.io/en/master/misc/projects.html) 项目
    - [Plotting Results](https://stable-baselines.readthedocs.io/en/master/misc/results_plotter.html) 绘制结果

- ## 引用Stable Baselines 

  在作品中引用此项目：

  ```python
  @misc{stable-baselines,
    author = {Hill, Ashley and Raffin, Antonin and Ernestus, Maximilian and Gleave, Adam and Traore, Rene and Dhariwal, Prafulla and Hesse, Christopher and Klimov, Oleg and Nichol, Alex and Plappert, Matthias and Radford, Alec and Schulman, John and Sidor, Szymon and Wu, Yuhuai},
    title = {Stable Baselines},
    year = {2018},
    publisher = {GitHub},
    journal = {GitHub repository},
    howpublished = {\url{https://github.com/hill-a/stable-baselines}},
  }
  ```

- ## 贡献

  如有兴趣改进RL baselines，有很多工作需要做。具体待修事宜见 [roadmap](https://github.com/hill-a/stable-baselines/projects/1).

  如果你想参与，请先阅读[CONTRIBUTING.md](https://github.com/hill-a/stable-baselines/blob/master/CONTRIBUTING.md)。

- ## 索引和表格

  - 索引
  - 搜索页面
  - 模型索引



> 更多详细内容见Github：<https://github.com/DBWangML/stable-baselines-zh>  
# examGPT
a small project, using exam papers to analyze the questions of the student, and the points deserving improving



## 整体任务

* **输入**：学生有一份/多份测试的卷子，格式为扫描版pdf
* **任务**：根据学生做题情况，分析他在哪个具体知识点有问题，然后针对性地提出建议
* **输出**：学生有问题的知识点，可能出现的习惯性失误，具体的解决方法（比如特殊方法等）



## 流程

1. **图片转文字**：试卷的扫描图片 -> 文字内容
2. **文字内容规范化**：将文字内容进行规范，比如分页处理等
3. **GPT提问**：将问题+文字内容输入到GPT中，得到对应回复



## 具体工作

### 1. 图片转文字

* 使用marker或者mineru，可将pdf转换为文字内容

### 2. 文字内容规范化

* 

### 3. GPT提问

* 设计instruction和query





## 面对困难

### 1. 图片转文字

* 区分试题内容与学生回答内容
* 学生在题目上标注或演草
* 老师批改痕迹

### 2. 文字内容规范化



### 3. GPT提问

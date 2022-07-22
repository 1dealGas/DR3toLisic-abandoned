# DR3toLisic

将DanceRail谱面有损转换为1deal-Lisic谱面，不带Tag和LockID。



### 转换规则

- Tap转换为Tap/LTap/RTap
  
  先识别位置为0的Note，转换成LTap
  
  然后识别位置为13的Note，转换成RTap
  
  最后为其余Tap选择一个合适的位置，转换成Lisic中一般的Tap

- ExTap转换为Catch/LCatch/RCatch，规则同上。

- 其它类型直接无视。



### 使用方法

1. 用Godot 4.0 alpha12导入这个工程，运行。

2. 在文本框复制粘贴完整的DanceRail3谱面，点击“Convert”按钮，即可得到处理完成的Lisic谱面。



### LICENSE

**Note that DRMaker is NOT a open-resource software, and DanceRail3Viewer is NOT a software under regular open-resource license.**



**MIT License for DR3toLisic:**

Copyright (c) 2022 1dealGas.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



**Godot Engine Included:**

This game uses Godot Engine, available under the following license:

Copyright (c) 2007-2022 Juan Linietsky, Ariel Manzur. Copyright (c) 2014-2022 Godot Engine contributors.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

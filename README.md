# Mecody

### About Mecody

正如引言所述，Mecody是一个使用代码操控的高效率音乐制作软件。它使用易学的代码行与控制逻辑来编写音乐，省去了大量拖动鼠标的烦恼，同时本软件完全开源（免费），以致力于让音乐制作不受外界条件的影响。

如果您曾经学习过一门程序语言，你会发现它是非常易用的。

Example:
```
$include<piano\*>
using global.speed 80 bpm;
using global.strength 65 dB; //单位可省略
```

后期我们将添加更多音源并允许用户自行上传。上传之音源与本软件遵循相同协议。

### Usage

#### Import Sources

Code：
```
$include<source_name\*> //Import all;
$include<source_name\part_name(,part_name,part_name...)> //Import some parts;

# Mecody

### About Mecody

正如引言所述，Mecody是一个使用代码操控的高效率音乐制作软件。它使用易学的代码行与控制逻辑来编写音乐，省去了大量拖动鼠标的烦恼，同时本软件完全开源（免费），以致力于让音乐制作不受外界条件的影响。

### Usage

#### I Source Pack

Grammer: `$ import <Packname>`

#### II Settings

Grammer: 

**Global**
```
$ define global_set {
  valuename = value
  ...
}
```
Example:
```
$ define global_set {
  strength = 80
  unit = (+4*,1/4) // or other kinds of notes
  speed = 120
}
```
**Others**
```
//(in the function main)
  valuename = value
```
Example:
```
$ define main {
  //lines...
  strength = 120
  //lines...
}
```

#### III Notes

Grammer:

```
((+,+0.5)(-,-0.5)Note(*,+8)(/,-8),length(beat))
```

Example:
`(1,1)` - C in centre


# ExportSceneToObj
`ExportSceneToObj`用于Unity中导出场景（包括物件和地形）到.obj文件的Editor脚本。

### 功能：
* 支持导出物件和地形
* 支持自定义裁剪区域
* 提供自动裁剪功能

### 用法：
1：放到Unity的Editor目录下
2：如果要自定义裁剪区域的话，场景中增加裁剪区域（左下角和右上角）
3：修改代码中CUT_LB_OBJ_PATH和CUT_RT_OBJ_PATH
4：在Unity的菜单栏上有ExportScene菜单即可

### 其他：
目前判断物件是否在裁剪区域只是判断物件的坐标是否在区域内，还没有实现物件边界裁剪。

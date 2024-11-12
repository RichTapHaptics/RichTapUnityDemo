# RichTapUnityDemo

本工程依据Unity 3D Beginner: Roll-a-Ball Game教程制作完成，目的是展示RichTap Haptics插件的使用。在运行之前，请首先联系 bd@richtap-haptics.com 获取完整的插件包。  

**以下是集成振动效果的一般步骤：**  
1. 将振动效果.he文件放入Assets文件夹  
2. 在Unity编辑器里，鼠标右键点击Create创建RichTap Clip Effect SO对象，点击Clip选择.he文件，并调整振动参数  
3. 在控制小球滚动的Script中，绑定创建的RichtapClipEffectSO对象，并在小球发生碰撞的
OnCollisionEnter方法中调用RichtapClipEffectSO的Play方法，便可在小球发生碰撞时播放指定的振动效果



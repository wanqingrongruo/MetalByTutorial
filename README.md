# MetalByTutorial
The Demos that l learn metal

Chapter1:
device -> model -> pipeline -> render

model: 还没理解
pipeline:  由 device  + pipelinedescriptor 一起生成
pipelinedescriptor： 管理管道信息， pixelformat + vertex function + fragment function + ...

> The vertex function is where you usually manipulate vertex positions and the fragment function is where you specify the pixel color

commandQueue: device.makeCmmandQueue
 * queue  -> command buffer -> command encoder 
                        
***

Chapter2:


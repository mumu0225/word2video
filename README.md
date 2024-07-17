# word2video
需要安装ComfyUI并安装animatediff  
将dreamshaper_8.safetensors文件放进\ComfyUI\models\checkpoints路径下  
将v3_sd15_adapter.ckpt文件放进\ComfyUI\models\loras路径下  
将controlnet_checkpoint.ckpt放进\ComfyUI\models\controlnet路径下  
将v3_sd15_mm.ckpt放进\ComfyUI\custom_nodes\ComfyUI-AnimateDiff-Evolved\models路径下  
启动服务器后将word2video.json工作流拖入网页  
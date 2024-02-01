 一开始使用cubemx配置freertos时，啥也不用写，但是要在__weak void LedTask(void const * argument)弱函数中进行led的控制。也可以将MX_FREERTOS_Init();和osKernelStart();函数注释掉，自己在main中创建任务。

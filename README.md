# STM32F4-Disco USB sound card

1. renamed folder to CubeSTM32F4USBAudio to be able to import to CubeIDE
2. convert and update project
3. error : stm32f4_discovery_audio.h: No such file or directory > add Drivers\BSP\Board in "path & symbols"
4. uncomment the ff, and still ok:  
	MX_I2C1_Init();  
	MX_I2S3_Init();  
  MX_DMA_Init();

## To do

1. update ioc file to F4_V1.25.2, problem at the moment
2. make a new project file

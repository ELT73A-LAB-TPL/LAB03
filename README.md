# LAB03 template for ELT73A course 

## MiniF4-STM32F401CEU6
- https://github.com/WeActStudio/WeActStudio.MiniSTM32F4x1
  
## STM32CubeF4 MCU Firmware Package
- https://github.com/STMicroelectronics/STM32CubeF4
- https://github.com/STMicroelectronics/STM32Cube_MCU_Overall_Offer

## STM32 Development Tools
- https://www.st.com/en/development-tools/stm32cubemx.html
- https://www.st.com/en/development-tools/stm32cubeclt.html
- https://www.st.com/en/development-tools/stm32cubeprog.html

## Running STM32CubeMX in command-line mode
- https://www.st.com/resource/en/user_manual/um1718-stm32cubemx-for-stm32-configuration-and-initialization-c-code-generation-stmicroelectronics.pdf
  
```bash
"%STM32CubeMX_PATH%\jre\bin\java" -jar "%STM32CubeMX_PATH%\STM32CubeMX.exe" -i
```
### Open STM32CubeMX
```bash
OpenMx
```

```bash
OpenMx STM32F411CEUx
```

### Load STM32CubeMX Script
Load default values
```bash
LoadMX
```
Load with Project Name
```bash
LoadMX ProjectName
```
Load with Project Name and Script Name
```bash
LoadMX ProjectName ScriptName.txt
```
Load with Project Name, Script Name and generate code
```bash
LoadMX ProjectName ScriptName.txt Y
``` 

### MX export 
```bash
export script ScriptToLoad.txt
```

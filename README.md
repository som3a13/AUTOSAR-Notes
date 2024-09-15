Automotive Open System Architecture

Goal : develop refrence arch for auto ECU software

WHy? Modulatrity , scalability, reusability

objective : improve software qualitt , reduce cost

AUTOSAR SW layers : APP LAYER ,RTE,BSW

BSW: Service , EAL,MAL,COmplex drivers

BSW:are divided to stacks like memory stack , com stack,system stack:OS,error ,states

![1722876301015](image/README/1722876301015.png)

![1722876334674](image/README/1722876334674.png)

![1722876311608](image/README/1722876311608.png)

## MCAL

lowest sw layers : contains internal drivers with direct acess to the microcontroller , internal peripherals

Com drivers , IO drivers , Memory Drivers,Microcontroller driver


![1722877087686](image/README/1722877087686.png)

## HAL

Drivers for external devices

![1722880038024](image/README/1722880038024.png)



![1722880588155](image/README/1722880588155.png)

![1722883039622](image/README/1722883039622.png)

![1722883365192](image/README/1722883365192.png)

![1722883541206](image/README/1722883541206.png)

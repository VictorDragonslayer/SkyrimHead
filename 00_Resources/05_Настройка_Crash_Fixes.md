# Настройка Crash Fixes

**1) {Опционально} SKSE.ini:**  
    Секцию [Memory] можно удалить целиком, она больше не имеет значения.

**2) enblocal.ini:**  
> ExpandSystemMemoryX64=false  
> ReduceSystemMemoryUsage=true

**3)** [**Plugin Preloader**](http://www.nexusmods.com/skyrim/mods/75795/?) - без него всё это не работает.

**4) CrashFixPlugin.ini:**  
> UseOSAllocators=1  
> AlignHeapAllocate=1  
> WarnSKSEMemoryPatch=0 - только если ты удалил секцию [Memory] в SKSE.ini.

------

|[*Назад к очень важным надстройкам*](../01_Minimum/02_Очень_важные_надстройки.md)|
|:---:|

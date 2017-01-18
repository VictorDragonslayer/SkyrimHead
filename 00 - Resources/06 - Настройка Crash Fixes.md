# Настройка Crash Fixes

**1) SKSE.ini**

Секцию [Memory] можно удалить целиком, она больше не имеет значения.

**2) enblocal.ini**

> ExpandSystemMemoryX64=false

> ReduceSystemMemoryUsage=true

**3) Plugin Preloader**

http://www.nexusmods.com/skyrim/mods/75795/ - без него всё это не работает.

**4) CrashFixPlugin.ini**

> UseOSAllocators=1

> AlignHeapAllocate=1

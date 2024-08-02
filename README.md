此版本为解决mohist与No Flesh Within Chest的冲突的mohist分支

支持插件类型和优化项目见mohist

启动参数
-XX:+UseG1GC -XX:+UnlockExperimentalVMOptions
-XX:+ParallelRefProcEnabled
-XX:MaxGCPauseMillis=200
-XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC
-XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 
-XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M
-XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5
-XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15
-XX:G1MixedGCLiveThresholdPercent=90
-XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 
-XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1
-Dusing.aikars.flags=https://mcflags.emc.gs -Daikars.new.flags=true 

推荐使用zulu17 需要服务器7G以上的内存

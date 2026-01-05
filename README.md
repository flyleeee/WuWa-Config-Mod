<details open>
<summary><strong>🇺🇸 English</strong></summary>

# WuWa-Config-Mod

WuWa Configs for Mod Users on Mid-to-Low-End PCs  

**Tested on:** RTX 4060 Laptop GPU (> 60 FPS in general scenarios with Smooth Motion enabled)

1. Use the latest **Fixer 3.0** to fix **LOD hash**.
   👉 ([Wuwa_Mod_Fixer](https://github.com/Moonholder/Wuwa_Mod_Fixer/releases/tag/v3.0.0))
   
3. Then use the engine.ini above
   - **Please set the following corresponding entries in WWMI to match those in `engine.ini`**
      - `r.Streaming.MinBoost`
      - `r.Kuro.SkeletalMesh.LODDistanceScaleDeviceOffset`
      - `r.Kuro.SkeletalMesh.LODDistanceScale`
      - `r.Streaming.LimitPoolSizeToVRAM`
      - `r.Streaming.PoolSize`
      - `r.Streaming.UseAllMips`
   - Please make sure that `Configure Game Settings` and `Apply Performance Tweaks` in WWMI are **not checked**.
4. Change the in-game **LOD bias** to **Medium** or **High**.

</details>

<details>
<summary><strong>🇨🇳 中文</strong></summary>

# WuWa-Config-Mod

面向**中低端 PC 的 Mod 用户**的《鸣潮》配置文件  

**测试环境：**  
RTX 4060 笔记本显卡（开启 Smooth Motion / AI 插帧的情况下，大多数场景可稳定 **60 FPS 以上**）

1. 使用最新版 **Fixer 3.0** 修复 **LOD hash**  
   👉 [Wuwa_Mod_Fixer](https://github.com/Moonholder/Wuwa_Mod_Fixer/releases/tag/v3.0.0)

2. 然后使用上方提供的 `engine.ini`  
   - **请将WWMI中的以下对应内容设置为与`engine.ini`中相同**  
     - `r.Streaming.MinBoost`  
     - `r.Kuro.SkeletalMesh.LODDistanceScaleDeviceOffset`  
     - `r.Kuro.SkeletalMesh.LODDistanceScale`  
     - `r.Streaming.LimitPoolSizeToVRAM`  
     - `r.Streaming.PoolSize`  
     - `r.Streaming.UseAllMips`
   - 请确保**没有勾选**WWMI中的`Configure Game Settings` 和 `Apply Performance Tweaks`

3. 在游戏内将 **画面细节** 设置为 **中** 或 **高**

</details>


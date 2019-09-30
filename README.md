# VRChatAvatarPrefabs
> 個人製作或修改的一些用於VRChatAvatar的Prefab

## Logo粒子走動路徑 (Logos.unitypackage)
行走散落隨機Unity/Blender/PS的Logo
```
使用
1. "Assets/!items/Logos/Logos3.prefab"丟到Avatar的Body同級

需要修改成其他Logo, 可參考"Assets/!items/Logos/Tex/logos3.png"
```

## 拍手粒子 (PiaParticle.unitypackage)
左右手接觸到一起時播放粒子
```
使用
1. "Assets/!items/PiaParticle/PiaParticleLeft.prefab"丟到Avatar的左手手掌骨骼
2. "Assets/!items/PiaParticle/PiaParticleRight.prefab"丟到Avatar的右手手掌骨骼
3. 將"[右手手掌]/PiaParticleRight"拖到"[左手手掌]/PiaParticleLeft/Trigger"的Particle System裏Triggers的Colliders

需要修改成其他Logo, 可參考"Assets/!items/PiaParticle/logos3.png"
```
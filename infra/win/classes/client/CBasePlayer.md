# CBasePlayer
Class client-side.

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseCombatCharacter](#DT_BaseCombatCharacter)|0 \| 0x0|
|localdata|[DT_LocalPlayerExclusive](#DT_LocalPlayerExclusive)|0 \| 0x0|
|m_hViewModel|array|0 \| 0x0|
|m_iHealth|int|244 \| 0xf4|
|m_fFlags|int|248 \| 0xf8|
|m_hGroundEntity|int|324 \| 0x144|
|m_lifeState|int|855 \| 0x357|
|pl|[DT_PlayerState](#DT_PlayerState)|5576 \| 0x15c8|
|m_iFOV|float|5596 \| 0x15dc|
|m_iFOVStart|float|5600 \| 0x15e0|
|m_ladderSurfaceProps|int|5628 \| 0x15fc|
|m_flFOVTime|float|5636 \| 0x1604|
|m_vecLadderNormal|vector|5656 \| 0x1618|
|m_iBonusProgress|int|5704 \| 0x1648|
|m_iBonusChallenge|int|5708 \| 0x164c|
|m_flMaxspeed|float|5712 \| 0x1650|
|m_hZoomOwner|int|5716 \| 0x1654|
|m_vphysicsCollisionState|int|5732 \| 0x1664|
|m_afPhysicsFlags|int|5892 \| 0x1704|
|m_hVehicle|int|5896 \| 0x1708|
|m_hViewModel[0]|int|5904 \| 0x1710|
|m_hUseEntity|int|5928 \| 0x1728|
|m_iDefaultFOV|float|5932 \| 0x172c|
|m_hViewEntity|int|5944 \| 0x1738|
|m_bShouldDrawPlayerWhileUsingViewEntity|int|5948 \| 0x173c|
|m_iObserverMode|int|5984 \| 0x1760|
|m_hObserverTarget|int|5988 \| 0x1764|
|m_szLastPlaceName|string|6524 \| 0x197c|
|m_ubEFNoInterpParity|int|6560 \| 0x19a0|
|m_hPostProcessCtrl|int|7004 \| 0x1b5c|
|m_hColorCorrectionCtrl|int|7008 \| 0x1b60|
|m_PlayerFog.m_hCtrl|int|7016 \| 0x1b68|

## Recv

### DT_BaseCombatCharacter

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseFlex](#DT_BaseFlex)|0 \| 0x0|
|bcc_localdata|[DT_BCCLocalPlayerExclusive](#DT_BCCLocalPlayerExclusive)|0 \| 0x0|
|m_hActiveWeapon|int|4948 \| 0x1354|

### DT_LocalPlayerExclusive

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nNextThinkTick|int|240 \| 0xf0|
|m_vecViewOffset[0]|float|252 \| 0xfc|
|m_vecViewOffset[1]|float|256 \| 0x100|
|m_vecViewOffset[2]|float|260 \| 0x104|
|m_vecVelocity[0]|float|264 \| 0x108|
|m_vecVelocity[1]|float|268 \| 0x10c|
|m_vecVelocity[2]|float|272 \| 0x110|
|m_vecBaseVelocity|vector|276 \| 0x114|
|m_flFriction|float|312 \| 0x138|
|m_nWaterLevel|int|854 \| 0x356|
|m_iAmmo|[m_iAmmo](#m_iAmmo)|4628 \| 0x1214|
|m_Local|[DT_Local](#DT_Local)|5104 \| 0x13f0|
|m_hTonemapController|int|5572 \| 0x15c4|
|m_hLastWeapon|int|5900 \| 0x170c|
|m_fOnTarget|int|5924 \| 0x1724|
|m_hConstraintEntity|int|5952 \| 0x1740|
|m_vecConstraintCenter|vector|5956 \| 0x1744|
|m_flConstraintRadius|float|5968 \| 0x1750|
|m_flConstraintWidth|float|5972 \| 0x1754|
|m_flConstraintSpeedFactor|float|5976 \| 0x1758|
|m_bConstraintPastRadius|int|5980 \| 0x175c|
|m_flDeathTime|float|6020 \| 0x1784|
|m_nTickBase|int|6248 \| 0x1868|
|m_flLaggedMovementValue|float|6492 \| 0x195c|

### DT_PlayerState

|Prop|Type|Offset|
|---|:-:|:-:|
|deadflag|int|4 \| 0x4|

### DT_BaseFlex

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseAnimatingOverlay](#DT_BaseAnimatingOverlay)|0 \| 0x0|
|m_viewtarget|vector|3616 \| 0xe20|
|m_flexWeight|[m_flexWeight](#m_flexWeight)|3672 \| 0xe58|
|m_blinktoggle|int|4100 \| 0x1004|
|m_vecLean|vector|4512 \| 0x11a0|
|m_vecShift|vector|4568 \| 0x11d8|

### DT_BCCLocalPlayerExclusive

|Prop|Type|Offset|
|---|:-:|:-:|
|m_flNextAttack|float|4624 \| 0x1210|
|m_hMyWeapons|[m_hMyWeapons](#m_hMyWeapons)|4756 \| 0x1294|

### m_iAmmo

|Prop|Type|Offset|
|---|:-:|:-:|
|000|int|0 \| 0x0|
|001|int|4 \| 0x4|
|002|int|8 \| 0x8|
|003|int|12 \| 0xc|
|004|int|16 \| 0x10|
|005|int|20 \| 0x14|
|006|int|24 \| 0x18|
|007|int|28 \| 0x1c|
|008|int|32 \| 0x20|
|009|int|36 \| 0x24|
|010|int|40 \| 0x28|
|011|int|44 \| 0x2c|
|012|int|48 \| 0x30|
|013|int|52 \| 0x34|
|014|int|56 \| 0x38|
|015|int|60 \| 0x3c|
|016|int|64 \| 0x40|
|017|int|68 \| 0x44|
|018|int|72 \| 0x48|
|019|int|76 \| 0x4c|
|020|int|80 \| 0x50|
|021|int|84 \| 0x54|
|022|int|88 \| 0x58|
|023|int|92 \| 0x5c|
|024|int|96 \| 0x60|
|025|int|100 \| 0x64|
|026|int|104 \| 0x68|
|027|int|108 \| 0x6c|
|028|int|112 \| 0x70|
|029|int|116 \| 0x74|
|030|int|120 \| 0x78|
|031|int|124 \| 0x7c|

### DT_Local

|Prop|Type|Offset|
|---|:-:|:-:|
|m_chAreaBits|[m_chAreaBits](#m_chAreaBits)|4 \| 0x4|
|m_chAreaPortalBits|[m_chAreaPortalBits](#m_chAreaPortalBits)|36 \| 0x24|
|m_flFOVRate|float|68 \| 0x44|
|m_bFOVSmooth|int|72 \| 0x48|
|m_iHideHUD|int|76 \| 0x4c|
|m_nDuckTimeMsecs|int|80 \| 0x50|
|m_nDuckJumpTimeMsecs|int|84 \| 0x54|
|m_nJumpTimeMsecs|int|88 \| 0x58|
|m_flFallVelocity|float|92 \| 0x5c|
|m_flStepSize|float|96 \| 0x60|
|m_vecPunchAngle|vector|100 \| 0x64|
|m_vecPunchAngleVel|vector|112 \| 0x70|
|m_bDucked|int|124 \| 0x7c|
|m_bDucking|int|125 \| 0x7d|
|m_bInDuckJump|int|126 \| 0x7e|
|m_bDrawViewmodel|int|128 \| 0x80|
|m_bWearingSuit|int|129 \| 0x81|
|m_bPoisoned|int|130 \| 0x82|
|m_bAllowAutoMovement|int|131 \| 0x83|
|m_skybox3d.scale|int|248 \| 0xf8|
|m_skybox3d.origin|vector|252 \| 0xfc|
|m_skybox3d.area|int|264 \| 0x108|
|m_skybox3d.fog.dirPrimary|vector|272 \| 0x110|
|m_skybox3d.fog.colorPrimary|int|284 \| 0x11c|
|m_skybox3d.fog.colorSecondary|int|288 \| 0x120|
|m_skybox3d.fog.start|float|300 \| 0x12c|
|m_skybox3d.fog.end|float|304 \| 0x130|
|m_skybox3d.fog.maxdensity|float|312 \| 0x138|
|m_skybox3d.fog.enable|int|336 \| 0x150|
|m_skybox3d.fog.blend|int|337 \| 0x151|
|m_skybox3d.fog.HDRColorScale|float|340 \| 0x154|
|m_audio.localSound[0]|vector|348 \| 0x15c|
|m_audio.localSound[1]|vector|360 \| 0x168|
|m_audio.localSound[2]|vector|372 \| 0x174|
|m_audio.localSound[3]|vector|384 \| 0x180|
|m_audio.localSound[4]|vector|396 \| 0x18c|
|m_audio.localSound[5]|vector|408 \| 0x198|
|m_audio.localSound[6]|vector|420 \| 0x1a4|
|m_audio.localSound[7]|vector|432 \| 0x1b0|
|m_audio.soundscapeIndex|int|444 \| 0x1bc|
|m_audio.localBits|int|448 \| 0x1c0|
|m_audio.entIndex|int|452 \| 0x1c4|

### DT_BaseAnimatingOverlay

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseAnimating](#DT_BaseAnimating)|0 \| 0x0|
|overlay_vars|[DT_OverlayVars](#DT_OverlayVars)|0 \| 0x0|

### m_flexWeight

|Prop|Type|Offset|
|---|:-:|:-:|
|000|float|0 \| 0x0|
|001|float|4 \| 0x4|
|002|float|8 \| 0x8|
|003|float|12 \| 0xc|
|004|float|16 \| 0x10|
|005|float|20 \| 0x14|
|006|float|24 \| 0x18|
|007|float|28 \| 0x1c|
|008|float|32 \| 0x20|
|009|float|36 \| 0x24|
|010|float|40 \| 0x28|
|011|float|44 \| 0x2c|
|012|float|48 \| 0x30|
|013|float|52 \| 0x34|
|014|float|56 \| 0x38|
|015|float|60 \| 0x3c|
|016|float|64 \| 0x40|
|017|float|68 \| 0x44|
|018|float|72 \| 0x48|
|019|float|76 \| 0x4c|
|020|float|80 \| 0x50|
|021|float|84 \| 0x54|
|022|float|88 \| 0x58|
|023|float|92 \| 0x5c|
|024|float|96 \| 0x60|
|025|float|100 \| 0x64|
|026|float|104 \| 0x68|
|027|float|108 \| 0x6c|
|028|float|112 \| 0x70|
|029|float|116 \| 0x74|
|030|float|120 \| 0x78|
|031|float|124 \| 0x7c|
|032|float|128 \| 0x80|
|033|float|132 \| 0x84|
|034|float|136 \| 0x88|
|035|float|140 \| 0x8c|
|036|float|144 \| 0x90|
|037|float|148 \| 0x94|
|038|float|152 \| 0x98|
|039|float|156 \| 0x9c|
|040|float|160 \| 0xa0|
|041|float|164 \| 0xa4|
|042|float|168 \| 0xa8|
|043|float|172 \| 0xac|
|044|float|176 \| 0xb0|
|045|float|180 \| 0xb4|
|046|float|184 \| 0xb8|
|047|float|188 \| 0xbc|
|048|float|192 \| 0xc0|
|049|float|196 \| 0xc4|
|050|float|200 \| 0xc8|
|051|float|204 \| 0xcc|
|052|float|208 \| 0xd0|
|053|float|212 \| 0xd4|
|054|float|216 \| 0xd8|
|055|float|220 \| 0xdc|
|056|float|224 \| 0xe0|
|057|float|228 \| 0xe4|
|058|float|232 \| 0xe8|
|059|float|236 \| 0xec|
|060|float|240 \| 0xf0|
|061|float|244 \| 0xf4|
|062|float|248 \| 0xf8|
|063|float|252 \| 0xfc|
|064|float|256 \| 0x100|
|065|float|260 \| 0x104|
|066|float|264 \| 0x108|
|067|float|268 \| 0x10c|
|068|float|272 \| 0x110|
|069|float|276 \| 0x114|
|070|float|280 \| 0x118|
|071|float|284 \| 0x11c|
|072|float|288 \| 0x120|
|073|float|292 \| 0x124|
|074|float|296 \| 0x128|
|075|float|300 \| 0x12c|
|076|float|304 \| 0x130|
|077|float|308 \| 0x134|
|078|float|312 \| 0x138|
|079|float|316 \| 0x13c|
|080|float|320 \| 0x140|
|081|float|324 \| 0x144|
|082|float|328 \| 0x148|
|083|float|332 \| 0x14c|
|084|float|336 \| 0x150|
|085|float|340 \| 0x154|
|086|float|344 \| 0x158|
|087|float|348 \| 0x15c|
|088|float|352 \| 0x160|
|089|float|356 \| 0x164|
|090|float|360 \| 0x168|
|091|float|364 \| 0x16c|
|092|float|368 \| 0x170|
|093|float|372 \| 0x174|
|094|float|376 \| 0x178|
|095|float|380 \| 0x17c|

### m_hMyWeapons

|Prop|Type|Offset|
|---|:-:|:-:|
|000|int|0 \| 0x0|
|001|int|4 \| 0x4|
|002|int|8 \| 0x8|
|003|int|12 \| 0xc|
|004|int|16 \| 0x10|
|005|int|20 \| 0x14|
|006|int|24 \| 0x18|
|007|int|28 \| 0x1c|
|008|int|32 \| 0x20|
|009|int|36 \| 0x24|
|010|int|40 \| 0x28|
|011|int|44 \| 0x2c|
|012|int|48 \| 0x30|
|013|int|52 \| 0x34|
|014|int|56 \| 0x38|
|015|int|60 \| 0x3c|
|016|int|64 \| 0x40|
|017|int|68 \| 0x44|
|018|int|72 \| 0x48|
|019|int|76 \| 0x4c|
|020|int|80 \| 0x50|
|021|int|84 \| 0x54|
|022|int|88 \| 0x58|
|023|int|92 \| 0x5c|
|024|int|96 \| 0x60|
|025|int|100 \| 0x64|
|026|int|104 \| 0x68|
|027|int|108 \| 0x6c|
|028|int|112 \| 0x70|
|029|int|116 \| 0x74|
|030|int|120 \| 0x78|
|031|int|124 \| 0x7c|
|032|int|128 \| 0x80|
|033|int|132 \| 0x84|
|034|int|136 \| 0x88|
|035|int|140 \| 0x8c|
|036|int|144 \| 0x90|
|037|int|148 \| 0x94|
|038|int|152 \| 0x98|
|039|int|156 \| 0x9c|
|040|int|160 \| 0xa0|
|041|int|164 \| 0xa4|
|042|int|168 \| 0xa8|
|043|int|172 \| 0xac|
|044|int|176 \| 0xb0|
|045|int|180 \| 0xb4|
|046|int|184 \| 0xb8|
|047|int|188 \| 0xbc|

### m_chAreaBits

|Prop|Type|Offset|
|---|:-:|:-:|
|000|int|0 \| 0x0|
|001|int|1 \| 0x1|
|002|int|2 \| 0x2|
|003|int|3 \| 0x3|
|004|int|4 \| 0x4|
|005|int|5 \| 0x5|
|006|int|6 \| 0x6|
|007|int|7 \| 0x7|
|008|int|8 \| 0x8|
|009|int|9 \| 0x9|
|010|int|10 \| 0xa|
|011|int|11 \| 0xb|
|012|int|12 \| 0xc|
|013|int|13 \| 0xd|
|014|int|14 \| 0xe|
|015|int|15 \| 0xf|
|016|int|16 \| 0x10|
|017|int|17 \| 0x11|
|018|int|18 \| 0x12|
|019|int|19 \| 0x13|
|020|int|20 \| 0x14|
|021|int|21 \| 0x15|
|022|int|22 \| 0x16|
|023|int|23 \| 0x17|
|024|int|24 \| 0x18|
|025|int|25 \| 0x19|
|026|int|26 \| 0x1a|
|027|int|27 \| 0x1b|
|028|int|28 \| 0x1c|
|029|int|29 \| 0x1d|
|030|int|30 \| 0x1e|
|031|int|31 \| 0x1f|

### m_chAreaPortalBits

|Prop|Type|Offset|
|---|:-:|:-:|
|000|int|0 \| 0x0|
|001|int|1 \| 0x1|
|002|int|2 \| 0x2|
|003|int|3 \| 0x3|
|004|int|4 \| 0x4|
|005|int|5 \| 0x5|
|006|int|6 \| 0x6|
|007|int|7 \| 0x7|
|008|int|8 \| 0x8|
|009|int|9 \| 0x9|
|010|int|10 \| 0xa|
|011|int|11 \| 0xb|
|012|int|12 \| 0xc|
|013|int|13 \| 0xd|
|014|int|14 \| 0xe|
|015|int|15 \| 0xf|
|016|int|16 \| 0x10|
|017|int|17 \| 0x11|
|018|int|18 \| 0x12|
|019|int|19 \| 0x13|
|020|int|20 \| 0x14|
|021|int|21 \| 0x15|
|022|int|22 \| 0x16|
|023|int|23 \| 0x17|

### DT_BaseAnimating

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseEntity](#DT_BaseEntity)|0 \| 0x0|
|serveranimdata|[DT_ServerAnimationData](#DT_ServerAnimationData)|0 \| 0x0|
|m_bClientSideRagdoll|int|881 \| 0x371|
|m_nHitboxSet|int|2696 \| 0xa88|
|m_flPlaybackRate|float|2728 \| 0xaa8|
|m_nSkin|int|2732 \| 0xaac|
|m_nBody|int|2736 \| 0xab0|
|m_nNewSequenceParity|int|2740 \| 0xab4|
|m_nResetEventsParity|int|2744 \| 0xab8|
|m_flEncodedController|[m_flEncodedController](#m_flEncodedController)|2756 \| 0xac4|
|m_nMuzzleFlashParity|int|2772 \| 0xad4|
|m_vecForce|vector|2792 \| 0xae8|
|m_nForceBone|int|2804 \| 0xaf4|
|m_bClientSideFrameReset|int|2856 \| 0xb28|
|m_flFrozen|float|2860 \| 0xb2c|
|m_flModelScale|float|2940 \| 0xb7c|
|m_ScaleType|int|2944 \| 0xb80|
|m_flPoseParameter|[m_flPoseParameter](#m_flPoseParameter)|2988 \| 0xbac|
|m_bClientSideAnimation|int|3284 \| 0xcd4|
|m_nSequence|int|3316 \| 0xcf4|
|m_hLightingOrigin|int|3452 \| 0xd7c|
|m_bSuppressAnimSounds|int|3458 \| 0xd82|

### DT_OverlayVars

|Prop|Type|Offset|
|---|:-:|:-:|
|m_AnimOverlay|[_ST_m_AnimOverlay_15](#_ST_m_AnimOverlay_15)|0 \| 0x0|

### DT_BaseEntity

|Prop|Type|Offset|
|---|:-:|:-:|
|AnimTimeMustBeFirst|[DT_AnimTimeMustBeFirst](#DT_AnimTimeMustBeFirst)|0 \| 0x0|
|movecollide|int|0 \| 0x0|
|movetype|int|0 \| 0x0|
|m_clrRender|int|108 \| 0x6c|
|m_cellbits|int|112 \| 0x70|
|m_cellX|int|120 \| 0x78|
|m_cellY|int|124 \| 0x7c|
|m_cellZ|int|128 \| 0x80|
|m_fEffects|int|232 \| 0xe8|
|m_iTeamNum|int|236 \| 0xec|
|m_angRotation|vector|288 \| 0x120|
|m_vecOrigin|vector|300 \| 0x12c|
|moveparent|int|316 \| 0x13c|
|m_hOwnerEntity|int|320 \| 0x140|
|m_iName|string|328 \| 0x148|
|m_iSignifierName|string|588 \| 0x24c|
|m_nModelIndex|int|848 \| 0x350|
|m_nRenderFX|int|850 \| 0x352|
|m_nRenderMode|int|851 \| 0x353|
|m_flSimulationTime|int|864 \| 0x360|
|m_iObjectCapsCache|int|960 \| 0x3c0|
|m_iParentAttachment|int|992 \| 0x3e0|
|m_fadeMinDist|float|1000 \| 0x3e8|
|m_fadeMaxDist|float|1004 \| 0x3ec|
|m_flFadeScale|float|1008 \| 0x3f0|
|m_Collision|[DT_CollisionProperty](#DT_CollisionProperty)|1040 \| 0x410|
|m_flElasticity|float|1168 \| 0x490|
|m_flShadowCastDistance|float|1172 \| 0x494|
|m_CollisionGroup|int|1384 \| 0x568|
|m_bSimulatedEveryTick|int|2606 \| 0xa2e|
|m_bAnimatedEveryTick|int|2607 \| 0xa2f|
|m_bAlternateSorting|int|2608 \| 0xa30|
|m_nMinCPULevel|int|2609 \| 0xa31|
|m_nMaxCPULevel|int|2610 \| 0xa32|
|m_nMinGPULevel|int|2611 \| 0xa33|
|m_nMaxGPULevel|int|2612 \| 0xa34|
|m_iTextureFrameIndex|int|2613 \| 0xa35|
|m_hEffectEntity|int|2624 \| 0xa40|

### DT_ServerAnimationData

|Prop|Type|Offset|
|---|:-:|:-:|
|m_flCycle|float|2724 \| 0xaa4|

### m_flEncodedController

|Prop|Type|Offset|
|---|:-:|:-:|
|000|float|0 \| 0x0|
|001|float|4 \| 0x4|
|002|float|8 \| 0x8|
|003|float|12 \| 0xc|

### m_flPoseParameter

|Prop|Type|Offset|
|---|:-:|:-:|
|000|float|0 \| 0x0|
|001|float|4 \| 0x4|
|002|float|8 \| 0x8|
|003|float|12 \| 0xc|
|004|float|16 \| 0x10|
|005|float|20 \| 0x14|
|006|float|24 \| 0x18|
|007|float|28 \| 0x1c|
|008|float|32 \| 0x20|
|009|float|36 \| 0x24|
|010|float|40 \| 0x28|
|011|float|44 \| 0x2c|
|012|float|48 \| 0x30|
|013|float|52 \| 0x34|
|014|float|56 \| 0x38|
|015|float|60 \| 0x3c|
|016|float|64 \| 0x40|
|017|float|68 \| 0x44|
|018|float|72 \| 0x48|
|019|float|76 \| 0x4c|
|020|float|80 \| 0x50|
|021|float|84 \| 0x54|
|022|float|88 \| 0x58|
|023|float|92 \| 0x5c|

### _ST_m_AnimOverlay_15

|Prop|Type|Offset|
|---|:-:|:-:|
|000|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|001|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|002|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|003|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|004|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|005|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|006|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|007|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|008|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|009|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|010|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|011|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|012|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|013|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|014|[DT_Animationlayer](#DT_Animationlayer)|0 \| 0x0|
|lengthproxy|[_LPT_m_AnimOverlay_15](#_LPT_m_AnimOverlay_15)|0 \| 0x0|

### DT_AnimTimeMustBeFirst

|Prop|Type|Offset|
|---|:-:|:-:|
|m_flAnimTime|int|856 \| 0x358|

### DT_CollisionProperty

|Prop|Type|Offset|
|---|:-:|:-:|
|m_vecMins|vector|8 \| 0x8|
|m_vecMaxs|vector|20 \| 0x14|
|m_usSolidFlags|int|32 \| 0x20|
|m_nSolidType|int|34 \| 0x22|
|m_triggerBloat|int|35 \| 0x23|
|m_nSurroundType|int|42 \| 0x2a|
|m_vecSpecifiedSurroundingMins|vector|44 \| 0x2c|
|m_vecSpecifiedSurroundingMaxs|vector|56 \| 0x38|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### DT_Animationlayer

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nOrder|int|8 \| 0x8|
|m_nSequence|int|12 \| 0xc|
|m_flPrevCycle|float|16 \| 0x10|
|m_flWeight|float|20 \| 0x14|
|m_flCycle|float|28 \| 0x1c|

### _LPT_m_AnimOverlay_15

|Prop|Type|Offset|
|---|:-:|:-:|
|lengthprop15|int|0 \| 0x0|
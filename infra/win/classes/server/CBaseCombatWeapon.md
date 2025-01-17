# CBaseCombatWeapon

Class server-side.

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseAnimating](#dt_baseanimating)|0 \| 0x0|
|LocalActiveWeaponData|[DT_LocalActiveWeaponData](#dt_localactiveweapondata)|0 \| 0x0|
|LocalWeaponData|[DT_LocalWeaponData](#dt_localweapondata)|0 \| 0x0|
|m_hOwner|int|1204 \| 0x4b4|
|m_iViewModelIndex|int|1220 \| 0x4c4|
|m_iWorldModelIndex|int|1224 \| 0x4c8|
|m_iState|int|1228 \| 0x4cc|

## Recv

### DT_BaseAnimating

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseEntity](#dt_baseentity)|0 \| 0x0|
|serveranimdata|[DT_ServerAnimationData](#dt_serveranimationdata)|0 \| 0x0|
|m_bClientSideRagdoll|int|552 \| 0x228|
|m_nForceBone|int|880 \| 0x370|
|m_vecForce|vector|884 \| 0x374|
|m_nSkin|int|896 \| 0x380|
|m_nBody|int|900 \| 0x384|
|m_nHitboxSet|int|904 \| 0x388|
|m_flModelScale|float|908 \| 0x38c|
|m_flPlaybackRate|float|912 \| 0x390|
|m_ScaleType|int|916 \| 0x394|
|m_nSequence|int|960 \| 0x3c0|
|m_flPoseParameter|[m_flPoseParameter](#m_flposeparameter)|964 \| 0x3c4|
|m_flEncodedController|[m_flEncodedController](#m_flencodedcontroller)|1060 \| 0x424|
|m_bClientSideAnimation|int|1076 \| 0x434|
|m_bClientSideFrameReset|int|1077 \| 0x435|
|m_nNewSequenceParity|int|1080 \| 0x438|
|m_nResetEventsParity|int|1084 \| 0x43c|
|m_bSuppressAnimSounds|int|1088 \| 0x440|
|m_nMuzzleFlashParity|int|1089 \| 0x441|
|m_hLightingOrigin|int|1092 \| 0x444|
|m_flFrozen|float|1116 \| 0x45c|

### DT_LocalActiveWeaponData

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nNextThinkTick|int|164 \| 0xa4|
|m_flNextPrimaryAttack|float|1212 \| 0x4bc|
|m_flNextSecondaryAttack|float|1216 \| 0x4c0|
|m_flTimeWeaponIdle|float|1248 \| 0x4e0|

### DT_LocalWeaponData

|Prop|Type|Offset|
|---|:-:|:-:|
|m_nViewModelIndex|int|1208 \| 0x4b8|
|m_iPrimaryAmmoType|int|1232 \| 0x4d0|
|m_iSecondaryAmmoType|int|1236 \| 0x4d4|
|m_iClip1|int|1240 \| 0x4d8|
|m_iClip2|int|1244 \| 0x4dc|

### DT_BaseEntity

|Prop|Type|Offset|
|---|:-:|:-:|
|AnimTimeMustBeFirst|[DT_AnimTimeMustBeFirst](#dt_animtimemustbefirst)|0 \| 0x0|
|m_iObjectCapsCache|int|4 \| 0x4|
|m_flSimulationTime|int|108 \| 0x6c|
|m_fEffects|int|168 \| 0xa8|
|m_nRenderFX|int|184 \| 0xb8|
|m_nRenderMode|int|185 \| 0xb9|
|m_nModelIndex|int|186 \| 0xba|
|m_clrRender|int|188 \| 0xbc|
|m_iName|string|208 \| 0xd0|
|m_iParentAttachment|int|217 \| 0xd9|
|movetype|int|218 \| 0xda|
|movecollide|int|219 \| 0xdb|
|moveparent|int|220 \| 0xdc|
|m_Collision|[DT_CollisionProperty](#dt_collisionproperty)|232 \| 0xe8|
|m_hOwnerEntity|int|324 \| 0x144|
|m_CollisionGroup|int|328 \| 0x148|
|m_flElasticity|float|440 \| 0x1b8|
|m_iTextureFrameIndex|int|500 \| 0x1f4|
|m_bSimulatedEveryTick|int|501 \| 0x1f5|
|m_bAnimatedEveryTick|int|502 \| 0x1f6|
|m_bAlternateSorting|int|503 \| 0x1f7|
|m_nMinCPULevel|int|504 \| 0x1f8|
|m_nMaxCPULevel|int|505 \| 0x1f9|
|m_nMinGPULevel|int|506 \| 0x1fa|
|m_nMaxGPULevel|int|507 \| 0x1fb|
|m_cellbits|int|684 \| 0x2ac|
|m_cellX|int|688 \| 0x2b0|
|m_cellY|int|692 \| 0x2b4|
|m_cellZ|int|696 \| 0x2b8|
|m_vecOrigin|vector|700 \| 0x2bc|
|m_angRotation|vector|712 \| 0x2c8|
|m_iTeamNum|int|756 \| 0x2f4|
|m_hEffectEntity|int|776 \| 0x308|
|m_fadeMinDist|float|780 \| 0x30c|
|m_fadeMaxDist|float|784 \| 0x310|
|m_flFadeScale|float|788 \| 0x314|
|m_flShadowCastDistance|float|792 \| 0x318|
|m_iSignifierName|string|800 \| 0x320|

### DT_ServerAnimationData

|Prop|Type|Offset|
|---|:-:|:-:|
|m_flCycle|float|956 \| 0x3bc|

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

### m_flEncodedController

|Prop|Type|Offset|
|---|:-:|:-:|
|000|float|0 \| 0x0|
|001|float|4 \| 0x4|
|002|float|8 \| 0x8|
|003|float|12 \| 0xc|

### DT_AnimTimeMustBeFirst

|Prop|Type|Offset|
|---|:-:|:-:|
|m_flAnimTime|int|104 \| 0x68|

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

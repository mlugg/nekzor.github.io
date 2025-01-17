# CSceneEntity

Class client-side.

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseEntity](#dt_baseentity)|0 \| 0x0|
|m_hActorList|[_ST_m_hActorList_16](#_st_m_hactorlist_16)|0 \| 0x0|
|m_bIsPlayingBack|int|2692 \| 0xa84|
|m_bPaused|int|2693 \| 0xa85|
|m_bMultiplayer|int|2694 \| 0xa86|
|m_flForceClientTime|float|2700 \| 0xa8c|
|m_nSceneStringIndex|int|2704 \| 0xa90|

## Recv

### DT_BaseEntity

|Prop|Type|Offset|
|---|:-:|:-:|
|AnimTimeMustBeFirst|[DT_AnimTimeMustBeFirst](#dt_animtimemustbefirst)|0 \| 0x0|
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
|m_Collision|[DT_CollisionProperty](#dt_collisionproperty)|1040 \| 0x410|
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

### _ST_m_hActorList_16

|Prop|Type|Offset|
|---|:-:|:-:|
|000|int|0 \| 0x0|
|001|int|0 \| 0x0|
|002|int|0 \| 0x0|
|003|int|0 \| 0x0|
|004|int|0 \| 0x0|
|005|int|0 \| 0x0|
|006|int|0 \| 0x0|
|007|int|0 \| 0x0|
|008|int|0 \| 0x0|
|009|int|0 \| 0x0|
|010|int|0 \| 0x0|
|011|int|0 \| 0x0|
|012|int|0 \| 0x0|
|013|int|0 \| 0x0|
|014|int|0 \| 0x0|
|015|int|0 \| 0x0|
|lengthproxy|[_LPT_m_hActorList_16](#_lpt_m_hactorlist_16)|0 \| 0x0|

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

### _LPT_m_hActorList_16

|Prop|Type|Offset|
|---|:-:|:-:|
|lengthprop16|int|0 \| 0x0|

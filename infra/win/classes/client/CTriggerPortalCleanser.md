# CTriggerPortalCleanser
Class client-side.

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseTrigger](#DT_BaseTrigger)|0 \| 0x0|
|m_bObject1InRange|int|2748 \| 0xabc|
|m_bObject2InRange|int|2749 \| 0xabd|
|m_hObject1|int|2752 \| 0xac0|
|m_hObject2|int|2756 \| 0xac4|
|m_bDisabled|int|2760 \| 0xac8|
|m_bVisible|int|2768 \| 0xad0|
|m_bUseScanline|int|2769 \| 0xad1|
|m_bPlayersPassTriggerFilters|int|2770 \| 0xad2|
|m_flPortalShotTime|float|2772 \| 0xad4|

## Recv

### DT_BaseTrigger

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseToggle](#DT_BaseToggle)|0 \| 0x0|
|m_spawnflags|int|956 \| 0x3bc|
|m_bClientSidePredicted|int|2736 \| 0xab0|

### DT_BaseToggle

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseEntity](#DT_BaseEntity)|0 \| 0x0|
|m_vecFinalDest|vector|2708 \| 0xa94|
|m_movementType|int|2720 \| 0xaa0|
|m_flMoveTargetTime|float|2724 \| 0xaa4|

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
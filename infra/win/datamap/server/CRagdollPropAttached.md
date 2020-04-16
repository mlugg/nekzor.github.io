# CRagdollPropAttached
Datamap server-side.

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|CBaseEntityScriptThink|void|0 \| 0x0||
|CBaseEntityShadowCastDistThink|void|0 \| 0x0||
|CBaseEntitySUB_CallUseToggle|void|0 \| 0x0||
|CBaseEntitySUB_DoNothing|void|0 \| 0x0||
|CBaseEntitySUB_FadeOut|void|0 \| 0x0||
|CBaseEntitySUB_Remove|void|0 \| 0x0||
|CBaseEntitySUB_StartFadeOut|void|0 \| 0x0||
|CBaseEntitySUB_StartFadeOutInstant|void|0 \| 0x0||
|CBaseEntitySUB_Vanish|void|0 \| 0x0||
|CRagdollPropClearFlagsThink|void|0 \| 0x0||
|CRagdollPropFadeOutThink|void|0 \| 0x0||
|CRagdollPropSetDebrisThink|void|0 \| 0x0||
|InputAddContext|string|0 \| 0x0|AddContext|
|InputAddOutput|string|0 \| 0x0|AddOutput|
|InputAlpha|integer|0 \| 0x0|Alpha|
|InputAlternativeSorting|boolean|0 \| 0x0|AlternativeSorting|
|InputBecomeRagdoll|void|0 \| 0x0|BecomeRagdoll|
|InputCallScriptFunction|string|0 \| 0x0|CallScriptFunction|
|InputClearContext|string|0 \| 0x0|ClearContext|
|InputClearParent|void|0 \| 0x0|ClearParent|
|InputColor|color32|0 \| 0x0|Color|
|InputDisableDamageForces|void|0 \| 0x0|DisableDamageForces|
|InputDisableDraw|void|0 \| 0x0|DisableDraw|
|InputDisableDrawInFastReflection|void|0 \| 0x0|DisableDrawInFastReflection|
|InputDisableMotion|void|0 \| 0x0|DisableMotion|
|InputDisableReceivingFlashlight|void|0 \| 0x0|DisableReceivingFlashlight|
|InputDisableShadow|void|0 \| 0x0|DisableShadow|
|InputDispatchResponse|string|0 \| 0x0|DispatchResponse|
|InputEnableDamageForces|void|0 \| 0x0|EnableDamageForces|
|InputEnableDraw|void|0 \| 0x0|EnableDraw|
|InputEnableDrawInFastReflection|void|0 \| 0x0|EnableDrawInFastReflection|
|InputEnableMotion|void|0 \| 0x0|EnableMotion|
|InputEnableReceivingFlashlight|void|0 \| 0x0|EnableReceivingFlashlight|
|InputEnableShadow|void|0 \| 0x0|EnableShadow|
|InputFadeAndRemove|float|0 \| 0x0|FadeAndRemove|
|InputFireUser1|string|0 \| 0x0|FireUser1|
|InputFireUser2|string|0 \| 0x0|FireUser2|
|InputFireUser3|string|0 \| 0x0|FireUser3|
|InputFireUser4|string|0 \| 0x0|FireUser4|
|InputIgnite|float|0 \| 0x0|IgniteHitboxFireScale|
|InputIgnite|integer|0 \| 0x0|IgniteNumHitboxFires|
|InputIgnite|void|0 \| 0x0|Ignite|
|InputIgniteLifetime|float|0 \| 0x0|IgniteLifetime|
|InputKill|void|0 \| 0x0|Kill|
|InputKillHierarchy|void|0 \| 0x0|KillHierarchy|
|InputRemoveContext|string|0 \| 0x0|RemoveContext|
|InputRemovePaint|void|0 \| 0x0|RemovePaint|
|InputRunScript|string|0 \| 0x0|RunScriptCode|
|InputRunScriptFile|string|0 \| 0x0|RunScriptFile|
|InputSetDamageFilter|string|0 \| 0x0|SetDamageFilter|
|InputSetLightingOrigin|string|0 \| 0x0|SetLightingOrigin|
|InputSetLightingOriginRelative|string|0 \| 0x0|SetLightingOriginHack|
|InputSetLocalAngles|string|0 \| 0x0|SetLocalAngles|
|InputSetLocalOrigin|string|0 \| 0x0|SetLocalOrigin|
|InputSetParent|string|0 \| 0x0|SetParent|
|InputSetParentAttachment|string|0 \| 0x0|SetParentAttachment|
|InputSetParentAttachmentMaintainOffset|string|0 \| 0x0|SetParentAttachmentMaintainOffset|
|InputSetTeam|integer|0 \| 0x0|SetTeam|
|InputStartRadgollBoogie|void|0 \| 0x0|StartRagdollBoogie|
|InputTurnOff|void|0 \| 0x0|Disable|
|InputTurnOn|void|0 \| 0x0|Enable|
|InputUse|void|0 \| 0x0|Use|
|m_iObjectCapsCache|integer|4 \| 0x4||
|m_pfnMoveDone|function|8 \| 0x8||
|m_pfnThink|function|12 \| 0xc||
|m_Network|[CServerNetworkProperty](#CServerNetworkProperty)|16 \| 0x10||
|m_iClassname|string|96 \| 0x60|classname|
|m_flPrevAnimTime|time|100 \| 0x64||
|m_flAnimTime|time|104 \| 0x68||
|m_flSimulationTime|time|108 \| 0x6c||
|m_nLastThinkTick|tick|112 \| 0x70||
|touchStamp|integer|116 \| 0x74||
|m_aThinkFunctions|custom|120 \| 0x78||
|m_ResponseContexts|custom|140 \| 0x8c||
|m_iszResponseContext|string|160 \| 0xa0|ResponseContext|
|m_nNextThinkTick|tick|164 \| 0xa4|nextthink|
|m_fEffects|integer|168 \| 0xa8|effects|
|m_ModelName|modelname|172 \| 0xac|model|
|m_target|string|180 \| 0xb4|target|
|m_nRenderFX|character|184 \| 0xb8|renderfx|
|m_nRenderMode|character|185 \| 0xb9|rendermode|
|m_nModelIndex|short|186 \| 0xba|modelindex|
|m_clrRender|color32|188 \| 0xbc|rendercolor|
|m_nSimulationTick|tick|192 \| 0xc0||
|m_iEFlags|integer|200 \| 0xc8||
|m_fFlags|integer|204 \| 0xcc||
|m_iName|string|208 \| 0xd0||
|m_pParent|ehandle|212 \| 0xd4||
|m_nTransmitStateOwnedCounter|character|216 \| 0xd8||
|m_iParentAttachment|character|217 \| 0xd9||
|m_MoveType|character|218 \| 0xda|MoveType|
|m_MoveCollide|character|219 \| 0xdb||
|m_hMoveParent|ehandle|220 \| 0xdc||
|m_hMoveChild|ehandle|224 \| 0xe0||
|m_hMovePeer|ehandle|228 \| 0xe4||
|m_Collision|[CCollisionProperty](#CCollisionProperty)|232 \| 0xe8||
|m_hOwnerEntity|ehandle|324 \| 0x144||
|m_CollisionGroup|integer|328 \| 0x148|CollisionGroup|
|m_pPhysicsObject|custom|332 \| 0x14c||
|m_nWaterType|character|338 \| 0x152||
|m_nWaterLevel|character|339 \| 0x153|waterlevel|
|m_flNavIgnoreUntilTime|time|340 \| 0x154||
|m_hGroundEntity|ehandle|344 \| 0x158||
|m_flGroundChangeTime|time|348 \| 0x15c||
|m_vecBaseVelocity|vector|352 \| 0x160|basevelocity|
|m_vecAbsVelocity|vector|364 \| 0x16c||
|m_vecAngVelocity|vector|376 \| 0x178|avelocity|
|m_rgflCoordinateFrame|float|388 \| 0x184||
|m_flFriction|float|436 \| 0x1b4|friction|
|m_flElasticity|float|440 \| 0x1b8||
|m_flLocalTime|float|444 \| 0x1bc|ltime|
|m_flVPhysicsUpdateLocalTime|float|448 \| 0x1c0||
|m_flMoveDoneTime|float|452 \| 0x1c4||
|m_vecAbsOrigin|pos-vector|460 \| 0x1cc||
|m_angAbsRotation|vector|472 \| 0x1d8||
|m_vecVelocity|vector|484 \| 0x1e4|velocity|
|m_pBlocker|ehandle|496 \| 0x1f0||
|m_iTextureFrameIndex|character|500 \| 0x1f4|texframeindex|
|m_bSimulatedEveryTick|boolean|501 \| 0x1f5||
|m_bAnimatedEveryTick|boolean|502 \| 0x1f6||
|m_bAlternateSorting|boolean|503 \| 0x1f7||
|m_nMinCPULevel|character|504 \| 0x1f8|mincpulevel|
|m_nMaxCPULevel|character|505 \| 0x1f9|maxcpulevel|
|m_nMinGPULevel|character|506 \| 0x1fa|mingpulevel|
|m_nMaxGPULevel|character|507 \| 0x1fb|maxgpulevel|
|m_iGlobalname|string|508 \| 0x1fc|globalname|
|m_iParent|string|512 \| 0x200|parentname|
|m_iHammerID|integer|516 \| 0x204|hammerid|
|m_flSpeed|float|520 \| 0x208|speed|
|m_iMaxHealth|integer|524 \| 0x20c|max_health|
|m_iHealth|integer|528 \| 0x210|health|
|m_iszDamageFilterName|string|532 \| 0x214|damagefilter|
|m_hDamageFilter|ehandle|536 \| 0x218||
|m_pfnTouch|function|540 \| 0x21c||
|m_pfnUse|function|544 \| 0x220||
|m_pfnBlocked|function|548 \| 0x224||
|m_bClientSideRagdoll|boolean|552 \| 0x228||
|m_lifeState|character|553 \| 0x229||
|m_takedamage|character|554 \| 0x22a||
|m_OnUser1|custom|560 \| 0x230|OnUser1|
|m_OnUser2|custom|584 \| 0x248|OnUser2|
|m_OnUser3|custom|608 \| 0x260|OnUser3|
|m_OnUser4|custom|632 \| 0x278|OnUser4|
|m_vecOrigin|vector|700 \| 0x2bc||
|m_angRotation|vector|712 \| 0x2c8||
|m_vecViewOffset|vector|728 \| 0x2d8|view_ofs|
|m_iInitialTeamNum|integer|752 \| 0x2f0|TeamNum|
|m_iTeamNum|integer|756 \| 0x2f4|teamnumber|
|m_spawnflags|integer|764 \| 0x2fc|spawnflags|
|m_AIAddOn|string|768 \| 0x300|addon|
|m_flGravity|float|772 \| 0x304|gravity|
|m_hEffectEntity|ehandle|776 \| 0x308||
|m_fadeMinDist|float|780 \| 0x30c|fademindist|
|m_fadeMaxDist|float|784 \| 0x310|fademaxdist|
|m_flFadeScale|float|788 \| 0x314|fadescale|
|m_flShadowCastDistance|float|792 \| 0x318|shadowcastdist|
|m_flDesiredShadowCastDistance|float|796 \| 0x31c||
|m_iSignifierName|string|800 \| 0x320||
|m_bLagCompensate|boolean|805 \| 0x325|LagCompensate|
|m_bForcePurgeFixedupStrings|boolean|806 \| 0x326||
|m_debugOverlays|integer|812 \| 0x32c||
|m_iszVScripts|string|820 \| 0x334|vscripts|
|m_iszScriptThinkFunction|string|824 \| 0x338|thinkfunction|
|m_iszScriptId|string|852 \| 0x354||
|m_flGroundSpeed|float|864 \| 0x360||
|m_flLastEventCheck|time|868 \| 0x364||
|m_nSkin|integer|896 \| 0x380|ModelSkin|
|m_nSkin|integer|896 \| 0x380|skin|
|m_nBody|integer|900 \| 0x384|SetBodyGroup|
|m_nBody|integer|900 \| 0x384|body|
|m_nHitboxSet|integer|904 \| 0x388|hitboxset|
|m_flModelScale|float|908 \| 0x38c|ModelScale|
|m_flPlaybackRate|float|912 \| 0x390|playbackrate|
|m_pIk|custom|940 \| 0x3ac||
|m_iIKCounter|integer|944 \| 0x3b0||
|m_bSequenceFinished|boolean|948 \| 0x3b4||
|m_bSequenceLoops|boolean|949 \| 0x3b5||
|m_flDissolveStartTime|time|952 \| 0x3b8||
|m_flCycle|float|956 \| 0x3bc|cycle|
|m_nSequence|integer|960 \| 0x3c0|sequence|
|m_flPoseParameter|float|964 \| 0x3c4||
|m_flEncodedController|float|1060 \| 0x424||
|m_bClientSideAnimation|boolean|1076 \| 0x434||
|m_bClientSideFrameReset|boolean|1077 \| 0x435||
|m_nNewSequenceParity|integer|1080 \| 0x438||
|m_nResetEventsParity|integer|1084 \| 0x43c||
|m_bSuppressAnimSounds|boolean|1088 \| 0x440|SuppressAnimSounds|
|m_nMuzzleFlashParity|character|1089 \| 0x441||
|m_hLightingOrigin|ehandle|1092 \| 0x444||
|m_hLightingOriginRelative|ehandle|1096 \| 0x448||
|m_iszLightingOriginRelative|string|1100 \| 0x44c|LightingOriginHack|
|m_iszLightingOrigin|string|1104 \| 0x450|LightingOrigin|
|m_fBoneCacheFlags|short|1112 \| 0x458||
|m_flFrozen|float|1116 \| 0x45c||
|m_flFrozenThawRate|float|1128 \| 0x468||
|m_flFrozenMax|float|1132 \| 0x46c||
|m_OnIgnite|custom|1136 \| 0x470|OnIgnite|
|m_OnFizzled|custom|1160 \| 0x488|OnFizzled|
|m_ragdoll.listCount|integer|1208 \| 0x4b8||
|m_ragdoll.allowStretch|boolean|1212 \| 0x4bc||
|m_ragdoll.pGroup|custom|1216 \| 0x4c0||
|m_ragdoll.list[1].originParentSpace|vector|1244 \| 0x4dc||
|m_ragdoll.list[1].pObject|custom|1256 \| 0x4e8||
|m_ragdoll.list[1].pConstraint|custom|1260 \| 0x4ec||
|m_ragdoll.list[1].parentIndex|integer|1264 \| 0x4f0||
|m_ragdoll.list[2].originParentSpace|vector|1268 \| 0x4f4||
|m_ragdoll.list[2].pObject|custom|1280 \| 0x500||
|m_ragdoll.list[2].pConstraint|custom|1284 \| 0x504||
|m_ragdoll.list[2].parentIndex|integer|1288 \| 0x508||
|m_ragdoll.list[3].originParentSpace|vector|1292 \| 0x50c||
|m_ragdoll.list[3].pObject|custom|1304 \| 0x518||
|m_ragdoll.list[3].pConstraint|custom|1308 \| 0x51c||
|m_ragdoll.list[3].parentIndex|integer|1312 \| 0x520||
|m_ragdoll.list[4].originParentSpace|vector|1316 \| 0x524||
|m_ragdoll.list[4].pObject|custom|1328 \| 0x530||
|m_ragdoll.list[4].pConstraint|custom|1332 \| 0x534||
|m_ragdoll.list[4].parentIndex|integer|1336 \| 0x538||
|m_ragdoll.list[5].originParentSpace|vector|1340 \| 0x53c||
|m_ragdoll.list[5].pObject|custom|1352 \| 0x548||
|m_ragdoll.list[5].pConstraint|custom|1356 \| 0x54c||
|m_ragdoll.list[5].parentIndex|integer|1360 \| 0x550||
|m_ragdoll.list[6].originParentSpace|vector|1364 \| 0x554||
|m_ragdoll.list[6].pObject|custom|1376 \| 0x560||
|m_ragdoll.list[6].pConstraint|custom|1380 \| 0x564||
|m_ragdoll.list[6].parentIndex|integer|1384 \| 0x568||
|m_ragdoll.list[7].originParentSpace|vector|1388 \| 0x56c||
|m_ragdoll.list[7].pObject|custom|1400 \| 0x578||
|m_ragdoll.list[7].pConstraint|custom|1404 \| 0x57c||
|m_ragdoll.list[7].parentIndex|integer|1408 \| 0x580||
|m_ragdoll.list[8].originParentSpace|vector|1412 \| 0x584||
|m_ragdoll.list[8].pObject|custom|1424 \| 0x590||
|m_ragdoll.list[8].pConstraint|custom|1428 \| 0x594||
|m_ragdoll.list[8].parentIndex|integer|1432 \| 0x598||
|m_ragdoll.list[9].originParentSpace|vector|1436 \| 0x59c||
|m_ragdoll.list[9].pObject|custom|1448 \| 0x5a8||
|m_ragdoll.list[9].pConstraint|custom|1452 \| 0x5ac||
|m_ragdoll.list[9].parentIndex|integer|1456 \| 0x5b0||
|m_ragdoll.list[10].originParentSpace|vector|1460 \| 0x5b4||
|m_ragdoll.list[10].pObject|custom|1472 \| 0x5c0||
|m_ragdoll.list[10].pConstraint|custom|1476 \| 0x5c4||
|m_ragdoll.list[10].parentIndex|integer|1480 \| 0x5c8||
|m_ragdoll.list[11].originParentSpace|vector|1484 \| 0x5cc||
|m_ragdoll.list[11].pObject|custom|1496 \| 0x5d8||
|m_ragdoll.list[11].pConstraint|custom|1500 \| 0x5dc||
|m_ragdoll.list[11].parentIndex|integer|1504 \| 0x5e0||
|m_ragdoll.list[12].originParentSpace|vector|1508 \| 0x5e4||
|m_ragdoll.list[12].pObject|custom|1520 \| 0x5f0||
|m_ragdoll.list[12].pConstraint|custom|1524 \| 0x5f4||
|m_ragdoll.list[12].parentIndex|integer|1528 \| 0x5f8||
|m_ragdoll.list[13].originParentSpace|vector|1532 \| 0x5fc||
|m_ragdoll.list[13].pObject|custom|1544 \| 0x608||
|m_ragdoll.list[13].pConstraint|custom|1548 \| 0x60c||
|m_ragdoll.list[13].parentIndex|integer|1552 \| 0x610||
|m_ragdoll.list[14].originParentSpace|vector|1556 \| 0x614||
|m_ragdoll.list[14].pObject|custom|1568 \| 0x620||
|m_ragdoll.list[14].pConstraint|custom|1572 \| 0x624||
|m_ragdoll.list[14].parentIndex|integer|1576 \| 0x628||
|m_ragdoll.list[15].originParentSpace|vector|1580 \| 0x62c||
|m_ragdoll.list[15].pObject|custom|1592 \| 0x638||
|m_ragdoll.list[15].pConstraint|custom|1596 \| 0x63c||
|m_ragdoll.list[15].parentIndex|integer|1600 \| 0x640||
|m_ragdoll.list[16].originParentSpace|vector|1604 \| 0x644||
|m_ragdoll.list[16].pObject|custom|1616 \| 0x650||
|m_ragdoll.list[16].pConstraint|custom|1620 \| 0x654||
|m_ragdoll.list[16].parentIndex|integer|1624 \| 0x658||
|m_ragdoll.list[17].originParentSpace|vector|1628 \| 0x65c||
|m_ragdoll.list[17].pObject|custom|1640 \| 0x668||
|m_ragdoll.list[17].pConstraint|custom|1644 \| 0x66c||
|m_ragdoll.list[17].parentIndex|integer|1648 \| 0x670||
|m_ragdoll.list[18].originParentSpace|vector|1652 \| 0x674||
|m_ragdoll.list[18].pObject|custom|1664 \| 0x680||
|m_ragdoll.list[18].pConstraint|custom|1668 \| 0x684||
|m_ragdoll.list[18].parentIndex|integer|1672 \| 0x688||
|m_ragdoll.list[19].originParentSpace|vector|1676 \| 0x68c||
|m_ragdoll.list[19].pObject|custom|1688 \| 0x698||
|m_ragdoll.list[19].pConstraint|custom|1692 \| 0x69c||
|m_ragdoll.list[19].parentIndex|integer|1696 \| 0x6a0||
|m_ragdoll.list[20].originParentSpace|vector|1700 \| 0x6a4||
|m_ragdoll.list[20].pObject|custom|1712 \| 0x6b0||
|m_ragdoll.list[20].pConstraint|custom|1716 \| 0x6b4||
|m_ragdoll.list[20].parentIndex|integer|1720 \| 0x6b8||
|m_ragdoll.list[21].originParentSpace|vector|1724 \| 0x6bc||
|m_ragdoll.list[21].pObject|custom|1736 \| 0x6c8||
|m_ragdoll.list[21].pConstraint|custom|1740 \| 0x6cc||
|m_ragdoll.list[21].parentIndex|integer|1744 \| 0x6d0||
|m_ragdoll.list[22].originParentSpace|vector|1748 \| 0x6d4||
|m_ragdoll.list[22].pObject|custom|1760 \| 0x6e0||
|m_ragdoll.list[22].pConstraint|custom|1764 \| 0x6e4||
|m_ragdoll.list[22].parentIndex|integer|1768 \| 0x6e8||
|m_ragdoll.list[23].originParentSpace|vector|1772 \| 0x6ec||
|m_ragdoll.list[23].pObject|custom|1784 \| 0x6f8||
|m_ragdoll.list[23].pConstraint|custom|1788 \| 0x6fc||
|m_ragdoll.list[23].parentIndex|integer|1792 \| 0x700||
|m_ragdoll.boneIndex|integer|1796 \| 0x704||
|m_bStartDisabled|boolean|1912 \| 0x778|StartDisabled|
|m_ragPos|pos-vector|1916 \| 0x77c||
|m_ragAngles|vector|2204 \| 0x89c||
|m_anglesOverrideString|string|2492 \| 0x9bc|angleOverride|
|m_hUnragdoll|ehandle|2496 \| 0x9c0||
|m_lastUpdateTickCount|integer|2500 \| 0x9c4||
|m_allAsleep|boolean|2504 \| 0x9c8||
|m_bFirstCollisionAfterLaunch|boolean|2505 \| 0x9c9||
|m_hDamageEntity|ehandle|2508 \| 0x9cc||
|m_hKiller|ehandle|2512 \| 0x9d0||
|m_hPhysicsAttacker|ehandle|2516 \| 0x9d4||
|m_flLastPhysicsInfluenceTime|time|2520 \| 0x9d8||
|m_flFadeOutStartTime|time|2524 \| 0x9dc||
|m_flFadeTime|float|2528 \| 0x9e0||
|m_strSourceClassName|string|2532 \| 0x9e4||
|m_bHasBeenPhysgunned|boolean|2536 \| 0x9e8||
|m_flBlendWeight|float|2540 \| 0x9ec||
|m_nOverlaySequence|integer|2544 \| 0x9f0||
|m_flDefaultFadeScale|float|2548 \| 0x9f4||
|m_ragdollMins|vector|2552 \| 0x9f8||
|m_ragdollMaxs|vector|2840 \| 0xb18||
|m_boneIndexAttached|integer|3128 \| 0xc38||
|m_ragdollAttachedObjectIndex|integer|3132 \| 0xc3c||
|m_attachmentPointBoneSpace|vector|3136 \| 0xc40||
|m_attachmentPointRagdollSpace|vector|3148 \| 0xc4c||
|m_bShouldDetach|boolean|3160 \| 0xc58||
|m_pAttachConstraint|custom|3164 \| 0xc5c||

## Embedded

### CServerNetworkProperty

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|m_hParent|ehandle|52 \| 0x34|

### CCollisionProperty

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|m_vecMins|vector|8 \| 0x8|
|m_vecMaxs|vector|20 \| 0x14|
|m_usSolidFlags|short|32 \| 0x20|
|m_nSolidType|character|34 \| 0x22|solid
|m_triggerBloat|character|35 \| 0x23|
|m_flRadius|float|36 \| 0x24|
|m_nSurroundType|character|42 \| 0x2a|
|m_vecSpecifiedSurroundingMins|vector|44 \| 0x2c|
|m_vecSpecifiedSurroundingMaxs|vector|56 \| 0x38|
|m_vecSurroundingMins|vector|68 \| 0x44|
|m_vecSurroundingMaxs|vector|80 \| 0x50|
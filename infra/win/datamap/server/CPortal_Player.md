# CPortal_Player

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
|CBasePlayerPlayerDeathThink|void|0 \| 0x0||
|CPortal_PlayerPlayerCatchPatnerNotConnectingThink|void|0 \| 0x0||
|CPortal_PlayerPlayerTransitionCompleteThink|void|0 \| 0x0||
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
|InputDisableReceivingFlashlight|void|0 \| 0x0|DisableReceivingFlashlight|
|InputDisableShadow|void|0 \| 0x0|DisableShadow|
|InputDispatchResponse|string|0 \| 0x0|DispatchResponse|
|InputEnableDamageForces|void|0 \| 0x0|EnableDamageForces|
|InputEnableDraw|void|0 \| 0x0|EnableDraw|
|InputEnableDrawInFastReflection|void|0 \| 0x0|EnableDrawInFastReflection|
|InputEnableReceivingFlashlight|void|0 \| 0x0|EnableReceivingFlashlight|
|InputEnableShadow|void|0 \| 0x0|EnableShadow|
|InputFireUser1|string|0 \| 0x0|FireUser1|
|InputFireUser2|string|0 \| 0x0|FireUser2|
|InputFireUser3|string|0 \| 0x0|FireUser3|
|InputFireUser4|string|0 \| 0x0|FireUser4|
|InputIgnite|integer|0 \| 0x0|IgniteNumHitboxFires|
|InputIgnite|float|0 \| 0x0|IgniteHitboxFireScale|
|InputIgnite|void|0 \| 0x0|Ignite|
|InputIgniteLifetime|float|0 \| 0x0|IgniteLifetime|
|InputKill|void|0 \| 0x0|Kill|
|InputKilledNPC|void|0 \| 0x0|KilledNPC|
|InputKillHierarchy|void|0 \| 0x0|KillHierarchy|
|InputRemoveContext|string|0 \| 0x0|RemoveContext|
|InputRemovePaint|void|0 \| 0x0|RemovePaint|
|InputRunScript|string|0 \| 0x0|RunScriptCode|
|InputRunScriptFile|string|0 \| 0x0|RunScriptFile|
|InputSetDamageFilter|string|0 \| 0x0|SetDamageFilter|
|InputSetFogController|string|0 \| 0x0|SetFogController|
|InputSetHealth|integer|0 \| 0x0|SetHealth|
|InputSetHUDVisibility|boolean|0 \| 0x0|SetHUDVisibility|
|InputSetLightingOrigin|string|0 \| 0x0|SetLightingOrigin|
|InputSetLightingOriginRelative|string|0 \| 0x0|SetLightingOriginHack|
|InputSetLocalAngles|string|0 \| 0x0|SetLocalAngles|
|InputSetLocalOrigin|string|0 \| 0x0|SetLocalOrigin|
|InputSetParent|string|0 \| 0x0|SetParent|
|InputSetParentAttachment|string|0 \| 0x0|SetParentAttachment|
|InputSetParentAttachmentMaintainOffset|string|0 \| 0x0|SetParentAttachmentMaintainOffset|
|InputSetTeam|integer|0 \| 0x0|SetTeam|
|InputUse|void|0 \| 0x0|Use|
|m_iObjectCapsCache|integer|4 \| 0x4||
|m_pfnMoveDone|function|8 \| 0x8||
|m_pfnThink|function|12 \| 0xc||
|m_Network|[CServerNetworkProperty](#cservernetworkproperty)|16 \| 0x10||
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
|m_Collision|[CCollisionProperty](#ccollisionproperty)|232 \| 0xe8||
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
|m_nSkin|integer|896 \| 0x380|skin|
|m_nSkin|integer|896 \| 0x380|ModelSkin|
|m_nBody|integer|900 \| 0x384|body|
|m_nBody|integer|900 \| 0x384|SetBodyGroup|
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
|m_AnimOverlay|custom|1204 \| 0x4b4||
|m_flexWeight|float|1224 \| 0x4c8||
|m_viewtarget|pos-vector|1608 \| 0x648||
|m_flAllowResponsesEndTime|time|1672 \| 0x688||
|m_flLastFlexAnimationTime|time|1700 \| 0x6a4||
|m_vecLean|vector|1728 \| 0x6c0||
|m_vecShift|vector|1740 \| 0x6cc||
|m_bForceServerRagdoll|boolean|1752 \| 0x6d8||
|m_bPreventWeaponPickup|boolean|1753 \| 0x6d9||
|m_flNextAttack|time|1756 \| 0x6dc||
|m_eHull|integer|1760 \| 0x6e0|HullType|
|m_bloodColor|integer|1764 \| 0x6e4|BloodColor|
|m_flFieldOfView|float|1768 \| 0x6e8||
|m_HackedGunPos|vector|1772 \| 0x6ec||
|m_RelationshipString|string|1784 \| 0x6f8|Relationship|
|m_impactEnergyScale|float|1788 \| 0x6fc|physdamagescale|
|m_LastHitGroup|integer|1808 \| 0x710||
|m_flDamageAccumulator|float|1812 \| 0x714||
|m_iDamageCount|integer|1816 \| 0x718||
|m_CurrentWeaponProficiency|integer|1820 \| 0x71c||
|m_Relationship|custom|1824 \| 0x720||
|m_nFaction|integer|1844 \| 0x734||
|m_hTriggerFogList|custom|1848 \| 0x738||
|m_hLastFogTrigger|ehandle|1868 \| 0x74c||
|m_iAmmo|integer|1872 \| 0x750||
|m_hMyWeapons|ehandle|2000 \| 0x7d0||
|m_hActiveWeapon|ehandle|2192 \| 0x890||
|m_StuckLast|integer|2220 \| 0x8ac||
|m_Local|[CPlayerLocalData](#cplayerlocaldata)|2224 \| 0x8b0||
|m_PlayerFog|[fogplayerparams_t](#fogplayerparams_t)|2736 \| 0xab0||
|m_hPostProcessCtrl|ehandle|2816 \| 0xb00||
|m_hColorCorrectionCtrl|ehandle|2820 \| 0xb04||
|m_hTriggerSoundscapeList|custom|2824 \| 0xb08||
|pl|[CPlayerState](#cplayerstate)|2844 \| 0xb1c||
|m_nButtons|integer|2896 \| 0xb50||
|m_afButtonPressed|integer|2900 \| 0xb54||
|m_afButtonReleased|integer|2904 \| 0xb58||
|m_afButtonLast|integer|2908 \| 0xb5c||
|m_afButtonDisabled|integer|2912 \| 0xb60||
|m_afButtonForced|integer|2916 \| 0xb64||
|m_szAnimExtension|character|2921 \| 0xb69||
|m_nUpdateRate|integer|2956 \| 0xb8c||
|m_fLerpTime|float|2960 \| 0xb90||
|m_bLagCompensation|boolean|2964 \| 0xb94||
|m_bPredictWeapons|boolean|2965 \| 0xb95||
|m_vecAdditionalPVSOrigin|pos-vector|2972 \| 0xb9c||
|m_vecCameraPVSOrigin|pos-vector|2984 \| 0xba8||
|m_bDropEnabled|boolean|2996 \| 0xbb4||
|m_bDuckEnabled|boolean|2997 \| 0xbb5||
|m_hUseEntity|ehandle|3000 \| 0xbb8||
|m_iTrain|integer|3004 \| 0xbbc||
|m_iRespawnFrames|float|3008 \| 0xbc0||
|m_afPhysicsFlags|integer|3012 \| 0xbc4||
|m_hVehicle|ehandle|3016 \| 0xbc8||
|m_bPauseBonusProgress|boolean|3024 \| 0xbd0||
|m_iBonusProgress|integer|3028 \| 0xbd4||
|m_iBonusChallenge|integer|3032 \| 0xbd8||
|m_flTimeLastTouchedGround|time|3036 \| 0xbdc||
|m_lastDamageAmount|integer|3040 \| 0xbe0||
|m_fTimeLastHurt|time|3044 \| 0xbe4||
|m_DmgOrigin|vector|3048 \| 0xbe8||
|m_DmgTake|float|3060 \| 0xbf4||
|m_DmgSave|float|3064 \| 0xbf8||
|m_bitsDamageType|integer|3068 \| 0xbfc||
|m_bitsHUDDamage|integer|3072 \| 0xc00||
|m_flDeathTime|time|3076 \| 0xc04||
|m_flDeathAnimTime|time|3080 \| 0xc08||
|m_iObserverMode|integer|3084 \| 0xc0c||
|m_iFOV|float|3088 \| 0xc10||
|m_iDefaultFOV|float|3092 \| 0xc14||
|m_iFOVStart|float|3096 \| 0xc18||
|m_flFOVTime|time|3100 \| 0xc1c||
|m_iObserverLastMode|integer|3104 \| 0xc20||
|m_hObserverTarget|ehandle|3108 \| 0xc24||
|m_bForcedObserverMode|boolean|3112 \| 0xc28||
|m_hZoomOwner|ehandle|3116 \| 0xc2c||
|m_tbdPrev|time|3120 \| 0xc30||
|m_idrowndmg|integer|3124 \| 0xc34||
|m_idrownrestored|integer|3128 \| 0xc38||
|m_nPoisonDmg|integer|3132 \| 0xc3c||
|m_nPoisonRestored|integer|3136 \| 0xc40||
|m_rgbTimeBasedDamage|character|3140 \| 0xc44||
|m_iSuicideCustomKillFlags|integer|3156 \| 0xc54||
|m_oldOrigin|pos-vector|3208 \| 0xc88||
|m_vecSmoothedVelocity|vector|3220 \| 0xc94||
|m_iTargetVolume|integer|3240 \| 0xca8||
|m_rgItems|integer|3244 \| 0xcac||
|m_flSuitUpdate|time|3276 \| 0xccc||
|m_rgSuitPlayList|integer|3280 \| 0xcd0||
|m_iSuitPlayNext|integer|3296 \| 0xce0||
|m_rgiSuitNoRepeat|integer|3300 \| 0xce4||
|m_rgflSuitNoRepeatTime|time|3428 \| 0xd64||
|m_fInitHUD|boolean|3568 \| 0xdf0||
|m_iFrags|integer|3592 \| 0xe08||
|m_iDeaths|integer|3596 \| 0xe0c||
|m_flNextDecalTime|time|3600 \| 0xe10||
|m_ArmorValue|integer|3608 \| 0xe18||
|m_AirFinished|time|3612 \| 0xe1c||
|m_PainFinished|time|3616 \| 0xe20||
|m_iPlayerLocked|integer|3620 \| 0xe24||
|m_hViewModel|ehandle|3628 \| 0xe2c||
|m_flStepSoundTime|float|3756 \| 0xeac||
|m_bAllowInstantSpawn|boolean|3760 \| 0xeb0||
|m_flMaxspeed|float|3764 \| 0xeb4||
|m_vecLadderNormal|vector|3772 \| 0xebc||
|m_flWaterJumpTime|time|3784 \| 0xec8||
|m_vecWaterJumpVel|vector|3788 \| 0xecc||
|m_nImpulse|integer|3800 \| 0xed8||
|m_flSwimSoundTime|time|3804 \| 0xedc||
|m_flFlashTime|time|3808 \| 0xee0||
|m_nDrownDmgRate|integer|3812 \| 0xee4||
|m_nNumCrouches|integer|3816 \| 0xee8||
|m_bDuckToggled|boolean|3820 \| 0xeec||
|m_flForwardMove|float|3824 \| 0xef0||
|m_flSideMove|float|3828 \| 0xef4||
|m_nNumCrateHudHints|integer|3832 \| 0xef8||
|m_fLastPlayerTalkTime|float|3860 \| 0xf14||
|m_hLastWeapon|ehandle|3864 \| 0xf18||
|m_flOldPlayerZ|float|3888 \| 0xf30||
|m_flOldPlayerViewOffsetZ|float|3892 \| 0xf34||
|m_bPlayerUnderwater|boolean|3896 \| 0xf38||
|m_hViewEntity|ehandle|3900 \| 0xf3c||
|m_bShouldDrawPlayerWhileUsingViewEntity|boolean|3904 \| 0xf40||
|m_hConstraintEntity|ehandle|3908 \| 0xf44||
|m_vecConstraintCenter|pos-vector|3912 \| 0xf48||
|m_flConstraintRadius|float|3924 \| 0xf54||
|m_flConstraintWidth|float|3928 \| 0xf58||
|m_flConstraintSpeedFactor|float|3932 \| 0xf5c||
|m_bConstraintPastRadius|boolean|3936 \| 0xf60||
|m_szNetname|character|3937 \| 0xf61||
|m_flLaggedMovementValue|float|3972 \| 0xf84||
|m_vNewVPhysicsPosition|vector|3976 \| 0xf88||
|m_vNewVPhysicsVelocity|vector|3988 \| 0xf94||
|m_flVehicleViewFOV|float|4024 \| 0xfb8||
|m_vecPreviouslyPredictedOrigin|pos-vector|4032 \| 0xfc0||
|m_szLastPlaceName|character|4052 \| 0xfd4||
|m_szNetworkIDString|character|4070 \| 0xfe6||
|m_bSinglePlayerGameEnding|boolean|4162 \| 0x1042||
|m_autoKickDisabled|boolean|4172 \| 0x104c||
|m_iPaintPower|integer|4744 \| 0x1288||
|m_hGrabbedEntity|ehandle|5012 \| 0x1394||
|m_hPortalThroughWhichGrabOccured|ehandle|5016 \| 0x1398||
|m_bForcingDrop|boolean|5020 \| 0x139c||
|m_bUseVMGrab|boolean|5021 \| 0x139d||
|m_bUsingVMGrabState|boolean|5022 \| 0x139e||
|m_flUseKeyStartTime|time|5024 \| 0x13a0||
|m_flAutoGrabLockOutTime|time|5028 \| 0x13a4||
|m_ForcedGrabController|integer|5032 \| 0x13a8||
|m_hAttachedObject|ehandle|5036 \| 0x13ac||
|m_vecTotalBulletForce|vector|5076 \| 0x13d4||
|m_bSilentDropAndPickup|boolean|5088 \| 0x13e0||
|m_hRagdoll|ehandle|5092 \| 0x13e4||
|m_bPitchReorientation|boolean|5096 \| 0x13e8||
|m_hPortalEnvironment|ehandle|5100 \| 0x13ec||
|m_vWorldSpaceCenterHolder|pos-vector|5104 \| 0x13f0||
|m_PortalLocal|[CPortalPlayerLocalData](#cportalplayerlocaldata)|5116 \| 0x13fc||
|m_pWooshSound|custom|5532 \| 0x159c||
|m_pGrabSound|custom|5536 \| 0x15a0||
|m_nWheatleyMonitorDestructionCount|integer|5540 \| 0x15a4||
|m_angEyeAngles|vector|5544 \| 0x15a8||
|m_iLastWeaponFireUsercmd|integer|5560 \| 0x15b8||
|m_iSpawnInterpCounter|integer|5564 \| 0x15bc||
|m_iPlayerSoundType|integer|5568 \| 0x15c0||
|m_bPingDisabled|boolean|5592 \| 0x15d8||
|m_bTauntDisabled|boolean|5593 \| 0x15d9||
|m_bTauntRemoteView|boolean|5594 \| 0x15da||
|m_bTauntRemoteViewFOVFixup|boolean|5595 \| 0x15db||
|m_vecRemoteViewOrigin|pos-vector|5596 \| 0x15dc||
|m_vecRemoteViewAngles|vector|5608 \| 0x15e8||
|m_fTauntCameraDistance|float|5620 \| 0x15f4||
|m_nTeamTauntState|integer|5624 \| 0x15f8||
|m_vTauntPosition|pos-vector|5628 \| 0x15fc||
|m_vTauntAngles|vector|5640 \| 0x1608||
|m_vPreTauntAngles|vector|5652 \| 0x1614||
|m_bTrickFire|boolean|5664 \| 0x1620||
|m_hTauntPartnerInRange|ehandle|5668 \| 0x1624||
|m_szTauntForce|character|5672 \| 0x1628||
|m_bHeldObjectOnOppositeSideOfPortal|boolean|5736 \| 0x1668||
|m_hHeldObjectPortal|ehandle|5740 \| 0x166c||
|m_bIntersectingPortalPlane|boolean|5744 \| 0x1670||
|m_bStuckOnPortalCollisionObject|boolean|5745 \| 0x1671||
|m_fNeuroToxinDamageTime|time|5748 \| 0x1674||
|m_StatsThisLevel|[PortalPlayerStatistics_t](#portalplayerstatistics_t)|5752 \| 0x1678||
|m_fTimeLastNumSecondsUpdate|time|5772 \| 0x168c||
|m_iNumCamerasDetatched|integer|5788 \| 0x169c||
|m_flLastPingTime|float|5792 \| 0x16a0||
|m_bClientCheckPVSDirty|boolean|5796 \| 0x16a4||
|m_flUseKeyCooldownTime|time|5800 \| 0x16a8||
|m_bIsHoldingSomething|boolean|5804 \| 0x16ac||
|m_bWasDroppedByOtherPlayerWhileTaunting|boolean|5813 \| 0x16b5||
|m_nPortalsEnteredInAirFlags|integer|6044 \| 0x179c||
|m_nAirTauntCount|integer|6048 \| 0x17a0||
|m_flMotionBlurAmount|float|6056 \| 0x17a8||
|m_bPotatos|boolean|6062 \| 0x17ae||
|m_PlayerGunType|integer|6064 \| 0x17b0||
|m_bSpawnFromDeath|boolean|6072 \| 0x17b8||
|m_flHullHeight|float|6100 \| 0x17d4||

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

### CPlayerLocalData

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|m_chAreaBits|character|4 \| 0x4|
|m_chAreaPortalBits|character|36 \| 0x24|
|m_iHideHUD|integer|60 \| 0x3c|
|m_flFOVRate|float|64 \| 0x40|
|m_bFOVSmooth|boolean|68 \| 0x44|
|m_vecOverViewpoint|vector|72 \| 0x48|
|m_bDucked|boolean|84 \| 0x54|
|m_bDucking|boolean|85 \| 0x55|
|m_bInDuckJump|boolean|86 \| 0x56|
|m_nDuckTimeMsecs|integer|88 \| 0x58|
|m_nDuckJumpTimeMsecs|integer|92 \| 0x5c|
|m_nJumpTimeMsecs|integer|96 \| 0x60|
|m_nStepside|integer|100 \| 0x64|
|m_flFallVelocity|float|104 \| 0x68|
|m_nOldButtons|integer|108 \| 0x6c|
|m_vecPunchAngle|vector|116 \| 0x74|
|m_vecPunchAngleVel|vector|128 \| 0x80|
|m_bDrawViewmodel|boolean|140 \| 0x8c|
|m_bWearingSuit|boolean|141 \| 0x8d|
|m_bPoisoned|boolean|142 \| 0x8e|
|m_flStepSize|float|144 \| 0x90|
|m_bAllowAutoMovement|boolean|148 \| 0x94|
|m_skybox3d|[sky3dparams_t](#sky3dparams_t)|152 \| 0x98|
|m_fog|[fogparams_t](#fogparams_t)|312 \| 0x138|
|m_audio|[audioparams_t](#audioparams_t)|388 \| 0x184|

### fogplayerparams_t

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|m_hCtrl|ehandle|4 \| 0x4|
|m_flTransitionTime|float|8 \| 0x8|
|m_OldColor|color32|12 \| 0xc|
|m_flOldStart|float|16 \| 0x10|
|m_flOldEnd|float|20 \| 0x14|
|m_NewColor|color32|36 \| 0x24|
|m_flNewStart|float|40 \| 0x28|
|m_flNewEnd|float|44 \| 0x2c|

### CPlayerState

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|deadflag|boolean|4 \| 0x4|
|v_angle|vector|8 \| 0x8|

### CPortalPlayerLocalData

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|m_bShowingViewFinder|boolean|4 \| 0x4|
|m_flAirControlSupressionTime|float|8 \| 0x8|
|m_nLocatorEntityIndices|integer|12 \| 0xc|
|m_bPlacingPhoto|boolean|76 \| 0x4c|
|m_StickNormal|vector|160 \| 0xa0|
|m_OldStickNormal|vector|172 \| 0xac|
|m_vPreUpdateVelocity|vector|184 \| 0xb8|
|m_Up|vector|196 \| 0xc4|
|m_vStickRotationAxis|vector|208 \| 0xd0|
|m_StandHullMin|vector|220 \| 0xdc|
|m_StandHullMax|vector|232 \| 0xe8|
|m_DuckHullMin|vector|244 \| 0xf4|
|m_DuckHullMax|vector|256 \| 0x100|
|m_CachedStandHullMinAttempt|vector|268 \| 0x10c|
|m_CachedStandHullMaxAttempt|vector|280 \| 0x118|
|m_CachedDuckHullMinAttempt|vector|292 \| 0x124|
|m_CachedDuckHullMaxAttempt|vector|304 \| 0x130|
|m_vLocalUp|vector|316 \| 0x13c|
|m_vEyeOffset|vector|328 \| 0x148|
|m_qQuaternionPunch|vector|340 \| 0x154|
|m_PaintedPowerType|integer|352 \| 0x160|
|m_flAirInputScale|float|368 \| 0x170|
|m_flCurrentStickTime|float|372 \| 0x174|
|m_nStickCameraState|integer|376 \| 0x178|
|m_InAirState|integer|380 \| 0x17c|
|m_bDoneStickInterp|boolean|384 \| 0x180|
|m_bDoneCorrectPitch|boolean|385 \| 0x181|
|m_bAttemptHullResize|boolean|386 \| 0x182|
|m_bJumpedThisFrame|boolean|387 \| 0x183|
|m_bBouncedThisFrame|boolean|388 \| 0x184|
|m_bDuckedInAir|boolean|389 \| 0x185|
|m_hTractorBeam|ehandle|392 \| 0x188|
|m_bZoomedIn|boolean|400 \| 0x190|
|m_fBouncedTime|time|404 \| 0x194|
|m_bPreventedCrouchJumpThisFrame|boolean|408 \| 0x198|

### PortalPlayerStatistics_t

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|iNumPortalsPlaced|integer|4 \| 0x4|
|iNumStepsTaken|integer|8 \| 0x8|
|fNumSecondsTaken|float|12 \| 0xc|
|fDistanceTaken|float|16 \| 0x10|

### sky3dparams_t

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|scale|integer|4 \| 0x4|
|origin|vector|8 \| 0x8|
|area|integer|20 \| 0x14|
|fog|[fogparams_t](#fogparams_t)|24 \| 0x18|

### fogparams_t

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|dirPrimary|vector|4 \| 0x4|
|colorPrimary|color32|16 \| 0x10|
|colorSecondary|color32|20 \| 0x14|
|colorPrimaryLerpTo|color32|24 \| 0x18|
|colorSecondaryLerpTo|color32|28 \| 0x1c|
|start|float|32 \| 0x20|
|end|float|36 \| 0x24|
|farz|float|40 \| 0x28|
|maxdensity|float|44 \| 0x2c|
|startLerpTo|float|48 \| 0x30|
|endLerpTo|float|52 \| 0x34|
|maxdensityLerpTo|float|56 \| 0x38|
|lerptime|time|60 \| 0x3c|
|duration|float|64 \| 0x40|
|enable|boolean|68 \| 0x44|
|blend|boolean|69 \| 0x45|

### audioparams_t

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|localSound|vector|4 \| 0x4|
|soundscapeIndex|integer|100 \| 0x64|
|localBits|integer|104 \| 0x68|
|entIndex|integer|108 \| 0x6c|

### fogparams_t

|Prop|Type|Offset|External|
|---|:-:|:-:|--:|
|dirPrimary|vector|4 \| 0x4|
|colorPrimary|color32|16 \| 0x10|
|colorSecondary|color32|20 \| 0x14|
|colorPrimaryLerpTo|color32|24 \| 0x18|
|colorSecondaryLerpTo|color32|28 \| 0x1c|
|start|float|32 \| 0x20|
|end|float|36 \| 0x24|
|farz|float|40 \| 0x28|
|maxdensity|float|44 \| 0x2c|
|startLerpTo|float|48 \| 0x30|
|endLerpTo|float|52 \| 0x34|
|maxdensityLerpTo|float|56 \| 0x38|
|lerptime|time|60 \| 0x3c|
|duration|float|64 \| 0x40|
|enable|boolean|68 \| 0x44|
|blend|boolean|69 \| 0x45|

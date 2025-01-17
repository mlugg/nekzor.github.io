# CBreakableSurface

Class server-side.

|Prop|Type|Offset|
|---|:-:|:-:|
|baseclass|[DT_BaseEntity](#dt_baseentity)|0 \| 0x0|
|m_nNumWide|int|1036 \| 0x40c|
|m_nNumHigh|int|1040 \| 0x410|
|m_flPanelWidth|float|1044 \| 0x414|
|m_flPanelHeight|float|1048 \| 0x418|
|m_vNormal|vector|1052 \| 0x41c|
|m_vCorner|vector|1064 \| 0x428|
|m_bIsBroken|int|1076 \| 0x434|
|m_nSurfaceType|int|1080 \| 0x438|
|m_RawPanelBitVec|[m_RawPanelBitVec](#m_rawpanelbitvec)|2168 \| 0x878|

## Recv

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

### m_RawPanelBitVec

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
|032|int|32 \| 0x20|
|033|int|33 \| 0x21|
|034|int|34 \| 0x22|
|035|int|35 \| 0x23|
|036|int|36 \| 0x24|
|037|int|37 \| 0x25|
|038|int|38 \| 0x26|
|039|int|39 \| 0x27|
|040|int|40 \| 0x28|
|041|int|41 \| 0x29|
|042|int|42 \| 0x2a|
|043|int|43 \| 0x2b|
|044|int|44 \| 0x2c|
|045|int|45 \| 0x2d|
|046|int|46 \| 0x2e|
|047|int|47 \| 0x2f|
|048|int|48 \| 0x30|
|049|int|49 \| 0x31|
|050|int|50 \| 0x32|
|051|int|51 \| 0x33|
|052|int|52 \| 0x34|
|053|int|53 \| 0x35|
|054|int|54 \| 0x36|
|055|int|55 \| 0x37|
|056|int|56 \| 0x38|
|057|int|57 \| 0x39|
|058|int|58 \| 0x3a|
|059|int|59 \| 0x3b|
|060|int|60 \| 0x3c|
|061|int|61 \| 0x3d|
|062|int|62 \| 0x3e|
|063|int|63 \| 0x3f|
|064|int|64 \| 0x40|
|065|int|65 \| 0x41|
|066|int|66 \| 0x42|
|067|int|67 \| 0x43|
|068|int|68 \| 0x44|
|069|int|69 \| 0x45|
|070|int|70 \| 0x46|
|071|int|71 \| 0x47|
|072|int|72 \| 0x48|
|073|int|73 \| 0x49|
|074|int|74 \| 0x4a|
|075|int|75 \| 0x4b|
|076|int|76 \| 0x4c|
|077|int|77 \| 0x4d|
|078|int|78 \| 0x4e|
|079|int|79 \| 0x4f|
|080|int|80 \| 0x50|
|081|int|81 \| 0x51|
|082|int|82 \| 0x52|
|083|int|83 \| 0x53|
|084|int|84 \| 0x54|
|085|int|85 \| 0x55|
|086|int|86 \| 0x56|
|087|int|87 \| 0x57|
|088|int|88 \| 0x58|
|089|int|89 \| 0x59|
|090|int|90 \| 0x5a|
|091|int|91 \| 0x5b|
|092|int|92 \| 0x5c|
|093|int|93 \| 0x5d|
|094|int|94 \| 0x5e|
|095|int|95 \| 0x5f|
|096|int|96 \| 0x60|
|097|int|97 \| 0x61|
|098|int|98 \| 0x62|
|099|int|99 \| 0x63|
|100|int|100 \| 0x64|
|101|int|101 \| 0x65|
|102|int|102 \| 0x66|
|103|int|103 \| 0x67|
|104|int|104 \| 0x68|
|105|int|105 \| 0x69|
|106|int|106 \| 0x6a|
|107|int|107 \| 0x6b|
|108|int|108 \| 0x6c|
|109|int|109 \| 0x6d|
|110|int|110 \| 0x6e|
|111|int|111 \| 0x6f|
|112|int|112 \| 0x70|
|113|int|113 \| 0x71|
|114|int|114 \| 0x72|
|115|int|115 \| 0x73|
|116|int|116 \| 0x74|
|117|int|117 \| 0x75|
|118|int|118 \| 0x76|
|119|int|119 \| 0x77|
|120|int|120 \| 0x78|
|121|int|121 \| 0x79|
|122|int|122 \| 0x7a|
|123|int|123 \| 0x7b|
|124|int|124 \| 0x7c|
|125|int|125 \| 0x7d|
|126|int|126 \| 0x7e|
|127|int|127 \| 0x7f|
|128|int|128 \| 0x80|
|129|int|129 \| 0x81|
|130|int|130 \| 0x82|
|131|int|131 \| 0x83|
|132|int|132 \| 0x84|
|133|int|133 \| 0x85|
|134|int|134 \| 0x86|
|135|int|135 \| 0x87|
|136|int|136 \| 0x88|
|137|int|137 \| 0x89|
|138|int|138 \| 0x8a|
|139|int|139 \| 0x8b|
|140|int|140 \| 0x8c|
|141|int|141 \| 0x8d|
|142|int|142 \| 0x8e|
|143|int|143 \| 0x8f|
|144|int|144 \| 0x90|
|145|int|145 \| 0x91|
|146|int|146 \| 0x92|
|147|int|147 \| 0x93|
|148|int|148 \| 0x94|
|149|int|149 \| 0x95|
|150|int|150 \| 0x96|
|151|int|151 \| 0x97|
|152|int|152 \| 0x98|
|153|int|153 \| 0x99|
|154|int|154 \| 0x9a|
|155|int|155 \| 0x9b|
|156|int|156 \| 0x9c|
|157|int|157 \| 0x9d|
|158|int|158 \| 0x9e|
|159|int|159 \| 0x9f|
|160|int|160 \| 0xa0|
|161|int|161 \| 0xa1|
|162|int|162 \| 0xa2|
|163|int|163 \| 0xa3|
|164|int|164 \| 0xa4|
|165|int|165 \| 0xa5|
|166|int|166 \| 0xa6|
|167|int|167 \| 0xa7|
|168|int|168 \| 0xa8|
|169|int|169 \| 0xa9|
|170|int|170 \| 0xaa|
|171|int|171 \| 0xab|
|172|int|172 \| 0xac|
|173|int|173 \| 0xad|
|174|int|174 \| 0xae|
|175|int|175 \| 0xaf|
|176|int|176 \| 0xb0|
|177|int|177 \| 0xb1|
|178|int|178 \| 0xb2|
|179|int|179 \| 0xb3|
|180|int|180 \| 0xb4|
|181|int|181 \| 0xb5|
|182|int|182 \| 0xb6|
|183|int|183 \| 0xb7|
|184|int|184 \| 0xb8|
|185|int|185 \| 0xb9|
|186|int|186 \| 0xba|
|187|int|187 \| 0xbb|
|188|int|188 \| 0xbc|
|189|int|189 \| 0xbd|
|190|int|190 \| 0xbe|
|191|int|191 \| 0xbf|
|192|int|192 \| 0xc0|
|193|int|193 \| 0xc1|
|194|int|194 \| 0xc2|
|195|int|195 \| 0xc3|
|196|int|196 \| 0xc4|
|197|int|197 \| 0xc5|
|198|int|198 \| 0xc6|
|199|int|199 \| 0xc7|
|200|int|200 \| 0xc8|
|201|int|201 \| 0xc9|
|202|int|202 \| 0xca|
|203|int|203 \| 0xcb|
|204|int|204 \| 0xcc|
|205|int|205 \| 0xcd|
|206|int|206 \| 0xce|
|207|int|207 \| 0xcf|
|208|int|208 \| 0xd0|
|209|int|209 \| 0xd1|
|210|int|210 \| 0xd2|
|211|int|211 \| 0xd3|
|212|int|212 \| 0xd4|
|213|int|213 \| 0xd5|
|214|int|214 \| 0xd6|
|215|int|215 \| 0xd7|
|216|int|216 \| 0xd8|
|217|int|217 \| 0xd9|
|218|int|218 \| 0xda|
|219|int|219 \| 0xdb|
|220|int|220 \| 0xdc|
|221|int|221 \| 0xdd|
|222|int|222 \| 0xde|
|223|int|223 \| 0xdf|
|224|int|224 \| 0xe0|
|225|int|225 \| 0xe1|
|226|int|226 \| 0xe2|
|227|int|227 \| 0xe3|
|228|int|228 \| 0xe4|
|229|int|229 \| 0xe5|
|230|int|230 \| 0xe6|
|231|int|231 \| 0xe7|
|232|int|232 \| 0xe8|
|233|int|233 \| 0xe9|
|234|int|234 \| 0xea|
|235|int|235 \| 0xeb|
|236|int|236 \| 0xec|
|237|int|237 \| 0xed|
|238|int|238 \| 0xee|
|239|int|239 \| 0xef|
|240|int|240 \| 0xf0|
|241|int|241 \| 0xf1|
|242|int|242 \| 0xf2|
|243|int|243 \| 0xf3|
|244|int|244 \| 0xf4|
|245|int|245 \| 0xf5|
|246|int|246 \| 0xf6|
|247|int|247 \| 0xf7|
|248|int|248 \| 0xf8|
|249|int|249 \| 0xf9|
|250|int|250 \| 0xfa|
|251|int|251 \| 0xfb|
|252|int|252 \| 0xfc|
|253|int|253 \| 0xfd|
|254|int|254 \| 0xfe|
|255|int|255 \| 0xff|

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

# Anime-Character-Recognizer

Up to now the EfficientNet-B1 CNN can recognize 203 characters with an accuracy of 87% circa:  
  
 0: '000_hatsune_miku',  
 1: '001_kinomoto_sakura',  
 2: '002_suzumiya_haruhi',  
 3: '003_fate_testarossa',  
 4: '004_takamachi_nanoha',  
 5: '005_lelouch_lamperouge',  
 6: '006_akiyama_mio',  
 7: '007_nagato_yuki',  
 8: '008_shana',  
 9: '009_hakurei_reimu',  
 10: '010_izumi_konata',  
 11: '011_kirisame_marisa',  
 12: '012_asahina_mikuru',  
 13: '013_saber',  
 14: '014_hiiragi_kagami',  
 15: '015_c.c',  
 16: '016_furukawa_nagisa',  
 17: '017_louise',  
 18: '018_kagamine_rin',  
 19: '019_ayanami_rei',  
 20: '020_remilia_scarlet',  
 21: '021_hirasawa_yui',  
 22: '022_kururugi_suzaku',  
 23: '023_hiiragi_tsukasa',  
 24: '024_fujibayashi_kyou',  
 25: '025_souryuu_asuka_langley',  
 26: '026_tohsaka_rin',  
 27: '027_izayoi_sakuya',  
 28: '028_tainaka_ritsu',  
 29: '029_kallen_stadtfeld',  
 30: '030_aisaka_taiga',  
 31: '031_kotobuki_tsumugi',  
 32: '032_yakumo_yukari',  
 33: '033_kagamine_len',  
 34: '034_sakagami_tomoyo',  
 35: '035_yoko',  
 36: '036_reisen_udongein_inaba',  
 37: '037_lala_satalin_deviluke',  
 38: '038_takara_miyuki',  
 39: '039_yagami_hayate',  
 40: '040_flandre_scarlet',  
 41: '041_saigyouji_yuyuko',  
 42: '042_tsukimura_mayu',  
 43: '043_konpaku_youmu',  
 44: '044_nakano_azusa',  
 45: '045_patchouli_knowledge',  
 46: '046_alice_margatroid',  
 47: '047_sheryl_nome',  
 48: '048_kerberos',  
 49: '049_kyon',  
 50: '050_megurine_luka',  
 51: '051_houjou_reika',  
 52: '052_ranka_lee',  
 53: '053_kousaka_tamaki',  
 54: '054_horo',  
 55: '055_ibuki_fuuko',  
 56: '056_nagi',  
 57: '057_li_syaoran',  
 58: '058_kochiya_sanae',  
 59: '059_sairenji_haruna',  
 60: '060_ichinose_kotomi',  
 61: '061_furude_rika',  
 62: '062_matou_sakura',  
 63: '063_ryuuguu_rena',  
 64: '064_amami_haruka',  
 65: '065_sanzenin_nagi',  
 66: '066_shameimaru_aya',  
 67: '067_feena_fam_earthlight',  
 68: '068_miyamura_miyako',  
 69: '069_hayase_mitsuki',  
 70: '070_nijihara_ink',  
 71: '071_nagase_minato',  
 72: '072_melon-chan',  
 73: '073_subaru_nakajima',  
 74: '074_daidouji_tomoyo',  
 75: '075_katsura_hinagiku',  
 76: '076_cirno',  
 77: '077_yoshida_kazumi',  
 78: '078_black_rock_shooter',  
 79: '079_teana_lanster',  
 80: '080_koizumi_itsuki',  
 81: '081_yuzuhara_konomi',  
 82: '082_fujibayashi_ryou',  
 83: '083_shirou_kamui',  
 84: '084_okazaki_tomoya',  
 85: '085_sonozaki_mion',  
 86: '086_tsuruya',  
 87: '087_suzumiya_haruka',  
 88: '088_vita',  
 89: '089_shigure_asa',  
 90: '090_minase_iori',  
 91: '091_komaki_manaka',  
 92: '092_shindou_kei',  
 93: '093_yuuki_mikan',  
 94: '094_fuyou_kaede',  
 95: '095_nerine',  
 96: '096_golden_darkness',  
 97: '097_kamikita_komari',  
 98: '098_mizunashi_akari',  
 99: '099_kaito',  
 100: '100_houjou_satoko',  
 101: '101_aoi_nagisa',  
 102: '102_katagiri_yuuhi',  
 103: '103_reinforce_zwei',  
 104: '104_fukuzawa_yumi',  
 105: '105_yuno',  
 106: '106_nia',  
 107: '107_chii',  
 108: '108_hagiwara_yukiho',  
 109: '109_yakumo_ran',  
 110: '110_houraisan_kaguya',  
 111: '111_suigintou',  
 112: '112_hinamori_amu',  
 113: '113_lisianthus',  
 114: '114_natsume_rin',  
 115: '115_komeiji_satori',  
 116: '116_pastel_ink',  
 117: '117_inaba_tewi',  
 118: '118_noumi_kudryavka',  
 119: '119_takatsuki_yayoi',  
 120: '120_asakura_yume',  
 121: '121_arcueid_brunestud',  
 122: '122_konohana_hikari',  
 123: '123_midori',  
 124: '124_hong_meiling',  
 125: '125_sakai_yuuji',  
 126: '126_kurosaki_ichigo',  
 127: '127_setsuna_f_seiei',  
 128: '128_amamiya_yuuko',  
 129: '129_primula',  
 130: '130_fujiwara_no_mokou',  
 131: '131_belldandy',  
 132: '132_minamoto_chizuru',  
 133: '133_chen',  
 134: '134_nunnally_lamperouge',  
 135: '135_monkey_d_luffy',  
 136: '136_shirley_fenette',  
 137: '137_sonsaku_hakufu',  
 138: '138_kanu',  
 139: '139_caro_ru_lushe',  
 140: '140_seto_san',  
 141: '141_yagokoro_eirin',  
 142: '142_ibuki_suika',  
 143: '143_miura_azusa',  
 144: '144_kotegawa_yui',  
 145: '145_hyuuga_kizuna',  
 146: '146_shinku',  
 147: '147_kanu_unchou',  
 148: '148_hanamoto_hagumi',  
 149: '149_asakura_otome',  
 150: '150_maria',  
 151: '151_uzumaki_naruto',  
 152: '152_maka_albarn',  
 153: '153_canal_volphied',  
 154: '154_kobayakawa_yutaka',  
 155: '155_vivio',  
 156: '156_miyafuji_yoshika',  
 157: '157_ogasawara_sachiko',  
 158: '158_enma_ai',  
 159: '159_andou_mahoro',  
 160: '160_ayasaki_hayate',  
 161: '161_ryougi_shiki',  
 162: '162_moriya_suwako',  
 163: '163_meiko',  
 164: '164_shindou_chihiro',  
 165: '165_rollo_lamperouge',  
 166: '166_katsura_kotonoha',  
 167: '167_reiuji_utsuho',  
 168: '168_asagiri_mai',  
 169: '169_shihou_matsuri',  
 170: '170_aoyagi_ritsuka',  
 171: '171_ikari_shinji',  
 172: '172_kisaragi_chihaya',  
 173: '173_reina',  
 174: '174_hayama_mizuki',  
 175: '175_saotome_alto',  
 176: '176_sendou_erika',  
 177: '177_sonozaki_shion',  
 178: '178_milfeulle_sakuraba',  
 179: '179_siesta',  
 180: '180_matsuoka_miu',  
 181: '181_allen_walker',  
 182: '182_corticarte_apa_lagranges',  
 183: '183_hanazono_shizuma',  
 184: '184_suzumiya_akane',  
 185: '185_akihime_sumomo',  
 186: '186_nanael',  
 187: '187_suzumi_tamao',  
 188: '188_aika_granzchesta',  
 189: '189_akizuki_ritsuko',  
 190: '190_kawashima_ami',  
 191: '191_shidou_hikaru',  
 192: '192_shirakawa_kotori',  
 193: '193_kagurazaka_asuna',  
 194: '194_kazami_yuuka',  
 195: '195_erio_mondial',  
 196: '196_kikuchi_makoto',  
 197: '197_illyasviel_von_einzbern',  
 198: '198_nogizaka_haruka',  
 199: '199_kusugawa_sasara',  
 200: '997_ana_coppola',  
 201: '998_ito_nobue',  
 202: '999_ito_chika'  
	  
  
 
 Kaggle Data: https://www.kaggle.com/code/gabriellisimone/anime-face-recognizer?scriptVersionId=91838196
   
 Training Info:
   

  ![__results___22_4](https://user-images.githubusercontent.com/29608176/161310192-e4d08a44-03f3-42ce-8907-27f2f88be8c8.png)
  ![__results___22_0](https://user-images.githubusercontent.com/29608176/161310186-d2c720e0-1070-45b3-8e06-e80a93f4a1e6.png)
  ![__results___22_1](https://user-images.githubusercontent.com/29608176/161310188-b0ec1d4a-94ed-4165-8292-de844d6547cd.png)
  ![__results___22_2](https://user-images.githubusercontent.com/29608176/161310189-4d7e2e11-f9fc-47d8-840a-b6575c65583c.png)
  ![__results___22_3](https://user-images.githubusercontent.com/29608176/161310191-1d75a54f-5476-434a-b156-d8836a4f4ce1.png)

![__results___22_5](https://user-images.githubusercontent.com/29608176/161310489-fb91f390-7ec6-4384-a739-8f217731df0c.png)
![__results___22_6](https://user-images.githubusercontent.com/29608176/161310493-9e108d3c-375e-4730-9382-2db3ad99963d.png)


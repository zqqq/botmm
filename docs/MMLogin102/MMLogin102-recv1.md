00 00 00 9D //包长度 :157
00 00 00 0B 02 00 00 00 //固定长度
00 0B //QQ字节数+4 :11
32 38 36 37 33 30 31 //QQ号 :"2867301"
8D A1 A5 1F 85 F1 79 02 98 B7 49 42 12 F6 99 60 CD 89 E3 30 50 05 21 EE 36 E9 E3 C2 25 E2 76 42 A0 C3 0B 1F CE 5B 66 5D C7 CE B6 68 A4 50 DE 04 1D 79 7F 29 CD 01 F7 66 76 21 63 27 6A 68 DB 50 C9 05 45 2D AF F9 E5 50 05 6A 35 B3 05 7D DB 98 31 4D FB 13 06 96 06 52 0F 1B DD 37 5D AF FF E7 61 4F 40 AD A7 63 72 98 BE 1F 26 11 D3 1E 1E 65 7A B9 A9 56 FB 57 E6 7B A2 87 CD 85 48 13 05 91 95 9C 5F 5D 5A 77 33 C9 //加密内容 :用0[16]解密 00000000000000000000000000000000
	MessageHead
	00 00 00 2D //Head总长度(包括这4字节) :45
	00 00 9A C1 00 00 00 00 00 00 00 04 00 00 00 11 77 74 6C 6F 67 69 6E 2E 6C 6F 67 69 6E 00 00 00 08 29 40 08 50 00 00 00 00 //先不管
	OicqRequestBuffer
	00 00 00 4D //Body总长度(包括这4字节) :77
	02
	00 49 //len :73
	1F 41 //pc_ver
	08 10 //cmd
	00 01 //sequence
	00 2B C0 65 //QQ :2867301
	00
	00
	B4 //retry
	B3 2D BA CB 04 E5 BE 40 92 3F 42 91 B6 4F 97 E2 2A 8F 1C F3 63 6D CF 7A 26 9B 0F 58 36 EA 68 82 3E 5A A4 38 B7 AD B8 2B 2B 63 3D 05 DD 4F E7 88 3C 70 93 BF 53 29 9F E8 //加密数据 :使用randkey解密 3f254b0e7939593255309b31d0bad582
		00 00
		B4 //返回标识
		00 01
		01 61 00 1E
		00
		01 //tlv_num :1
		01 72 //tlv_t172
		00 18 //tlv_len :24
		C6 5D 78 95 84 CC 37 B5 B5 2E 71 1D 2C 6C CB 04 82 64 FF FD D9 63 E3 AD
	03
已经不是单身狗的我，仍致力于学习撩妹技能，啊哈哈哈哈
准备给女朋友写封情书，并附上情书的词云图 ~+~

实现功能：
1。从网易云音乐中爬取指定歌曲的热评，生成给定图片形状的词云~~~-）（-~~~~。
2。生成给定文字和图片形状的词云\^O^/

usage: python word.py -m <music_id> -i <input_image_file> -o <out_file>
		required argument:
			-m | --music_id : input music id
			-i | --input_image_file: input image file
			-f | --font_file: font file
			-o | --out_file : output file prefix


usage: python word.py -t <input_text_file> -i <input_image_file> -o <out_file>
		required argument:
			-t | --input_text_file : input file in text
			-i | --input_image_file: input image file
			-f | --font_file: font file
			-o | --out_file : output file prefix



P.S:生成词云代码来自fyuanfen/wordcloud
安装过程参见fyuanfen/wordcloud，很详细啦
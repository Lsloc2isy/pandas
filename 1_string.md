# Pandas中使用string方法
* table['column'].str.len() 判断列中每一个对象的字符数
* lambda x: x['column'].startswith('A') 判断列中的每一个对象是否是以A为开头的
* table.apply(function,axis=1)function表示对二维表使用的函数，可以是库函数或者自己定义的函数，axis表示应用的方向，1代表行，0代表列
* table['column'].str[0].str.lower()这里要注意一点由.str[0]获得的对象还是series对象，需要再.str获取字符串对象
* table['column'].str.match(r'pattern')使用match方法正则匹配
* table['column'].str.contains(r'pattern',regex=True)contains方法检查字符串中是否包含子字符串，regex=True表示按正则表达式匹配
* 

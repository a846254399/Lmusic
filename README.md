# Lmusic 一个音乐播放jquery插件
注意：本插件依赖font-awesome以及必须的Jquery,请务必进行引入
使用方法如下

1、引入js主体和css样式文件
<link rel="stylesheet" href="lmusic.css">
<script src="lmusic.js"></script>

2、初始化
<script>
var source = [
		{
			url : 'red.mp3',
			cover : 'http://p4.music.126.net/Z7JNUkL5cjZETD232S510w==/2540971372183769.jpg',
			name : 'Red Lights (Radio Edit)',
		},
		{
			url : 'avicii.flac',
			cover : 'http://p3.music.126.net/YyPaRiqjA2UFz-T3IXuXbw==/1308418837090130.jpg',
			name : 'Avicii - I Could Be the One',
		}
];
var myMusic = $('.container').lmusic({
	source : source,
	height : 120, //可定义 若不存在则选用容器高度 若容器也没有固定高度，则默认为150px
});
myMusic.init();//初始化即完成
</script>

PS:由于版本简单，暂不提供更多API，简单使用

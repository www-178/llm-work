10.21�ղ���
�ڱ��ش���һ���ļ��н�test10.21 ,�ļ�����Ӧ����5��html�ļ�,�ֱ�����Ϊ1.html��.�ٴ���һ��readme.txt�ļ�,���⼸��������������,���html�е�js������������·�.

1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:  
    <body>
		<h1 id="h1"></h1>
		<script type="text/javascript">
			var a='nihao'
			var b='С��'
			document.getElementById('h1').innerHTML=a.concat(b)
		</script>
   </body>
2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:  
     <body>
		<h2 id="h2"></h2>
		<script type="text/javascript">
			var estr='87'
			var nstr=estr.padEnd(6,'0');
			document.getElementById('h2').innerHTML=nstr
		</script>
      </body>

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:  <body>
		<h3 id="h3"></h3>
		<script type="text/javascript">
			var num=new Number(79387.348);
			document.getElementById('h3').innerHTML=num.toFixed(2);
			
		</script>
     </body>

4.һ��ͼƬ��һ�����·��img/head/,icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:
        <body>
		<img src="" id="h4"/ >
	    <script type="text/javascript">
	    	document.getElementById('h4').src='img/head/icon/1.jpg'
	        console.log(document.getElementById('h4').Location.href)
	    </script>
	</body>

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����,��ʾ��ҳ��idΪh4��Ԫ����
��:
<body>
		<div id="h5"></div>
		<input type="text" name="" id="ipt" value="" placeholder="��֤�벻���ִ�Сд"/>
		<button id="btn">��֤</button>
		<script type="text/javascript">
			
	     var btn=document.getElementById('btn')
	     var ipt=document.getElementById('ipt')
	     btn.onclick=function(){
	       document.getElementById('h5').innerHTML='��֤��Ϊ:'+ipt.value.toLowerCase()+'��֤ͨ��';
	     }
		</script>
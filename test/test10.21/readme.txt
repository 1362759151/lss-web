1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:
        var h1 = document.getElementById('h1');
        var a = 'Hello';
        var b = 'word';
        h1.innerHTML = a.concat(b);

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:
        var h2 = document.getElementById('h2');
        var num = '87';
        h2.innerHTML = num.padEnd(6,'0');

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:
        var h3 = document.getElementById('h3');
        var num = 79387.348;
        h3.innerHTML = num.toFixed(2);

4.һ��ͼƬ��һ�����·��img/head/icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:
        var h4 = document.getElementById('h4');
        var str = "img/head/icon/1.jpg"; 
        h4.innerHTML = str.substr(-5,5);

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh4��Ԫ����
��:
        var ipt = prompt('��������֤��');
        var h4 = document.getElementById('h4');
        h4.innerHTML = ipt.toLocaleUpperCase();

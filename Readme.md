# xadmin_django2.0.1

[![Build Status](https://travis-ci.org/mtianyan/hexoBlog-Github.svg?branch=master)](https://travis-ci.org/mtianyan/hexoBlog-Github)

����ԭ�� for Django 2.0�汾��֧�޸Ĳ���bug��

- ֻ�޸�bug, �Լ���Ҫ�Ķ���������Ŀ����, �ײ�Python3.5+django2.0.1��������

## bug����(Ҳ��ͨ��commit��¼�鿴���޸�bug):

- IndexError(�ѽ��)

```
list index out of range
```

>�����������: https://github.com/sshwsfc/xadmin/issues/499

- ����csv��������(�ѽ��)

>�������: �޸�xadmin/plugins/export.py(��Լ221��)get_response��charset��Ϊgbk

```
content_type="%s; charset=gbk" % self.export_mimes[file_type])
```



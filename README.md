Myproxypool

������ѧϰ������By Amos  
ʹ��redis���ݿ�ά����һ����Ѵ����  
����Ϊ��װ��ʹ�ã����غ���Ŀ���Ƶ����python������·���� �磺~\Python36\Lib\site-packages  


ʹ�÷�����  
ps:ʹ��ǰ�����ȸ����Լ��ĵ��Խ������á�   
import Myproxypool  #�����   
Myproxypool.run() #������ά�������   


���ã���ʹ��֮ǰ���У���   
Ŀǰû���ṩ�ⲿ���õ����ýӿڡ�   
��ԭ�ļ����޸����ü��ɣ��ļ���ַ��Myproxypool\proxypool\settings.py   
�������£�   
�Ƿ�����ҳapi�������������󱾵�5000�˿ڣ�����һ������IP�������ַΪ��localhost:5000/get   
WEBAPI_ENABLED = False   

redis���ݿ�������Ϣ   
REDIS_HOST = 'localhost'  # redis���ݿ����ӵ�ַ   
REDIS_PORT = 6379   # redis���ݿ�˿�   
REDIS_PASSWORD = 'xxxxxxx'  # redis���ݿ�����   

�������վ��   
TEST_WEB = 'http://www.baidu.com/'  # ���ڲ��Դ����Ƿ���õ�վ�㣬�ɸ��������Զ���   
���������ҳ��ʱʱ������   
TEST_TIMEOUT = 10   
������� ��λ����   
TEST_PERIOD = 60   

�������������������   
PROXIES_MAX = 100  # �������������   
PROXIES_MIN = 10  # �������������   
����ش�С������� ��λ����   
PROXIES_LEN_CHECK_PERIOD = 30   

����Ĭ������handers   
BASE_HEADERS = {
    'User-Agent':'Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/58.0.3029.110 Safari/537.36'
}
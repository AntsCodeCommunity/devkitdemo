����ָ����
1����java_perf_test�������ص�����
2����cmd����̨�У����뵽java_perf_testĿ¼
3��ִ��mvn clean install -DskipTests ������й���
4�������ɹ��󣬿��ڹ�����־���ҵ���Ӧ��·��
5���������ɹ��İ��ϴ���Ҫ����ķ�������ѡ��jdk11������Ŀ java -Xlog:gc*=info,gc+heap=debug:file=/home/gc-%t.log -jar demo_test-0.0.1-SNAPSHOT.jar ������Ŀ
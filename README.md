# "Call-center issues" (service && client)
(CDEK test task)

<b>����������� �������:</b><br>������� ������ ��� �������, ����� ��������� ������� � Call-�����.

��� ����� ����� �������:

Web-��������� ��� �������, ��� �� ��������� ����� ������ � �������� ������ ��� ��������.

��� ������� ����������� ����� ������� ��� call-������ � ��.

Web-��������� ��� ��������� call-������: ������ ������� ��� �������� ��������. ������
���� ������� � ���������:

����� ������, ���� � ����� ���������� �������.

����� ������ ���� ������ ��� ����� ��� ������ �������.

****************************************************

<h2>������ ������� �� ���� ����������:</h2>

1) service (���-������ ��� ��������� ������ ���������� �������� ������� � ���������� �����)

Spring boot

��: MySQL (��������� ����������� � application.properties)

dump ��: issues.sql (� �������� �������� �������) 

�������: Maven

<h4>������ �������:</h4>

������� 1: mvn spring-boot:run

������� 2: mvn clean package, � IDE - ������ Application.class

<b>URL: http://localhost:9000/postponed</b>

=======================================================================================

2) client (���-���������� ����������� 2 ���� web-�����������: ��� ������� � ��� ��������� call-������)

<h4>������ �������:</h4>

������� 1: mvn clean package, java -jar target/client.jar

������� 2: mvn spring-boot:run

������� 3: mvn clean package, � IDE - ������ Application.class

<b>URL: http://localhost:8080/index.html<b>




=== uLogin - ������ ����������� ����� ���������� ���� ===
Donate link: http://ulogin.ru/
Tags: ulogin, login, social, authorization
Tested up to: 1.27.0
License: GPL3

����� ����������� uLogin ����� ���������� ����. ���������� ������ loginza.

== Description ==

uLogin � ��� ����������, ������� ��������� ������������� �������� ������ ������ � ��������� ��������-�������� ��� ������������� ��������� �����������,
� ���������� ������ � �������� �������������� ������ �������� �� ���������� ����� � ���������� �������� (Google, ������, Mail.ru, ���������, Facebook � ��.)

== Installation ==
1. ����������� ���������� � ����� extensions
2. �������� ��� ������� � ����� ����� /mediaWiki/LocalSettings.php:
  wfLoadExtension( 'ULogin');
3. � ����� LocalSettings.php ����� ������ ������������ ���������:
  $wgULoginProviders = 'vkontakte,odnoklassniki,mailru'; //�������, ��������� �����
  $wgULoginHidden = 'other'; //�������, ��������� ��� ���������
  $wgULoginDisplay = 'small'; //��� 'panel'

== Frequently Asked Questions ==

= ����� �� ���-�� ����������������, ����� ������ ���������? =

���, ������ ���������� ����� ����� ���������!

== Upgrade Notice ==
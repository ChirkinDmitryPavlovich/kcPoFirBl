*������: �������� ���������, ������� �� ���������� ������� ����� ��������� ����� ������ �� �����, ����� ������� ������, ���� ����� 3 ��������. �������������� ������ ����� ������ � ����������, ���� ������ �� ������ ���������� ���������. ��� ������� �� ������������� ������������ �����������, ����� �������� ������������� ���������.*

_1. ������� ����������� �� GitHub_ - ����������

_2. ���������� ����-����� ��������� (����� �������� ����-������ �������� �������������� �����, ���� �� ��������� � � ��������� �����)_

����������: start // ������ �����
�������: array = { "abc", "defg", "hi", "jklm", "no" } // ������������� �������
������: newArray // ����� ������
�������: if (str.Length <= 3) // �������� �� "������ 3" � ���������� � ����� ������ ����, ��� ������ ��������
����� ������: Console.WriteLine(str) // ����� ������ ����������� �������
����������: end // �����

_3. �������� ����������� ����������� ��������� ��������� ������� (���� README.md)_ - ������

_4. �������� ���������, �������� ������������ ������_

array = { "abc", "defg", "hi", "jklm", "no" };

newArray = array.Where(str => str.Length <= 3).ToArray();

Console.WriteLine("����� ������ � ��������, ����� ������� ������ ��� ����� 3:");

foreach (string str in newArray)

        {
        Console.WriteLine(str);
        }

_5. ������������ �������� ������ � ������ ��� ���� ��������� �������� (�� ������ ���� ���, ��� �� ������ ����� ��������, ��� ������� ����� 2, 3, � 4 ������ ���� ����������� � ������ ��������)_
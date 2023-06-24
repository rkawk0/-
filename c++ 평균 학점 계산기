#include <iostream>
using namespace std;

int main() {

	char name[12]; //이름 변수
	int number; //학번 변수

	cout << "이름: ";
	cin.getline(name, 12); //cin.getline으로 공백 포함한 문자열 입력 받기

	cout << "학번: ";
	cin >> number;

	cout << "반갑습니다. " << name << "님\n" << endl;

	cout << "학점 입력을 " << "시작합니다.\n" << endl;

	cout << "===============" << " SWING 31기 " << "===============" << endl;

	float cgrade; //C프로그래밍 변수
	cout << "C프로그래밍(3학점): ";
	cin >> cgrade;

	float cisgrade; //컴퓨터및정보보호개론 변수
	cout << "컴퓨터및정보보호개론(3학점): ";
	cin >> cisgrade;

	float swegrade; //소프트웨어개발실무영어 변수
	cout << "소프트웨어개발실무영어I(1학점): ";
	cin >> swegrade;

	float cegrade; //대학고급영어 변수
	cout << "대학고급영어(2학점): ";
	cin >> cegrade;

	cout << "==========================================" << std::endl;

	float avgrade = (cgrade * 3 + cisgrade * 3 + swegrade * 1 + cegrade * 2) / 9; //학점 평균 변수
	cout << "\n" << name << "(" << number << ")" << "님의 전체 학점은 " << avgrade << "입니다." << endl;

	return 0;
}

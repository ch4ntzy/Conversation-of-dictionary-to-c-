# Convertion-of-dictionary-to-c-
https://youtube.com/shorts/jGSdkYF1H9U?si=GQiDqCAD5bH0Gh-s
#include <iostream>
#include <map>
#include <string>

int main() {

    std::map<std::string, std::string> data = {
        {"EMILIO AGUINALDO", "THE 1st PRESIDENT OF THE PHILIPPINES"},
        {"MANUEL L. QUEZON", "THE 2nd PRESIDENT OF THE PHILIPPINES"},
        {"JOSE P. LAUREL", "THE 3rd PRESIDENT OF THE PHILIPPINES"},
        {"SERGIO OSMEÑA", "THE 4th PRESIDENT OF THE PHILIPPINES"},
        {"MANUEL ROXAS", "THE 5th PRESIDENT OF THE PHILIPPINES"},
        {"ELPIDIO QUIRINO", "THE 6th PRESIDENT OF THE PHILIPPINES"},
        {"RAMON MAGSAYSAY", "THE 7th PRESIDENT OF THE PHILIPPINES"},
        {"CARLOS P. GARCIA", "THE 8th PRESIDENT OF THE PHILIPPINES"},
        {"DIOSDADO MACAPAGAL", "THE 9th PRESIDENT OF THE PHILIPPINES"},
        {"FERSINAND MARCOS", "THE 10th PRESIDENT OF THE PHILIPPINES"},
        {"CORAZON AQUINO", "THE 11th PRESIDENT OF THE PHILIPPINES"},
        {"FIDEL V. RAMOS", "THE 12th PRESIDENT OF THE PHILIPPINES"},
        {"JOSEPH ESTRADA", "THE 13th PRESIDENT OF THE PHILIPPINES"},
        {"GLORIA MACAPAGAL ARROYO", "THE 14th PRESIDENT OF THE PHILIPPINES"},
        {"BENIGNO AQUINO 3rd", "THE 15th PRESIDENT OF THE PHILIPPINES"},
        {"RODRIGO DUTERTE", "THE 16th PRESIDENT OF THE PHILIPPINES"},
        {"BONGBONG MARCOS", "THE 17th PRESIDENT OF THE PHILIPPINES"},
        {"1st PRESIDENT TERM", "JANUARY 23, 1899-APRIL 19, 1901"},
        {"2nd PRESIDENT TERM", "NOVEMBER 15, 1935-AUGUST 1, 1994"}, 
        {"3rd PRESIDENT TERM", "OCTOBER 14, 1943"},
        {"4th PRESIDENT TERM", "AUGUST 1, 1944-MAY 28, 1946"},
        {"5th PRESIDENT TERM", "MAY 28, 1946-APRIL 15, 1948"},
        {"6th PRESIDENT TERM", "APRIL 17, 1948-DECEMBER 30, 1953"},
        {"7th PRESIDENT TERM", "DECEMBER 30, 1953-MARCH 17, 1957"},
        {"8th PRESIDENT TERM", "MARCH 18, 1957-DECEMBER 30, 1961"},
        {"9th PRESIDENT TERM", "DECEMBER 30, 1961-DECEMBER 30, 1965"},
        {"10th PRESIDENT TERM", "DECEMBER 30, 1965-FEBRUARY 25, 1986"},
        {"11th PRESIDENT TERM", "FEBRUARY 25, 1986-JUNE 30, 1992"},
        {"12th PRESIDENT TERM", "JUNE 30, 1992-JUNE 30, 1998"},
        {"13th PRESIDENT TERM", "JUNE 30, 1998-JANUARY 20, 2001"},
        {"14th PRESIDENT TERM", "JANUARY 20, 2001-JUNE 30, 2010"},
        {"15th PRESIDENT TERM", "JUNE 30, 2010-JUNE 30, 2016"},
        {"16th PRESIDENT TERM", "JUNE 30, 2016-JUNE 30, 2022"},
        {"17th PRESIDENT TERM", "JUNE 30, 2022-PRESENT"}
    };

    std::string input;
    std::cout << "question?: ";
    std::getline(std::cin, input); 

    auto it = data.find(input);
    if (it != data.end()) {
        std::cout << it->second << std::endl;
    } else {
        std::cout << "wala naman ganyan eh" << std::endl;
    }

    return 0;
}

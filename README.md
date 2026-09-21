# ratunil_grade_equivalent

#include <stdio.h>

int main() {
    //declare variables
    int score;
    char grade;

    //input
    printf("Enter your score: ");
    scanf("%d", &score);
    
    //process
    if (score >= 90)
        grade = 'A';
    else if (score >= 80)
        grade = 'B';
    else if (score >= 70)
        grade = 'C';
    else if (score >= 60)
        grade = 'D';
    else
        grade = 'F';

    //output
    printf("Grade: %c\n", grade);

    return 0;
}
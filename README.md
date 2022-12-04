# GradingSystem


#include <stdio.h>



int main() {

    

	float courseWork,exam,grade;

	float FinalGrade,courseWorkGrade,examGrade;

	char Pass,Fail,TechnicalFail;

	

	printf(" enter the marks of courseWork ");

	scanf("%f", &courseWork);

	grade=courseWork*100/50;

	printf("%f",grade);

	printf(" enter the marks of exam ");

	scanf("%f", &exam);

	grade=exam*100/50;

	printf("%f",grade);



	FinalGrade=courseWorkGrade+examGrade;

	printf("\n the Final grade is %.2f ",FinalGrade); 

	

	 if(courseWork>=15,exam>=15,FinalGrade>=40) printf("\n Pass %c",Pass);

	else if(courseWork<=14,exam<=14,FinalGrade<=39) printf("\n TechnicalFail %c",TechnicalFail);

	

	Fail=FinalGrade<=39;

	printf("\n Fail %c",Fail);

		

	if (courseWork>=15,exam>=15,FinalGrade=39) printf("\n FinalGrade = 40,\n Pass");

	elseif( FinalGrade=39,courseWork>=14,exam>=14),printf("\n fail");

	

	if(	FinalGrade>=80) printf("\n Grade : A");

	else if(FinalGrade>=60) printf("\n Grade : B");

		else if(FinalGrade>=50) printf("\n Grade : C");

	else if(FinalGrade>=40) printf("\n Grade : D");

	else if(FinalGrade<40) printf("\n F");

	





    return 0;

}




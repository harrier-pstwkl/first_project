# first_project
releasing analysis of employee job satisfaction survey data

dafa features:
1. satisfaction_level - Уровень удовлетворенности работой
2. Last_evaluation - Время с момента последней оценки в годах
3. number_projects - Количество проектов, выполненных за время работы
4. average_monthly_hours - Среднее количество часов на рабочем месте в месяц
5. time_spend_company - Стаж работы в компании в годах
6. work_accident - Происходили ли несчастные случаи на рабочем месте с сотрудником
7. left - уволился ли сотрудник
8. promotion_last_5years - повышался ли сотрудник за последние пять лет
9. department - отдел в котором работает сотрудник
10. salary - относительный уровень зарплаты

implemented analysis elements:
1. read file
2. got descriptice statistics
3. performed correlation analysis with sns.heatmap
4. got number of employees inside each department
5. described salary destribution 
6. described salary destribution inside departments
7. performed statistical tests: checked data destribution and selected the appropriate test
8. for a better understanding, I carried out statistics on the employees who left and those who remained
9. built plots for binary and non binary features, trained a few LinearDiiscriminantAnalysis models (for scaled, normalized data) 

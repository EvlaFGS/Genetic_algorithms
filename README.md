Представлена реализация алгоритма светлячков - оригинального и модифицированого. В качестве целевой функции выбрана: f(x)=x^6-sin⁡(x+7*x^3). В качестве модификаций предлагается:
		1.Не сравнивать положения светлячков между собой, а сравнивать с лучшим положением в предыдущей итерации – то есть наиболее близким к ответу. Это позволит алгоритму работать быстрее.
	2.Шаг задавать через функцию f(t)=X_coef/√(t+1), где Xcoef – это число, подобранное вручную (в данной задаче Xcoef = 30, выбрано для того, чтобы на начальных итерациях шаг был больше стандартного); t – это итерация. Таким образом, чем больше будет итерация, тем меньше шаг, то есть алгоритм будет получать более точные значения. 

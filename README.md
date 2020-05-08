# project_spring_2020

[![CircleCI](https://circleci.com/gh/biof309/project_spring_2020/tree/master.svg?style=shield)](https://circleci.com/gh/biof309/project_spring_2020/tree/master)

My project is "Writting a Python program to covert tempratures".

In this project I would like to learn how to use python programming language to convert the tempratures.
About 5 major temperature scales are used in world. Among them,the Fahrenheit and Celsius scales are mostly used in our daily life,
and the Kelvin and Rankine scales are mostly used in industry and science.
I would like to practise the convesion among  Celsius, Fahrenheit and Rankine. 

The orignal material and code source are from:

1. biof309/project_spring_2020_Thursday class;
2. NIAID bioinformatics training webinar;
3. Learn python in y monuts;
4. google search for conversion of the temperature scales. 

The formulas to convert between degrees Celsius (C) to to degrees Fahrenheit (F) are:
Celsius to Fahrenheit formula: oF = oC * 1.8 + 32;
Fahenheit to Celsius formula : oC = (oF-32)/1.8;

The formula to convert between degrees Rankine (Ra) to degrees Celsius (C) is:
Rankine (Ra) to Celsius formula: oC = Ra/1.8 - 273.15;
celsius to Rankine (Ra) formula: oR = (oC +273.15) * 1.8;

The formula to convert between degrees Rankine (Ra) to degrees Fahrenheit (F) is:
Fahrenheit to Rankine formula : oR = F + (237.15 * 1.8 - 32);
Rankine to Fahrenheit formula:  oF = oR - (237.15 * 1.8-32);

The formula to convert from degrees Celsius (C) to to degrees Kelvin (k) is:
Celsius to Kelvin formula: oK = oC +273.15
Kelvin to Celsius formula: oC = oK - 273.15 (oK 0 degree == -273.15 oC---absolute temprature)

I would first to practise with a assumed temperature mesurement to do the conversion and then will extend the script to any number of the temprature measurement.

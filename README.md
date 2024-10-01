# DADS5001-Miniproject
Mini-Project is about data Analysis of socio-economic : Thailand on the global stage

# Import data and Read data information

*   **Import data from csv.file :** socio-economic and gdp per capita
*   **Read data information :** we found that DataFrame has 9 columns and 3,269 rows

## Describe data informantion in each column

*   **Country name :** 174 countries
*   **Country code :** 3 letter code
*   **Year :** 2000-2019
*   **Life expectancy :**  The statistical measure of the average number of years a person is expected to live
*   **Health Expenditure (% of GDP) :** Level of current health expenditure expressed as a percentage of GDP
*   **Education Expenditure (% of GDP) :** General government expenditure on education (current,capital, and transfers) is expressed as a percentage of GDP
*   **Unemployment (% total labor force) :** Unemployment refers to the % share of the labor force that is without work but available for and seeking employment
*  **GDP per Capita :** measure that represents the average economic output (or income) per person in a country.
      It is calculated by dividing a country's Gross Domestic Product (GDP)—the total value of 
# Table of contents

**1. Question we want to know**
- xxxxxxxx

**2. Data preparation process**
- Choosing data for analyze
- Data importing
- Data cleansing

**3. Data analyze process**
- Part 1 : Global scale
- Part 2 : Thailand in Global scale
- Part 3 : Summary & Conclusion

# Import data and Read data information

*   **Import data from csv.file :** socio-economic and gdp per capita
*   **Read data information :** we found that DataFrame has 9 columns and 3,269 rows

## Describe data informantion in each column

*   **Country name :** 174 countries
*   **Country code :** 3 letter code
*   **Year :** 2000-2019
*   **Life expectancy :**  The statistical measure of the average number of years a person is expected to live
*   **Health Expenditure (% of GDP) :** Level of current health expenditure expressed as a percentage of GDP
*   **Education Expenditure (% of GDP) :** General government expenditure on education (current,capital, and transfers) is expressed as a percentage of GDP
*   **Unemployment (% total labor force) :** Unemployment refers to the % share of the labor force that is without work but available for and seeking employment
*  **GDP per Capita :** measure that represents the average economic output (or income) per person in a country.
      It is calculated by dividing a country's Gross Domestic Product (GDP)—the total value of goods and services produced within a country over a specific time period—by its population.

# Data cleansing process

![image](https://github.com/user-attachments/assets/07c64229-95ea-42af-bf4a-8430fef81f3b)

![image](https://github.com/user-attachments/assets/4f708c32-6036-4b5f-8fef-6e24256224ba)

# Part 1 : Global Scale
**1)    Choropleth map**
*   Global Life expectancy
*   Global Healthcare expenditure
*   Global Education expenditure
*   Global Unemployment rate

**2) Scatter plot : GDP per capita vs. 4 parameters**
*   Global Life expectancy
*   Global Healthcare expenditure
*   Global Education expenditure
*   Global Unemployment rate

**3) Bubble chart : The relationship between GDP per Capita, life expectancy rate and health expenditure rate**
*   Represent the relationship between GDP per capita (x-axis) , life expectancy (y-axis) and health expenditure (bubble size)
*   Represent the relationship between GDP per capita (x-axis) , health expenditure rate (y-axis) and education expenditure rate (bubble size)

**4) Correlation matrix :** The relationship between GDP per Capita, life expectancy, health expenditure rate, education expenditure rate and unemployment rate.

**5) Box plot :** Box plot of life expectancy to represent life expectancy shape

## Choropleth map

![image](https://github.com/user-attachments/assets/9be0d0dc-8fa2-4816-938c-1071653699fc)

![image](https://github.com/user-attachments/assets/50c8735f-92b5-4c21-a073-a666702859d0)

![image](https://github.com/user-attachments/assets/421464c6-4d3d-462b-8a11-0ace8cc9fc0f)

![image](https://github.com/user-attachments/assets/0e12001c-7264-4b53-902c-7bb8e088d5b1)

## Box plot

*   นำข้อมูลอายุขัยของประชากร (Life expectancy) มาพล๊อตในกราฟ Box plot เพื่อดูการกระจายของข้อมูล ซึ่งจากการดำเนินการพล๊อตกราฟพบว่า อายุขัยของประชากรโลกจำนวนประมาณ 50% จะอยู่ที่ช่วง 65 - 75 ปี เมื่อพิจารณาค่า Interquatile range (IQR) หรือถ้าดูจากรูปคือพื้นที่กล่องสีน้ำเงินของกราฟ Box plot

![image](https://github.com/user-attachments/assets/97c421b4-314b-47bb-ab1d-2eba3f53d4c4)

## Trendline
### Thailand vs Global Life expectancy Over Time

* จากกราฟ จะเห็นได้ว่า ค่าอายุขัยของประเทศไทยตั้้งแต่ปี 2001 ถึงปี 2019 มีค่าที่อยู่ใน<u>แนวโน้มที่เพิ่มมากขึ้น</u> โดยมีอัตราการเพิ่มขึ้นอยู่ที่ 8.92 %
  
* อายุขัยของประชากรโลกตั้้งแต่ปี 2001 ถึงปี 2019 <u>มีแนวโน้มที่เพิ่มมากขึ้น</u>ด้วยเช่นกัน โดยมีอัตราการเพิ่มขึ้นอยู่ที่ 8.43 %
  
* สามารถสรุปได้ว่าค่าอายุขัยของประชากรไทยและค่าอายุขัยของประชากรโลก ตั้งแต่ปี 2001 ถึงปี 2019 <u>มีแนวโน้มที่เพิ่มมากขึ้น</u> โดยค่าอายุขัยประชากรของประเทศไทยจะมีค่า<u>มากกว่า</u>ค่าเฉลี่ยของประชากรโลก

![image](https://github.com/user-attachments/assets/12710f28-e8f7-4048-99d8-ce1bb7a9f6aa)

### Thailand vs Health expenditure Over Time

* จากกราฟ จะเห็นได้ว่า ค่าใช้จ่ายด้านสุขภาพประเทศไทยตั้้งแต่ปี 2001 ถึงปี 2019 มีค่าที่อยู่ใน<u>แนวโน้มที่เพิ่มมากขึ้น</u> โดยมีอัตราการเพิ่มขึ้นอยู่ที่ 25.08 %

* ค่าใช้จ่ายด้านสุขภาพของโลกตั้้งแต่ปี 2001 ถึงปี 2019 <u>มีแนวโน้มที่เพิ่มมากขึ้น</u>ด้วยเช่นกัน โดยมีอัตราการเพิ่มขึ้นอยู่ที่ 14.87 %
  
* สามารถสรุปได้ว่าค่าใช้จ่ายด้านสุขภาพไทยและค่าใช้จ่ายด้านสุขภาพของโลก ตั้งแต่ปี 2001 ถึงปี 2019 <u>มีแนวโน้มที่เพิ่มมากขึ้น</u> โดยค่าใช้จ่ายด้านสุขภาพของประเทศไทยจะมีค่า<u>น้อยกว่า</u>ค่าเฉลี่ยค่าใช้จ่ายด้านสุขภาพของโลก

![image](https://github.com/user-attachments/assets/80dbdcfe-738a-4aab-97ca-0ebbdbb46235)

### Thailand vs Global Education expenditure over time

* จากกราฟ จะเห็นได้ว่า ค่าใช้จ่ายด้านการศึกษาของประเทศไทยตั้้งแต่ปี 2001 ถึงปี 2019 มีค่าที่อยู่ใน<u>แนวโน้มที่ลดลง</u> โดยมีอัตราการลดลงอยู่ที่ 38.32 %

* ค่าใช้จ่ายด้านการศึกษาของประชากรโลกตั้้งแต่ปี 2001 ถึงปี 2019 <u>มีแนวโน้มที่ลดลง</u>ด้วยเช่นกัน โดยมีอัตราการลดลงอยู่ที่ 1.996 %

* สามารถสรุปได้ว่าค่าใช้จ่ายด้านการศึกษาของประชากรไทยและค่าใช้จ่ายด้านการศึกษาของประชากรโลก ตั้งแต่ปี 2001 ถึงปี 2019 <u>มีแนวโน้มที่ลดลง</u> โดยค่าใช้จ่ายด้านการศึกษาของประเทศไทยจะมีค่า<u>น้อยกว่า</u>ค่าเฉลี่ยของค่าใช้จ่ายด้านการศึกษาโลก

![image](https://github.com/user-attachments/assets/589e82ab-8436-4d12-a5ef-9384fe3b34d4)

### Thailand vs Global Unemployment rate over time

* จากกราฟ จะเห็นได้ว่า อัตราการว่างงานของประเทศไทยตั้้งแต่ปี 2001 ถึงปี 2019 มีค่าที่อยู่ใน<u>แนวโน้มที่ลดลง</u> โดยมีอัตราการลดลงอยู่ที่ 72.31 %

* อัตราการว่างงานของประชากรโลกตั้้งแต่ปี 2001 ถึงปี 2019 <u>มีแนวโน้มที่ลดลง</u>ด้วยเช่นกัน โดยมีอัตราการลดลงอยู่ที่ 16.28 %

* สามารถสรุปได้ว่าอัตราการว่างงานของประชากรไทยและอัตราการว่างงานของประชากรโลก ตั้งแต่ปี 2001 ถึงปี 2019 <u>มีแนวโน้มที่ลดลง</u> โดยอัตราการว่างงานของประเทศไทยจะมีค่า<u>น้อยกว่า</u>ค่าเฉลี่ยของอัตราการว่างงานโลก

![image](https://github.com/user-attachments/assets/241c89ee-f508-42bf-94e3-75bd4da1ce39)

## Scatter plot : GDP per Capita compare to our four parameters

### Prepare data for visualization
1) Merged two data table (socio-ecomomic data and gdp per capita)
2) Calculate the median of 'GDP per capita'
3) Fill NaN values in 'GDP per capita' with the median
4) Print the updated DataFrame

![image](https://github.com/user-attachments/assets/727414cd-fb98-4fc3-b797-523f9dd9b06f)

### GDP per capita vs. Life Expectancy
* กราฟนี้แสดงความสัมพันธ์ระหว่าง GDP ต่อหัวของแต่ละประเทศกับอายุขัยเฉลี่ยของประชากรโดยใช้เส้น trendline ordinary least squares แสดงแนวโน้มโดยรวมของข้อมูล
  
* จากการวิเคราะห์ Treanline บ่งบอกว่า ยิ่ง GDP per Capita มากขึ้น อายุขัยของประชากรก็จะเพิ่มมากขึ้นด้วยเช่นกัน

![image](https://github.com/user-attachments/assets/76a2e944-0de4-4da8-ac93-0f83d0063b93)

### Thailand's GDP per Capita compare to Life expectancy

* กราฟนี้แสดงความสัมพันธ์ระหว่าง GDP ต่อหัวของแต่ละประเทศ กับ อายุขัยเฉลี่ยของประชากรโดยใช้เส้น trendline ordinary least squares แสดงแนวโน้มโดยรวมของข้อมูล
  
* จุดสีแดงจากกราฟ บ่งบอกถึง ค่า GDP ต่อหัวของประเทศไทยเทียบ กับ อายุขัยเฉลี่ยของประชากร
  
* จุดสีแดงที่แทนประเทศไทยอยู่ในตำแหน่งที่บ่งบอกว่า ประเทศไทยมีทั้ง GDP ต่อหัวและอายุขัยเฉลี่ยที่อยู่ในระดับปานกลาง เมื่อเทียบกับประเทศอื่นๆ ทั่วโลก ซึ่งหมายความว่าประเทศไทยยังมีศักยภาพในการพัฒนาคุณภาพชีวิตของประชาชนให้ดีขึ้นได้อีก
  
* จุดข้อมูลของประเทศต่างๆ กระจายตัวออกไปตามแนวเส้นตรงที่มีความชันเป็นบวก ซึ่งแสดงให้เห็นถึงแนวโน้มทั่วไปของความสัมพันธ์นี้ 
อย่างไรก็ตาม ก็มีบางประเทศที่แม้จะมี GDP ต่อหัวสูง แต่กลับมีอายุขัยเฉลี่ยต่ำกว่าที่คาดการณ์ไว้ ซึ่งอาจเกิดจากปัจจัยอื่นๆ ที่เกี่ยวข้อง

![image](https://github.com/user-attachments/assets/1df0f947-6d34-4d22-9363-9ba9dd939f21)

### GDP per capita vs. Health expenditure rate

*  กราฟนี้แสดงความสัมพันธ์ระหว่าง GDP ต่อหัวของแต่ละประเทศ กับ ค่าใช้จ่ายด้านสุขภาพ โดยใช้เส้น trendline ordinary least squares แสดงแนวโน้มโดยรวมของข้อมูล

*   จากการวิเคราะห์ Treanline บ่งบอกว่า ยิ่ง GDP per Capita มากขึ้น ค่าใช้จ่ายด้านสาธารณสุขก็จะเพิ่มตามไปด้วย

![image](https://github.com/user-attachments/assets/59c522ea-af5a-42e2-9fda-7fe93fa297b3)

### Thailand's GDP per Capita compare to  Health expenditure rate

* กราฟนี้แสดงความสัมพันธ์ระหว่าง GDP ต่อหัวของแต่ละประเทศ กับ อัตราค่าใช้จ่ายด้านสุขภาพ โดยใช้เส้น trendline ordinary least squares แสดงแนวโน้มโดยรวมของข้อมูล
  
* จุดสีแดงจากกราฟ บ่งบอกถึง ค่า GDP ต่อ หัวของประเทศไทยเทียบ กับ อัตราค่าใช้จ่ายด้านสุขภาพ
  
* ประเทศที่มีรายได้เฉลี่ยต่อหัวสูง (GDP ต่อหัวสูง) มักจะมีสัดส่วนการใช้จ่ายด้านสุขภาพที่สูงขึ้นตามไปด้วย ซึ่งแสดงให้เห็นว่าประเทศที่มีรายได้สูงมักจะให้ความสำคัญกับการดูแลสุขภาพของประชาชนมากขึ้น
  
* จุดสีแดงที่แทนประเทศไทยอยู่ในตำแหน่งที่บ่งบอกว่า ประเทศไทยมีทั้ง GDP ต่อหัวและสัดส่วนการใช้จ่ายด้านสุขภาพที่อยู่ในระดับปานกลาง เมื่อเทียบกับประเทศอื่นๆ ทั่วโลก
  
* จุดข้อมูลของประเทศต่างๆ กระจายตัวออกไปตามแนวเส้นตรงที่มีความชันเป็นบวกซึ่งแสดงให้เห็นถึงแนวโน้มทั่วไปของความสัมพันธ์นี้ 
อย่างไรก็ตาม ก็มีบางประเทศที่แม้จะมี GDP ต่อหัวสูง แต่กลับมีสัดส่วนการใช้จ่ายด้านสุขภาพต่ำกว่าที่คาดการณ์ไว้ ซึ่งอาจเกิดจากปัจจัยอื่นๆ ที่เกี่ยวข้อง

![image](https://github.com/user-attachments/assets/a6cd8125-761b-4f8e-879a-18e6ab89d736)

### GDP per capita vs. Education expenditure rate
* กราฟนี้แสดงความสัมพันธ์ระหว่าง GDP ต่อหัวของแต่ละประเทศ กับ อัตราค่าใช้จ่ายด้านการศึกษา โดยใช้เส้น trendline ordinary least squares แสดงแนวโน้มโดยรวมของข้อมูล
  
* จากการวิเคราะห์ Treanline บ่งบอกว่า ยิ่ง GDP per Capita มากขึ้น อัตราค่าใช้จ่ายด้านการศึกษา ก็จะเพิ่มตาม
  
* ทั้งนี้ จากการสังเกตจากกราฟพบว่า ความชันของเส้น Treandline มีไม่มากนัก ทำให้สรุปได้ว่า การเพิ่มขึ้นของ GDP per Capita ไม่ได้ทำให้อัตราค่าใช้จ่ายด้านการศึกษาเพิ่มขึ้นตามอย่างมีนัยสำคัญ

![image](https://github.com/user-attachments/assets/4ef51954-3e7c-4a64-b17d-edbc8fa3a4bb)

### Thailand's GDP per Capita compare to Education expenditure rate

* กราฟนี้แสดงความสัมพันธ์ระหว่าง GDP ต่อหัวของแต่ละประเทศ กับ อัตราค่าใช้จ่ายด้านการศึกษาโดยใช้เส้น trendline ordinary least squares แสดงแนวโน้มโดยรวมของข้อมูล
  
* จุดสีแดงจากกราฟ บ่งบอกถึง ค่า GDP ต่อ หัวของประเทศไทยเทียบ กับ อัตราค่าใช้จ่ายด้านการศึกษา
  
* กราฟแสดงให้เห็นถึงความสัมพันธ์ในทางเดียวกันระหว่าง GDP ต่อหัวกับอัตราค่าใช้จ่ายด้านการศึกษา ซึ่งหมายความว่า เมื่อ GDP ต่อหัวของประเทศหนึ่งสูงขึ้น อัตราค่าใช้จ่ายด้านการศึกษาจะมีแนวโน้มเพิ่มขึ้นตาม
  
* จุดสีแดงที่แทนประเทศไทยอยู่ในตำแหน่งที่บ่งบอกว่า ประเทศไทยมีทั้ง GDP ต่อหัวและสัดส่วนค่าใช้จ่ายด้านการศึกษาที่อยู่ในระดับปานกลาง เมื่อเทียบกับประเทศอื่นๆ ทั่วโลก
  
* จุดข้อมูลของประเทศต่างๆ กระจายตัวออกไปตามแนวเส้นตรงที่มีความชันเป็นบวก 
อย่างไรก็ตาม ก็มีบางประเทศที่แม้จะมี GDP ต่อหัวสูง แต่กลับมีสัดส่วนการใช้จ่ายด้านการศึกษาสูงกว่าที่คาดการณ์ไว้ ซึ่งอาจเกิดจากปัจจัยอื่นๆ ที่เกี่ยวข้อง

![image](https://github.com/user-attachments/assets/9cce80e4-3e54-4502-9018-888e29892f29)

### GDP per capita vs. Unemployment rate

* กราฟนี้แสดงความสัมพันธ์ระหว่าง GDP ต่อหัวของแต่ละประเทศ กับ อัตราการว่างงาน โดยใช้เส้น trendline ordinary least squares แสดงแนวโน้มโดยรวมของข้อมูล
  
* จากการวิเคราะห์ Treanline บ่งบอกว่า ยิ่ง GDP per Capita มากขึ้น อัตราการว่างงาน จะลดลง
  
* จากการวิเคราะห์กราฟ ทำให้พบว่า GDP ต่อหัวของแต่ละประเทศ กับ อัตราการว่างงาน มีความสัมพันธ์ในทางตรงกันข้ามกัน

![image](https://github.com/user-attachments/assets/425eda47-8623-40b3-9740-d7c4a75eb100)

### Thailand's GDP per Capita compare to Unemployment rate

* กราฟนี้แสดงความสัมพันธ์ระหว่าง GDP ต่อหัวของแต่ละประเทศ กับ อัตราการว่างงาน โดยใช้เส้น trendline ordinary least squares แสดงแนวโน้มโดยรวมของข้อมูล
  
* จุดสีแดงจากกราฟ บ่งบอกถึง ค่า GDP ต่อ หัวของประเทศไทยเทียบ กับ อัตราการว่างงาน
  
* กราฟแสดงให้เห็นถึงความสัมพันธ์ในทางตรงกันข้ามระหว่าง GDP ต่อหัวกับอัตราการว่างงาน ซึ่งหมายความว่า เมื่อ GDP ต่อหัวของประเทศหนึ่งสูงขึ้น อัตราการว่างงานกลับมีแนวโน้มลดลง
  
* จุดสีแดงที่แทนประเทศไทย ซึ่งบ่งบอกว่า ประเทศไทยมีทั้ง GDP ต่อหัวและอัตราการว่างงานที่อยู่ในระดับปานกลาง เมื่อเทียบกับประเทศอื่นๆ ทั่วโลก
  
* จุดข้อมูลของประเทศต่างๆ มีแนวโน้มการกระจายกระจายตัวออกไปตามแนวเส้นตรงที่ความชันเป็นลบ แต่อย่างไรก็ตาม บางประเทศที่แม้จะมี GDP ต่อหัวสูง แต่กลับมีอัตราการว่างงานสูงกว่าที่คาดการณ์ไว้ ซึ่งอาจเกิดจากปัจจัยอื่นๆ ที่เกี่ยวข้อง

![image](https://github.com/user-attachments/assets/76567279-de3b-46da-9e84-83012390a459)

## Bubble chart
### The relationship between GDP per capita, life expectancy, and health expenditure rate
* Bubble chart แสดงถึงความสัมพันธ์ระหว่าง <u>GDP per capita (แกน x)</u> , <u>life expectancy (แกน y)</u> และ <u>health expenditure rate(ขนาดของฟองสบู่)</u>

* ประเทศที่ความแข็งแกร่งทางเศรษฐกิจที่มากกว่า (ปรากฎอยู่ทางขวาของกราฟ) มีแนวโน้มที่จะมีอายุขัยที่ยาวนานกว่า แต่ประเทศที่ระบบสาธารณสุขมีประสิทธิภาพมากกว่า (ฟองขนาดเล็กกว่า) อาจบรรลุผลลัพธ์ที่ดีได้ (ในที่นี้หมายถึงการทำให้อายุขัยของประชากรในประเทศเพิ่มขึ้น) โดยไม่จำเป็นต้องจ่ายค่าใช้จ่ายด้านสาธารณสุขมากจนเกินไป
  
* ประเทศที่มีฟองขนาดใหญ่กว่า อาจส่งสัญญาณถึงความไม่มีประสิทธิภาพในการจัดการด้านสาธารณสุข เนื่องจากมีค่าใช้จ่ายสูงในด้านการดูแลสุขภาพแต่อายุขัยไม่ได้สูงสูงตามสัดส่วนที่ควรจะเป็น

![image](https://github.com/user-attachments/assets/1482cd47-afe0-40f9-8258-8b81f94efd09)

### Relationship between GDP per capita, Life Expectancy and Health expenditure rate : Thailand
* ประเทศไทยมี GDP ต่อหัว อยู่ในระดับกลางๆ ของกลุ่ม (ประมาณ 5,000-10,000 ดอลลาร์สหรัฐฯ ต่อคน)
  
* อายุขัยเฉลี่ย ของประชากรไทยอยู่ในระดับประมาณ 70-75 ปี ซึ่งสอดคล้องกับกลุ่มประเทศที่มีรายได้ปานกลาง
  
* Bubble ของประเทศไทยอยู่ในระดับกลาง ซึ่งหมายถึง ค่าใช้จ่ายด้านสุขภาพอยู่ในเกณฑ์ปานกลางเมื่อเทียบกับประเทศอื่นๆ

![image](https://github.com/user-attachments/assets/4899a270-037a-46ad-957f-905b6ce1e04b)

### The relationship between GDP per capita, life expectancy, and Education expenditure rate
*   Bubble chart แสดงถึงความสัมพันธ์ระหว่าง <u>GDP per capita (แกน x)</u> , <u>health expectancy rate (แกน y)</u> และ <u>education expenditure rate (ขนาดของฟองสบู่)</u>

![image](https://github.com/user-attachments/assets/a122a6ea-019f-4793-8d0f-51bb78de00ad)

# Relationship between GDP per capita, Life Expectancy and Education expenditure rate : Thailand

* ประเทศไทยมี GDP ต่อหัว อยู่ในระดับปานกลาง (ประมาณ 5,000-10,000 ดอลลาร์สหรัฐฯ ต่อคน)
  
* อัตราการใช้จ่ายด้านสุขภาพ ของประเทศไทยอยู่ในช่วงประมาณ 3-6 % ของ GDP ซึ่งอยู่ในระดับปานกลางเมื่อเทียบกับประเทศอื่น ๆ ในกราฟ
  
* ขนาด Bubble ของประเทศไทยมีขนาดค่อนข้างเล็ก แสดงให้เห็นว่าค่าใช้จ่ายด้านการศึกษาไม่ได้มากเท่ากับบางประเทศที่มีขนาดของ Bubble ที่ใหญ่กว่า

![image](https://github.com/user-attachments/assets/4f2085ce-5937-4d11-8872-fe96cac6f756)

## Correlation matrix

* จากการวิเคราะห์กราฟ Correlation matrix พบว่า <u>อัตราค่าใช้จ่ายด้านสุขภาพ (Health expenditure rate)</u> กับ <u>อัตราค่าใช้จ่ายด้านการศึกษา (Education expenditure rate)</u> <u>มีค่าความสัมพันธ์ (Correlation) มากที่สุด โดยเท่ากับ 0.32</u> ซึ่งค่าดังกล่าว บ่งบอกถึงกรณีที่รัฐบาลของประเทศนั้นๆ มีความต้องการจะลงทุนด้านการพัฒนาทรัพยากรมนุษย์ พวกเขามีแนวโน้มที่จะเพิ่มค่าใช้จ่ายทั้งในด้านการศึกษาและสาธารณสุขพร้อมกัน ซึ่งสามารถสะท้อนได้ว่า <u>อัตราค่าใช้จ่ายด้านสุขภาพ (Health expenditure rate) กับ อัตราค่าใช้จ่ายด้านการศึกษา (Education expenditure rate) เป็นค่าที่บ่งบอกถึงสถานะความเป็นอยู่ที่ดีของสังคม</u>
   
![image](https://github.com/user-attachments/assets/5620dd96-ee29-4c25-a9a2-a66fdda76a1f)

## Correlation matrix : Thailand

*   จากการวิเคราะห์กราฟ Correlation matrix พบว่า <u>อัตราค่าใช้จ่ายด้านสุขภาพ (Health expenditure rate)</u> กับ <u>อายุขัย (Life expectancy)</u> <u>มีค่าความสัมพันธ์ (Correlation) มากที่สุด โดยเท่ากับ 0.91</u>

![image](https://github.com/user-attachments/assets/833a7372-8aaa-41ce-ba1d-bf55397994f7)


  








# CO2 Emissions Data Analysis in Tableau

We often come across situations where our data is divided into multiple tables and we need to combine these tables to create a final data report. If we are using Tableau as a tool for data visualization we can perform the following steps:

## 1. Loading multiple datasets
The first step in this process is loading all the datasets that we want to connect into the tableau.

![image](https://github.com/user-attachments/assets/e1f937a0-1962-4158-a9a6-f605e6fddbbe)

## 2. Link them using JOINS
Once we have all the tables loaded in Tableau we can now connect them with the help of JOINS

![image](https://github.com/user-attachments/assets/6bc29938-1cbb-46b4-85c8-acd9ece43f22)

Once the table populates we can see the Year and Year 1 column has number(#) above them which we need to change to Date as shown below

![image](https://github.com/user-attachments/assets/5d93af8c-d477-417a-9039-ac80cb2d41f9)

![image](https://github.com/user-attachments/assets/7fe5218f-acf1-4d14-9099-58d441b9788d)

![image](https://github.com/user-attachments/assets/2f44abdc-0eaa-4ce8-9794-040233e6b7c5)

![image](https://github.com/user-attachments/assets/398f9023-0ac6-4141-818d-bb4fd45b4aeb)

Finally, we have all the tables linked to each other and now we can go ahead to create our reports

## 3. Create data visualizations:

![image](https://github.com/user-attachments/assets/a1ddc834-a407-4077-b7c1-e4777450ec0d)

![image](https://github.com/user-attachments/assets/b4d61414-5863-4c51-8495-183462d400eb)

![image](https://github.com/user-attachments/assets/153cdee3-d7f7-466d-a456-2d144c739a7a)

![image](https://github.com/user-attachments/assets/70e29b13-7f13-4b4f-b3f1-732a46d8da7f)

![image](https://github.com/user-attachments/assets/26fa5849-40c2-4cd0-bd9d-f4c361d704e5)

![image](https://github.com/user-attachments/assets/9dadc97e-e5e0-4f32-8d59-96a045915707)

## Analysis:

Based on the interactive visualization, we can observe the following as shown below:

1. Let us consider the GDP scatterplot which showcases that the US has the largest GDP in the world but it does not produce the highest CO2 emissions per capita. Whereas, Qatar has a much smaller GDP and yet produces the highest CO2 emissions per capita in the world.

2. All the metrics mentioned in this Energy scatterplot are on a per capita basis. While observing this scatterplot, it can be seen that an increase in Energy consumption is not directly proportional to an increase in CO2 emissions. Let us take the example of Iceland that is using 18.16k kgoe of energy while emitting CO2 of 5.90 ppm. Whereas, Qatar consumes 15.34k kgoe of energy and emits CO2 of 44.02 ppm. The difference in energy consumption between these two countries is 3000 kgoe which is relatively small but the difference in overall emissions is very large.


Conclusions:
- GDP is not directly proportional to CO2 emissions. Hence, the size of the GDP does not relate to the per capita CO2 emissions
- Energy consumption per capita is also not directly proportional to CO2 emissions per capita
- Based on the examples and the scatterplot, we can infer that using different types of energy sources can result in lower CO2 emissions per capita 
  irrespective of GDP and Energy Consumption
- Saudi Arabia tops the list of carbon dioxide-emitting nations, primarily due to the burning of fossil fuels such as coal, oil and natural gas for power 
  generation or to fuel vehicles and machines
- The U.S. is second on the list due to industrialization and population growth
- In 2011, Australian emissions (including land use and forestry) made the country rank third on the list

Please click on the link below to see the data visualization in tableau:
https://public.tableau.com/views/CO2emissions_17242244722020/Dashboard32?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

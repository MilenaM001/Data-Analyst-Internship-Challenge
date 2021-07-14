Customer Lifetime Value (CLV). 

Data Analysit Interhip challenge to calculate  CLV. Original Post 

https://www.linkedin.com/jobs/view/2635526057/?refId=c7fa0b8a-70c3-4675-826b-ce1392c4a9d2

To calculate CLV the information of this video is used. 

https://www.youtube.com/watch?v=JR8_GNINmuQ


1. A pivot table is created to group all orders by customer. 

<img width="362" alt="Screenshot 2021-07-10 at 17 39 32" src="https://user-images.githubusercontent.com/87210577/125171134-7d6e4280-e1aa-11eb-8396-b5c2777fb332.png">


<img width="362" alt="Screenshot 2021-07-10 at 18 14 07" src="https://user-images.githubusercontent.com/87210577/125171168-a8589680-e1aa-11eb-87f3-96300678141a.png">

2. Calculate Average order value for each customer.

<img width="362" alt="Screenshot 2021-07-10 at 18 42 33" src="https://user-images.githubusercontent.com/87210577/125171895-9f69c400-e1ae-11eb-9042-75c8bdea8267.png">

<img width="362" alt="Screenshot 2021-07-10 at 18 44 25" src="https://user-images.githubusercontent.com/87210577/125171956-e0fa6f00-e1ae-11eb-8bb9-80fba3e86028.png">

<img width="192" alt="Screenshot 2021-07-12 at 21 41 21" src="https://user-images.githubusercontent.com/87210577/125353051-f5c73600-e359-11eb-9ada-cad278bb1ba8.png">

3. Calculate number of orders per customer (Use the first column from the sheet "data", A2 is in the actual sheet you are working)

<img width="100" alt="Screenshot 2021-07-12 at 21 42 55" src="https://user-images.githubusercontent.com/87210577/125353215-28712e80-e35a-11eb-9c83-e0bbd3f44aee.png">

4. Calculate the total number of customers 

<img width="100" alt="Screenshot 2021-07-12 at 21 44 24" src="https://user-images.githubusercontent.com/87210577/125353347-58203680-e35a-11eb-9a50-8facdc79e840.png">


5. Calculate average order frequency: number of orders per customer divided by number of customers

<img width="120" alt="Screenshot 2021-07-14 at 20 39 16" src="https://user-images.githubusercontent.com/87210577/125682751-5daea08b-9d5b-436d-ac99-ad1d05b249ca.png">


6. Calculate average customer value: average order value multiplied by average order frequency

<img width="80" alt="Screenshot 2021-07-12 at 21 53 55" src="https://user-images.githubusercontent.com/87210577/125354440-b863a800-e35b-11eb-9af0-c5572761b2ae.png">


7. Average customer lifespan: 1st order date subtracted by the last order date. For this find the minimun and maximun date. Then use the function DATEDIF to find the difference between the data in months. 

<img width="150" alt="Screenshot 2021-07-12 at 21 56 56" src="https://user-images.githubusercontent.com/87210577/125354768-185a4e80-e35c-11eb-9f0c-d37a7d5dbc8f.png">

<img width="150" alt="Screenshot 2021-07-12 at 22 15 50" src="https://user-images.githubusercontent.com/87210577/125356904-c666f800-e35e-11eb-8225-44e3aaeff4e0.png">


<img width="140" alt="Screenshot 2021-07-12 at 21 59 05" src="https://user-images.githubusercontent.com/87210577/125355034-6b340600-e35c-11eb-8891-65350bbec8e5.png">

8. Customer lifetime value: average customer lifespan multiplied by average value

<img width="130" alt="Screenshot 2021-07-12 at 22 05 13" src="https://user-images.githubusercontent.com/87210577/125355729-44c29a80-e35d-11eb-8a8f-9d5625c98273.png">


<img width="700" alt="Screenshot 2021-07-11 at 18 17 20" src="https://user-images.githubusercontent.com/87210577/125355819-628fff80-e35d-11eb-8c64-917876ba6864.png">



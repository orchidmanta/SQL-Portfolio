## Question 1
### What are the most popular EV brands?

\n SELECT make, COUNT(*) AS vehicle_count 
FROM ev_clean
GROUP BY make
ORDER BY vehicle_count DESC
LIMIT 10; \n


## Answer 1

|make      |vehicle_count|
|----------|-------------|
|TESLA     |110,537      |
|CHEVROLET |19,044       |
|NISSAN    |15,955       |
|FORD      |14,938       |
|KIA       |13,617       |
|TOYOTA    |11,381       |
|BMW       |11,202       |
|HYUNDAI   |9,828        |
|RIVIAN    |8,511        |
|VOLKSWAGEN|7,368        |

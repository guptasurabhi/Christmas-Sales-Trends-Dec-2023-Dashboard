Christmas-Sales-Trends-Dec-2023-Dashboard

In this project I analysis Christmas sales & trends of last year (Dec 2023) by the help of Power  Bi.
First I clean the raw data by the help of power query editor and create new measures and new columns and then create visuals.
Unclean Data contain columns:



TransactionID (Unique identifier for each transaction)
Date (Date of the transaction, format: YYYY-MM-DD)
Time (Time of the transaction, format: HH:MM:SS)
CustomerID (Unique identifier for each customer)
Age (Age of the customer)
Gender (Gender of the customer: Male, Female, Other)
Location (City or town where the purchase was made)
StoreID (Unique identifier for the store, if applicable)
OnlineOrderFlag (Boolean: True if online, False if in-store)
ProductID (Unique identifier for the product)
ProductName (Name of the product)
Category (Category of the product, e.g., Electronics, Clothing, Toys, Food, Decorations)
Quantity (Number of items purchased in the transaction)
UnitPrice (Price per unit of the product)
PaymentType (Type of payment, e.g., Credit Card, Debit Card, Cash, Online Payment)
PromotionApplied (Boolean: True if any promotion was applied, False otherwise)
DiscountAmount (The amount of discount, if any)
GiftWrap (Boolean: True if the product was gift-wrapped, False otherwise)
ShippingMethod (Method of shipping, e.g., Standard, Express, Overnight, if online)
DeliveryTime (Number of days taken for delivery, if online)
Weather (General weather condition on the day of purchase, e.g., Snowy, Rainy, Sunny)
Event (Special events on the purchase day, e.g., Christmas Market, Black Friday)
CustomerSatisfaction (Customer satisfaction rating, on a scale of 1-5)
ReturnFlag (Boolean: True if the product was returned, False otherwise)


Data cleaning steps:

check for duplicates,
check for null values,
change datatypes,
create custom columns = total price,total price after discount,
create conditional columns= Types of order,items returned or not returned,
create new measures

after that create visuals





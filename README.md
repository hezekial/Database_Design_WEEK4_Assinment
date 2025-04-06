# Database_Design_WEEK4_Assignment

SELECT payment_date, SUM(payment_amount) AS total_payment
FROM payments
GROUP BY payment_date
ORDER BY payment_date DESC
LIMIT 5;

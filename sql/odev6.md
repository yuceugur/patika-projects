# ODEV 6
1. film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?

Cevap: 2.98
```SQL
SELECT AVG(rental_rate) FROM film
```
2. film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?

Cevap: 92
```SQL
SELECT COUNT(*) FROM film WHERE title LIKE 'C%'
```
3. film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?

Cevap: 184
```SQL
SELECT MAX(length) FROM film WHERE rental_rate = 0.99
```
4. film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?

Cevap: 21
```SQL
SELECT COUNT(DISTINCT replacement_cost) FROM film WHERE length > 150
```
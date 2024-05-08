# HackerRank SQL Soruları Çözümleri

Bu repo, HackerRank platformundaki SQL sorularını çözmek için SQL sorgularını içermektedir. Her bir sorunun altında sorunun adı veya açıklaması, sorunun SQL sorgusu, çözümün açıklaması ve SQL kodu bulunmaktadır.

## İçindekiler

1. [Revising the Select Query I](#sorun-1-soru-adı-veya-açıklaması)
2. [Sorun 2: Soru Adı veya Açıklaması](#sorun-2-soru-adı-veya-açıklaması)
3. ...

## Soru 1: Revising the Select Query I

**Soru:**

Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.
The CITY table is described as follows: 

![alt text](image.png)

**Açıklama:**

Bu soruda **where** ve **and** komutunu kullanmalıyız.


**SQL Kodu:**

```sql
select * from city where population > 100000 and countrycode = "USA"

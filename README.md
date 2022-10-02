# Capstone-Project-Web-Scrapping

This project is developed as a capstone project from Algoritma Academy Data Analytics Specialization with a simple webscrapping case and how to visualise the data with plots

Web Scraping is the process of downloading data from websites and extracting valuable information from the data.

At this project, i will do a web scrapping method using BeautifulSoup. I scrap exchange rate Indonesian Rupiahs (IDR) per US Dollar (USD) data's from https://www.exchange-rates.org/history/IDR/USD/T

Exchange-Rates.org allows us to check the latest foreign exchange rates. Data on the website is up-to-date and provided by one of the financial leaders. I will scrap historical exchange rates data the Indonesian Rupiah (IDR) and the US Dollar (USD) between 4/4/2022 and 9/30/2022. The data consist of the value of 1 USD in IDR with date and price per day.  

This is the visualization of the data

![plot](https://user-images.githubusercontent.com/112872476/193433854-e5753e25-bb33-4b8f-abf1-c26208286cb7.png)


### Conclusion

From the data, here are my conclusions for exchange rate US to IDR in the time frame from 4/4/2022 and 9/30/2022 

- The highest exchange rate occured in September 29th and the lowest occured on April
- The exchange rate on average is always rising from April - September 2022
- The exchange rate in every month tends to always move (decline and increase) and is rarely stable.
- The highest decline of exchange rates occurred in July
- The average exchange rate from April untul August is around 14700 IDR








## Here are the steps that guide me finished this project


## Dependencies

- beautifulSoup4
- pandas
- flask
- matplotlib

Atau Bapak Ibu cukup menginstall requirements.txt dengan cara berikut

```python
pip install -r requirements.txt
```

## Rubics

- Environment preparation (2 points)
- Finding the right key to scrap the data  & Extracting the right information (5 points)
- Creating data frame & Data wrangling (5 points)
- Creating a tidy python notebook as a report. (2 points)
- Implement it on flask dashboard (2 points)


## What You Need to Do

* Silahkan mencoba melakukan scraping soal di bawah menggunakan `beautiful soup` di notebook Bapak/Ibu terlebih dahulu.
* Bapak/Ibu dapat men-clone repo ini.
* Silahkan buka notebook template pada capstone ini dan isi sesuai dengan arahan yang ada. Pastikan Bapak/Ibu memberikan analisa yang dibutuhkan pada notebook tersebut.
* File di repo ini adalah skeleton yang dapat digunakan untuk membuat flask dashboard sederhana.
* Silahkan isi di bagian yang masih kosong.
* Isi fungsi `scrap` dengan proses scraping yang sudah Bapak/Ibu lakukan di notebook. 

```python
table = soup.find(___)
tr = table.find_all(___)
```

* Isi bagian ini untuk menyimpan hasil scrap yang Bapak/Ibu buat menjadi sebuah dataframe.

```python
df = pd.DataFrame(name of your tupple, columns = (name of the columns))
```

* Terakhir Bapak/Ibu dapat menggunakan fungsi `scrap` dengan cara mengisi bagian berikut dengan link web yang Bapak/Ibu scrap.

```python
df = scrap(___) #insert url here
```

* Bapak/Ibu juga dapat bermain dengan UI nya pada `index.html` yang dimana Bapak/Ibu dapat mengikuti comment yang ada untuk mengetahui bagian mana yang dapat diubah. 

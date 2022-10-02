# Capstone-Project-Web-Scrapping

This project is developed as a capstone project from Algoritma Academy Data Analytics Specialization with a simple webscrapping case and how to visualise the data with plots

Web Scraping is the process of downloading data from websites and extracting valuable information from the data.

At this project, i will do a web scrapping method using BeautifulSoup. I scrap exchange rate Indonesian Rupiahs (IDR) per US Dollar (USD) data's from https://www.exchange-rates.org/history/IDR/USD/T

Exchange-Rates.org allows us to check the latest foreign exchange rates. Data on the website is up-to-date and provided by one of the financial leaders. I will scrap historical exchange rates data the Indonesian Rupiah (IDR) and the US Dollar (USD) between 4/4/2022 and 9/30/2022. The data consist of the value of 1 USD in IDR with date and price per day.  

This is the visualization of the data

![plot](https://user-images.githubusercontent.com/112872476/193433854-e5753e25-bb33-4b8f-abf1-c26208286cb7.png)











## Here are the steps to finish this project


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

### The Final Mission

Pada captsone kali ini, Bapak Ibu bisa memilih salah satu soal ini untuk dikerjakan.

1. (Easy) Data Volume Penjualan Ethereum dari `https://www.coingecko.com/en/coins/ethereum/historical_data/usd?start_date=2020-01-01&end_date=2021-06-30#panel`

   * Dari halaman tersebut carilah `Date`, dan `Volume`.
   * Buat lah plot pergerakan volume perdagangan dari Ethereum. 

2. (Medium) Data kurs US Dollar ke rupiah dari `https://www.exchange-rates.org/history/IDR/USD/T`

    * Dari halaman tersebut carilah `harga harian`, dan `tanggal`
    * Bualah plot pergerakan kurs USD 
    
3. (Hard) Data film yang rilis di tahun 2021 dari `https://www.imdb.com/search/title/?release_date=2021-01-01,2021-12-31`

    * Dari Halaman tersebut carilah `judul` , `imdb rating` , `metascore`, dan `votes`
    * Buatlah plot dari 7 film paling populer di tahun 2021.


Happy learning! 

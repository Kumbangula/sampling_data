#Mendownload file excel dan menyimpannya di folder data
#wget -P data https://github.com/labusiam/dataset/raw/main/weather_data.xlsx

#pindah ke folder data
#cd data

#melakukan convert data menjadi csv
#in2csv weather_data.xlsx > weather_data.csv

#melakukan convert data weather_2014 dan weather_2015 menjadi .csv
#in2csv weather_data.xlsx --sheet "weather_2014" > weather_2014.csv
#in2csv weather_data.xlsx --sheet "weather_2015" > "weather_2015.csv

#menggabungkan dua file .csv weather_2014 dan weather_2015 menjadi satu file weather.csv
#csvstack weather_2014.csv weather_2015.csv > weather.csv

#menghapus data excel weather_data.xlsx
#rm weather_data.xlsx

#melakukan sampling dengan rate 0.3 dan menyimpannya ke file sample_weather.csv
#head weather.csv | sample -r 0.3 -d 2 > sample_weather.csv


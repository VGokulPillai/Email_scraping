In this code I used a set of urls which is saved in a separate text file called suppliers.txt,from that using BeautifulSoup lib in python I had scrap out the emails id ,boundry condition was given:
(\w+@\w+\.\w+\.\w+):info@munneries.co.uk
info,munneries,co,uk these terms will change so we can't depend on that instead there will be non-changable terms like 'dots and @'.
After scrapping out,it is saved in a hash_map with key as website and value as email ids
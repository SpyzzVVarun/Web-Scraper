# Web-Scraper
This Web Scraping Script can be used to scrape recent job posts related to Machine Learning filtered based on user's preferred skills. It runs and updates every 10 mins

# How-to-Use
Run the script as ipynb notebook and in [with  open(fr'C:\Users\nagpa\OneDrive\Desktop\Job Posts/{index}.txt','w') as f:] and [f.unlink() for f in Path(r"C:\Users\nagpa\OneDrive\Desktop\Job Posts").glob("*") if f.is_file()]  change the folder path according to the path of the folder you want to get your job posts in.
OR
You can simply use the csv file being created.

# latest-indonesia-magnitude
this package will get lates eartquake in indonesia from BMKG (METEOROLOGICAL, CLIMATOLOGICAL, AND GEOPHYSICAL AGENCY)
## HOW IT WORK?
This package will scrape from [bmkg](http://bmkg.go.id) to get latest earthquake occured in Indonesia.
This package will use BeautifulSoup4 and Requests, then return output as JSON tha t ready for other application both mobile or web
## HOU TO  USE

import gempaterkini

if __name__ == '__main__':
    result = gempaterkini.ekstraksi_data()
    gempaterkini.tampilkan_data(result)
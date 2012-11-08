####
# Web-crawler
####

####
#Description:
#  Scans websites html looking for <a href=" tag and parses the url 
#  between the quotes and stores that into a array 
#  called toCrawl once it is completed parsing a specific url, 
#  it will go through the urls in toCrawl looking for more 
#  urls within that list based on the depth.
# 
####

####
#How to use:
#  use the function crawl_web to look through a particular 
#  url and parse crawl the links inside.
#  for example:
#  crawl_web("http://www.cs.ucf.edu/courses/cop3502/summer12/rec/")
####


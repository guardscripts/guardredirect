# guardredirect
query-based php redirect service (you are able to use fowardslashes in the url id)

---

### the values in [create.json](https://github.com/guardscripts/guardredirect/blob/main/create.json) are all the ids, and the value attached to them is the url it will redirect to
----
### example of working redirect: https://guard.lol/redirect?id=guard
the id "guard" above cannot be overridden, and whether or not [fastredirectenabled](https://github.com/guardscripts/guardredirect/blob/main/fastredirectenabled) is enabled or not, the above url will always fast redirect! 

###### Also, it will work with capitalization (UTF-8 + 5 characters)
###### there is a blacklist system so my domain doesnt get in trouble and an anti-offensive word filter
#### there is shortened version for each redirect, it is https://guard.lol/r
###### useage of shortened version is https://guard.lol/r?id=[id]

---
# guardurl
guardurl allows you to redirect to any url on the internet!
### example useage: https://guard.lol/redirect?url=[the_url]
###### shortened: https://guard.lol/r?url=[the_url]
#### examples of working guardurl links: <br>https://guard.lol/redirect?url=https://www.sleep.com/ or https://guard.lol/redirect?url=https://www.roblox.com/ <br>https://guard.lol/re?url=www.guard.com or https://guard.lol/r?url=amazon.com <br>(upon clicking it will take you to the corresponding url in the url query)

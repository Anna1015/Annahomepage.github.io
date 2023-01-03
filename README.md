# modify

## 1 _config.yml 
add new page

-  patents:
-    output: true
-    permalink: /:collection/:path/



-  # _patents
-  - scope:
-      path: ""
-      type: patents
-    values:
-      layout: single
-      author_profile: true
-      share: true
-      comments: true



## 2 _data/navigation.yml

add new page
-  - title: "Patents"
     url: /talks/    
 
note some unnecessary page, for example
-#  - title: "Teaching"
-#    url: /teaching/  




## 3 _pages/about.md
delete words and add new words on the front page

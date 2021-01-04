---
layout: post
title: This site goes live
subtitle: Today is an exceptional Sunday, because this website & blog is now live
cover-img: /imgs/mc.png
thumbnail-img: /imgs/dfd.png
share-img: /imgs/123.png
tags: [meta, happy]
---

# Weclome! 
I will put leet here. And thoughts and ideas.

## Ideas
All blogs are written via markdown


![test](../imgs/30362574.png)

![f](/imgs/mc.png)

![f](/_posts/2020-07-19/monsters.jpeg)

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

## Code 
```cpp
vector<int> pancakeSort( const vector<int>& arr ) 
{
  vector<int> result(arr);
  
  int n = result.size();
  
  int cm = getMax(result, n);
  
  int cnt = 1;
  
  for (int i = 0; cnt <= result.size(); i++) {
     if (result[i] == cm) {
       flip(result, i);
       flip(result, n-cnt);
       cm = getMax(result, n-cnt);
       i = 0;
       cnt++;
     }
      
  }
  
  return result;
  
}

int main() {
  
  vector<int> a = {1, 5, 4, 3, 2};
  
  vector<int> res = pancakeSort(a);
  
  for (auto i : res) cout << i  << " ";
  
  return 0;
}
```
---
layout: post
title: "Algorithms . Day 1"
author: "Alexey Frunza"
categories: journal
tags: [documentation,sample]
---

Hey ! Today I started working on JavaScript Algorithms . I have a lot to remember because it's been a long time since my last project using js . Hope it will be easier than it seems

Here is my Two Sum solution 

```
var twoSum = function(nums, target) {
  for(let i = 0; i < nums.length; i++) {
    for(let j = 0; j < nums.length; j++) {
      if (nums[i]+nums[j] == target && i !== j) {
        return [i,j]
      }
    }
  }
};
```

I'm Solving Remove Duplicates from Sorted Array , but don't fully understand the task so far . I'll try to solve it tonight . 

Bye!

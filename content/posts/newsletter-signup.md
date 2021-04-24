---
title: Method of Approach
subtitle:
category:
  - Third Party Integrations
featureImage: /uploads/purge-css-hero.jpg
---

## Method of Approach

Reading, understanding, and analyzing the literature surrounding marriage in Morocco has not only provided context for the relationship between Moroccan education and marriage, but also narrowed down the variables to pull for further exploration. While understanding the history, stories, and written works surrounding Moroccan marriage is essential for a holistic analysis, examining the numerical trends in the Moroccan population is also telling of the various impacts and factors that weigh in on the formation of marriage. The qualitative data that’s been used thus far has been extremely helpful, however did not seem sufficient enough to fully understand the relationship between education and marriage in Morocco. Many scholars continuously implied that it was a given that arranged marriages were more common among less educated women, however this assumption did not seem obvious to me. This is why I decided to conduct my own research by gathering data, and implementing its automated analysis, then displaying my findings on a website that is accessible to everyone. These trends were explored using the data from the World Bank, the United Nations, and a few other databases. Analyzing a data driven perspective by discovering the relationship between variables and visualizing data trends and dependencies was helpful in understanding how education plays a part in marriage. After preliminary exploration of data using Python programming languages, the relationship between education and marriage proved to be more complex than previously expected.

```
x = np.arange(len(labels))  # the label locations
width = 0.35  # the width of the bars

fig, ax = plt.subplots()
rects1 = ax.bar(x - width/2, casa_means, width, label='Casablanca')
rects2 = ax.bar(x + width/2, tan_means, width, label='Tangier')

# Add some text for labels, title and custom x-axis tick labels, etc.
ax.set_ylabel('Percentage (%)')
ax.set_title('Circumstance of Meeting in 2011')
ax.set_xticks(x)
ax.set_xticklabels(labels)
ax.legend()

fig.tight_layout()

plt.show()
```
[Method of Approach](https://docs.google.com/document/d/169YV4Vi_7xaKhsxBiOM-DDUpm_MneLld01Rw9ueWOwY/edit?usp=sharing)

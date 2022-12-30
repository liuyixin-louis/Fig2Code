# Fig2Code: Conver figure in paper to python code with a simple snipping

## Motivation

I am currently interested in applying recent vision-language models to achieve a tool similar to Mathpix, which aims to do reverse engineering to convert the figure in paper into its corresponding generated code. The main flow of this tool is shown as follows. If you feel this project proposal interesting, please contact me to contribute to building it together. The possible benefit might be similar to Mathpix, which can save research time when doing the plotting stuff by resuing some awesome figures from others. 

![framework-fig2code](https://s2.loli.net/2022/12/31/nLDUHh4SJTobgC2.png)

## Some Possible Challenges

- How to collect data?

- End2end or sequential model? Adding a filtering net will help improve code-generating performance, given that the input snip might not be clean. 

## Plan
- Data collection
  - script that can sample snipping photos
  - script for generating petty figures, or some example code-figure pairs from some book
- Surveying and Method design

## Resources
1. https://github.com/lukas-blecher/LaTeX-OCR
2. An Image is Worth 16x16 Words
3. Attention Is All You Need
4. Image-to-Markup Generation with Coarse-to-Fine Attention
5. https://twitter.com/rasbt/status/1608133663937495041?utm_source=wechat_session&utm_medium=social&utm_oi=651177626656575488
# Recipe Vision
Detect ingredients in user-uploaded images, and recommend recipes based on label detection. (See full project repo at https://github.com/asela1982/master-chef)

### Ingredient detection app ("Recipe Vision")
[View on Heroku](https://frozen-bayou-15416.herokuapp.com/static/UploadImage.html)

### Project Overview
- Web scraping of recipes (https://github.com/asela1982/master-chef)

- Data cleaning with Pandas to extract and normalize ingredients & tags (https://github.com/asela1982/master-chef)

- Applied regression analysis to predict the recipe rating (https://github.com/asela1982/master-chef)

- Use CNN to evaluate images (Google Cloud Vision API). 

- Recommend recipes based on ingredients detected
  - Use a similarity measure (cosine similarity) to score recipes by relevancy.
  - NLTK (natural language processing), numpy, math, Pandas
  - Flask template, Bootstrap, CSS

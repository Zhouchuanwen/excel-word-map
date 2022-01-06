# Data Visualization for Excel

### Background

Excel is widely used by people, and here is tool for users to view excel data in a word cloud map.

The goals for this repository are:

1.Generate a word cloud map picture.
2.Find the words used frequently in excel.
3.Help to build a whole picture of excel sentences.


### Install

Just download the repo and open the main.html file in broswer then upload your excel with supported format.


### Usage

Following steps:

1.Keep your excel header must have this two column, only 'Title'(words to count) and 'Comment'(the important value for this sentence) name supported.
2.Upload xlsx file.
3.There will be a picture showing like `pic of result`.
4.If there is no result showing, please check the data format and the network to reach this website `https://jsonplaceholder.typicode.com/`.
5.If still nothing showing, check your browser's cross domain strategy and add this  ` --allow-file-access-from-files ` into configuration.


![pic of result](https://github.com/Zhouchuanwen/excel-word-map/blob/master/word_cloud.jpeg)


### Contributors

This project exists thanks to all the people who contribute. 
<a href="https://github.com/Zhouchuanwen/excel-word-map/graphs/contributors"><img src="https://opencollective.com/excel-word-map/contributors.svg?width=890&button=false" /></a>


### License

[MIT](LICENSE) © Chuanwen Zhou


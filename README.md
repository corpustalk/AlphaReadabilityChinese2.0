# AlphaReadabilityChinese 2.0

This is the repo for AlphaReadabilityChinese 2.0, a tool that automatically assess the readability of a Chinese text.

**AlphaReadabilityChinese 2.0** is a tool that calculates the readability of Chinese texts, which includes indices at lexical, syntactic, semantic, and textual (cohesive) levels.

## Download

Download AlphaReadabilityChinese 2.0 for MS Windows and MacOS at Releases of this repo (the right side of this page). 



## AlphaReadabilityChinese 2.0

Hi all,

Happy to release our new app, AlphaReadabilityChinese 2.0 (or the ARC 2.0).

The ARC 2.0 is a tool that calculates the readability of Chinese texts, which includes indices at lexical, syntactic, and semantic levels.

The ARC 2.0 provides versions working on both MS Windows and Mac OS. It is free to use the ARC Chinese. It is very much appreciated if you cite our work as follows when you use the ARC Chinese.

Lei, Lei, Wei, Yaoyu, & Liu, Kanglong. 2024. AlphaReadabilityChinese: A tool for the measurement of readability in Chinese texts and its applications. Foreign Languages and Their Teaching. 46(1):83-93. (in Chinese)

or 雷蕾, 韦瑶瑜, 刘康龙. 2024. AlphaReadabilityChinese：汉语文本可读性工具开发与应用. 外语与外语教学. 46(1):83-93.

You can also find detailed information of the ARC Chinese in the foregoing article.

The ARC 2.0 is designed and developed by Lei Lei (雷蕾) and Tingyu Zhang (张婷玉), Shanghai International Studies University.

Hope the ARC 2.0 helps. Comments and suggestions are welcome! (leileicnATqqDOTcom)

## What's new

Compared to the ARC 1.0, the ARC 2.0 adds a new metric at the textual level. The new metric calculates the semantic coherence of a Chinese text in terms of the cosine similarities of all neighbouring sentences. 

## Guidelines for Users

- Put all the texts you are going to process in a folder (such as "my_test_files", the test folder that we provide and that contains five abstracts of our articles). Note that all texts should be in the .txt format with the encoding 'UTF-8'.

- Open the ARC Chinese.

- Click "Select" besides "Input folder" to select the folder (such as the folder "my_test_files") that contains the files you are going to calculate the readability of.

- Click "Select" besides "Output folder" to select the folder where you would like the resulting file is stored. The resulting file contains the results of the readability measures in a .csv format.

- Click "Run". When the ARC Chinese says "Processing ends", find the newly generated resulting file entitled "0ARC_Chinese_Results.csv".

- Open the resulting file with your spreadsheet app such as MS Office Excel or Numbers on Mac OS and check out the readability measures of all texts in the Input Folder.

**Known issues for Mac users**

On MacOS, if you encounter the "App is damaged and can't be opened" error: 

1) copy AlphaReadabilityChinese.app to the Applications folder,
  
2) go to Terminal and type/run the following, and reopen AlphaReadabilityChinese.app.

`sudo xattr -cr /Applications/AlphaReadabilityChinese.app`

or

`sudo xattr -r -d com.apple.quarantine /Applications/AlphaReadabilityChinese.app`

**Notes**

Note that it may take a while (approximately 30 seconds on my MacBook) the first time we open AlphaReadabilityChinese when it loads many models behind. The good news is that it works highly efficiently to process our data after all the models are loaded.

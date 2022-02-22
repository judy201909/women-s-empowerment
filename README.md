# women-s-empowerment
script, data, results on my graduation paper

Description of the project: My graduation project is an analysis of the causal relationship between the percent of female director(s) in the board and the firm's performance in terms of ROA. The target firms are those listed on Tokyo Stock Exchange (TSE). During data collection, I noticed that there seemed to have a barrier for researchers to get related infomation despite the fact that all the infomation needed are available to the public through EDINET which is run by the FSA. The reality is that in order to get the infomation, researchers have to pay a large subscription fee to financial infomation providers. Therefore, I'd like to share the scripts, data, and results I gathered and used during the project so that going forward if researchers facing similar dilemma of obtaining information they could have a reference.

The files will be organized as following:
1. data collection
2. data cleaning
3. data analysis



1. data collection
Platform used: google colab
Scripts that I have referenced:
a. https://qiita.com/XBRLJapan/items/b1e66f79d597df7b6037
b. https://qiita.com/XBRLJapan/items/27e623b8ca871740f352

Scripts that I used for the project which is modified based on above:
a.ipynb file named: download_files_from_edinet_by_batch
Note: the only modification needed to run the script is to set the start date and end date according to you request. Pls be reminded that the EDINET only allowed access to hitstorical files up to 5 years ago.
b.ipynb file named: extract_company_info_from_zip_files_to_excel

2.data cleaning

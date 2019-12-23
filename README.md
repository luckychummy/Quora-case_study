{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf600
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue-Bold;\f1\fmodern\fcharset0 Courier;\f2\fnil\fcharset0 HelveticaNeue;
\f3\fnil\fcharset0 HelveticaNeue-Light;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red255\green255\blue255;\red0\green0\blue109;
\red14\green115\blue192;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;\cssrgb\c100000\c100000\c100000;\cssrgb\c0\c0\c50196;
\cssrgb\c0\c53333\c80000;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}.}{\leveltext\leveltemplateid201\'02\'00.;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl500\partightenfactor0

\f0\b\fs52 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 1. Business Problem\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl420\partightenfactor0

\f0\b\fs44 \cf2 \cb3 \strokec2 1.1 Description\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl320\qj\partightenfactor0

\f2 \cf2 \strokec2 \
\pard\pardeftab720\sl320\qj\partightenfactor0
\cf2 \cb3 Quora is a place to gain and share knowledge\'97about anything. It\'92s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.\cb1 \
\
\cb3 Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.\cb1 \
\pard\pardeftab720\sl320\partightenfactor0
\cf2 \
\pard\pardeftab720\sl400\qj\partightenfactor0

\f3\fs32\fsmilli16250 \cf2 \cb3 Credits: Kaggle\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl340\qj\partightenfactor0

\f2\b \cf2 \cb3 \strokec2 Problem Statement
\b0 \cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl400\partightenfactor0
\ls1\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Identify which questions asked on Quora are duplicates of questions that have already been asked.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 This could be useful to instantly provide answers to questions that have already been answered.\cb1 \
\ls1\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 We are tasked with predicting whether a pair of questions are duplicates or not.\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1 \cf4 \strokec4 \
\pard\pardeftab720\sl420\partightenfactor0

\f0\b\fs44 \cf2 \cb3 \strokec2 1.2 Sources/Useful Links\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl400\partightenfactor0
\ls2\ilvl0
\f2 \cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Source :\'a0{\field{\*\fldinst{HYPERLINK "https://www.kaggle.com/c/quora-question-pairs"}}{\fldrslt \cf5 \ul \ulc5 \strokec5 https://www.kaggle.com/c/quora-question-pairs}}\cb1 \uc0\u8232 \u8232 
\b \cb3 Useful Links
\b0 \cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Discussions :\'a0{\field{\*\fldinst{HYPERLINK "https://www.kaggle.com/anokas/data-analysis-xgboost-starter-0-35460-lb/comments"}}{\fldrslt \cf5 \ul \ulc5 \strokec5 https://www.kaggle.com/anokas/data-analysis-xgboost-starter-0-35460-lb/comments}}\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Kaggle Winning Solution and other approaches:\'a0{\field{\*\fldinst{HYPERLINK "https://www.dropbox.com/sh/93968nfnrzh8bp5/AACZdtsApc1QSTQc7X0H3QZ5a?dl=0"}}{\fldrslt \cf5 \ul \ulc5 \strokec5 https://www.dropbox.com/sh/93968nfnrzh8bp5/AACZdtsApc1QSTQc7X0H3QZ5a?dl=0}}\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Blog 1 :\'a0{\field{\*\fldinst{HYPERLINK "https://engineering.quora.com/Semantic-Question-Matching-with-Deep-Learning"}}{\fldrslt \cf5 \ul \ulc5 \strokec5 https://engineering.quora.com/Semantic-Question-Matching-with-Deep-Learning}}\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Blog 2 :\'a0{\field{\*\fldinst{HYPERLINK "https://towardsdatascience.com/identifying-duplicate-questions-on-quora-top-12-on-kaggle-4c1cf93f1c30"}}{\fldrslt \cf5 \ul \ulc5 \strokec5 https://towardsdatascience.com/identifying-duplicate-questions-on-quora-top-12-on-kaggle-4c1cf93f1c30}}\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1 \cf4 \strokec4 \
\pard\pardeftab720\sl420\partightenfactor0

\f0\b\fs44 \cf2 \cb3 \strokec2 1.3 Real world/Business Objectives and Constraints\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl400\partightenfactor0
\ls3\ilvl0
\f2 \cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	1.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 The cost of a mis-classification can be very high.\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	2.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	3.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 No strict latency concerns.\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	4.	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Interpretability is partially important.\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1 \cf4 \strokec4 \
\pard\pardeftab720\sl500\partightenfactor0

\f0\b\fs52 \cf2 \cb3 \strokec2 2. Machine Learning Probelm\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl420\partightenfactor0

\f0\b\fs44 \cf2 \cb3 \strokec2 2.1 Data\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl360\partightenfactor0

\f0\b\fs36 \cf2 \cb3 \strokec2 2.1.1 Data Overview\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl320\qj\partightenfactor0

\f2 \cf2 \cb3 \strokec2 - Data will be in a file Train.csv\cb1 \uc0\u8232 \cb3 - Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate\cb1 \uc0\u8232 \cb3 - Size of Train.csv - 60MB\cb1 \uc0\u8232 \cb3 - Number of rows in Train.csv = 404,290\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1 \cf4 \strokec4 \
\pard\pardeftab720\sl360\partightenfactor0

\f0\b\fs36 \cf2 \cb3 \strokec2 2.1.2 Example Data point\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl320\partightenfactor0
\cf2 \cb3 \strokec2 "id","qid1","qid2","question1","question2","is_duplicate"\
"0","1","2","What is the step by step guide to invest in share market in india?","What is the step by step guide to invest in share market?","0"\
"1","3","4","What is the story of Kohinoor (Koh-i-Noor) Diamond?","What would happen if the Indian government stole the Kohinoor (Koh-i-Noor) diamond back?","0"\
"7","15","16","How can I be a good geologist?","What should I do to be a great geologist?","1"\
"11","23","24","How do I read and find my YouTube comments?","How can I see all my Youtube comments?","1"\
\pard\pardeftab720\sl340\qr\partightenfactor0
\cf4 \cb1 \strokec4 \
\pard\pardeftab720\sl420\partightenfactor0

\f0\b\fs44 \cf2 \cb3 \strokec2 2.2 Mapping the real world problem to an ML problem\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl360\partightenfactor0

\f0\b\fs36 \cf2 \cb3 \strokec2 2.2.1 Type of Machine Leaning Problem\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl320\qj\partightenfactor0

\f2 \cf2 \cb3 \strokec2 It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1 \cf4 \strokec4 \
\pard\pardeftab720\sl360\partightenfactor0

\f0\b\fs36 \cf2 \cb3 \strokec2 2.2.2 Performance Metric\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl320\qj\partightenfactor0

\f2 \cf2 \cb3 \strokec2 Source:\'a0{\field{\*\fldinst{HYPERLINK "https://www.kaggle.com/c/quora-question-pairs#evaluation"}}{\fldrslt \cf5 \ul \ulc5 \strokec5 https://www.kaggle.com/c/quora-question-pairs#evaluation}}\cb1 \
\cb3 Metric(s):\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl400\partightenfactor0
\ls4\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 log-loss :\'a0{\field{\*\fldinst{HYPERLINK "https://www.kaggle.com/wiki/LogarithmicLoss"}}{\fldrslt \cf5 \ul \ulc5 \strokec5 https://www.kaggle.com/wiki/LogarithmicLoss}}\cb1 \
\ls4\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Binary Confusion Matrix\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1 \cf4 \strokec4 \
\pard\pardeftab720\sl420\partightenfactor0

\f0\b\fs44 \cf2 \cb3 \strokec2 2.3 Train and Test Construction\cb1 \
\pard\pardeftab720\sl340\qr\partightenfactor0

\f1\b0\fs28 \cf4 \strokec4 \
\pard\pardeftab720\sl320\qj\partightenfactor0

\f2 \cf2 \strokec2 \
\pard\pardeftab720\sl320\qj\partightenfactor0
\cf2 \cb3 We build train and test by randomly splitting in the ratio of 70:30 or 80:20 whatever we choose as we have sufficient points to work with.\cb1 \
}
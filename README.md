\title{CMPT310 Group7 Autism Prediction Report}

\author{Chenzheng Li\\
School of Computing Science\\
Simon Fraser University\\
8888 University Dr, Burnaby, BC \\
\texttt{cla429@sfu.ca}\\
\And 
Bofan Yu\\
School of Computing Science\\
Simon Fraser University\\
8888 University Dr, Burnaby, BC\\
\texttt{bofany@sfu.ca}\\
\And
Phuong Thuy Dang\\
School of Computing Science\\
Simon Fraser University\\
8888 University Dr, Burnaby, BC\\
\texttt{pdang@sfu.ca}\\
\And
Jialong Qiao\\
School of Computing Science\\
Simon Fraser University\\
8888 University Dr, Burnaby, BC \\
\texttt{jialongq@sfu.ca}\\
\And
Beibei Tang\\
School of Computing Science\\
Simon Fraser University\\
8888 University Dr, Burnaby, BC \\
\texttt{beibeit@sfu.ca}\\
}

\begin{document}
\linenumbers
\maketitle
\begin{abstract}    %(Bofan)
Autistic Spectrum Disorder (ASD) refers to a group of developmental disorders that affect the nervous system. Some of the most common ASD symptoms include impairment, challenges in social interaction, and repetitive behaviour that affect communication. ASD has a significant impact on health care not only due to the number of ASD cases raising but also the time involved to diagnose ASD. Moving in line with the rise in machine learning to speed up the time to detect a disease using existing data, the goal is to construct a model that accurately predicts whether an individual has ASD or not in order to provide early intervention for those who has a high chance of having ASD later. We use different models to compare the performance, including Logistic Regression, Support Vector Machines (SVM), Naive Bayes, k-Nearest Neighbours (KNN), Artificial Neural Network (ANN), Convolutional Neural Network (CNN) over 3 datasets: Adult, Children, and Adolescent. For the dataset, all datasets contains of 21 attributes; however, different instances. While adult dataset contains 704 instances, children dataset contains 292 instances, and adolescent dataset contains only 104 instances. After pre-processing the data, applying the model, and evaluating, results strongly suggest the high results for Logistic Regression with the accuracy 98\%, 100\%, 90\%, and neural network with accuracy 100\%, 96\% and 70\%  for Adult, Children, Adolescent dataset respectively.
\end{abstract}

# Topic-Modeling-with-DistilBERT

While studying topic modeling, we questioned the reason why a single model would (through a softmax function) decide which topic a text would belong to . We hypothesized that by creating numerous models that only decides whether a text belongs to a topic or not (i.e., binary classification) and putting them in parallel, topic modeling would be more accurate.

For the data, we collected the 'abstracts' of papers published in arXiv. We adopted **DistilBERT** for modeling the papers of 8 topics. **Tensorflow(Keras BE)** was used for modeling.

The results, however, proved that the former approach was slightly more accurate and more time-saving than the latter approach.

This project has been awarded a **Grand Prize** from the Student Academic Conference Organizing Committee of HUFS College of English, and the paper was published in the proceedings of the Advanced Engineering and ICT-Convergence conference.

For the papers, please click [here](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/8f0ea2ac-13f5-4d9c-8f96-e920f98638d0/%28FINAL%29_ELLT__%28%29.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210911%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210911T062326Z&X-Amz-Expires=86400&X-Amz-Signature=22bcdeb42b03739ceda29fd1969028a7439a3ad387d4a9614f28683349ad63f3&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22%28FINAL%29%2520%25ED%2595%2599%25EC%2588%25A0%25EC%25A0%259C_ELLT%25ED%2595%2599%25EA%25B3%25BC%2520%25EA%25B0%259C%25EC%259D%25B8%25ED%258C%2580%2520%28%25EC%259D%25B4%25ED%2598%25B8%25EC%259E%25AC%29.pdf%22) for the work presented in the Student Academic Conference, and [here](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/df89dbc8-da5f-4f26-b48c-401081a089c4/%28FINAL%29_NICAES_.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210911%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210911T062421Z&X-Amz-Expires=86400&X-Amz-Signature=33a0bd63bbd8c7aa46101f3753ae996363780c9f01b80b9b1dbfec6deece7410&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22%28FINAL%29%2520AEICP_%25EC%259D%25B4%25ED%2598%25B8%25EC%259E%25AC.pdf%22) for the paper that as published in the proceedings of Advanced Engineering and ICT-Convergence Conference.  

Please refer to [this link](https://www.notion.so/nokomon/2020-f5d58fb35eb74a69a00a5357101f0a5f) for details (written in Korean).  


# Attention
All data in the master branch！

# MultiMET 
This is the official implementation for “MultiMET: A Multimodal Dataset for Metaphor Understanding
 ” (ACL2021)

# Info

we introduce MultiMET, a novel multimodal metaphor dataset to facilitate understanding metaphorical information from multimodal text and image. It contains 10,437 text-image pairs from a range of sources with multimodal annotations of the occurrence of metaphors, domain relations, sentiments metaphors convey, and author intents. MultiMET opens the door to automatic metaphor understanding by investigating multimodal cues and their interplay. Moreover, we propose a range of strong baselines and show the importance of combining multimodal cues for metaphor understanding. 

Data Collection 

1.The first part, named 'ads.xlsx'.The first column is the ID of the image, which can be found in the folder "ads" for the corresponding row of images.  The second column contains image links, which can be used to access the images.The third column represents the category, with the metaphorical label being "1" and the literal meaning label being "0". The fourth and fifth columns represent the source and target domains. The sixth column is the type of emotion, including VN=very negative; N=negative; Z=natural; P=positive; VP=very positive. The seventh column is the text in the image.

2.The second part is named "Facebook_pic_solved. xlsx". The first column is the ID of the image, which can be found in the folder "Facebook_pic_solved". The second column is the text. The third column represents the category, with a metaphorical label of "1" and a literal label of "0". The fourth column indicates whether it is a textual metaphor. The fifth column represents categories, where 1, 2, and 3 respectively represent 1: text dominant, 2: image dominant, and 3: completeness. The sixth and eighth columns represent the source and target domains, while the seventh and ninth columns represent the modal information of the source and target domains, where 1, 2, and 3 represent: 1: text, 2: image, and 3: text+image, respectively. The 10th column represents sentiment classification, 1: very negative, 2: negative, 3: neutral, 4: positive, 5: very positive. The 11th list diagram includes: 1: supervisory, 2: informative, and 3: expressive.

3.The third part is named "Twitter_pic_solved. xlsx". The first column is the ID of the image, which can be found in the folder "Facebook_pic_solved". The second column is the text. The third column represents the category, with a metaphorical label of "1" and a literal label of "0". The fourth column indicates whether it is a textual metaphor. The fifth column represents categories, where 1, 2, and 3 respectively represent 1: text dominant, 2: image dominant, and 3: completeness. The sixth and eighth columns represent the source and target domains, while the seventh and ninth columns represent the modal information of the source and target domains, where 1, 2, and 3 represent: 1: text, 2: image, and 3: text+image, respectively. The 10th column represents sentiment classification, 1: very negative, 2: negative, 3: neutral, 4: positive, 5: very positive. The 11th list diagram includes: 1: supervisory, 2: informative, and 3: expressive.

# Citation
Dongyu Zhang, Minghao Zhang, Heting Zhang, Liang Yang, and Hongfei Lin. 2021. MultiMET: A Multimodal Dataset for Metaphor Understanding. In Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers), pages 3214–3225, Online. Association for Computational Linguistics.

# 📦 MultiMET

**Official Repository for**  
**_“MultiMET: A Multimodal Dataset for Metaphor Understanding”_**  
📄 *ACL 2021, Long Papers*

---

## 🧠 Overview

**MultiMET** is a novel **multimodal metaphor dataset** designed to facilitate metaphor understanding from both text and image. It consists of **10,437** text-image pairs annotated with:

- Metaphor occurrence  
- Source and target domains  
- Emotion polarity  
- Author intent  

We also introduce a suite of strong baseline models to demonstrate the importance of multimodal fusion in metaphor comprehension.

---

## 📂 Dataset Structure

### 1. `ads.xlsx`
| Column | Description |
|--------|-------------|
| 1 | Image ID (refer to folder `ads/`) |
| 2 | Image URL |
| 3 | Category (1 = metaphorical, 0 = literal) |
| 4–5 | Source and Target Domains |
| 6 | Emotion (VN, N, Z, P, VP) |
| 7 | Text in image |

### 2. `Facebook_pic_solved.xlsx`
| Column | Description |
|--------|-------------|
| 1 | Image ID (refer to `Facebook_pic_solved/`) |
| 2 | Text |
| 3 | Category (1 = metaphorical, 0 = literal) |
| 4 | Is textual metaphor (0/1) |
| 5 | Type: 1=text-dominant, 2=image-dominant, 3=balanced |
| 6–9 | Source/Target Domains + Modal Types (1=text, 2=image, 3=both) |
| 10 | Sentiment (1–5 = very negative to very positive) |
| 11 | Intent (1=supervisory, 2=informative, 3=expressive) |

### 3. `Twitter_pic_solved.xlsx`
Same structure as `Facebook_pic_solved.xlsx`.

---

## 📈 Citation

If you use **MultiMET** in your work, please cite:

<pre>
<code>
@inproceedings{zhang2021multimet,
  title     = {MultiMET: A multimodal dataset for metaphor understanding},
  author    = {Zhang, Dongyu and Zhang, Minghao and Zhang, Heting and Yang, Liang and Lin, Hongfei},
  booktitle = {Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)},
  pages     = {3214--3225},
  year      = {2021}
}
</code>
</pre>


## 🔬 Explore More Research from Our Lab

**Important❗**  Please cite the following relevant papers if you use our data.❗

1. **[MultiMET: A Multimodal Dataset for Metaphor Understanding (ACL 2021)](https://github.com/DUTIR-YSQ/MultiMET)**  
   A foundational multimodal dataset for metaphor understanding, combining text and visual modalities.  
   **Citation Format**:  
   Dongyu Zhang, Minghao Zhang, Heting Zhang, Liang Yang, and Hongfei Lin. 2021. MultiMET: A Multimodal Dataset for Metaphor Understanding. In Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers), pages 3214–3225, Online. Association for Computational Linguistics.

2. **[Cultural Bias Matters: A Cross-Cultural Benchmark Dataset and Sentiment-Enriched Model for Understanding Multimodal Metaphors (ACL 2025)](https://github.com/DUTIR-YSQ/MultiMM)**  
   A cross-cultural benchmark dataset that incorporates sentiment signals to improve multimodal metaphor detection across languages.  
   **Citation Format**:  
   Senqi Yang, Dongyu Zhang, Jing Ren, Ziqi Xu, Xiuzhen Zhang, Yiliao Song, Hongfei Lin, and Feng Xia. 2025. *Cultural Bias Matters: A Cross-Cultural Benchmark Dataset and Sentiment-Enriched Model for Understanding Multimodal Metaphors*. In *Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)*, pages XX–XX, **Vienna, Austria**. Association for Computational Linguistics.

3. **[EmoMeta: A Chinese Multimodal Metaphor Dataset and Novel Method for Emotion Classification (WWW 2025)](https://github.com/DUTIR-YSQ/EmoMeta)**  
   A new Chinese dataset and method for emotion classification based on multimodal metaphors.  
   **Citation Format**:  
   Lu, X., Liu, Y., Zhang, D., Wu, Z., Ren, J., & Xia, F. (2025, May). EmoMeta: A Multimodal Dataset for Fine-grained Emotion Classification in Chinese Metaphors. In Companion Proceedings of the ACM on Web Conference 2025 (pp. 3080-3083).

4. **[MultiCMET: A Novel Chinese Benchmark for Understanding Multimodal Metaphor (EMNLP 2023)](https://github.com/DUTIR-YSQ/MultiCMET)**  
   A high-quality Chinese benchmark designed to support multimodal metaphor understanding in NLP and vision-language tasks.  
   **Citation Format**:  
   Zhang, D., Yu, J., Jin, S., Yang, L., & Lin, H. (2023, December). Multicmet: A novel Chinese benchmark for understanding multimodal metaphor. In Findings of the Association for Computational Linguistics: EMNLP 2023 (pp. 6141-6154).


### 📚 References (BibTeX)

```bibtex
@inproceedings{zhang2021multimet,
  title     = {MultiMET: A multimodal dataset for metaphor understanding},
  author    = {Zhang, Dongyu and Zhang, Minghao and Zhang, Heting and Yang, Liang and Lin, Hongfei},
  booktitle = {Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)},
  pages     = {3214--3225},
  year      = {2021}
}

@inproceedings{yang2025cultural,
  title     = {Cultural Bias Matters: A Cross-Cultural Benchmark Dataset and Sentiment-Enriched Model for Understanding Multimodal Metaphors},
  author    = {Yang, Senqi and Zhang, Dongyu and Ren, Jing and Xu, Ziqi and Zhang, Xiuzhen and Song, Yiliao and Lin, Hongfei and Xia, Feng},
  booktitle = {Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages     = {XX--XX},
  year      = {2025},
  address   = {Vienna, Austria},
  publisher = {Association for Computational Linguistics}
}

@inproceedings{lu2025emometa,
  title     = {EmoMeta: A Multimodal Dataset for Fine-grained Emotion Classification in Chinese Metaphors},
  author    = {Lu, Xingyuan and Liu, Yuxi and Zhang, Dongyu and Wu, Zhiyao and Ren, Jing and Xia, Feng},
  booktitle = {Companion Proceedings of the ACM on Web Conference 2025},
  pages     = {3080--3083},
  year      = {2025}
}

@inproceedings{zhang2023multicmet,
  title     = {Multicmet: A novel chinese benchmark for understanding multimodal metaphor},
  author    = {Zhang, Dongyu and Yu, Jingwei and Jin, Senyuan and Yang, Liang and Lin, Hongfei},
  booktitle = {Findings of the Association for Computational Linguistics: EMNLP 2023},
  pages     = {6141--6154},
  year      = {2023}
}

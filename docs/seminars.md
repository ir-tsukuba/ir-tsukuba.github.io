---
hide:
  - navigation
  - toc
---

!!! info "リサーチセミナー Research Seminars"
    リサーチグループメンバーや学内外の研究者・学生による研究成果や進捗の発表会<br/>
    Research seminars invite group members and affiliated researchers and students to present their work

## 2026年


!!! example "リサーチセミナー Research Seminar #3 2026.03.18"
    - 日付 Date：2026.03.18
    - 発表者 Speaker：Benjamin Clavié (Mixedbread / National Institute of Informatics)
    - 題目 Title：ColBERT and Late Interaction Retrieval: Why, How, and What Next?
    - 要旨 Abstract：Within Neural IR, three major paradigms have emerged: dense single-vector retrieval (e.g. DPR), the most dominant one, contextualized sparse retrieval (e.g. SPLADE), and dense multi-vector retrieval (ColBERT), also called "late interaction". In this talk, we will briefly discuss the strengths and weaknesses of each of those paradigms. We will then take a deeper dive into late interaction models and cover both their theoretical and practical advantages. We will then assess how much we understand about the mechanisms of late interaction models, covering aspects which are well-understood as well as others which remain empirical or subject to strong practical constraints. Building on this, we will finally outline potential next steps for late interaction methods.

!!! example "リサーチセミナー Research Seminar #2 2026.02.18"
    - 日付 Date：2026.02.18
    - 発表者 Speaker：Jiaman He (RMIT University)
    - 題目 Title：Characterizing Personality from Eye-Tracking: The Role of Gaze and Its Absence in Interactive Search Environments
    - 要旨 Abstract：Personality traits influence how individuals engage, behave, and make decisions during the information-seeking process. However, few studies have linked personality to observable search behaviors. This study aims to characterize personality traits through a multimodal time-series model that integrates eye-tracking data and gaze missingness-periods when the user&#39;s gaze is not captured. This approach is based on the idea that people often look away when they think, signaling disengagement or reflection. We conducted a user study with 25 participants, who used an interactive application on an iPad, allowing them to engage with digital artifacts from a museum. We rely on raw gaze data from an eye tracker, minimizing preprocessing so that behavioral patterns can be preserved without substantial data cleaning. From this perspective, we trained models to predict personality traits using gaze signals. Our results from a five-fold cross- validation study demonstrate strong predictive performance across all five dimensions: Neuroticism (Macro F1 = 77.69%), Conscientiousness (74.52%), Openness (77.52%), Agreeableness (73.09%), and Extraversion (76.69%). The ablation study examines whether the absence of gaze information affects the model performance, demonstrating that incorporating missingness improves multimodal time-series modeling. The full model, which integrates both time-series signals and missingness information, achieves 10–15% higher accuracy and macro F1 scores across all Big Five traits compared to the model without time-series signals and missingness. These findings provide evidence that personality can be inferred from search-related gaze behavior and demonstrate the value of incorporating missing gaze data into time-series multimodal modeling.
    - プロフィール Bio：Ms. Jiaman He is a PhD student at RMIT University, Australia. Her research focuses on information retrieval, human behavior, and physiological sensing. Ms. He develops novel methodologies that use eye-tracking data to understand human behavior and cognitive states during search activities. In addition, her work investigates the statistical differences between large language model (LLM) annotations and human decision-making in annotation tasks.

!!! example "リサーチセミナー Research Seminar #1 2026.01.14"
    - 日付 Date：2026.01.14
    - 発表者 Speaker：上保秀夫（筑波大学）Hideo Joho (University of Tsukuba)
    - 題目 Title：モデル検索行動 Model Search Behaviour
    - 要旨 Abstract：近年、Retrieval Augmented Generation（RAG）手法などを背景に、人間ユーザのリクエストを受けた大規模言語モデルが、ユーザの代わりに文書コーパスを検索する応用が拡大している。しかし、大規模言語モデルを含む生成AIモデルの出力機序は未解明な部分が多く、各種モデルの検索行動も明らかになっていない。そこで、本研究では、従来人間ユーザを対象に実施してきたユーザスタディ手法を生成AIモデルに適応する「モデル検索行動研究」を紹介する。また、モデル検索行動分析のために開発したgeniie-labライブラリも紹介することで、研究の具体的な手続きや得られる知見を提示する。In recent years, with the rise of methods such as Retrieval-Augmented Generation (RAG), applications have increasingly emerged in which large language models search document corpora on behalf of human users. However, the output mechanisms of generative AI models, including large language models, are essentially black boxes, and their search behaviors remain poorly understood. In this talk, I introduce "model search behaviour" research, which adapts traditional user‑study methodologies, originally designed for human users, to generative AI models. I also present the geniie-lab library, developed for analysing model search behaviour, and illustrate the concrete research procedures and insights that can be obtained.
    - プロフィール Bio：筑波大学図書館情報メディア系・教授。専門はインタラクティブ情報検索、人間情報インタラクション、モデル検索行動、など。 Full Professor at the Institute of Library, Information and Media Science, University of Tsukuba. His research interests include Interactive Information Retrieval, Human Information Interaction, and Model Search Behaviour.
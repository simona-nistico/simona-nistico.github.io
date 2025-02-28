---
widget: blank
headless: false

# ... Put Your Section Options Here (title etc.) ...
title: Research
subtitle:
weight: 10  # section position on page

design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
---

<div style="text-align: left; margin-right: -10cm">
    <p>Her research interests are in Artificial Intelligence and span different ares such as:</p>
    <ul>
        <li><strong>Explainable Artificial Intelligence (xAI),</strong></li>
        <li><strong>Anomaly Detection (AD),</strong></li>
        <li><strong>Audio Super-resolution,</strong></li>
        <li><strong>Federated Learning,</strong></li>
        <li><strong>Neuro-symbolic AI.</strong></li>
    </ul>
    <h2>Explainable AI</h2>
    <p>Concerning xAI, her work explores various perspectives to address challenges relating to the opaqueness of sub-symbolic AI systems.</p>
    <h3>Post-hoc explanation</h3>
    <p>
        Her research on post-hoc model explanation encompassed both textual and continuous data. Concerning textual data her work leveraged semantic neighbourhood generation, investigating both application-dependent and LLM-based approaches to produce richer local explanations. As for continuous data, her research work focused on designing more accurate explanations, even when dealing with data like images.
        In particular, a method based on building counterfactuals through masking models -- which are neural networks specialized in transforming samples to change black-box model outcomes -- has been developed. 
        Moreover, she has also looked at the study of the outcome sensitivity to feature modification to find features having similar behaviour as a way to extract interpretable features in a black-box-driven way.
    </p>
    <h3>Explainable Anomaly Detection</h3>
    <p>
        Her research efforts have also been invested in developing explainable by-design Anomaly Detection (AD) systems that assist decision-makers in taking effective actions. The bedrock of this research line is embedding the concept of explainability through an ad-hoc designed loss. The proposed loss is shaped to guide the network in accurately reconstructing normal features while intentionally poorly reconstructing the features that, according to the neural network, contribute to sample outlierness.
    </p>
    <h2>Outlier explanation</h2>
    <p>
        Her work also addressed the outlier explanation problem by introducing a new perspective in sample outlierness description based on transformation-based justifications. Unlike existing methods that focus on subspaces or feature ranking, this explanation shape is aimed at providing users with multifaceted explanations that enhance their understanding of sample outlierness. The transformation itself illustrates how to modify the sample to remove factors contributing to its outlierness, while its application provides the user with an example of a normal instance similar to the outlier. Furthermore, to capture different peculiarities of the analysed samples, the method is designed to generate diverse explanations for a single instance.  The above-described approach has been extended to handle groups of outliers, a less explored area in the literature.  In this context, the method aims to identify a single transformation justifying all the outliers composing the group.  Since groups are not known in advance, the method employs a hierarchical strategy in which outliers are grouped according to explanation fitness.
    </p>
    <h2>Audio Super-resolution</h2>
    <p>
Another explored area has been the audio super-resolution, which focuses on restoring audio files with missing or corrupted information. 
The preliminary studies have primarily addressed the problem of missing high frequencies, which applies to scenarios where an inappropriate sampling rate or low-quality recording hardware results in the miss of information beyond a certain frequency threshold.
To restore this data, a GAN-based approach leveraging vision transformers has been designed to generate the missing frequency range by leveraging the information available from the lower frequencies.
Within this field, her efforts are currently committed to facing a more general scenario in which the missing frequencies are unknown.
    </p>
    <h2>Federated Learning</h2>
    <p>Her research interests also extended to the area of Federated Learning, for which a broad study has been carried out to analyse its issue in controlled environments. Currently,  her research in this area is focusing on client clustering as a means to improve the aggregation of model weight updates and client personalization.
    </p>
    <h2>Neuro-symbolic AI</h2>
    <p>
    Recently, she has started to delve into Neuro-symbolic approaches for detecting and repairing anomalous evolutions of intelligent agents in planning systems.
    </p>
</div>

# An Integrative Survey on Mental Health Conversational Agents to Bridge Computer Science and Medical Perspectives

This repository contains the resources associated with the EMNLP 2023 paper:

> Cho et al. (2023). "An Integrative Survey on Mental Health Conversational Agents to Bridge Computer Science and Medical Perspectives".

You can find the paper [HERE](https://arxiv.org/abs/2310.17017).


Contents in this repository are:
 - /annotated_papers - Annotated papers' PDF files. 
   - /aaai
   - /acl
   - /acm
   - /ieee
   - /pubmed
 - LICENSE
 - README.md - This file.
 - full_table.csv - Full table contains all selected papers in the final list with attributes.

   
We only share annotated experiment/model papers. Some papers are not included due to copyright restrictions.


Below are the descriptions of each attributes in the full_table.csv:
  * _Title_: The title of the selected paper.
  * _Link_: The url of the paper.
  * _File Name_: the corresponding pdf filename of the paper in our repository.
  * _Public Access_: Whether the paper is publicly avilable. x indicates false. If false, the paper is not uploaded in our repository.
  * _Affiliation_: Affiliation of the authors of the paper. cs: Computer Science, med: Medicine, joint: has authors from both fields, dns: did not specify. 
  * _Database_: The source of the paper.
  * _Paper Type_: The type of the paper. We here only show model or experiment papers.
  * _Language_: Target language used in this paper.
  * _Mental Health Category_: Target mental health category in this paper.
  * _Target Group_: Target group of this paper. Could be patients, caregivers, or clinicians.
  * _Target Demographic_: Target demographic of this paper.
  * _Chatbot Name_: The name of the chatbot model used in this paper.
  * _Chatbot Type_: Type of the mental health CA. Could be QA, open domain, or task oriented.
  * _Model Technique_: Type of technique used to build the model. Could be rule-based, retrieval-based, or generative.
  * _Off the Shelf_: Information about the usage of off-the-shelf models in the system. We limit Off-the-shelf models to pre-trained models or applications. Could be yes (directly used), used as a part (off-the-shelf model consists a part of the pipeline), or finetuned.
  * _Oursourced Model Name_: The name of the off-the-shelf model, if any.
  * _Training Data_: The name or source of the training data, if any.
  * _Interface_: Type of input the model takes. Could be text, voice, visual, or button.
  * _Embodiment_: Embodiment of the model. Could be physical or visual.
  * _Platform_: The platform the model run on. Could be Web, Mobile, PC, or other devices.
  * _Public Access_: If the availability of the model is disclosed in the paper. Could be fully open (parameter level) or API (able to use).
  * _Study Design_: Type of user study performed in the paper. Could be RCT (Randomized Controlled Trial), user study (ask participants to use and evaluate), or comparative analysis (divide users with different conditions and compare the result).
  * _Recruitment_: How participants are recruited.
  * _Sample Size_: Size of the participants.
  * _Duration_: Duration taken for the user study.
  * _Automatic Evaluation_: List of automatic evaluations used in this paper.
  * _Human Evaluation_: List of Human Evaluation used in this paper.
  * _Statistical Test_: List of statistical tests used for measuring significance in this paper.
  * _Ethics_: Whether the paper mentioned ethical consideration. Could be IRB (Institutional Review Boards), or yes (mentioned in the paper).
  * _Statistical Test_: Name of statistical tests used in this paper.

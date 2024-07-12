
The identification of online hate speech is a challenging task due to the nuanced and evolv-
ing nature of harmful language. Modern Natural Language Processing(NLP) Language Models

performs better in various tasks but performs poorly in identifying hate speech while consider-
ing zero-short or transfer learning issues. Traditional ”black box” models, while offering some

success, lack transparency in their decision-making processes. To address these issues In this

project, we implemented a framework called Space Modelling(SM) [1][1] which uses the projec-
tion of sentence representations onto task-specific conceptual spaces for improved explainability.

Each concept space corresponds to a classification class and is learned in the training phase. This

framework shows that each dimension of a class space represents words of a class space. To op-
timize these class spaces we have used inter and intra space losses. our experiments across 2 hate

speech datasets evidences that SM’s out performs existing methods. Experimental results demon-
strate that the implemented approach enhances detection performance compared to baselines and

generates meaningful explanations.


**You can view the detailed documentation [here](https://github.com/sivamani121/hatespeech/blob/main/ProjectReport.pdf).

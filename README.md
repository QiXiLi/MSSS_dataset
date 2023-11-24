***\*MSSS\****

To validate the efficacy of the methodology proposed in this paper, we have collected two new multimodal datasets using handheld devices equipped with camera and audio recording capabilities, such as smartphones and tablets. These datasets consist of a genuine signature dataset and a corresponding skilled forgery dataset, both based on signature images and stroke audio signals. Compared to existing works, our datasets have the following advantages:

***\*·\**** This is a multimodal dataset that simultaneously captures signature images and stroke audio signals, filling the data gap in the signature domain under multimodal conditions and encouraging more researchers to engage in this field.

***\*·\**** Our proposed dataset includes 1000 signature images and 1000 signature stroke audio signals from 100 users. We also created skilled forgeries corresponding to these 100 genuine user data, which serve to validate our work.

***\*·\**** The data collection devices used are personal handheld devices such as smartphones or tablets, without any specific requirement for the collection equipment. The only prerequisites are built-in camera and audio recording modules, eliminating the need for additional experimental equipment. The operation is straightforward and the cost is low.

The MSSS dataset is the first multimodal signature dataset we have produced. Unlike other public signature datasets, MSSS contains data information in two different modalities, including the image information of the signature and the audio signal of the handwriting when signing. The MSSS dataset is composed of genuine signature data and skillfully forged data from 100 signatories, which includes 10 original signatures, 10 original audio recordings, 10 forged signatures, and 10 audio recordings collected during the forgery of the signatures for each individual. Fig 1 provides a selection of samples from our dataset.

![](https://github.com/QiXiLi/img/raw/main/%E5%9B%BE%E7%89%871.png)

Fig 1. Example of a self-built dataset MSSS section. (The first three columns are the genuine signatures and their corresponding audio data, and the last are the skillfully forged signatures and sound.)

Table 1. Statistics description of the proposed MSSS dataset

| Data                 | Subjects | Repetitions | Total |
| -------------------- | -------- | ----------- | ----- |
| Genuine Image        | 100      | 10          | 1000  |
| Genuine Stroke sound | 100      | 10          | 1000  |
| Fake Image           | 100      | 10          | 1000  |
| Fake Stroke sound    | 100      | 10          | 1000  |

## Acquisition equipment

In terms of the data collection apparatus, as Fig 2 show, we employed the built-in camera modules of personal smart phones or tablets to capture the image data, while the native audio sensors of the devices were used to collect the audio signals. To ensure standardization of the collected data, we stipulated that the mobile device must be positioned horizontally above the first line of the signature form.

![](https://github.com/QiXiLi/img/blob/main/%E5%9B%BE%E7%89%872.png)

Fig 2. Acquisition equipment of MSSS

## Genuine dataset collection details

The authentic dataset presented in this paper is designed to meet the needs of different users across various real-life deployment scenarios. It necessitates the collection of a sufficiently complex cohort of participants and a substantial number of samples. Consequently, we invited 100 participants to contribute to our data collection. These volunteers, hailing from various backgrounds, participated in the data compilation, spanning an age range of 14 to 74 years. They represent a diverse group including informal workers, farmers, students, and corporate employees. Each group possesses a unique educational background and working environment, and they use signatures in distinct circumstances and settings. Collecting data from diverse deployment scenarios and different groups to represent potential users in various contexts is one of the key contributions of our dataset. Fig 3 illustrates the distribution proportion of our dataset. Each participant was asked to produce ten signatures on the signature form, during which the accompanying audio signals of the writing process were captured. During the collection, we maintained a detailed statistical table that recorded the identity of each signature creator, along with their age, occupation, preferred hand for writing, and surrounding environment.

![](https://github.com/QiXiLi/img/blob/main/%E5%9B%BE%E7%89%873.png)

Fig3. Proportional distribution of people in the MSSS dataset. ((a) shows the proportional distribution of each age group; (b) shows the proportional distribution of all volunteers by gender; (c) shows the distribution of all volunteers by occupation; (d) shows the distribution of all volunteers by education.)

Due to the inherent intra-class variability of signatures, changes in contexts and emotional states could potentially induce variations in an individual's signature. This presents a significant challenge to signature verification systems. In different deployment scenarios, the session span could result in alterations in the same subject's handwriting style. To ensure the universality of our dataset, we requested each participant to engage in a 20-minute session span interval during the data collection process. This methodology was implemented to guarantee a more comprehensive encapsulation of potential signature variations.

## Skilled forgeries production details

In this work, twenty researchers from our laboratory have produced skilled forgeries of signatures. These researchers were not only observers but also participants during the entire process of the genuine dataset creation, and it is upon this experience that the forged dataset was produced. The forged dataset maintains the same acquisition criteria as the genuine dataset, and the order and number are consistent with the order and number of the genuine dataset. In addition, the forged dataset was constructed without a session span and ultimately completed in one go after extensive practice.

## Signle modal performance test

![](https://github.com/QiXiLi/img/blob/main/%E5%9B%BE%E7%89%874.png)

![](https://github.com/QiXiLi/img/blob/main/%E5%9B%BE%E7%89%875.png)
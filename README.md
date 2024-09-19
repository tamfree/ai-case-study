# An AI Case on Sensity AI 

<details>
<summary>Document purpose</summary>
This is a markdown academic assignment. The main goal is to learn more about creating GitHub README.md documents. It was recommended that we create content that is significantly more succint than a typical case study given the main goal. The below represents those goals and recommendations.
With that said, the below company selection reflects my genunine interest in deepfake detection.
</details>

## Overview and Origin

* Name of company

    ![Sensity](https://sensity.ai/wp-content/themes/sensity/assets/icons/logo.svg)
   

* When was the company incorporated?
 
     [Sensity](http://sensity.ai/) was founded in 2018. [^1]  [^4]

[^1]: Source: [World Economic Forum](https://www.weforum.org/organizations/sensity-ai/#:~:text=Founded%20in%20late%202018%2C%20Sensity,forms%20of%20malicious%20visual%20media)


[^4]: Source: [Sensity AI](https://sensity.ai/why-sensity/)

* Who are the founders of the company?


    | ![Francesco Cavalli's picture](https://photos.wellfound.com/users/9045186-medium_jpg?1701412716) | ![Giorgio Patrini](https://photos.wellfound.com/users/150438-medium_jpg?1552549137) |
    | -- | -- |
    | Francesco Cavalli | Giorgio Patrini |
    | Chief Operating Officer|  Chief Executive Officer <br> and Chief Scientist |


[^2]

[^2]: Source: [Crunchbase people](https://www.crunchbase.com/organization/deeptrace/people)

<!-- * How did the idea for the company (or project) come about?

    xxx -->
* How is the company funded? How much funding have they received?

    Sensity is a private company that has received €1.3 million in investor funding. [^3]


[^3]: Source: [Crunchbase company financials](https://www.crunchbase.com/organization/deeptrace/company_financials)

## Business Activities

* What specific problem is the company or project trying to solve?

    Sensity is a cybersecurity company that aims to help entities detect and combat deepfake videos, audio and images.

* Who is the company's intended customer? Is there any information about the market size of this set of customers?
    
    Companies and government agencies are their target customers.
    The overall deepfake AI market is expected to approach $5.1 billion dollars by 2030. Deepfake detection tools are a segment within the overall deepfake AI market [^5]

[^5]: Source: [Markets and Markets](https://www.marketsandmarkets.com/Market-Reports/deepfake-ai-market-256823035.html)

* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
    Their differentiator is that they offer more comprehensive deepfake detection tooling.
    They are reported to be first deep fake detection tool made available in the market. [^6]

[^6]: Source: [Forbes - Deepfakes: The Danger of Artificial Intelligence](https://www.forbes.com/sites/lutzfinger/2022/09/08/deepfakesthe-danger-of-artificial-intelligence-that-we-will-learn-to-manage-better/)

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing&mdash;you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
This is has been difficult to clearly determine. They do not provide technology details to individuals.

 I have found sources that may allude to what their offerings  may use.

1. They may be running on AWS, at least in part, because they appear in the AWS Marketplace (but with no details) and they need access to significant amount of compute and are therefore likely reliant one of the major cloud providers.
1. . In github they offer a deepfake generation tool to use for testing called the Deepfake Offensive toolkit. That repository uses, [Python](https://www.python.org), [Cuda](https://developer.nvidia.com/cuda-toolkit) and [Jupyter Notebook](https://jupyter.org). [^7]

[^7]: Source: https://github.com/sensity-ai/dot

## Landscape

* What field is the company in?
    It is a cybersecurity technology company that serves political entities and businesses in a variety of industries including but not limited to finance, education and entertainment.

* What have been the major trends and innovations of this field over the last 5&ndash;10 years?
Recent advances in the ability and access to generative AI has cause a sharp increase in the threat of nefarious deepfakes.

* What are the other major companies in this field?

    * Intel
    * Google
    * Microsoft
    * OpenAI
    * Sentinel
    * Deepware
    * BioID 


## Results

* What has been the business impact of this company so far?

    Sensity has successfully detected over 44,000 deepfakes as of February 2024. [^8]

[^8]: Source: https://www.iamsterdam.com/en/business/key-sectors-for-business/artificial-intelligence/stories/sensity

* What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?
    * One key metric is detection rate. Sensity has been reported to have a detection rate of 95%. [^9]

    [^9]: Source: [LinkedIn Deepfake Detection: Accuracy of Commercial Tools](https://www.linkedin.com/pulse/deepfake-detection-accuracy-commercial-tools-konstantin-simonchik-u0z3e#:~:text=Sensity.ai%20is%20reported%20to,of%20image%20and%20video%20manipulations)
    

* How is your company performing relative to competitors in the same field?
    
    Sensity has been ranked amongst the top ten deepfake detection technologies  per [Expert Insights Reports](https://expertinsights.com/insights/the-top-deepfake-detection-solutions/)
 and [Vlink](https://www.vlinkinfo.com/blog/top-ai-deepfake-detector-tools/)

    They also have self-reported a 95% detection accuracy rate.

## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

    Once it is financially and technically viable, I would suggest that they create a publicly available site where individuals can verify whether or not the media they are consuming is a fake.

* Why do you think that offering this product or service would benefit the company?
If done via government funding, it introduces a steady income stream that is likely to increase over time. There is also the altruistic benefit of being an accessible deterernt to 

* What technologies would this additional product or service utilize?
I am not sure. However, certain jurisdictions may mandate that the infrastructure reside within in that jurisdiction. For example, all cloud compute and storage instances may need to reside in country X and be fully supported by its citizens.

* Why are these technologies appropriate for your solution?
It aligns with existing regulations in locales such as the EU, Switzerland and Singapore, to name a few.